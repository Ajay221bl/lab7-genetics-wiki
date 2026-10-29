# Lab 7 Genetics Wiki

A first-principles wiki for **Principles of Biology Lab 7: Genetics and Patterns of Inheritance** (corn ears, Punnett squares, chi-square), built with [Quartz 4](https://quartz.jzhao.xyz/).

**Live site:** https://ajay221bl.github.io/lab7-genetics-wiki/

## What's inside (`content/`)

| Folder | What it holds |
|---|---|
| `0 Start Here` | The Learning Path (stages with checkboxes), Class Questions (about 50 questions students ask, answered from first principles), All Notes (every note with a one-line description), References |
| `1 Maps of Content` | Reading orders: one map per topic area, Basics from Zero, Why We Do It This Way, calculations, exam prep, common mix-ups, a one-hour crash course |
| `2 Molecular Notes` | *Why* notes that explain the reason behind each rule and lab step, and *Topic* notes that tell the story connecting a group of atomic notes |
| `3 Atomic Notes` | One concept per note, from basic math to every term in the Lab 7 manual, slides and study guide. Each goes: plain idea, picture or analogy, worked example, the common trap, a try-it-yourself question with its answer, and links |
| `4 Calculations` | Every calculation students perform: reusable skills, worked lab calculations, and study guide problems |
| `Figures` | Teaching diagrams used across the notes |

## Site features

- Light theme only
- Larger local graph; hovering a node in the graph shows a preview of that note
- Link previews on hover, full-text search, backlinks

## Editing

Notes are plain Markdown with `[[wikilinks]]`, so the `content` folder opens directly as an Obsidian vault. Every push to `main` rebuilds and redeploys the site through `.github/workflows/deploy.yml`.

To preview locally: `npm ci && npx quartz build --serve`, then open http://localhost:8080.
