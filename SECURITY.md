# Security Policy

## Supported versions

| Version | Supported |
|---------|-----------|
| 0.2.x   | Yes       |
| < 0.2   | No        |

## Reporting a vulnerability

If you discover a security issue in this skill, **do not open a public issue.**

Instead, email the maintainer directly or use GitHub's [private vulnerability reporting](https://github.com/Abderrahman-Jalled/improve-relationships/security/advisories/new).

Include:

- A description of the vulnerability
- Steps to reproduce
- The potential impact
- Any suggested fix

You should receive a response within 72 hours. Critical issues will be addressed in the next patch release.

## Security principles

This skill is designed to be conservative by default:

1. **Draft-only** — it never sends, posts, or delivers any message
2. **Least privilege** — it only uses data the user explicitly provides
3. **No storage** — it does not persist contact data beyond the session unless configured
4. **Evidence boundaries** — it states exactly what it saw and where
5. **Cross-context privacy** — work and personal streams are kept separate
6. **Sensitive-situation caution** — it asks before drafting in delicate situations

If you believe any of these principles are being violated, please report it.
