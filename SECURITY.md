# Security Policy

## Supported versions

| Version | Status |
|---------|--------|
| v2.2.x  | ✅ Supported (current) |
| v2.1.x  | ✅ Supported |
| v2.0.x and older | ❌ Not supported |

AlaCraft is a continuously deployed web platform. "Supported" means security patches are actively applied to the live production site at [alacraft.day](https://alacraft.day).

## Reporting a vulnerability

**Do not report security issues in public GitHub Issues.**

Contact us privately:

- **Email** — support@alacraft.day
- **Discord** — send a direct message to the maintainer via [discord.gg/ky7cFDF8JD](https://discord.gg/ky7cFDF8JD)
- **Twitter / X** — DM [@alacraftday](https://x.com/alacraftday)

Include in your report:

- Description of the vulnerability
- Steps to reproduce
- Affected URL or feature
- Potential impact

We will acknowledge the report within 48 hours and keep you updated on the fix.

## Scope

**In scope:** anything at `alacraft.day` that could compromise player data, authentication, or site integrity — XSS, CSRF, authentication bypass, data exposure, unauthorized access.

**Out of scope:** social engineering, rate-limiting on public read endpoints, theoretical vulnerabilities without a working proof of concept.

## Disclosure

We follow coordinated disclosure. Please allow reasonable time to patch before publishing details publicly.

Thank you for helping keep AlaCraft and its community safe.
