# skills

Packaged, reusable instructions for a specific kind of task — the same idea as Anthropic's Claude Skills format. Each one gets its own folder with a `SKILL.md`.

See `templates/skill-template/` for a starting point.

## Current skills

Each one is the Claude version of a template in `prompts/`. When you change one, update the other.

| Skill | Fires when | Prompt |
|---|---|---|
| `red-team` | You ask to critique or pre-mortem an idea | [red-team](../prompts/red-team.md) |
| `expert-review` | You ask how a professional would judge your approach | [expert-review](../prompts/expert-review.md) |
| `decision-matrix` | You're choosing between options | [decision-matrix](../prompts/decision-matrix.md) |
| `opportunity-scan` | You ask for overlooked opportunities | [opportunity-scan](../prompts/opportunity-scan.md) |
| `goal-system` | You want a goal or habit to stick | [goal-system](../prompts/goal-system.md) |
| `deep-read` | You share reading material and want more than a summary | [deep-read](../prompts/deep-read.md) |

Not skills on purpose: `explain-two-levels` and `learning-plan` overlap Claude's built-in `learn` skill; promote them only if `learn` falls short.

## Installing

This repo is a Claude plugin marketplace (`.claude-plugin/marketplace.json`); the skills install as the `ai-workspace` plugin, invoked as `/ai-workspace:<skill>`.

- **Claude Code:** `/plugin install ai-workspace --marketplace Hoshi-Corp/ai-workspace`. Update with `/plugin marketplace update ai-workspace`.
- **Claude desktop / claude.ai:** Customize → Plugins → Add → Add marketplace → `Hoshi-Corp/ai-workspace`, then install `ai-workspace`. Private repo: connect GitHub and give the Claude GitHub App access when asked. Turn on "Sync automatically" to pick up merges.

Record what's installed where in `deployments/claude/`.
