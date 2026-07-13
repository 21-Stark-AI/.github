<div align="center">

# 21Stark

**One engineer's platform org, run as a playground.**
Multi-agent tooling, infra-as-code, and `MCP` servers. `Claude` + `Codex` + `Gemini` in parallel.

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

- **[stark-skills](https://github.com/21-Stark-AI/stark-skills)** - multi-agent PR code review. 3 AI agents × N domains, hierarchical config, prompts that improve themselves. The flagship.
- **[stark-marketplace](https://github.com/21-Stark-AI/stark-marketplace)** - share skills, prompts, commands, agents, and MCP servers across `Claude Code`, `Codex`, and `Gemini`.
- **[agent-native](https://github.com/21-Stark-AI/agent-native)** - my fork of Builder.io's framework; my GCP deployment of it (Cloud Run behind one origin, `Terraform` + Actions, Cloud SQL on a private IP) runs privately.

### Behind the curtain

35 repos, most of them private. What that adds up to, solo:

- Multi-cloud `Terraform` foundations that provision and validate themselves - Workload Identity Federation, split plan/apply CI identities, `KMS`, a registry that drives the subnets, one shared LB + wildcard cert.
- A vendor-admin layer over a dozen SaaS APIs, exposed as **one `MCP` tool across 400+ capabilities**.
- Self-hosted observability - logs, metrics, dashboards, alerts - on its own tier.
- A Slack knowledge server: `BigQuery` hybrid search with an agentic ask layer.
- A transcription pipeline - `Speech-to-Text v2` into multi-stage LLM enhancement.
- Image and video generation behind `MCP` - `Veo`, animated media, brand icons.
- A second brain, with its own `MCP` server and CLI.

### How it works here

- **Branch + PR for everything** - no exceptions
- **Every review's findings land on the PR** - nothing lost
- **Test live** - the real cloud surface, not localhost
- **Go / TypeScript** - no new Python

<div align="center">
<br>
<sub>Ships to <code>main</code>. No SLAs. That's the point.</sub>
</div>
