# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is **not a software project**. It is a private, German-language personal wiki ("Personal Wiki") for self-reflection: thoughts, values, goals, difficulties, recurring patterns, decisions, and journal entries. There are no build, lint, or test commands — all content is plain Markdown.

The full purpose, principles, and intended structure are described in `README.md` (in German). Read it before making structural changes.

## Language and naming rules

- **Content is always written in German** — file contents, headings, and journal entries.
- **File and folder names are always in English**, always lowercase, with hyphens as separators where needed (e.g. `who-i-am.md`, `01-personality/`, `decision-log.md`). Root content folders additionally use two-digit numeric prefixes. Never use German, uppercase, spaces, or underscores in names.

## Structure

```text
index.md          entry point, links all areas
00-inbox/         unsorted notes and files — captured first, processed later
01-personality/   who-i-am, values, goals, strengths-weaknesses, patterns
02-health/        free-form health area, starts with overview.md
03-relationship/  the user's partner Angeli (angeli.md, us.md)
04-people/        other people, one file per person (see 04-people/about.md)
05-decisions/     one file per decision, template in 05-decisions/about.md
06-documents/     real files (PDFs, scans) in topic subfolders (see 06-documents/about.md)
99-archive/       outdated content — move here instead of deleting (created on demand)
```

Workflow: new notes, PDFs, and other unclassified files go into `00-inbox/` first; processing means moving them into the right area, turning them into a decision file, or deleting them. The inbox should shrink, not grow. Its note is `00-inbox/inbox.md`. Each `about.md` documents its folder's conventions — read it before adding files there. Root content folders use two-digit numeric prefixes for stable ordering in file browsers and Obsidian.

Processing the inbox is a semantic task, not a verbatim move. Read and understand each item, synthesize its new information into the appropriate existing files, and update multiple areas when needed. Preserve useful concrete observations, label interpretations as interpretations, avoid duplication, and ask the user when ambiguity would materially affect meaning or placement. Remove the source item only after all relevant information has been incorporated.

## Writing principles (from README, follow when drafting or editing content)

- Honesty over polish: raw and honest beats well-formulated; short beats not at all.
- No artificial drama, no excuses, no unnecessary self-deprecation.
- Document process, not a finished state — doubts, corrections, and new insights belong here.
- This repository is private; content is never written for outside presentation.

## Maintenance rhythms

The README defines review routines the user may ask for: weekly short review, monthly check-in, quarterly goal review, yearly retrospective, and occasional archiving of outdated thoughts (move to `99-archive/` rather than delete).

## Git workflow

Do not commit or push changes unless the user explicitly asks. Leave changes in the working tree for review.

## Privacy

Contents are deeply personal. Never publish, share, summarize to external services, or expose this material outside the repository.
