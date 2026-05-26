# Security Policy

## Supported versions

Only the latest release on the `main` branch is actively supported.

## Reporting a vulnerability

**Do not open a public GitHub issue** for security or privacy vulnerabilities.

Instead:

1. Open a [GitHub Security Advisory](../../security/advisories/new) for this repository, **or**
2. Email **security@gas.ac** with the subject line `BlackBox vulnerability`.

Please include description + impact, reproduction steps, browser + OS, and embargo status.

## Our commitment

- Acknowledge your report within **3 business days**
- Initial assessment within **7 business days**
- Credit you in release notes with your permission

## Scope

In-scope: XSS / HTML-injection, privacy-posture bypasses, BlackBox JS vulnerabilities, supply-chain risk in pinned CDN deps.

Out of scope: third-party LLM provider issues, attacks requiring physical device access, self-XSS via dev-console paste, reports against forked/modified builds.
