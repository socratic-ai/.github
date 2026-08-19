# Security Policy

Thank you for helping keep Cosmo and its users secure.

## Reporting a vulnerability

Please report suspected vulnerabilities privately through GitHub's
**private vulnerability reporting** on the affected repository:
open the repository's **Security** tab and choose **Report a vulnerability**.

Please do not open a public issue for security reports, and please do not
include exploit details in a public issue or pull request.

We will acknowledge your report, keep you informed of progress, and credit
you in the fix release notes unless you prefer otherwise.

## Our commitment

- **Acknowledgement** within 3 business days.
- **Triage and an initial severity assessment** (CVSS v3.1) within 10 business
  days.
- **Status updates** at least every 10 business days until the report is
  resolved.
- We aim to remediate high-severity issues within **90 days** and will
  coordinate public disclosure and any CVE assignment with you.

## Safe harbor

We consider security research and vulnerability disclosure conducted in good
faith and in accordance with this policy to be authorized. We will not pursue or
support legal action against you for such activity — including activity that
would otherwise violate our terms or anti-circumvention or computer-misuse law
(such as the CFAA) — provided you:

- make a good-faith effort to avoid privacy violations, data destruction, and
  interruption or degradation of our services;
- only access, modify, or store data that belongs to you, and stop and report as
  soon as you encounter data that is not yours;
- do not run high-volume, automated, or denial-of-service testing against
  production systems;
- give us a reasonable opportunity to remediate before any public disclosure;
  and
- do not exploit the issue beyond the minimum necessary to demonstrate it.

If you are unsure whether a specific test is authorized, ask first via private
vulnerability reporting. This safe harbor does not extend to third-party services
or dependencies that the SDKs rely on — please report those to their respective
maintainers.

## How fixes ship

Development of the Cosmo SDKs happens in an internal repository. The public
SDK repositories are release mirrors. A security fix lands internally first
and then appears here in the next tagged release, so a fix may reference an
internal change rather than a public commit.

## Scope

This policy covers the repositories in the `socratic-ai` organization,
including `cosmo-ai` (the home of the Cosmo SDKs and examples) and
`cosmo-swift-sdk` (the Swift Package Manager distribution repository).
For issues in the Cosmo service itself, use the same private reporting
flow on `cosmo-ai` and note that the report concerns the service.
