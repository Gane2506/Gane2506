### Hi, I'm Ganesh

I build AI agent systems and developer tools. I also build custom applications and websites for clients, taking each one from idea to production. My work spans Python, automation and infrastructure.

**Now:** building [Baton Agent Orchestrator](https://github.com/Gane2506/baton), an open-source CLI that runs a pipeline of AI agents on a git repo to turn an idea into reviewed, tested code.

---

#### Featured project: [Baton](https://github.com/Gane2506/baton) (`jev` CLI)

Baton plans an idea, validates the plan, then codes, tests, reviews and integrates the result. At every decision point, a decision model picks the agent, the model and how much effort to spend. A deterministic rules dispatcher takes over when the model is unavailable or unsure.

- **Workers:** Claude Code CLI, Codex CLI, and OpenRouter API models, including free ones
- **Safety:** hard budgets, a git worktree per task, a quality and security gate, secret redaction and an audit log
- **Day to day:** a web dashboard, an idea queue with a scheduler, a Kanban board, chat, and learning profiles that improve over time
- **Shipping:** `jev ship` opens pull requests and tracks KPIs

Contributions are welcome. Start with [CONTRIBUTING.md](https://github.com/Gane2506/baton/blob/main/CONTRIBUTING.md) and the [open issues](https://github.com/Gane2506/baton/issues).

---

#### What I build

- **Custom applications:** internal tools, dashboards, automations and integrations built for a business's own workflow
- **Websites:** fast, maintainable sites, from landing pages to full web apps
- **AI agents:** orchestration, tool use and pipelines with guardrails, as in Baton

#### What I work with

- **Language:** Python (asyncio, Typer, Pydantic, Starlette, SQLite)
- **AI and agents:** LLM orchestration with Claude Code, Codex, OpenRouter and MCP tools
- **Infra and automation:** Linux, Ansible, CI/CD with GitHub Actions, SSH tooling

#### How I build

- Tests come first, and the suite makes no network calls.
- Modules stay small enough for a newcomer to read in five minutes.
- Decisions are written down, with the reasons.
- Defaults are safe: budgets, sandboxed workers, and nothing destructive without a confirmation.
