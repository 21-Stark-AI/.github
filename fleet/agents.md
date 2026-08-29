# 🤖 Agents & AI workflow

> The AI dev workflow, the marketplace, review agents, MCP servers and the orchestration that drives them.

**10 repos** · [← the fleet](https://github.com/21StarkCom/.github/blob/main/profile/README.md#the-fleet) · ⭐ public · 🔒 internal · 🪦 retired

| Repo | Lang | Description |
| :-- | :-- | :-- |
| **[stark-skills](https://github.com/21StarkCom/stark-skills)** ⭐ | `TypeScript` | AI-powered development workflow for Claude Code and Codex: human-gated spec and plan authoring, check-gated builds, evidence-contract PR review, multi-agent IaC review, and session ops. Gemini optional. |
| **[bifrost](https://github.com/21StarkCom/bifrost)** ⭐ | `Go` | Internal marketplace for sharing stark skills, prompts, commands, agents and MCP servers across Claude Code, Codex and Gemini. |
| **[stark-agents](https://github.com/21StarkCom/stark-agents)** | `Python` | Domain-specialized code-review agents on Cloud Run (DevOps/A11y/Dependency/Docs/APICompat/Cost) behind MCP; 3-LLM ensemble consensus. |
| **[stark-admin-agent](https://github.com/21StarkCom/stark-admin-agent)** | `TypeScript` | LLM agent exposed as one MCP tool over stark-admin's 466 capabilities |
| **[stark-mcp](https://github.com/21StarkCom/stark-mcp)** | `Go` | Go monorepo of MCP servers over the stark data platform (data/catalog/image/group-sync) — OAuth-gated, night-watch-scoped. |
| **[stark-automations](https://github.com/21StarkCom/stark-automations)** | `Python` | GCP execution layer for the stark automation fleet — Cloud Scheduler→Pub/Sub→Functions calling Anthropic with github/slack/shell tools. |
| **[alfred](https://github.com/21StarkCom/alfred)** | `Go` | Alfred, the always-on ops butler. Keeps ClickUp tickets current, runs a Slack agent over the fleet, and dispatches work from a durable local daemon. |
| **[hermod](https://github.com/21StarkCom/hermod)** | `TypeScript` | TypeScript engine and client for the cmux control API, built on Bun. |
| **[sleipnir](https://github.com/21StarkCom/sleipnir)** | `TypeScript` | Local harness driving a dedicated, persistent Chrome profile for ad-hoc agent tasks. Per-task UA, headless-capable. |
| **[user-management-agent](https://github.com/21StarkCom/user-management-agent)** | `Go` | uma: records how you onboard and offboard users on SaaS admin UIs, distills the recordings into declarative playbooks, and replays them for any email. Go and chromedp. |
