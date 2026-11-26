# ai-workspace

Masaru's personal hub for AI tooling: a home for the workflows, skills, and agents he builds, a catalog of what's actually scheduled and running on ChatGPT, Claude, and other platforms, and templates for starting new ones.

Companion pieces:
- Day-to-day tasks and personal knowledge base live in [Hoshi-Corp/masaru-obsidian](https://github.com/Hoshi-Corp/masaru-obsidian) (private) — this repo is linked from the "AI Skills" goal there.
- Durable runbooks/ADRs live in [Hoshi-Corp/documentation-portal](https://github.com/Hoshi-Corp/documentation-portal) (private).

## Structure

- `instructions/` — standing behaviour rules pasted into every platform's custom instructions (always on).
- `prompts/` — copy-paste prompt templates for on-demand tasks; work on any platform.
- `workflows/` — reusable multi-step prompt workflows. Each one gets its own folder: `README.md` (purpose, inputs, expected output), `prompt.md` (the reusable instructions), `examples/` (sample inputs and good outputs).
- `skills/` — packaged, reusable instructions for a specific kind of task (Claude Skills and equivalents). Each one gets its own folder with a `SKILL.md`.
- For a custom agent, use `templates/agent-template/` to document its responsibilities and boundaries and draft its system prompt. Reserve `agents/` for Claude agent definitions. The plugin currently ships six skills.
- `deployments/` — what's actually deployed and running right now, organized by platform:
  - `chatgpt/` — ChatGPT scheduled tasks, custom GPTs, and custom instructions
  - `claude/` — Claude scheduled tasks, projects, plugins, standing instructions, and installed skills
  - `codex/` — Codex automations (placeholder — not in use yet)
- `templates/` — starter files for adding a new workflow, skill, or agent.
- `resources/` — external resources worth learning from or adopting.

## Install the skills in Claude

In Claude Desktop or claude.ai, open **Customize → Plugins → Add → Add marketplace**. Enter `Hoshi-Corp/ai-workspace`, then select and install `ai-workspace`.

In Claude Code, run these commands in order:

```
/plugin marketplace add Hoshi-Corp/ai-workspace
/plugin install ai-workspace@ai-workspace
```

See the [skill list](skills/README.md). This project is available under the [MIT License](LICENSE).

## Status

Just getting started (Sep 2026). First pass is cataloging what's already running as scheduled automations across ChatGPT and Claude, before building new agents/skills/workflows here.
