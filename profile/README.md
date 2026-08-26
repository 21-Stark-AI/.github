<div align="center">

# 21Stark

**One engineer's platform org, run as a playground.**
Multi-agent tooling, infra-as-code and `MCP` servers. `Claude` + `Codex` + `Gemini` in parallel.

<br>

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

[**Aryeh Kiovetsky**](https://21stark.com) · [**Writing**](https://21stark.com/blog)

</div>

---

### Open source

- **[stark-skills](https://github.com/21StarkCom/stark-skills)**: the development workflow for `Claude Code` and `Codex`. Human-gated spec and plan, check-gated build, evidence-contract PR review, multi-agent IaC review, session ops. The flagship.
- **[bifrost](https://github.com/21StarkCom/bifrost)**: the marketplace. One catalog of skills, prompts, commands, agents and MCP servers, rendered per runtime for `Claude Code`, `Codex` and `Gemini`, served at [marketplace.21stark.com](https://marketplace.21stark.com).

### Behind the curtain

Three dozen repos, most of them private. What that adds up to, solo:

- Multi-cloud `Terraform` foundations that provision and validate themselves: Workload Identity Federation, split plan/apply CI identities, `KMS`, a registry that drives the subnets, one shared LB and wildcard cert.
- GitHub itself as code: enterprise and org governance in Terraform, import-first, PR-reviewed.
- A vendor-admin layer over a dozen SaaS APIs: **1,300+ capabilities** behind keyfile auth, allowlisted transports, gated writes and kill switches.
- Self-hosted observability on its own tier: logs, metrics, dashboards, alerts.
- A Slack knowledge server: `BigQuery` hybrid search with an agentic ask layer.
- An always-on ops agent in Slack that keeps tickets current and dispatches work from a durable local daemon.
- A transcription pipeline: `Speech-to-Text v2` into multi-stage LLM enhancement.
- Image, video and document generation behind `MCP`: `Veo`, `GPT Image`, `Nano Banana`; Excel, Word, PowerPoint, PDF.
- A second brain with its own CLI and sync hub.
- A Mac-native encrypted secrets manager. No credential files on disk.

### How it works here

- **Branch + PR for everything.** No exceptions.
- **Every review's findings land on the PR.** Nothing lost.
- **Test live.** The real cloud surface, not localhost.
- **Go and TypeScript.** No new Python.

<div align="center">
<br>
<sub>Ships to <code>main</code>. No SLAs. That's the point.</sub>
</div>
