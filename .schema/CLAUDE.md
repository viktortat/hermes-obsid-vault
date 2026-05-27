# Schema — LLM Wiki conventions

This file defines how the knowledge base is structured, how to maintain it, and what workflows to follow. The LLM reads this at the start of every session and follows it strictly.

## Overview

This is an **LLM-maintained wiki** (LLM Wiki pattern by Karpathy). Three layers:

1. **`raw/`** — immutable source documents. LLM reads from here but never modifies.
2. **`wiki/`** — LLM-generated markdown pages. LLM creates, updates, and cross-references everything.
3. **`.schema/CLAUDE.md`** — this file. Configuration that teaches the LLM how to be a disciplined wiki maintainer.

## Directory conventions

```
wiki/
├── index.md          # Каталог всех страниц (обновляется при каждом ingest)
├── log.md            # Хронологический лог (append-only)
├── concepts/         # Концепции, идеи, темы
├── entities/         # Люди, организации, проекты, места
├── sources/          # Саммари каждого обработанного источника
└── queries/          # Сохранённые ответы на вопросы
```

## Page conventions

- All wiki pages are **Obsidian-flavored Markdown** (.md).
- Use `[[wikilinks]]` for cross-references between wiki pages.
- Use `![alt](path)` for images (absolute or relative to `raw/assets/`).
- Add YAML frontmatter to every wiki page:
  ```yaml
  ---
  title: "Page Title"
  tags: [tag1, tag2]
  created: 2026-05-27
  updated: 2026-05-27
  sources: [source-file-name.md]
  ---
  ```
- Keep frontmatter minimal but include `title` and `updated`.
- Prefer English for concepts/entities, Russian for user-facing summaries (user's native language). Code and technical terms stay in English.

## index.md format

```markdown
# Index

## Concepts
- [[Page Name]] — one-line description

## Entities
...

## Sources
...
```

Update this file **every time** you add, update, or remove a wiki page.

## log.md format

Each entry starts with:
```
## [2026-05-27] ingest | Article Title
## [2026-05-27] query | Question summary
## [2026-05-27] lint | Lint results
```

Append only. Never edit old entries.

## Workflows

### Ingest

When the user drops a new source into `raw/` and asks to process it:

1. Read the source file completely.
2. Discuss key takeaways with the user — ask what to emphasize.
3. Create a summary page in `wiki/sources/`.
4. Update or create relevant concept pages in `wiki/concepts/`.
5. Update or create relevant entity pages in `wiki/entities/`.
6. Update `wiki/index.md` to include new/updated pages.
7. Append an entry to `wiki/log.md`.

A single source may touch 5-15 wiki pages. Do the full sweep.

### Query

When the user asks a question:

1. Read `wiki/index.md` to find relevant pages.
2. Read the relevant pages.
3. Synthesize an answer with citations to wiki pages.
4. If the answer is valuable enough to keep, file it as a page in `wiki/queries/` and update the index.

### Lint

When asked to lint:

1. Walk the wiki and look for:
   - Contradictions between pages
   - Stale claims that newer sources have superseded
   - Orphan pages (no inbound [[wikilinks]])
   - Missing pages for important concepts/entities
   - Broken [[wikilinks]]
2. Fix issues automatically (update pages, add cross-references, create missing pages).
3. Append a lint entry to `wiki/log.md`.
4. Suggest new sources to look for.

### General rules

- Never modify files in `raw/`.
- Never delete content from `wiki/` without user approval (except fixing broken links).
- Keep the index up to date at all times.
- Prefer many small, linked pages over one giant page.
- Use [[wikilinks]] liberally — they are the graph edges of the wiki.
- If you're unsure about a change, ask the user first.
- When in doubt, err on the side of creating a page over leaving an orphan concept.

## Obsidian integration

- This wiki is designed to be opened as an Obsidian vault.
- Uses Obsidian Web Clipper for sourcing articles.
- Graph view shows the shape of the wiki.
- Dataview plugin can query YAML frontmatter.
- Marp plugin can generate slide decks from wiki content.

