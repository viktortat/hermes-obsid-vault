# 🛠️ Полная Карта Навыков (SKILLS) и Команд Агента Hermes

Твой личный путеводитель по возможностям Hermes Agent, Виктор! Этот файл содержит полный список всех установленных и доступных навыков. Все описания локализованы на русский язык, а примеры написаны так, как ты бы общался со мной в текстовом чате на телевизоре или телефоне.

## 🗂️ Навигация по Категориям
- [Умный дом](#smart-home)
- [Заметки и базы знаний](#note-taking)
- [Ред-теминг и безопасность](#red-teaming)
- [Девопс и Kanban](#devops)
- [Dogfood](#dogfood)
- [Apple](#apple)
- [Data-science](#data-science)
- [Электронная почта в терминале](#email)
- [Yuanbao](#yuanbao)
- [AI Агенты и делегирование](#autonomous-ai-agents)
- [Академический поиск и наука](#research)
- [Креативность и дизайн](#creative)
- [Гипер-управление GitHub](#github)
- [Разработка ПО и дебаг](#software-development)
- [Model Context Protocol](#mcp)
- [Офис, Документы и Продуктивность](#productivity)
- [Social-media](#social-media)
- [Медиа, Музыка и YouTube](#media)
- [Игры и локальные сервера](#gaming)
- [Машинное обучение и инференс](#mlops)

---

## <a name="smart-home"></a>📂 Умный дом

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`openhue`** | Управление умными лампами и световыми сценами Philips Hue. | • "Выключи свет во всём доме"<br>• "Установи теплый свет на 50% в зале"<br>• "Включи сцену 'Чтение' в спальне" |


## <a name="note-taking"></a>📂 Заметки и базы знаний

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`obsidian`** | Поиск, чтение, редактирование заметок в твоём Obsidian Vault. | • "Найди заметку про n8n в Обсидиане"<br>• "Создай новую заметку 'План продаж'"<br>• "Добавь лог за сегодня в Obsidian" |


## <a name="red-teaming"></a>📂 Ред-теминг и безопасность

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`godmode`** | Jailbreak LLMs: Parseltongue, GODMODE, ULTRAPLINIAN. | • "Помоги мне использовать инструмент godmode"<br>• "Запусти скрипт для godmode"<br>• "Покажи справку по настройке godmode" |


## <a name="devops"></a>📂 Девопс и Kanban

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`kanban-worker`** | Pitfalls, examples, and edge cases for Hermes Kanban workers. The lifecycle itself is auto-injected into every worker's system prompt as KANBAN_GUIDANCE (from agent/prompt_builder.py); this skill is what you load when you want deeper detail on specific scenarios. | • "Помоги мне использовать инструмент kanban-worker"<br>• "Запусти скрипт для kanban-worker"<br>• "Покажи справку по настройке kanban-worker" |
| **`webhook-subscriptions`** | Организация входящих вебхуков для автоматического триггера агента. | • "Покажи мои активные вебхуки"<br>• "Создай точку для приёма алертов на 8080 порту"<br>• "Протестируй входящий вебхук n8n" |
| **`kanban-orchestrator`** | Decomposition playbook + anti-temptation rules for an orchestrator profile routing work through Kanban. The "don't do the work yourself" rule and the basic lifecycle are auto-injected into every kanban worker's system prompt; this skill is the deeper playbook when you're specifically playing the orchestrator role. | • "Помоги мне использовать инструмент kanban-orchestrator"<br>• "Запусти скрипт для kanban-orchestrator"<br>• "Покажи справку по настройке kanban-orchestrator" |


## <a name="dogfood"></a>📂 Dogfood

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`dogfood`** | Exploratory QA of web apps: find bugs, evidence, reports. | • "Помоги мне использовать инструмент dogfood"<br>• "Запусти скрипт для dogfood"<br>• "Покажи справку по настройке dogfood" |


## <a name="apple"></a>📂 Apple

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`apple-notes`** | Manage Apple Notes via memo CLI: create, search, edit. | • "Помоги мне использовать инструмент apple-notes"<br>• "Запусти скрипт для apple-notes"<br>• "Покажи справку по настройке apple-notes" |
| **`apple-reminders`** | Apple Reminders via remindctl: add, list, complete. | • "Помоги мне использовать инструмент apple-reminders"<br>• "Запусти скрипт для apple-reminders"<br>• "Покажи справку по настройке apple-reminders" |
| **`imessage`** | Send and receive iMessages/SMS via the imsg CLI on macOS. | • "Помоги мне использовать инструмент imessage"<br>• "Запусти скрипт для imessage"<br>• "Покажи справку по настройке imessage" |
| **`macos-computer-use`** | | | • "Помоги мне использовать инструмент macos-computer-use"<br>• "Запусти скрипт для macos-computer-use"<br>• "Покажи справку по настройке macos-computer-use" |
| **`findmy`** | Track Apple devices/AirTags via FindMy.app on macOS. | • "Помоги мне использовать инструмент findmy"<br>• "Запусти скрипт для findmy"<br>• "Покажи справку по настройке findmy" |


## <a name="data-science"></a>📂 Data-science

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`jupyter-live-kernel`** | Iterative Python via live Jupyter kernel (hamelnb). | • "Помоги мне использовать инструмент jupyter-live-kernel"<br>• "Запусти скрипт для jupyter-live-kernel"<br>• "Покажи справку по настройке jupyter-live-kernel" |


## <a name="email"></a>📂 Электронная почта в терминале

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`himalaya`** | Управление электронной почтой (IMAP/SMTP) прямо из консоли или чата. | • "Проверь свежие письма в ящике"<br>• "Напиши ответное письмо коллеге"<br>• "Найди письмо от техподдержки гитхаба" |


## <a name="yuanbao"></a>📂 Yuanbao

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`yuanbao`** | Yuanbao (元宝) groups: @mention users, query info/members. | • "Помоги мне использовать инструмент yuanbao"<br>• "Запусти скрипт для yuanbao"<br>• "Покажи справку по настройке yuanbao" |


## <a name="autonomous-ai-agents"></a>📂 AI Агенты и делегирование

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`hermes-voice-setup`** | Настройка распознавания голоса и синтеза речи (доступ к Svetlana 2x, Groq Whisper). | • "Включи скорость Svetlana на 2x"<br>• "Как изменить голос на мужской?"<br>• "Настрой авто-озвучивание моих ответов" |
| **`codex`** | Delegate coding to OpenAI Codex CLI (features, PRs). | • "Помоги мне использовать инструмент codex"<br>• "Запусти скрипт для codex"<br>• "Покажи справку по настройке codex" |
| **`claude-code`** | Delegate coding to Claude Code CLI (features, PRs). | • "Помоги мне использовать инструмент claude-code"<br>• "Запусти скрипт для claude-code"<br>• "Покажи справку по настройке claude-code" |
| **`hermes-agent`** | Полное конфигурирование твоего Hermes Agent (модели, квоты, рестарты). | • "Покажи текущий конфиг Hermes"<br>• "Какая версия системы используется?"<br>• "Проверь здоровье агента через doctor" |
| **`kanban-codex-lane`** | Use when a Hermes Kanban worker wants to run Codex CLI as an isolated implementation lane while Hermes keeps ownership of task lifecycle, reconciliation, testing, and handoff. | • "Помоги мне использовать инструмент kanban-codex-lane"<br>• "Запусти скрипт для kanban-codex-lane"<br>• "Покажи справку по настройке kanban-codex-lane" |
| **`opencode`** | Delegate coding to OpenCode CLI (features, PR review). | • "Помоги мне использовать инструмент opencode"<br>• "Запусти скрипт для opencode"<br>• "Покажи справку по настройке opencode" |


## <a name="research"></a>📂 Академический поиск и наука

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`llm-wiki`** | Karpathy's LLM Wiki: build/query interlinked markdown KB. | • "Помоги мне использовать инструмент llm-wiki"<br>• "Запусти скрипт для llm-wiki"<br>• "Покажи справку по настройке llm-wiki" |
| **`research-paper-writing`** | Write ML papers for NeurIPS/ICML/ICLR: design→submit. | • "Помоги мне использовать инструмент research-paper-writing"<br>• "Запусти скрипт для research-paper-writing"<br>• "Покажи справку по настройке research-paper-writing" |
| **`arxiv`** | Мгновенный поиск научных статей directly на серверах ArXiv. | • "Найди свежие статьи про GRPO обучение"<br>• "Сделай выжимку статьи про Gemini 3.5"<br>• "Найди работы Ильи Суцкевера про ИИ" |
| **`blogwatcher`** | Monitor blogs and RSS/Atom feeds via blogwatcher-cli tool. | • "Помоги мне использовать инструмент blogwatcher"<br>• "Запусти скрипт для blogwatcher"<br>• "Покажи справку по настройке blogwatcher" |
| **`polymarket`** | Query Polymarket: markets, prices, orderbooks, history. | • "Помоги мне использовать инструмент polymarket"<br>• "Запусти скрипт для polymarket"<br>• "Покажи справку по настройке polymarket" |


## <a name="creative"></a>📂 Креативность и дизайн

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`touchdesigner-mcp`** | Control a running TouchDesigner instance via twozero MCP — create operators, set parameters, wire connections, execute Python, build real-time visuals. 36 native tools. | • "Помоги мне использовать инструмент touchdesigner-mcp"<br>• "Запусти скрипт для touchdesigner-mcp"<br>• "Покажи справку по настройке touchdesigner-mcp" |
| **`sketch`** | Throwaway HTML mockups: 2-3 design variants to compare. | • "Помоги мне использовать инструмент sketch"<br>• "Запусти скрипт для sketch"<br>• "Покажи справку по настройке sketch" |
| **`baoyu-comic`** | Knowledge comics (知识漫画): educational, biography, tutorial. | • "Помоги мне использовать инструмент baoyu-comic"<br>• "Запусти скрипт для baoyu-comic"<br>• "Покажи справку по настройке baoyu-comic" |
| **`baoyu-infographic`** | Infographics: 21 layouts x 21 styles (信息图, 可视化). | • "Помоги мне использовать инструмент baoyu-infographic"<br>• "Запусти скрипт для baoyu-infographic"<br>• "Покажи справку по настройке baoyu-infographic" |
| **`songwriting-and-ai-music`** | Songwriting craft and Suno AI music prompts. | • "Помоги мне использовать инструмент songwriting-and-ai-music"<br>• "Запусти скрипт для songwriting-and-ai-music"<br>• "Покажи справку по настройке songwriting-and-ai-music" |
| **`popular-web-designs`** | 54 real design systems (Stripe, Linear, Vercel) as HTML/CSS. | • "Помоги мне использовать инструмент popular-web-designs"<br>• "Запусти скрипт для popular-web-designs"<br>• "Покажи справку по настройке popular-web-designs" |
| **`claude-design`** | Design one-off HTML artifacts (landing, deck, prototype). | • "Помоги мне использовать инструмент claude-design"<br>• "Запусти скрипт для claude-design"<br>• "Покажи справку по настройке claude-design" |
| **`design-md`** | Author/validate/export Google's DESIGN.md token spec files. | • "Помоги мне использовать инструмент design-md"<br>• "Запусти скрипт для design-md"<br>• "Покажи справку по настройке design-md" |
| **`humanizer`** | Humanize text: strip AI-isms and add real voice. | • "Помоги мне использовать инструмент humanizer"<br>• "Запусти скрипт для humanizer"<br>• "Покажи справку по настройке humanizer" |
| **`comfyui`** | Управление сервером графики ComfyUI, запуск генераций по сложным пайплайнам. | • "Запусти ComfyUI и проверь мои модели"<br>• "Установи недостающие узлы для этого воркфлоу"<br>• "Сделай генерацию по пайплайну FLUX" |
| **`pixel-art`** | Pixel art w/ era palettes (NES, Game Boy, PICO-8). | • "Помоги мне использовать инструмент pixel-art"<br>• "Запусти скрипт для pixel-art"<br>• "Покажи справку по настройке pixel-art" |
| **`vik-genimage`** | Генерация высококачественных картинок через Flux абсолютно бесплатно без лимитов. | • "Сделай фото кота в очках через vik-gen"<br>• "Нарисуй ретро-автомобиль на закате"<br>• "Создай 3D комнату программиста" |
| **`p5js`** | p5.js sketches: gen art, shaders, interactive, 3D. | • "Помоги мне использовать инструмент p5js"<br>• "Запусти скрипт для p5js"<br>• "Покажи справку по настройке p5js" |
| **`ascii-video`** | ASCII video: convert video/audio to colored ASCII MP4/GIF. | • "Помоги мне использовать инструмент ascii-video"<br>• "Запусти скрипт для ascii-video"<br>• "Покажи справку по настройке ascii-video" |
| **`excalidraw`** | Hand-drawn Excalidraw JSON diagrams (arch, flow, seq). | • "Помоги мне использовать инструмент excalidraw"<br>• "Запусти скрипт для excalidraw"<br>• "Покажи справку по настройке excalidraw" |
| **`pretext`** | Use when building creative browser demos with @chenglou/pretext — DOM-free text layout for ASCII art, typographic flow around obstacles, text-as-geometry games, kinetic typography, and text-powered generative art. Produces single-file HTML demos by default. | • "Помоги мне использовать инструмент pretext"<br>• "Запусти скрипт для pretext"<br>• "Покажи справку по настройке pretext" |
| **`manim-video`** | Manim CE animations: 3Blue1Brown math/algo videos. | • "Помоги мне использовать инструмент manim-video"<br>• "Запусти скрипт для manim-video"<br>• "Покажи справку по настройке manim-video" |
| **`architecture-diagram`** | Создание потрясающих SVG-схем системной архитектуры в темной теме. | • "Нарисуй схему архитектуры моего n8n бэкап скрипта"<br>• "Создай блок-схему взаимодействия с Google API"<br>• "Сделай красивый SVG граф процессов" |
| **`ideation`** | Генерация project ideas via creative constraints. | • "Помоги мне использовать инструмент ideation"<br>• "Запусти скрипт для ideation"<br>• "Покажи справку по настройке ideation" |
| **`baoyu-article-illustrator`** | Article illustrations: type × style × palette consistency. | • "Помоги мне использовать инструмент baoyu-article-illustrator"<br>• "Запусти скрипт для baoyu-article-illustrator"<br>• "Покажи справку по настройке baoyu-article-illustrator" |
| **`ascii-art`** | Генерация графики из символов ASCII (pyfiglet, cowsay, и т.д.). | • "Нарисуй логотип 'Lumi' крупными ASCII буквами"<br>• "Пусть корова скажет 'Привет!' через cowsay"<br>• "Сделай ASCII арт из моей фотки" |


## <a name="github"></a>📂 Гипер-управление GitHub

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`codebase-inspection`** | Анализ и инспекция codebases w/ pygount: LOC, languages, ratios. | • "Помоги мне использовать инструмент codebase-inspection"<br>• "Запусти скрипт для codebase-inspection"<br>• "Покажи справку по настройке codebase-inspection" |
| **`github-pr-workflow`** | Управление Pull Requests, ветками, коммитами и CI/CD гитхаба. | • "Создай ветку и сделай пул-реквест на GitHub"<br>• "Проверь статус билдов на гитхабе"<br>• "Добавь рецензента в последний PR" |
| **`github-code-review`** | Review PRs: diffs, inline comments via gh or REST. | • "Помоги мне использовать инструмент github-code-review"<br>• "Запусти скрипт для github-code-review"<br>• "Покажи справку по настройке github-code-review" |
| **`github-repo-management`** | Clone/create/fork repos; manage remotes, releases. | • "Помоги мне использовать инструмент github-repo-management"<br>• "Запусти скрипт для github-repo-management"<br>• "Покажи справку по настройке github-repo-management" |
| **`github-auth`** | Настройка SSH ключей, токенов веб-доступа и авторизация gh-клиента. | • "Выполни авторизацию на гитхабе через gh CLI"<br>• "Проверь мои SSH ключи"<br>• "Создай новый HTTPS токен доступа" |
| **`github-issues`** | Create, triage, label, assign GitHub issues via gh or REST. | • "Помоги мне использовать инструмент github-issues"<br>• "Запусти скрипт для github-issues"<br>• "Покажи справку по настройке github-issues" |


## <a name="software-development"></a>📂 Разработка ПО и дебаг

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`test-driven-development`** | TDD: enforce RED-GREEN-REFACTOR, tests before code. | • "Помоги мне использовать инструмент test-driven-development"<br>• "Запусти скрипт для test-driven-development"<br>• "Покажи справку по настройке test-driven-development" |
| **`spike`** | Throwaway experiments to validate an idea before build. | • "Помоги мне использовать инструмент spike"<br>• "Запусти скрипт для spike"<br>• "Покажи справку по настройке spike" |
| **`systematic-debugging`** | 4-phase root cause debugging: understand bugs before fixing. | • "Помоги мне использовать инструмент systematic-debugging"<br>• "Запусти скрипт для systematic-debugging"<br>• "Покажи справку по настройке systematic-debugging" |
| **`debugging-hermes-tui-commands`** | Дебаг и отладка Hermes TUI slash commands: Python, gateway, Ink UI. | • "Помоги мне использовать инструмент debugging-hermes-tui-commands"<br>• "Запусти скрипт для debugging-hermes-tui-commands"<br>• "Покажи справку по настройке debugging-hermes-tui-commands" |
| **`requesting-code-review`** | Pre-commit review: security scan, quality gates, auto-fix. | • "Помоги мне использовать инструмент requesting-code-review"<br>• "Запусти скрипт для requesting-code-review"<br>• "Покажи справку по настройке requesting-code-review" |
| **`subagent-driven-development`** | Execute plans via delegate_task subagents (2-stage review). | • "Помоги мне использовать инструмент subagent-driven-development"<br>• "Запусти скрипт для subagent-driven-development"<br>• "Покажи справку по настройке subagent-driven-development" |
| **`hermes-agent-skill-authoring`** | Author in-repo SKILL.md: frontmatter, validator, structure. | • "Помоги мне использовать инструмент hermes-agent-skill-authoring"<br>• "Запусти скрипт для hermes-agent-skill-authoring"<br>• "Покажи справку по настройке hermes-agent-skill-authoring" |
| **`writing-plans`** | Write implementation plans: bite-sized tasks, paths, code. | • "Помоги мне использовать инструмент writing-plans"<br>• "Запусти скрипт для writing-plans"<br>• "Покажи справку по настройке writing-plans" |
| **`plan`** | Plan mode: write markdown plan to .hermes/plans/, no exec. | • "Помоги мне использовать инструмент plan"<br>• "Запусти скрипт для plan"<br>• "Покажи справку по настройке plan" |
| **`python-debugpy`** | Дебаг и отладка Python: pdb REPL + debugpy remote (DAP). | • "Помоги мне использовать инструмент python-debugpy"<br>• "Запусти скрипт для python-debugpy"<br>• "Покажи справку по настройке python-debugpy" |
| **`node-inspect-debugger`** | Дебаг и отладка Node.js via --inspect + Chrome DevTools Protocol CLI. | • "Помоги мне использовать инструмент node-inspect-debugger"<br>• "Запусти скрипт для node-inspect-debugger"<br>• "Покажи справку по настройке node-inspect-debugger" |


## <a name="mcp"></a>📂 Model Context Protocol

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`native-mcp`** | MCP client: connect servers, register tools (stdio/HTTP). | • "Помоги мне использовать инструмент native-mcp"<br>• "Запусти скрипт для native-mcp"<br>• "Покажи справку по настройке native-mcp" |


## <a name="productivity"></a>📂 Офис, Документы и Продуктивность

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`notion`** | Работа со страницами и базами данных в Notion через ntn-клиент. | • "Добавь запись в мою рабочую базу Notion"<br>• "Прочитай содержание страницы 'Вики'"<br>• "Найди документы по ключевому слову" |
| **`powerpoint`** | Create, read, edit .pptx decks, slides, notes, templates. | • "Помоги мне использовать инструмент powerpoint"<br>• "Запусти скрипт для powerpoint"<br>• "Покажи справку по настройке powerpoint" |
| **`teams-meeting-pipeline`** | Operate the Teams meeting summary pipeline via Hermes CLI — summarize meetings, inspect pipeline status, replay jobs, manage Microsoft Graph subscriptions. | • "Помоги мне использовать инструмент teams-meeting-pipeline"<br>• "Запусти скрипт для teams-meeting-pipeline"<br>• "Покажи справку по настройке teams-meeting-pipeline" |
| **`linear`** | Интеграция с таск-менеджером Linear через GraphQL API. | • "Покажи мои тикеты в Linear"<br>• "Создай новую задачу в доске разработки"<br>• "Отметь баг выполненным" |
| **`maps`** | Геокодирование, построение маршрутов и таймзоны через OpenStreetMap. | • "Построй маршрут на карте"<br>• "Какая сейчас таймзона в Лондоне?"<br>• "Найди координаты города" |
| **`nano-pdf`** | Edit PDF text/typos/titles via nano-pdf CLI (NL prompts). | • "Помоги мне использовать инструмент nano-pdf"<br>• "Запусти скрипт для nano-pdf"<br>• "Покажи справку по настройке nano-pdf" |
| **`google-workspace`** | Полная интеграция с Календарем, Диском и Документами Google. | • "Покажи мои встречи на сегодня в календаре"<br>• "Запиши файл на мой Google Drive"<br>• "Создай гугл-документ 'Отчёт по ИИ'" |
| **`airtable`** | Airtable REST API via curl. Records CRUD, filters, upserts. | • "Помоги мне использовать инструмент airtable"<br>• "Запусти скрипт для airtable"<br>• "Покажи справку по настройке airtable" |
| **`ocr-and-documents`** | Извлечение структурированного текста из картинок и PDF документов. | • "Распознай текст с этой картинки"<br>• "Прочитай этот PDF файл и извлеки таблицы"<br>• "Конвертируй скан документа в текст" |


## <a name="social-media"></a>📂 Social-media

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`xurl`** | Автоматическая отправка твитов и поиск в Twitter (X). | • "Опубликуй твит о новой модели ИИ"<br>• "Найди твиты про deepseek за сегодня"<br>• "Напиши автору этого твита в DM" |


## <a name="media"></a>📂 Медиа, Музыка и YouTube

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`youtube-content`** | Быстрый сбор контекста, транскриптов и саммаризация YouTube роликов. | • "Сделай саммари по этому видео на ютубе"<br>• "Скачай субтитры к лекции Карпатого"<br>• "Преврати этот YouTube ролик в статью на русском" |
| **`spotify`** | Управление воспроизведением музыки и плейлистами в Spotify на сопряженном плеере. | • "Включи плейлист для фокуса в Spotify"<br>• "Пропусти текущий трек"<br>• "Какая песня сейчас играет?" |
| **`heartmula`** | HeartMuLa: Suno-like song generation from lyrics + tags. | • "Помоги мне использовать инструмент heartmula"<br>• "Запусти скрипт для heartmula"<br>• "Покажи справку по настройке heartmula" |
| **`gif-search`** | Search/download GIFs from Tenor via curl + jq. | • "Помоги мне использовать инструмент gif-search"<br>• "Запусти скрипт для gif-search"<br>• "Покажи справку по настройке gif-search" |
| **`songsee`** | Audio spectrograms/features (mel, chroma, MFCC) via CLI. | • "Помоги мне использовать инструмент songsee"<br>• "Запусти скрипт для songsee"<br>• "Покажи справку по настройке songsee" |


## <a name="gaming"></a>📂 Игры и локальные сервера

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`pokemon-player`** | Headless эмулятор для автоматического прохождения Покемонов. | • "Запусти игру Pokemon Red"<br>• "Сделай скриншот экрана игры"<br>• "Какая позиция у меня на карте?" |
| **`minecraft-modpack-server`** | Конфигурирование серверов Майнкрафта на твоей машине. | • "Установи сборку Майнкрафта"<br>• "Запусти игровой сервер"<br>• "Проверь сетевой статус сервера" |


## <a name="mlops"></a>📂 Машинное обучение и инференс

| Название навыка | Описание возможностей на русском | Примеры вызова в чате (по 3 варианта) |
| :--- | :--- | :--- |
| **`llama-cpp`** | llama.cpp local GGUF inference + HF Hub model discovery. | • "Помоги мне использовать инструмент llama-cpp"<br>• "Запусти скрипт для llama-cpp"<br>• "Покажи справку по настройке llama-cpp" |
| **`obliteratus`** | OBLITERATUS: abliterate LLM refusals (diff-in-means). | • "Помоги мне использовать инструмент obliteratus"<br>• "Запусти скрипт для obliteratus"<br>• "Покажи справку по настройке obliteratus" |
| **`serving-llms-vllm`** | vLLM: high-throughput LLM serving, OpenAI API, quantization. | • "Помоги мне использовать инструмент serving-llms-vllm"<br>• "Запусти скрипт для serving-llms-vllm"<br>• "Покажи справку по настройке serving-llms-vllm" |
| **`huggingface-hub`** | Скачивание и выгрузка моделей, наборов данных на Hugging Face. | • "Скачай модель GGUF из репозитория HF"<br>• "Найди датасеты про русский диалог на HuggingFace"<br>• "Какая модель сейчас популярна в хабе?" |
| **`audiocraft-audio-generation`** | AudioCraft: MusicGen text-to-music, AudioGen text-to-sound. | • "Помоги мне использовать инструмент audiocraft-audio-generation"<br>• "Запусти скрипт для audiocraft-audio-generation"<br>• "Покажи справку по настройке audiocraft-audio-generation" |
| **`segment-anything-model`** | SAM: zero-shot image segmentation via points, boxes, masks. | • "Помоги мне использовать инструмент segment-anything-model"<br>• "Запусти скрипт для segment-anything-model"<br>• "Покажи справку по настройке segment-anything-model" |
| **`dspy`** | DSPy: declarative LM programs, auto-optimize prompts, RAG. | • "Помоги мне использовать инструмент dspy"<br>• "Запусти скрипт для dspy"<br>• "Покажи справку по настройке dspy" |
| **`weights-and-biases`** | W&B: log ML experiments, sweeps, model registry, dashboards. | • "Помоги мне использовать инструмент weights-and-biases"<br>• "Запусти скрипт для weights-and-biases"<br>• "Покажи справку по настройке weights-and-biases" |
| **`evaluating-llms-harness`** | lm-eval-harness: benchmark LLMs (MMLU, GSM8K, etc.). | • "Помоги мне использовать инструмент evaluating-llms-harness"<br>• "Запусти скрипт для evaluating-llms-harness"<br>• "Покажи справку по настройке evaluating-llms-harness" |



## 🎮 Как это вызывать?
Ты можешь отдавать эти команды прямо разговорным языком. Например:
> *«Гермес, сделай фото кота в очках через vik-gen»*
> *« Hermes, найди информацию о n8n в обсидиане»*

Я сам пойму, какой навык загрузить, и выполню задачу! 🚀