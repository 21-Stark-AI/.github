<div align="center">

# 21Stark

**One engineer's platform org, run as a playground.**
Multi-agent tooling, infra-as-code and `MCP` servers. `Claude` + `Codex` + `Gemini`, in parallel.

<br>

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

`58 repositories` · `Go` + `TypeScript` first · `one operator` · `ships to main`

[**Aryeh Kiovetsky**](https://21stark.com) · [**Writing**](https://21stark.com/blog)

</div>

---

### ⭐ Open source

The public face of the fleet — the rest is private by default.

- **[stark-skills](https://github.com/21StarkCom/stark-skills)** — the development workflow for `Claude Code` and `Codex`. Human-gated spec and plan, check-gated build, evidence-contract PR review, multi-agent IaC review, session ops. **The flagship.**
- **[bifrost](https://github.com/21StarkCom/bifrost)** — the marketplace. One catalog of skills, prompts, commands, agents and `MCP` servers, rendered per runtime for `Claude Code`, `Codex` and `Gemini`, served at [marketplace.21stark.com](https://marketplace.21stark.com).

---

### The fleet

**58 repositories, run solo — the whole thing, by domain.** Each row opens a full index with every repo and what it does.

| Domain | Repos | What lives here |
| :-- | :-- | :-- |
| 🤖 **[Agents & AI workflow](https://github.com/21StarkCom/.github/blob/main/fleet/agents.md)** | 10 | The dev workflow, the marketplace, review agents, MCP servers, orchestration. |
| 🏗️ **[Platform & infrastructure](https://github.com/21StarkCom/.github/blob/main/fleet/platform.md)** | 8 | GCP + Terraform foundations, GKE, observability, GitHub-as-code. |
| 🔧 **[Vendor & workspace admin](https://github.com/21StarkCom/.github/blob/main/fleet/admin.md)** | 6 | A capability layer over a dozen SaaS APIs, behind gated writes and kill switches. |
| 🧠 **[Data, knowledge & search](https://github.com/21StarkCom/.github/blob/main/fleet/data.md)** | 12 | Data platform, Slack + second-brain knowledge, the secrets vault, transcription. |
| 🎨 **[Media & documents](https://github.com/21StarkCom/.github/blob/main/fleet/media.md)** | 4 | Image, video and document generation, behind MCP. |
| 💻 **[Frontend, design & UI](https://github.com/21StarkCom/.github/blob/main/fleet/frontend.md)** | 7 | Design system, command-center dashboards, the brand site, TUI + Stream Deck. |
| ⚙️ **[Ops & meta](https://github.com/21StarkCom/.github/blob/main/fleet/ops.md)** | 7 | Maintenance, notifications, the workspace constitution, this profile repo. |
| 🪦 **[Archived & retired](https://github.com/21StarkCom/.github/blob/main/fleet/archived.md)** | 4 | Decommissioned or superseded — kept as memory, not dependency. |

<sub>By language: **22** Go · **14** TypeScript · **8** Python · **5** Terraform (HCL) · **2** Swift · **+5** others</sub>

---

### How it works here

| | |
| :-- | :-- |
| **Branch + PR for everything** | No exceptions. Nothing lands on `main` by hand. |
| **Findings land on the PR** | Every review's output is attached. Nothing lost. |
| **Test live** | The real cloud surface, not localhost. |
| **Go and TypeScript** | No new Python. |

<div align="center">
<br>
<sub>Ships to <code>main</code>. No SLAs. That's the point.</sub>
</div>
