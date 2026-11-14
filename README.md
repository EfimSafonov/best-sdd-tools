# Best SDD Tools

> A short, opinionated list of the spec-driven development (SDD) tools that matter: the ones teams actually ship with, not every weekend experiment.

[Spec-driven development](https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html) means writing the specification first and letting it drive the code, tests and review. With AI coding agents it is the difference between guessing and engineering.

📄 [Download as PDF](best-sdd-tools.pdf)

**Inclusion bar:** an established product from a known company, or an open-source project with 10k+ GitHub stars and active maintenance. Long-tail lists already exist (see [Related](#related)).

## Contents

- [Spec Platforms](#spec-platforms)
- [Spec Toolkits](#spec-toolkits)
- [Agent Methodologies](#agent-methodologies)
- [IDEs](#ides)
- [Task & Workflow Management](#task--workflow-management)
- [Standards](#standards)
- [Related](#related)

## Spec Platforms

- [Entalpa](https://entalpa.com) [![](https://img.shields.io/github/stars/entalpa/entalpa-mcp.svg?cacheSeconds=86400)](https://github.com/entalpa/entalpa-mcp) - Persistent, MCP-native spec layer for AI coding agents: stakeholders, user stories and requirements with acceptance criteria, open questions raised before the build, locked requirements, and traceability to code and tests. Works with Claude Code, Cursor and Codex, and composes with Spec Kit and OpenSpec instead of replacing them.

## Spec Toolkits

- [Spec Kit](https://github.com/github/spec-kit) ![](https://img.shields.io/github/stars/github/spec-kit.svg?cacheSeconds=86400) - GitHub's open-source toolkit: `specify`, `plan`, `tasks`, `implement` commands that turn product scenarios into a spec, a technical plan and an ordered task list for any coding agent.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) ![](https://img.shields.io/github/stars/Fission-AI/OpenSpec.svg?cacheSeconds=86400) - Lightweight change-based specs (proposal, spec deltas, design, tasks) that align humans and AI assistants before code is written; strong fit for brownfield repos.

## Agent Methodologies

- [Superpowers](https://github.com/obra/superpowers) ![](https://img.shields.io/github/stars/obra/superpowers.svg?cacheSeconds=86400) - Skills-based development methodology for coding agents: brainstorm, approved spec, written plan, subagent execution with TDD and review.
- [Agent Skills](https://github.com/addyosmani/agent-skills) ![](https://img.shields.io/github/stars/addyosmani/agent-skills.svg?cacheSeconds=86400) - Production-grade skill pack with explicit spec-to-plan-to-build workflows and quality gates.
- [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) ![](https://img.shields.io/github/stars/bmad-code-org/BMAD-METHOD.svg?cacheSeconds=86400) - Agile AI-driven development with role agents (analyst, PM, architect, scrum master, dev, QA) that hand off PRDs, architecture docs and stories.
- [GSD](https://github.com/open-gsd/gsd-core) ![](https://img.shields.io/github/stars/open-gsd/gsd-core.svg?cacheSeconds=86400) - Light-weight meta-prompting, context engineering and spec-driven development system for coding agents.

## IDEs

- [Kiro](https://kiro.dev) ![](https://img.shields.io/github/stars/kirodotdev/Kiro.svg?cacheSeconds=86400) - AWS's agentic IDE built around specs: requirements in EARS notation, design and task files, plus hooks and steering docs.

## Task & Workflow Management

- [Taskmaster](https://github.com/eyaltoledano/claude-task-master) ![](https://img.shields.io/github/stars/eyaltoledano/claude-task-master.svg?cacheSeconds=86400) - Parses a PRD into dependency-ordered tasks and drives implementation in Cursor, Claude Code and other agents.
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) ![](https://img.shields.io/github/stars/BloopAI/vibe-kanban.svg?cacheSeconds=86400) - Kanban board that runs Claude Code, Codex and other agents in parallel, one isolated worktree per task, with review before merge.

## Standards

- [AGENTS.md](https://github.com/agentsmd/agents.md) ![](https://img.shields.io/github/stars/agentsmd/agents.md.svg?cacheSeconds=86400) - Open Markdown format for guiding coding agents, read by most major agents.

## Related

- [Awesome Spec-Driven Development](https://github.com/engineering4ai/awesome-spec-driven-development) - The long-tail list: every SDD tool, big and small.

## Contributing

PRs welcome for tools that meet the inclusion bar. One line per tool, factual description, no marketing superlatives.

## License

[CC0 1.0](LICENSE)
