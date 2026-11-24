# instructions

Standing instructions: behaviour rules loaded into every session, on every platform. Unlike `prompts/` and `skills/`, these are never invoked — they are always on.

- `core.md` — the canonical text. Edit it here, then re-paste it everywhere it's deployed.

## Where to paste it

| Platform | Location |
|---|---|
| ChatGPT | Settings → Personalization → Custom Instructions ("How would you like ChatGPT to respond?") |
| Claude.ai / desktop | Settings → Profile → personal preferences |
| Claude Code | `~/.claude/CLAUDE.md` |

Record each deployment (and the date) in `deployments/<platform>/instructions.md`.

Keep `core.md` short: ChatGPT's field has a character limit (~1,500 when last checked), and every line costs attention in every conversation. Anything situational belongs in `prompts/` or `skills/` instead.
