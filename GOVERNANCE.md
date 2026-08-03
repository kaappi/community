# Governance

This document describes decision-making authority for the
[kaappi GitHub org](https://github.com/kaappi). It applies org-wide; individual
repos don't have separate governance today.

## Current state

Kaappi has a single maintainer (see [MAINTAINERS.md](MAINTAINERS.md)) with
full decision authority across all org repos. This document exists so that
changes — as the project and contributor base grow — have somewhere to be
made and explained, rather than happening informally.

## How decisions are made

- **Routine changes** (bug fixes, small features, docs) go through normal PR
  review on the relevant repo — no separate process needed.
- **Substantial or cross-cutting changes** (new runtime subsystems,
  language/library-surface changes, new core libraries, build-model changes)
  go through the [KEP process](https://github.com/kaappi/keps) so the design
  and its trade-offs are recorded before implementation starts.
- **Access and repo policy** (who can create issues/PRs, team permissions)
  follows the standard described in
  [infra/docs/repo-conventions.md](https://github.com/kaappi/infra/blob/main/docs/repo-conventions.md).

## Becoming a maintainer

There's no formal nomination process yet, given the size of the project.
In practice: sustained, high-quality contribution across one or more repos,
followed by an invitation from an existing maintainer. Once added, a
maintainer is:

- Listed in [MAINTAINERS.md](MAINTAINERS.md)
- Granted the relevant repo access per
  [infra/docs/repo-conventions.md](https://github.com/kaappi/infra/blob/main/docs/repo-conventions.md)

## Stepping down

Maintainers who become inactive or wish to step down should say so (an issue
or a note to another maintainer is enough) and will be moved out of
[MAINTAINERS.md](MAINTAINERS.md). Access is removed accordingly.

## Changing this document

This document reflects a single-maintainer project and will be revisited
(e.g. how multiple maintainers reach consensus, per-repo ownership) once
there's more than one maintainer for it to matter. Until then, changes to
this file follow the same PR process as everything else.
