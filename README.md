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

> ⏰ Last updated: 2026-10-27 14:45 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [SanHsien/khoj](https://github.com/SanHsien/khoj) | 1 | Python | 2026-10-27 | Your AI second brain. Self-hostable. Windows-first maintenance fork of khoj-ai/khoj. |
| 2 | [osoman2/Paper_implementations](https://github.com/osoman2/Paper_implementations) | 0 | Python | 2026-10-27 | Proofs of concept of recent AI research, shipped daily by an author agent behind CI and an independent reviewer. |
| 3 | [chentianxiong123/chat-clone](https://github.com/chentianxiong123/chat-clone) | 0 | Python | 2026-10-27 | Build a Qwen persona agent on low-cost GPUs (RX580/RX590) via RAG + LoRA — chat-record extraction, segmentation, embeddi |
| 4 | [grprakasam/agentic-ai-learning-lab](https://github.com/grprakasam/agentic-ai-learning-lab) | 0 | Python | 2026-10-27 | Agentic AI learning lab: workflow modernization agent (built, tested offline) and regulatory RAG on AWS with Terraform ( |
| 5 | [idevelopAI/llm-eval-control-plane](https://github.com/idevelopAI/llm-eval-control-plane) | 2 | Python | 2026-10-27 | Production-grade LLM evaluation control plane with FastAPI, PostgreSQL, release gates, worker recovery, and a privacy-bo |
| 6 | [IHUI-INF-AI/IHUI-AI](https://github.com/IHUI-INF-AI/IHUI-AI) | 31 | TypeScript | 2026-10-27 | Eight-platform full-stack AI operating system - unifies 176 LLMs via LangGraph + MCP + A2A. Multi-tenant RLS over 340 ta |
| 7 | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 148558 | Python | 2026-10-27 | The agent engineering platform. |
| 8 | [Matlan1/localm](https://github.com/Matlan1/localm) | 5 | Python | 2026-10-27 | Run local LLMs fully offline - chat, coding agent, image & music generation, knowledge/RAG, voice. Privacy-first, one CL |
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
