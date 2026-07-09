# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is **not a software project**. It is a private, German-language personal wiki ("Personal Wiki") for self-reflection: thoughts, values, goals, difficulties, recurring patterns, decisions, and journal entries. There are no build, lint, or test commands — all content is plain Markdown.

The full purpose, principles, and intended structure are described in `README.md` (in German). Read it before making structural changes.

## Language and naming rules

- **Content is always written in German** — file contents, headings, and journal entries.
- **File and folder names are always in English**, always lowercase, with hyphens as separators where needed (e.g. `01-who-i-am.md`, `journal/`, `decision-log.md`). Never use German, uppercase, spaces, or underscores in names.

## Structure

```text
index.md          entry point, links all areas
inbox.md          unsorted thoughts — captured first, processed later
personality/      who-i-am, values, strengths-weaknesses, patterns
goals.md          short- and long-term goals
relationship/     the user's partner Angeli (angeli.md, us.md)
people/           other people, one file per person (see people/about.md)
decisions/        one file per decision, template in decisions/about.md
health/           free-form health area, starts with overview.md
documents/        real files (PDFs, scans) in topic subfolders (see documents/about.md)
archive/          outdated content — move here instead of deleting (created on demand)
```

Workflow: new thoughts go into `inbox.md` first; processing means moving them into the right area, turning them into a decision file, or deleting them. The inbox should shrink, not grow. Each `about.md` documents its folder's conventions — read it before adding files there.

## Writing principles (from README, follow when drafting or editing content)

- Honesty over polish: raw and honest beats well-formulated; short beats not at all.
- No artificial drama, no excuses, no unnecessary self-deprecation.
- Document process, not a finished state — doubts, corrections, and new insights belong here.
- This repository is private; content is never written for outside presentation.

## Maintenance rhythms

The README defines review routines the user may ask for: weekly short review, monthly check-in, quarterly goal review, yearly retrospective, and occasional archiving of outdated thoughts (move to `archive/` rather than delete).

## Privacy

Contents are deeply personal. Never publish, share, summarize to external services, or expose this material outside the repository.
