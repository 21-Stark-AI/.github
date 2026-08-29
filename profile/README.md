<div align="center">

# 21Stark

**One engineer's platform org, run as a playground.**
Multi-agent tooling, infra-as-code and `MCP` servers. `Claude` + `Codex` + `Gemini`, in parallel.

<br>

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

`58 repositories` · `Go` + `TypeScript` first · `one operator` · `ships to main`

[**Aryeh Kiovetsky**](https://21stark.com) · [**Writing**](https://21stark.com/blog)

</div>

---

### Open source

The public face of the fleet — the rest is private by default.

- **[stark-skills](https://github.com/21StarkCom/stark-skills)** — the development workflow for `Claude Code` and `Codex`. Human-gated spec and plan, check-gated build, evidence-contract PR review, multi-agent IaC review, session ops. **The flagship.**
- **[bifrost](https://github.com/21StarkCom/bifrost)** — the marketplace. One catalog of skills, prompts, commands, agents and `MCP` servers, rendered per runtime for `Claude Code`, `Codex` and `Gemini`, served at [marketplace.21stark.com](https://marketplace.21stark.com).

---

### The fleet

Three dozen private repos, run solo. What they add up to, by domain:

**Agents & tooling** — orchestrating `Claude Code`, `Codex` and `Gemini`
- A multi-agent dev workflow: human-gated spec and plan, check-gated build, evidence-contract review.
- A cross-runtime marketplace of skills, commands and `MCP` servers, rendered per host.
- Domain-specialized code-review agents on `Cloud Run` — DevOps, a11y, dependencies, docs, API-compat.
- A typed engine for driving fleets of coding agents over a terminal control socket.
- An always-on `Slack` ops agent on a durable local daemon that keeps tickets current and dispatches work.

**Platform & infra** — foundations that provision and validate themselves
- Multi-cloud `Terraform`: Workload Identity Federation, split plan/apply CI identities, `KMS`, a registry that drives the subnets, one shared LB and wildcard cert.
- GitHub itself as code: enterprise and org governance in `Terraform`, import-first, PR-reviewed.
- Self-hosted observability on its own tier: logs, metrics, dashboards, alerts.

**Vendor & workspace administration**
- A capability layer over a dozen SaaS APIs — **1,300+ operations** behind keyfile auth, allowlisted transports, gated writes and kill switches.

**Data & knowledge**
- A `GraphQL` data platform with RBAC over `PostgreSQL`, fronted by `MCP` servers.
- A `Slack` knowledge server: `BigQuery` hybrid search with an agentic ask layer.
- A second brain with its own CLI and sync hub.
- A Mac-native encrypted secrets manager — no credential files on disk.

**Media & documents** — behind `MCP`
- Image and video: `Veo`, `GPT Image`, `Nano Banana`.
- Documents: Excel, Word, PowerPoint, PDF.
- Transcription: `Speech-to-Text v2` into multi-stage LLM enhancement.

---

### How it works here

| | |
|---|---|
| **Branch + PR for everything** | No exceptions. Nothing lands on `main` by hand. |
| **Findings land on the PR** | Every review's output is attached. Nothing lost. |
| **Test live** | The real cloud surface, not localhost. |
| **Go and TypeScript** | No new Python. |

<div align="center">
<br>
<sub>Ships to <code>main</code>. No SLAs. That's the point.</sub>
</div>
