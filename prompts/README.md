# prompts

Copy-paste prompt templates for tasks you run on demand. They work on any platform (ChatGPT, Claude, others): copy the block, fill the `[PLACEHOLDERS]`, send.

On Claude, most of these also exist as a skill in `skills/` that fires on its own, so you don't need to paste. Each file links its skill. **When you change a prompt, update its skill too** (and vice versa) — they are two copies of the same behaviour.

| Prompt | Use when | Claude skill |
|---|---|---|
| [red-team](red-team.md) | Stress-testing an idea or plan | `red-team` |
| [explain-two-levels](explain-two-levels.md) | A quick reference-card explanation of a topic | — (use `learn` for real learning) |
| [expert-review](expert-review.md) | Getting your current approach to something reviewed | `expert-review` |
| [decision-matrix](decision-matrix.md) | Choosing between two options | `decision-matrix` |
| [opportunity-scan](opportunity-scan.md) | Finding overlooked opportunities in a sector, skill, or business | `opportunity-scan` |
| [learning-plan](learning-plan.md) | Planning how to master a skill | — (try `learn` first) |
| [goal-system](goal-system.md) | Turning a goal into a repeatable system | `goal-system` |
| [deep-read](deep-read.md) | Extracting insight from an article, book, or transcript | `deep-read` |

"Ask clarifying questions first" isn't here: it's in `instructions/core.md`. To force it, say "ask me first".
