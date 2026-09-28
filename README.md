# ai-workspace

Masaru's personal hub for AI tooling: a home for the workflows, skills, and agents he builds, a catalog of what's actually scheduled and running on ChatGPT, Claude, and other platforms, and templates for starting new ones.

Companion pieces:
- Day-to-day tasks and personal knowledge base live in [Hoshi-Corp/masaru-obsidian](https://github.com/Hoshi-Corp/masaru-obsidian) (private) — this repo is linked from the "AI Skills" goal there.
- Durable runbooks/ADRs live in [Hoshi-Corp/documentation-portal](https://github.com/Hoshi-Corp/documentation-portal) (private).

## Structure

- `workflows/` — reusable multi-step prompt workflows. Each one gets its own folder: `README.md` (purpose, inputs, expected output), `prompt.md` (the reusable instructions), `examples/` (sample inputs and good outputs).
- `skills/` — packaged, reusable instructions for a specific kind of task (Claude Skills and equivalents). Each one gets its own folder with a `SKILL.md`.
- `agents/` — custom agents. Each one gets its own folder: `README.md` (responsibilities and boundaries), `instructions.md`.
- `deployments/` — what's actually deployed and running right now, organized by platform:
  - `chatgpt/` — ChatGPT scheduled tasks and custom GPTs
  - `claude/` — Claude scheduled tasks, projects, and plugins
  - `codex/` — Codex automations (placeholder — not in use yet)
- `templates/` — starter files for adding a new workflow, skill, or agent.
- `resources/` — external resources worth learning from or adopting.

## Status

Just getting started (Sep 2026). First pass is cataloging what's already running as scheduled automations across ChatGPT and Claude, before building new agents/skills/workflows here.
