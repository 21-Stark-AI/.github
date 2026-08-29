# 🧠 Data, knowledge & search

> The data platform, Slack and second-brain knowledge servers, the secrets vault, transcription and ingestion.

**12 repos** · [← the fleet](https://github.com/21StarkCom/.github/blob/main/profile/README.md#the-fleet) · ⭐ public · 🔒 internal · 🪦 retired

| Repo | Lang | Description |
| :-- | :-- | :-- |
| **[stark-data-core](https://github.com/21StarkCom/stark-data-core)** | `Python` | Data-platform service — Strawberry GraphQL API with RBAC over PostgreSQL powering sync connectors, reports, and dashboards. |
| **[stark-slack-indexer](https://github.com/21StarkCom/stark-slack-indexer)** | `Go` | Slack workspace knowledge server: GCS-fed ingestion, BigQuery hybrid search and an agentic ask layer. Go on GCP. |
| **[atlas](https://github.com/21StarkCom/atlas)** | `TypeScript` | The second-brain code monorepo: brain-cli, brain-hub and vault-keeper. The engine, not the notes (vault data lives in its own repo). |
| **[stark-2nd-brain-hub](https://github.com/21StarkCom/stark-2nd-brain-hub)** | `Go` | Hosted 2nd-brain gateway: live vault clone + remote brain MCP + personal Slack app + GitHub ingest, on GKE Autopilot |
| **[stark-2nd-brain-cli](https://github.com/21StarkCom/stark-2nd-brain-cli)** | `Go` | — |
| **[mimir](https://github.com/21StarkCom/mimir)** | `Swift` | Mac-native encrypted secrets manager, the vaulted replacement for on-disk credential files. |
| **[mimir-automations](https://github.com/21StarkCom/mimir-automations)** | `JavaScript` | Dedicated Mimir automation repo: JavaScript automations, no secrets ever. |
| **[transcript-optimizer](https://github.com/21StarkCom/transcript-optimizer)** | `Python` | Transcription & intelligence service — recordings → Chirp 3 → multi-stage LLM enhancement → Drive/Slack; pgvector search + dashboard. |
| **[kotodama](https://github.com/21StarkCom/kotodama)** | `Go` | Long-lived transcription and intelligence service. The Go rewrite of transcript-optimizer (personal playground, not production). |
| **[stark-invoices-collector](https://github.com/21StarkCom/stark-invoices-collector)** | `TypeScript` | Manifest V3 Chrome extension that harvests, parses, renames and files vendor invoice PDFs. Rides your logged-in sessions: no servers, no stored credentials. |
| **[infra-pulse](https://github.com/21StarkCom/infra-pulse)** | `Python` | The director's cockpit. Aggregates Jira, Slack, GitHub, Calendar, Gmail, Confluence and Drive into operational dashboards for running distributed engineering teams. |
| **[manual-auditor-project](https://github.com/21StarkCom/manual-auditor-project)** | `Python` | Data collection & harvesting orchestration for the Manual Auditor project |
