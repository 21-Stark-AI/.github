<div align="center">

# 21 Stark AI

**My lab for multi-agent tooling and infrastructure automation.**
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

### The spine

```text
stark-skills             hub · skills + multi-LLM review (Claude · Codex · Gemini)
├── stark-night-watch    automation plane · webhooks + cron
├── stark-automations    execution plane · Scheduler → Pub/Sub → Cloud Fn → Anthropic
└── stark-team           dashboard over the fleet

ev-infra-group /         shared Terraform foundation
infra-ai-platform        VPC · WIF · KMS · GAR · registry-driven subnets · LB + cert
```

### The rest of the fleet

- **`stark-admin`** - workspace + cloud admin capabilities behind an `MCP` server
- **`stark-marketplace`** - plugin & skill catalog with its own engine
- **`stark-visual`** - image/video/media generation + an `MCP` server (`Veo`, animated WebP, brand icons)
- **`stark-voice-to-text`** - transcription pipeline (`Speech-to-Text v2` + multi-LLM enhancement)
- **`stark-slack-indexer`** - searchable Slack knowledge base
- **`stark-docs`** - PDF → Markdown
- **`infra-sentinel`** - platform health & observability

### How it works here

- **Branch + PR for everything** - no exceptions
- **Every review's findings land on the PR** - nothing lost
- **Test live** - the real cloud surface, not localhost
- **Go / TypeScript** - no new Python
- **Ships to `main`, no SLAs** - it's a playground, that's the point
