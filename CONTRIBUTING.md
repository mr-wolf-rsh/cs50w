# Contributing

Notes for whoever maintains this hub (currently me). The README is for visitors; this file is
the workflow.

## Updating the set

1. To edit a project, **unarchive** it on GitHub, make the change, push, then **re-archive**
   (archived repositories are read-only).
2. Keep the hub table in sync: project name, repository link, stack, status.
3. Link targets must match the real repository names (`cs50w-*`).

## Rules for the shared files

- `spec.md` is the map, not a second assignment brief — requirements live in each project's
  README and CS50W's published specs.
- Do not renumber or rename projects; the order is the course order.
- The hub itself is a plain index: no project code lives here.

## Known context

- The set is archived by design; no active work is expected.
- Search is static HTML/CSS/JS; the rest are Django-based; the capstone adds React + PostgreSQL.
