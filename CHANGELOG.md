# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] — 2026-03-08

### Added

- Evidence ladder: High / Medium / Low classification for every signal
- Ranking thresholds: 4.2+ recommend now, 3.2–4.1 suggest lightly, <3.2 omit
- Top 5 pagination: show 5 at a time with total count, "next" for more
- Multilingual drafting: any language, auto-detected from communication history with fallback to profile and user default. Example templates in Arabic, French, English
- Privacy and security section: 8 principles including draft-only, cross-context privacy, safe drafting
- "Why now" logic: every recommendation answers why this person, why this moment, why this channel
- Channel logic table: explicit channel per signal type per stream
- Composite score visible in output format
- Stream field visible in output format
- Arabic draft examples for Ramadan and Eid templates
- French draft examples for Nowruz and New Year templates
- Language column in example contacts CSV
- GitHub Actions: markdown lint, link check, SKILL.md frontmatter validation
- Community files: CODE_OF_CONDUCT.md, CONTRIBUTING.md, SECURITY.md
- Issue and PR templates

### Changed

- Default from top 3 to top 5 with pagination
- "Send" action renamed to "Approve to send" throughout
- "Cross-account privacy" renamed to "cross-context privacy" with stronger definition
- Digest closer now says "These are drafts — nothing has been sent"
- Product thesis safety row updated to "Draft-only — never sends"

### Removed

- Plugin directory (deferred to v2, separate repo)

## [0.1.0] — 2026-03-07

### Added

- Initial SKILL.md with signal detection, scoring, tone framework
- Work / personal stream separation
- Cultural occasion support (10 occasions)
- Tone framework (6 tones)
- 5-dimension scoring model
- Approval-first safety model
- Templates: digest, personal outreach, professional outreach, rituals
- Examples: weekly digest, signal objects, sample contacts
- Docs: product thesis, testing guide, roadmap
