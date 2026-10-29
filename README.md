# Lab 7 Genetics Wiki

A first-principles wiki for **Principles of Biology Lab 7: Genetics and Patterns of Inheritance** (corn ears, Punnett squares, chi-square), built with [Quartz 4](https://quartz.jzhao.xyz/).

**Live site:** https://ajay221bl.github.io/lab7-genetics-wiki/

## What's inside (`content/`)

| Folder | What it holds |
|---|---|
| `1 Maps of Content` | Reading orders: the full learning path, one map per topic area, exam prep, common mix-ups, a one-hour crash course |
| `2 Molecular Notes` | Topic notes that tell the story connecting a group of atomic notes |
| `3 Atomic Notes` | One concept per note, covering every term in the Lab 7 manual, slides and study guide. Each has a one-sentence definition, a plain-language (Feynman-style) explanation, the idea built from first principles, where it appears in Lab 7, and a test-yourself question |
| `4 Calculations` | Every calculation students perform: reusable skills, worked lab calculations, and study guide problems |
| `Vault Index.md` | Every note, grouped by category |

## Site features

- Light theme only
- Larger local graph; hovering a node in the graph shows a preview of that note
- Link previews on hover, full-text search, backlinks

## Editing

Notes are plain Markdown with `[[wikilinks]]`, so the `content` folder opens directly as an Obsidian vault. Every push to `main` rebuilds and redeploys the site through `.github/workflows/deploy.yml`.

To preview locally: `npm ci && npx quartz build --serve`, then open http://localhost:8080.
