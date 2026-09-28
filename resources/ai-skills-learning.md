# AI skills — learning resources

Resources worth learning from or adopting for building agents/skills/workflows here. Mirrors the "AI Skills" goal tracked in the [masaru-obsidian vault](https://github.com/Hoshi-Corp/masaru-obsidian/blob/main/Productivity/memory/goals/ai-skills.md) — this repo is where that goal's actual work happens now.

## claude-cto-team (Alireza Rezvani)
- **Link:** [github.com/alirezarezvani/claude-cto-team](https://github.com/alirezarezvani/claude-cto-team) — skills: [/skills](https://github.com/alirezarezvani/claude-cto-team/tree/main/skills)
- **Added:** Sep 24, 2026
- **What it is:** an MIT-licensed Claude Code plugin that acts as a "CTO team": 3 agents, 4 slash commands, and 12 skills
- **Agents:** `cto-orchestrator` (clarifies vague requests and routes them), `cto-architect` (system design and roadmaps), `strategic-cto-mentor` (stress-tests plans, build vs buy)
- **Commands:** `/validate`, `/design`, `/decide`, `/cto`
- **Skills:** request-analyzer, clarification-protocol, delegation-prompt-crafter, cost-estimator, architecture-pattern-selector, roadmap-generator, tech-stack-recommender, scalability-advisor, ml-cv-specialist, assumption-challenger, antipattern-detector, validation-report-generator
- **Install:** `claude /plugin install alirezarezvani/claude-cto-team`, or copy `agents/`, `commands/`, `skills/` into a project's `.claude/`
- [ ] Explore the agents and skills
- [ ] Try it on real architecture work (e.g. a roadmap, design, or build-vs-buy decision)
- [ ] Decide whether to adopt it, adapt parts of it, or use it as a model for the agents/skills built in this repo
