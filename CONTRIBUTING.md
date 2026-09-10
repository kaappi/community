# Contributing to Kaappi

Kaappi is an open-source project under the MIT license. Contributions,
questions, and feedback are welcome. This page covers the org-wide "how do I
get involved" mechanics; each repo's own `CONTRIBUTING.md` covers its
specific build/test/PR workflow (e.g.
[kaappi/kaappi](https://github.com/kaappi/kaappi/blob/main/CONTRIBUTING.md)).

## Get involved

**[GitHub Discussions](https://github.com/orgs/kaappi/discussions)** is the
starting point for everyone — whether you have a question, found a bug, want
to propose a feature, or are interested in contributing code.

Use Discussions for:

- Questions about using Kaappi
- Bug reports and reproduction cases
- Ideas and feature suggestions
- Show and tell — share what you've built
- General discussion about Scheme and language implementation

There is also a subreddit,
[r/KaappiScheme](https://www.reddit.com/r/KaappiScheme/), for news, questions,
and show-and-tell. Bug reports and feature proposals are best posted in
Discussions, where maintainers actually track them.

Screencasts live on YouTube at
[@KaappiScheme](https://www.youtube.com/@KaappiScheme).

## Issues and pull requests

Issues and pull requests on every Kaappi repository are open to everyone.
No org membership is required: fork, branch, and open the PR (see
[infra/docs/repo-conventions.md](https://github.com/kaappi/infra/blob/main/docs/repo-conventions.md)
for the policy and its guards).

What is *not* open is merging. Every PR needs all CI checks green and an
approving review from a maintainer before it merges, and CI on a PR from a
fork waits for a maintainer to approve the workflow run first. That is a
safeguard on the runners, not a judgement on the PR.

Kaappi has one maintainer, and review time is the scarcest resource the
project has. These rules keep it spent well, and each repo's own
`CONTRIBUTING.md` may add specifics:

- **Run the tests yourself before opening the PR.** CI is a check, not a
  substitute. A PR opened red is closed, not debugged.
- **Be able to explain the change.** "The tool generated it" is not an
  answer, and a PR whose author cannot walk through it is closed without
  further review.
- **Disclose AI assistance** in the PR description. Using an LLM is fine;
  the sign-off below certifies that *you* stand behind the result and have
  the right to submit it under MIT.
- **One change per PR.** A fix and an unrelated refactor are two PRs.
- **Talk first for anything large.** A new subsystem, a language-surface
  change, or a change to the build model goes through a
  [KEP](https://github.com/kaappi/keps) before code.

Bug reports use issue forms that require a version, a platform, and a
pasted reproduction. If you are not sure something is a bug, a Discussion
is the right first stop.

### Typical path for a new contributor

1. **Explore** — install Kaappi, try the [Playground](https://kaappi-lang.org/playground/),
   read the [Guide](https://kaappi-lang.org/guide/)
2. **Join the conversation** — post in Discussions (questions, ideas)
3. **File or pick an issue** — bug reports go straight to the relevant
   repo's issue tracker; `good first issue` marks the ones meant for
   newcomers
4. **Submit a PR** — fork, branch, test, open a pull request against the
   relevant repo, following that repo's own `CONTRIBUTING.md`

## Sign off your commits (DCO)

Every commit must include a `Signed-off-by` trailer, certifying the
[Developer Certificate of Origin](https://developercertificate.org/) — that
you wrote the contribution (or have the right to submit it) under the
project's license. Add it automatically with:

```bash
git commit -s -m "Your commit message"
```

A [DCO check](https://github.com/cncf/dco2) runs on every pull request and
must pass before merging. If you forget:

- **Single commit:** `git rebase HEAD~1 --signoff && git push --force-with-lease`
- **Multiple commits:** squash them, then sign off the result before pushing

## What to contribute

- **Bug fixes and features** on [kaappi/kaappi](https://github.com/kaappi/kaappi)
  — see its `CONTRIBUTING.md` for the build/test workflow
- **New or improved ecosystem libraries** — see
  [Library Authoring](https://kaappi-lang.org/guide/library-authoring.md)
- **Documentation** — edit files in
  [kaappi.github.io](https://github.com/kaappi/kaappi.github.io)

## Report a security vulnerability

See [SECURITY.md](SECURITY.md). Do not open a public issue for security
reports.

## Code of conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). Be
respectful and constructive in all interactions.

## License

Kaappi and all ecosystem libraries are released under the
[MIT License](https://opensource.org/licenses/MIT).
