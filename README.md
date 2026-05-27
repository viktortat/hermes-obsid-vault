# Karpaty DB — LLM-maintained knowledge base

A personal knowledge wiki maintained by an LLM agent, following the [LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) pattern.

## Структура

```
.
├── .schema/               # Конфигурация для LLM-агента
│   └── CLAUDE.md          # Схема: структура, соглашения, воркфлоу
├── raw/                   # Неизменяемые исходники (raw sources)
│   ├── articles/          # Статьи, PDF, web-клиппинг
│   └── assets/            # Изображения, медиа
└── wiki/                  # LLM-генерируемая вики
    ├── index.md           # Каталог всех страниц
    ├── log.md             # Хронологический лог операций
    ├── concepts/          # Страницы концепций
    ├── entities/          # Страницы сущностей (люди, места, проекты)
    ├── sources/           # Саммари источников
    └── queries/           # Ответы на вопросы, сохранённые в базу
```

## Рабочий процесс

1. **Ingest** — положить источник в `raw/` и попросить LLM обработать
2. **Query** — задать вопрос, LLM ищет по вики и синтезирует ответ
3. **Lint** — периодически проверять здоровье вики (противоречия, устаревшие данные, сиротские страницы)

Подробнее — в `.schema/CLAUDE.md`.

