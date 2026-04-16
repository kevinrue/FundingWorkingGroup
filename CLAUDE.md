# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Role

Human contributors add and maintain markdown files documenting funding opportunities and grants. Claude's role is to:

1. **Standardise content** — when asked to review or tidy a file, align it with the relevant template in terms of structure, section headings, and field names. Preserve the contributor's wording; only reformat or flag missing fields.
2. **Draft summary pages** — when asked, synthesise information across multiple files in a directory into a readable summary (e.g. a table or list of current opportunities, or an overview of active grants).

## Structure

- `opportunities/` — One file per upcoming funding opportunity, added manually by contributors.
  - `template.md` — Canonical structure: title, brief description, timeline (call opens/closes), details.
- `active/` — One file per currently funded grant.
  - `template.md` — Canonical structure: title, brief description, funder, grant period (start/end dates), details.
- `past/` — Concluded grants, moved from `active/` when the end date passes.
- `unsuccessful/` — Submitted applications that were not funded.

## Conventions

- File names use underscores and are descriptive (e.g. `R_Consortium_Technical_Grant_Cycle_2026.md`).
- Dates are written as `YYYY-MM-DD`.
