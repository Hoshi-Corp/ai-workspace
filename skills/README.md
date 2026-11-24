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

- **Claude Code:** symlink each folder into `~/.claude/skills/`, e.g. `ln -s "$PWD/red-team" ~/.claude/skills/red-team`. Symlinks keep this repo the single source.
- **Claude.ai / desktop:** zip the skill folder and upload it under Settings → Capabilities → Skills.

Record what's installed where in `deployments/claude/`.
