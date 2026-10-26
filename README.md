<!--
SEO: rag radar
-->

<div align="center">

# RAG Radar

Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/rag-radar?style=for-the-badge&logo=github)](https://github.com/linny006/rag-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/rag-radar?style=for-the-badge)](https://github.com/linny006/rag-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-15-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-26 13:45 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [oceanbase/seekdb](https://github.com/oceanbase/seekdb) | 3188 | C++ | 2026-10-26 | The AI-Native Search Database. Best for agent storage, it unifies vector, text, structured, and semi-structured data int |
| 2 | [nwl01234/rag-docs-bot](https://github.com/nwl01234/rag-docs-bot) | 0 | Python | 2026-10-26 | AI bot answering over corporate docs with source citations, fully offline |
| 3 | [prasad-kavuri/prasad-portfolio](https://github.com/prasad-kavuri/prasad-portfolio) | 0 | TypeScript | 2026-10-26 | VP / Head of AI Engineering portfolio — 14 production AI demos, governance-first architecture. prasadkavuri.com |
| 4 | [Thazg/knowledge-intelligence-platform](https://github.com/Thazg/knowledge-intelligence-platform) | 1 | Python | 2026-10-26 | Production-minded Enterprise RAG platform with hybrid retrieval, benchmark-driven evaluation, cloud deployment, observab |
| 5 | [Azure/agent-landing-zone](https://github.com/Azure/agent-landing-zone) | 1190 | Python | 2026-10-26 | Enterprise-grade landing zone for AI agent applications on Azure. Deploy the secure infrastructure, the agent app, or bo |
| 6 | [77777R7/Octocrawl](https://github.com/77777R7/Octocrawl) | 2 | TypeScript | 2026-10-26 | Octocrawl: readable Markdown and checked fields from public web pages, for AI agents, RAG and research. Failures come ba |
| 7 | [ggozad/haiku.rag](https://github.com/ggozad/haiku.rag) | 636 | Python | 2026-10-26 | Agentic RAG for local and self-hosted document search: hybrid retrieval, reranking and multimodal RAG on embedded LanceD |
| 8 | [georgeguimaraes/arcana](https://github.com/georgeguimaraes/arcana) | 341 | Elixir | 2026-10-26 | Embeddable RAG library for Elixir/Phoenix with agentic pipelines and dashboard |
| 9 | [heyvaldemar/dify-traefik-letsencrypt-docker-compose](https://github.com/heyvaldemar/dify-traefik-letsencrypt-docker-compose) | 0 | Shell | 2026-10-26 | Dify with Let's Encrypt Using Docker Compose |
| 10 | [PersonaliAI/chatty](https://github.com/PersonaliAI/chatty) | 7 | TypeScript | 2026-10-26 | Open-source, self-hostable Zendesk and Intercom alternative for AI customer support: chat widget, shared inbox, real-tim |
| 11 | [markhuangai/dense-mem](https://github.com/markhuangai/dense-mem) | 39 | Go | 2026-10-26 | Self-hosted AI agent memory server with MCP, evidence provenance, typed claims, conflict detection, embeddings, recall,  |
| 12 | [forwaryan/rumor-checking](https://github.com/forwaryan/rumor-checking) | 0 | Python | 2026-10-26 | 带执行过程可视化的中文谣言核查:拆原子事实、多源并行检索、逐条判真假,全程流式可观测 |
| 13 | [horizonbymuneeb/agentic-rag-pipeline](https://github.com/horizonbymuneeb/agentic-rag-pipeline) | 0 | Python | 2026-10-26 | Agentic RAG with BM25 + dense hybrid retrieval, reciprocal rank fusion, query rewriting and a grounding check |
| 14 | [NirDiamant/GenAI_Agents](https://github.com/NirDiamant/GenAI_Agents) | 24690 | Jupyter Notebook | 2026-10-26 | 50+ tutorials and implementations for Generative AI Agent techniques, from basic conversational bots to complex multi-ag |
| 15 | [gnasseem/nyuad.life](https://github.com/gnasseem/nyuad.life) | 0 | TypeScript | 2026-10-26 | Answers for NYU Abu Dhabi students, from the Room of Requirement archive, official pages and other students. |
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
