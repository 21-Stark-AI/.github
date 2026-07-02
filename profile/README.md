<div align="center">

# 21 Stark AI

**Multi-agent developer tooling, built in the open.**
`Claude` + `Codex` + `Gemini` in parallel. Everything ships through a PR.

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

### Building on

- **[agent-native](https://github.com/21-Stark-AI/agent-native)** - my fork of Builder.io's agent-native framework. My GCP deployment of it - Cloud Run behind one origin, `Terraform` + Actions, Cloud SQL on a private IP - lives in `agent-native-gcp` (private, in this org).

### The rest is private

A working fleet of ~30 repos behind the curtain: Terraform foundations (`ev-infra-group`, `infra-ai-platform`), the automation and execution planes, `MCP` servers over a vendor-admin capability library, plus data, voice, and visual tooling. It runs my day-to-day. Ships to `main`, no SLAs. It's a playground, that's the point.

### How it works here

- **Branch + PR for everything** - no exceptions
- **Every review's findings land on the PR** - nothing lost
- **Test live** - the real cloud surface, not localhost
- **Go / TypeScript** - no new Python
