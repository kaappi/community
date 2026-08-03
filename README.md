# kaappi/community

The canonical org-wide home for getting involved with the
[kaappi GitHub org](https://github.com/kaappi): how to contribute, governance,
maintainers, code of conduct, and security reporting.

Individual repos still own their own repo-specific `CONTRIBUTING.md` (build,
test, and PR workflow for that codebase) — e.g.
[kaappi/kaappi](https://github.com/kaappi/kaappi/blob/main/CONTRIBUTING.md).
For the generic "how do I get involved" mechanics (Discussions, org access,
the contributor path), this repo is the source of truth; those other docs
link back here rather than repeating it.

Unlike every other repo in the org, **issues and pull requests here are open
to everyone** — no org membership required. Most kaappi repos restrict
creation to collaborators (see
[infra/docs/repo-conventions.md](https://github.com/kaappi/infra/blob/main/docs/repo-conventions.md));
this repo is the intentional exception, since governance, Code of Conduct,
and security-policy questions shouldn't require an invite first.

## What's here

| File | Purpose |
|------|---------|
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to get involved — Discussions, org access, contributor path |
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
