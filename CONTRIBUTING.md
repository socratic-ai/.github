# Contributing to Cosmo

Thanks for your interest in improving Cosmo — Socratic AI's realtime voice and
multimodal agent SDKs. This guide applies across the public Cosmo repositories:
[cosmo-typescript-sdk](https://github.com/socratic-ai/cosmo-typescript-sdk),
[cosmo-python-sdk](https://github.com/socratic-ai/cosmo-python-sdk),
[cosmo-swift-sdk](https://github.com/socratic-ai/cosmo-swift-sdk), and
[cosmo-ai](https://github.com/socratic-ai/cosmo-ai).

## How these repositories work

Development of the Cosmo SDKs happens in Socratic AI's internal monorepo. The
public repositories are **release mirrors**: each release is exported as a single
commit (a `Monorepo-commit` trailer records the internal source revision) and
tags are immutable. There is no development branch on the mirrors.

Pull requests are welcome. Because these repos are mirrors, accepted changes are
imported into the internal repository with `Co-authored-by` credit and ship in
the next tagged release, rather than being merged in place — we'll keep you
posted on the issue or PR about when your change lands.

## Bugs and feature requests

Open an issue on the relevant repository. Include the SDK version and a minimal
reproduction where possible. For anything security-related, do **not** open a
public issue — use private vulnerability reporting (the repository's **Security**
tab); see the
[Security Policy](https://github.com/socratic-ai/.github/blob/main/SECURITY.md).

## Examples

Runnable examples live in [cosmo-ai](https://github.com/socratic-ai/cosmo-ai)
under `examples/` — example contributions are best sent there. Keep each example
self-contained (its own README and `.env.example`), depend on the published SDK
packages (never local paths), and don't commit credentials.

## Developer Certificate of Origin (DCO)

Contributions are accepted under the **Developer Certificate of Origin** — a
lightweight certification that you wrote, or otherwise have the right to submit,
the code you contribute. We do **not** require a Contributor License Agreement.

Sign off every commit:

```bash
git commit -s -m "your commit message"
```

This appends a `Signed-off-by: Your Name <you@example.com>` line certifying the
DCO (full text at <https://developercertificate.org/>). Use your real name and a
reachable email. Commits without a valid sign-off cannot be merged; add it after
the fact with `git commit --amend -s`, or rebase to sign off several commits.

Only submit code you have the right to contribute under
[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0). Do not paste
employer-owned code (unless you are authorized) or code under a copyleft license
(GPL/AGPL/LGPL/MPL).

## Code of conduct

This project follows the organization-wide
[Code of Conduct](https://github.com/socratic-ai/.github/blob/main/CODE_OF_CONDUCT.md).
