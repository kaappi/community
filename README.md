# kaappi/community

The canonical org-wide home for getting involved with the
[kaappi GitHub org](https://github.com/kaappi): how to contribute, governance,
maintainers, code of conduct, and security reporting.

Individual repos still own their own repo-specific `CONTRIBUTING.md` (build,
test, and PR workflow for that codebase) — e.g.
[kaappi/kaappi](https://github.com/kaappi/kaappi/blob/main/CONTRIBUTING.md).
For the generic "how do I get involved" mechanics (Discussions, the review
rules, the contributor path), this repo is the source of truth; those other docs
link back here rather than repeating it.

Issues and pull requests here, as on every other repo in the org, are open
to everyone — no org membership required. This repo was the one exception
while the others were collaborators-only (until 2026-09-10); it remains the
place for governance, Code of Conduct, and security-policy questions, which
should never need an invite first. The org-wide policy and its guards are
described in
[infra/docs/repo-conventions.md](https://github.com/kaappi/infra/blob/main/docs/repo-conventions.md).

## What's here

| File | Purpose |
|------|---------|
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to get involved — Discussions, review rules, contributor path |
| [GOVERNANCE.md](GOVERNANCE.md) | Who has decision authority and how that changes over time |
| [MAINTAINERS.md](MAINTAINERS.md) | Current org-wide maintainers |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Canonical Contributor Covenant text |
| [SECURITY.md](SECURITY.md) | Canonical vulnerability-reporting policy |

`CODE_OF_CONDUCT.md` and `SECURITY.md` here are the source of truth for other
repos too. A repo that doesn't yet have its own copy gets one seeded from here
(see [kaappi/infra](https://github.com/kaappi/infra)'s repo-maintenance
scripts); a repo may extend `SECURITY.md` with its own threat model, as
[kaappi/kaappi](https://github.com/kaappi/kaappi/blob/main/SECURITY.md) does
for its sandbox and FFI trust boundary.

## License

MIT
