# n8n Docker Setup

Инструкции по управлению, структуре, переменным окружения и временной остановке/запуску сервиса **n8n** вместе с обратным прокси **Caddy**.

---

## 📌 Текущее состояние и конфигурация

Сервис развернут в Docker с использованием `docker-compose` и Caddy в качестве TLS-терминатора.

### 🗂️ Пути на сервере
* **Директория проекта:** `/home/viktor/n8n-docker-caddy`
* **Файл конфигурации Compose:** `/home/viktor/n8n-docker-caddy/docker-compose.yml`
* **Caddyfile (конфигурация reverse proxy):** `/home/viktor/n8n-docker-caddy/caddy_config/Caddyfile`
* **Локальная папка для файлов (внутри n8n `/files`):** `/home/viktor/n8n-docker-caddy/local_files`
* **Docker Volume базы данных/кода n8n (`n8n_data`):** `/var/lib/docker/volumes/n8n_data/_data` (монтируется в `/home/node/.n8n`)
* **Docker Volume данных Caddy (`caddy_data`):** `/var/lib/docker/volumes/caddy_data/_data` (монтируется в `/data`)

### 🌐 Сетевые настройки
* **Домен:** `n8n.viktortat.info`
* **Протокол:** HTTPS (SSL-сертификаты автоматически выпускаются Caddy через Let's Encrypt)
* **Внутренний порт n8n:** 5678

### ⚙️ Переменные окружения n8n (актуальные на момент фиксации)
* `N8N_HOST` = `n8n.viktortat.info`
* `N8N_PORT` = `5678`
* `N8N_PROTOCOL` = `https`
* `NODE_ENV` = `production`
* `N8N_SECURE_COOKIE` = `true`
* `WEBHOOK_URL` = `https://n8n.viktortat.info/`
* `GENERIC_TIMEZONE` = `Europe/Kyiv`

---

## 📴 Как временно остановить n8n и Caddy

Для корректной и безопасной остановки контейнеров перейдите в директорию проекта и выполните команду остановки. Это сохранит все тома данных (volumes), состояние БД и настройки — они не пропадут.

```bash
# Переход в директорию
cd /home/viktor/n8n-docker-caddy

# Остановка контейнеров (выключает и Caddy, и n8n)
docker compose down
```

Если вы хотите остановить **только n8n**, оставив Caddy включенным (например, чтобы домен отдавал ошибку прокси, но сам сервер Caddy работал):
```bash
cd /home/viktor/n8n-docker-caddy
docker compose stop n8n
```

---

## 🔛 Как снова запустить n8n и Caddy

Чтобы запустить всё обратно в фоновом режиме (detached mode):

```bash
# Переход в директорию
cd /home/viktor/n8n-docker-caddy

# Запуск в фоновом режиме
docker compose up -d
```

Если останавливали только n8n через `stop`:
```bash
cd /home/viktor/n8n-docker-caddy
docker compose start n8n
```

---

## 🩺 Проверка статуса работы
Для проверки состояния контейнеров используйте:
```bash
docker ps
# или в папке проекта
cd /home/viktor/n8n-docker-caddy && docker compose ps
```

Дополнительно логи можно читать так:
```bash
docker compose logs -f --tail=100 n8n
```
