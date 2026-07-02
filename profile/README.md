<div align="center">

# 21 Stark AI

**A personal engineering lab for multi-agent tooling and infrastructure automation.**

Small, sharp tools. Claude + Codex + Gemini in parallel.
Everything ships through a PR. Nothing magic.

<br>

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

[**Aryeh Kiovetsky →**](https://21stark.com) · [**Writing →**](https://21stark.com/blog)

</div>

---

### The fleet

**🤖 Multi-agent tooling** — the core
- **`stark-skills`** — the hub: skills, prompts, and multi-LLM dispatchers (Claude + Codex + Gemini) plus the automation fleet
- **`stark-marketplace`** — plugin & skill catalog with its own engine
- **`stark-admin`** — workspace + cloud admin capabilities behind an MCP server

**⚙️ Automation planes**
- **`stark-night-watch`** — the long-lived automation plane (webhooks + cron)
- **`stark-automations`** — the lightweight execution plane (Scheduler → Pub/Sub → Cloud Functions → Anthropic)
- **`stark-team`** — the dashboard across it all

**☁️ Infrastructure foundations**
- **`ev-infra-group`** / **`infra-ai-platform`** — the shared Terraform base: VPC/NAT, WIF, split plan/apply CI service accounts, KMS, GAR, registry-driven subnets, LB + wildcard cert, monitoring
- **`infra-sentinel`** — platform health & observability

**🎨 Visual & media**
- **`stark-visual`** — image / video / media generation tools + an MCP server (Veo, animated WebP, brand icons, and more)
- **`stark-showcase`** — the public showcase surface
- **`stark-docs`** — PDF → Markdown extraction

**🎙️ Voice & knowledge**
- **`stark-voice-to-text`** — transcription pipeline (Speech-to-Text v2 + multi-LLM enhancement)
- **`stark-slack-indexer`** — searchable Slack knowledge base

### How it works here

- **Branch + PR for everything** — no exceptions
- **Every review's findings land on the PR** — nothing lost
- **Test live** — the real cloud surface, not just localhost
- **Go / TypeScript** — no new Python
- **Ships to main, no SLAs** — playground tier, and proud of it

<div align="center">
<br>
<sub>Multi-agent review · Infra-as-code · MCP servers · Claude Code</sub>
</div>
