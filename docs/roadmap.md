# Improve Relationships — Roadmap

## v1.0 — Skill (Current)

SKILL.md that teaches OpenClaw relationship intelligence within a single session.

**Ships with:**

- Signal detection across all available context (calendar, email, messaging, shared browser tabs, social profiles, news, user-provided info)
- Work / personal stream separation
- 5-dimension scoring model with ranking thresholds (4.2+ / 3.2–4.1 / <3.2)
- Evidence ladder (High / Medium / Low)
- Top 5 recommendations by default
- Tone framework (warm personal, respectful professional, celebratory, light reconnect, ritual/holiday, condolence)
- Multilingual drafting — any language, auto-detected from communication history
- Cultural occasion support (Ramadan, Eid, Diwali, Lunar New Year, Nowruz, Christmas, Hanukkah, New Year)
- Privacy and security model (least privilege, evidence boundaries, cross-context privacy, safe drafting)
- Draft-only safety model — never sends anything
- Digest mode (daily/weekly, by stream)
- Browser tab review (opt-in)
- Templates and examples

**Limitations:**

- No persistent state across sessions
- No background scanning
- User provides context each session
- No outreach history tracking

---

## v1.5 — Skill improvements

Refinements based on usage. Still skill-only.

- Improved scoring calibration
- Additional cultural occasion templates
- Additional language support
- Digest scheduling guidance for cron/heartbeat setup
- Better handling of contacts spanning both streams
- Compact digest format for large networks
- Guidance for Google Contacts via gog connector

---

## v2.0 — Plugin

Durable state and typed tools.

- Persistent signal store (contacts, signals, outreach history)
- `relationship_signals` typed tool for querying the store
- `log_outreach` and `query_outreach` tools for tracking what was sent
- Deduplication across sources
- Google Calendar connector for automatic birthday/event detection
- Email connector for last-contact-date detection
- Configurable silence thresholds and scoring weights

---

## v3.0 — External signal engine (speculative)

- MCP server for polling external sources
- Webhook ingestion (Zapier, IFTTT, custom)
- Unified relationship graph
- Relationship health analytics

Build only if v2 proves the value of persistent relationship intelligence.

---

## Principles across all versions

1. Never send anything. All outputs are drafts — the user approves and sends themselves.
2. Always show evidence level and source.
3. Support global occasions and languages, not just Western/English defaults.
4. Separate work and personal streams.
5. Never overclaim access or intelligence.
6. Protect cross-context privacy — no work/personal stream leakage.
