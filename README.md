<!--
SEO: rag radar
-->

<div align="center">

# RAG Radar

Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/rag-radar?style=for-the-badge&logo=github)](https://github.com/linny006/rag-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/rag-radar?style=for-the-badge)](https://github.com/linny006/rag-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-8-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

RAG Radar continuously monitors GitHub for newly published retrieval-augmented generation projects, libraries, and production patterns. It scores and categorizes discoveries by component type (chunking, embedding, retrieval, generation) and outputs a structured feed developers can subscribe to or browse. Powered by GitHub Actions and the GitHub Search API.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 16:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [iamswayam/incidentweave](https://github.com/iamswayam/incidentweave) | 7 | Python | 2026-10-27 | Evidence-grounded incident investigation for code repositories, built with hybrid retrieval, PostgreSQL/pgvector, and Ge |
| 2 | [SArora2712/InsightAI](https://github.com/SArora2712/InsightAI) | 0 | Python | 2026-10-27 | Multi-agent business analytics copilot: LangGraph, hybrid RAG, SQL agent, critique pass, confidence scoring |
| 3 | [Artexis10/exomem](https://github.com/Artexis10/exomem) | 9 | Python | 2026-10-27 | Self-hosted MCP server that makes your Obsidian/markdown vault searchable — text, PDFs, Office docs, images, audio — fro |
| 4 | [rajeshm71/ai-engineer-roadmap](https://github.com/rajeshm71/ai-engineer-roadmap) | 0 | — | 2026-10-27 | An opinionated, curated learning path from Python basics to production AI: classical ML, deep learning, LLMs, agents, an |
| 5 | [zexion7873/radar-rag](https://github.com/zexion7873/radar-rag) | 0 | Java | 2026-10-27 | Ask the GitHub Radar archive in Chinese or English: semantic search and cited answers from a Java 25 / Spring AI service |
| 6 | [alexk202/maqs-way](https://github.com/alexk202/maqs-way) | 0 | Python | 2026-10-27 | Common path from policies to implementation for long-term AI memory |
| 7 | [linny006/rag-radar](https://github.com/linny006/rag-radar) | 3 | Python | 2026-10-27 | Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes |
| 8 | [guilhermerissondev/guilhermerissondev.github.io](https://github.com/guilhermerissondev/guilhermerissondev.github.io) | 0 | HTML | 2026-10-27 | Portfólio pessoal - AI Software Engineer. LLM, RAG, agentes de IA e harnesses de avaliação. |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)
- [awesome-agent-skills](https://github.com/linny006/awesome-agent-skills) — Curated auto-updated awesome-list of AI agent skills (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.
