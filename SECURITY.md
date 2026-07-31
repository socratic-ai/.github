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

## How fixes ship

Development of the Cosmo SDKs happens in an internal repository. The public
SDK repositories are release mirrors. A security fix lands internally first
and then appears here in the next tagged release, so a fix may reference an
internal change rather than a public commit.

## Scope

This policy covers the repositories in the `socratic-ai` organization,
including the Cosmo SDKs (`cosmo-swift-sdk`, `cosmo-python-sdk`,
`cosmo-typescript-sdk`) and `cosmo-examples`. For issues in the Cosmo
service itself, use the same private reporting flow on any SDK repository
and note that the report concerns the service.
