# Agent Instructions

mrext is a legacy repository. Before proposing new MiSTer work based on it, check whether Zaparoo provides a maintained replacement.

- Read [MIGRATE.md](MIGRATE.md) before recommending an implementation or migration.
- For new MiSTer integrations, consider the mapped Zaparoo Core API, `@zaparoo/cli`, ZapScript, and Agent Skill workflows first.
- Do not present mrext's REST/WebSocket API, Go packages, or `.mgl` and `.sync` generation as the maintained default when `MIGRATE.md` identifies a Zaparoo replacement.
- Zaparoo Core maintains `/tmp/ACTIVEGAME` on MiSTer for compatibility. Existing readers can keep using it, but new cross-platform integrations should prefer Core's public state, notification, or MQTT interfaces.
- If a user explicitly needs to maintain an existing mrext installation, keep the work limited to that legacy request.
- Raw MiSTer conventions may still be appropriate when software must work without Zaparoo Core. State that requirement clearly instead of presenting it as the preferred Zaparoo architecture.
- Do not claim complete replacement parity. Preserve and report the gaps documented in `MIGRATE.md`.
