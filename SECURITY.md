# Security policy

## Supported branches

`main` is the supported branch. Fixes land there.

## Reporting a vulnerability

Email security@presencis.com. Include the repository, the commit or version, and a minimal reproduction. Do not open a public issue for an unfixed vulnerability.

We acknowledge a report within 3 business days and send a triage update within 10 business days. The time to a fix follows severity and whether a release is required.

## Scope

In scope: the public Presencis repositories (this profile, the bill-of-materials schemas, the offline verifier) and the public datasets we publish under huggingface.co/presencis.

Out of scope:

- Third-party customer environments and customer-operated deployments.
- Vulnerabilities in unmodified third-party dependencies. Report those to the upstream project.
- Physical attacks against a person, a building, or a network we do not operate.
- Volume exhaustion that does not cross a trust boundary in the offline verifier.

## Disclosure

We prefer coordinated disclosure. We credit reporters who want credit, after a fix is public.
