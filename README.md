<!--
SEO: rag radar
-->

<div align="center">

# RAG Radar

Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes

[![Stars](https://img.shields.io/github/stars/linny006/rag-radar?style=for-the-badge&logo=github)](https://github.com/linny006/rag-radar/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/rag-radar?style=for-the-badge)](https://github.com/linny006/rag-radar/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-50-brightgreen?style=for-the-badge)](#)
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

> ⏰ Last updated: 2026-10-23 12:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [epqlffltm/ai-trpg](https://github.com/epqlffltm/ai-trpg) | 0 | Python | 2026-10-23 | LLM이 게임 상태를 바꾸지 못하게 설계한 AI TRPG 플랫폼 · 엔진이 판정하고 LLM은 구조화된 제안과 서술만 · 서버 4개(Django·FastAPI·NestJS·Go), RAG, 서비스 간 서명, 원장 기반 |
| 2 | [leskoont/askdocs-bot](https://github.com/leskoont/askdocs-bot) | 0 | Python | 2026-10-23 | Telegram bot that answers questions about your documents (RAG, local embeddings, any OpenAI-compatible LLM) |
| 3 | [r-uby-dev/llm](https://github.com/r-uby-dev/llm) | 145 | Ruby | 2026-10-23 | An agentic runtime |
| 4 | [LocketKeyLLC/scaffold-engine](https://github.com/LocketKeyLLC/scaffold-engine) | 0 | Python | 2026-10-23 | Self-hosted AI agent engine for local LLMs. Give it an idea — it researches the web, plans a DAG of steps, executes each |
| 5 | [letims/fastapi-docs-rag](https://github.com/letims/fastapi-docs-rag) | 0 | Python | 2026-10-23 | RAG over the FastAPI docs, built to study what happens when the first retrieval pass isn’t enough. Idempotent Postgres-q |
| 6 | [HungHsunHan/cs329z-assignment1-agentic-harness-reference](https://github.com/HungHsunHan/cs329z-assignment1-agentic-harness-reference) | 0 | Python | 2026-10-23 | Unofficial reference implementation for Stanford CS329Z Engineering AI Agents, Assignment 1: from-scratch agent harness, |
| 7 | [architecture-zero/architecture-zero](https://github.com/architecture-zero/architecture-zero) | 0 | Python | 2026-10-23 | A self-hosted AI assistant platform where trust is measured, not claimed - hybrid retrieval behind a reranker seam, clea |
| 8 | [IHUI-INF-AI/IHUI-AI](https://github.com/IHUI-INF-AI/IHUI-AI) | 31 | TypeScript | 2026-10-23 | Eight-platform full-stack AI operating system - unifies 176 LLMs via LangGraph + MCP + A2A. Multi-tenant RLS over 340 ta |
| 9 | [alexeyban/EKOS](https://github.com/alexeyban/EKOS) | 22 | Rust | 2026-10-23 | EKOS is an AI-native platform that continuously reconstructs, compiles, stores and serves enterprise knowledge. |
| 10 | [NITISH-R-G/hackerrank-orchestrate-skills](https://github.com/NITISH-R-G/hackerrank-orchestrate-skills) | 6 | Python | 2026-10-23 | Unofficial community toolkit for HackerRank Orchestrate: 8 agent skills (Claude Code, Codex, Cursor, Copilot) for the 24 |
| 11 | [SMESCH1/InforMessi](https://github.com/SMESCH1/InforMessi) | 1 | Python | 2026-10-23 | Automated daily Telegram pipeline about the Argentine national team. LLMs + RAG anti-repetition + GitHub Actions |
| 12 | [jakubstuglik/hybrid-code-rag-mcp](https://github.com/jakubstuglik/hybrid-code-rag-mcp) | 1 | Python | 2026-10-23 | Local code search engine for AI agents: incremental indexer, hybrid retrieval (BM25 + dense embeddings in Qdrant, RSF, p |
| 13 | [deepakpradhan1021/docRag](https://github.com/deepakpradhan1021/docRag) | 0 | Python | 2026-10-23 | Zero-Budget Document RAG System: Upload PDFs, ask questions, and receive grounded answers with verified source citations |
| 14 | [kagura-ai/memory-cloud](https://github.com/kagura-ai/memory-cloud) | 12 | Python | 2026-10-23 | Adaptive memory for AI agents & teams — beyond RAG. Self-hosted MCP server that gets smarter every time you search: hybr |
| 15 | [Atsirkunov/anchorcore](https://github.com/Atsirkunov/anchorcore) | 2 | Rust | 2026-10-23 | Local-first, source-available AI knowledge base: folders, Drive, Jira and Linear in one private memory with cited answer |
| 16 | [cortexkit/aft](https://github.com/cortexkit/aft) | 331 | Rust | 2026-10-23 | Give your agent a proper IDE and OS. The sensorimotor cortex for coding agents (OpenCode + Pi), part of CortexKit: symbo |
| 17 | [nike-cpu/mini-14](https://github.com/nike-cpu/mini-14) | 0 | HTML | 2026-10-23 | mini-14 v1.1 — 本地离线 AI 助手：Qwen2.5-1.5B + bge-m3 检索 + 分片索引 + 可选联网搜索 / 简繁切换（MIT） |
| 18 | [Le-Who/Bobby-Botique](https://github.com/Le-Who/Bobby-Botique) | 0 | Python | 2026-10-23 | Open-source Telegram AI assistant framework with provider routing, streaming recovery, agentic research, multimodal tool |
| 19 | [chetto1983/Aura](https://github.com/chetto1983/Aura) | 33 | Go | 2026-10-23 | Self-hosted AI agent in Go with temporal graph memory, scheduled jobs, MCP tools and Telegram/WhatsApp channels. Docker  |
| 20 | [dinulimann/rag-regulations](https://github.com/dinulimann/rag-regulations) | 0 | Python | 2026-10-23 | RAG over Indonesian employment regulations (PP 35/2021, PP 36/2021 as amended): OCR repair, amendment consolidation, pgv |
| 21 | [codecentric/c4-genai-suite](https://github.com/codecentric/c4-genai-suite) | 174 | TypeScript | 2026-10-23 | [archived] c4 GenAI Suite |
| 22 | [HiAi-gg/docsmint](https://github.com/HiAi-gg/docsmint) | 110 | TypeScript | 2026-10-23 | Open-source knowledge base for people and AI agents. Rich-text editing, hybrid search, GraphRAG, and MCP. Self-host with |
| 23 | [weihuaguo270-ops/react-agent](https://github.com/weihuaguo270-ops/react-agent) | 0 | Python | 2026-10-23 | Agent 业务执行底座：受控工具调用、多应用 HTTP、可审计轨迹与回归闭环 |
| 24 | [OfficialSpicrawl/docs2skill](https://github.com/OfficialSpicrawl/docs2skill) | 0 | JavaScript | 2026-10-23 | Turn any docs site into a Claude Code / Codex agent skill (SKILL.md), llms.txt, llms-full.txt and AGENTS.md. Web scrapin |
| 25 | [heyvaldemar/dify-traefik-letsencrypt-docker-compose](https://github.com/heyvaldemar/dify-traefik-letsencrypt-docker-compose) | 0 | Shell | 2026-10-23 | Dify with Let's Encrypt Using Docker Compose |
| 26 | [furuse-kazufumi/fullseye](https://github.com/furuse-kazufumi/fullseye) | 6 | HTML | 2026-10-23 | Fullseye — a numpy-native operator library for vision, 3-D and measurement: 3,000+ typed ops (v0.6.0) spanning 2-D imagi |
| 27 | [Mein-Augenstern/MUYI](https://github.com/Mein-Augenstern/MUYI) | 11 | JavaScript | 2026-10-23 | 📚 持续生长的后端×AI 生产级知识体系｜每篇从上线代码回写，真实类名可点击验证 · 追问链式深度标尺：答案经得起面试官连环追问 · 整库工程化治理：kb-upkeep 脚本体检零空壳零死链 + 配图全本地化 + VitePress 电子书 |
| 28 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 92722 | Go | 2026-10-23 | RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capa |
| 29 | [BauDahn/rag-local-system](https://github.com/BauDahn/rag-local-system) | 0 | Python | 2026-10-23 | Fully local, private RAG for your PDFs: hybrid retrieval (dense + BM25), cross-encoder reranking, verified citations and |
| 30 | [agentty-org/agentty](https://github.com/agentty-org/agentty) | 623 | C++ | 2026-10-23 | AI pair programming in your terminal — one static binary, sub-ms startup, any model |
| 31 | [Go-Go-Zeppelin/LumenMind-pi](https://github.com/Go-Go-Zeppelin/LumenMind-pi) | 0 | Python | 2026-10-23 | Multi-agent customer support with TypeScript/Pi SDK, Python/FastAPI, RAG, and SQLite memory (development preview) |
| 32 | [wenisch-tech/ContextCrate](https://github.com/wenisch-tech/ContextCrate) | 2 | Java | 2026-10-23 | ContextCrate is an open-source, self-hosted retrieval-augmented generation platform. It ingests websites and Git reposit |
| 33 | [pipeshub-ai/pipeshub-ai](https://github.com/pipeshub-ai/pipeshub-ai) | 3844 | Python | 2026-10-23 | The open-source context layer for AI agents. PipesHub turns your company's knowledge (Slack, Drive, Jira, GitHub, Micros |
| 34 | [iberi22/xavier](https://github.com/iberi22/xavier) | 1 | Rust | 2026-10-23 | Xavier — Rust vector memory & knowledge graph for AI agents (HTTP/CLI/MCP). Powers SWAL communal context |
| 35 | [schmitech/orbit](https://github.com/schmitech/orbit) | 355 | Python | 2026-10-23 | Self-hosted AI gateway for private RAG, natural-language data access, and tool-calling agents. |
| 36 | [syed-adeel872/syed-adeel-waseem-portfolio](https://github.com/syed-adeel872/syed-adeel-waseem-portfolio) | 0 | HTML | 2026-10-23 | Portfolio of Syed Adeel Waseem — Agentic AI Developer specializing in AI automation, RAG systems, and AI-powered workflo |
| 37 | [iamswayam/incidentweave](https://github.com/iamswayam/incidentweave) | 6 | Python | 2026-10-23 | Evidence-grounded incident investigation for code repositories, built with hybrid retrieval, PostgreSQL/pgvector, and Ge |
| 38 | [pxlcrtiv/embed-playground](https://github.com/pxlcrtiv/embed-playground) | 0 | Python | 2026-10-23 | Compare lexical vs semantic search on a bundled DeFi/Web3 corpus: deterministic TF-IDF baseline, optional sentence-trans |
| 39 | [chedim/babyseat](https://github.com/chedim/babyseat) | 12 | Python | 2026-10-23 | Semantic slurper open-api proxy and claude agent with memory. Save tokens. Communicate through it. Your words and action |
| 40 | [Hashim57/olo-commons](https://github.com/Hashim57/olo-commons) | 0 | Python | 2026-10-23 | Olo Brain. Open, verifiable knowledge base an AI can think with. Grows hourly from trusted open sources (Wikipedia, Inte |
| 41 | [espadat-studio/pi-memsearch](https://github.com/espadat-studio/pi-memsearch) | 3 | TypeScript | 2026-10-23 | Long-term memory for pi: recall what a session learned weeks later, by meaning, from the memsearch store Claude Code, Co |
| 42 | [frankxai/ai-architect-academy](https://github.com/frankxai/ai-architect-academy) | 3 | HTML | 2026-10-23 | Learn AI architecture by building with a coding agent: hands-on labs for RAG, multi-agent systems and MCP servers, plus  |
| 43 | [xerj-org/xerj](https://github.com/xerj-org/xerj) | 13276 | Rust | 2026-10-23 | Local-first search engine and MCP server for AI agents. One Rust binary indexes code, docs, logs, JSONL/CSV and PDFs for |
| 44 | [xujian519/sati](https://github.com/xujian519/sati) | 3 | TypeScript | 2026-10-23 | 面向专利代理人、专利律师与知识产权从业者的桌面端专利智能体 |
| 45 | [gyr0byte/Generative-AI](https://github.com/gyr0byte/Generative-AI) | 0 | Python | 2026-10-23 | Hands-on GenAI projects learning with LangChain: chatbots, RAG pipelines, and AI agents. Built while learning LLM engine |
| 46 | [Bike4Mind/bike4mind](https://github.com/Bike4Mind/bike4mind) | 90 | TypeScript | 2026-10-23 | The open-core AI workbench — notebooks, agents, RAG, voice, and images across any model: OpenAI, Anthropic, Google, xAI, |
| 47 | [privacydied/discord-llm-chatbot](https://github.com/privacydied/discord-llm-chatbot) | 2 | Python | 2026-10-23 | Discord bot that integrates LLMs with multimodal capabilities including text chat, voice synthesis (TTS), speech recogni |
| 48 | [sdwurg180507280211/metersphere](https://github.com/sdwurg180507280211/metersphere) | 0 | Java | 2026-10-23 | MeterSphere v2.10 个人开发分支 — 一站式开源持续测试平台。工作流引擎(Flowable 7) · 需求池(从0到1) · 微前端(qiankun→micro-app) · AI知识库 · 测试跟踪，含个人笔记与创意项目。 |
| 49 | [leon1111-wgl/loopdesk](https://github.com/leon1111-wgl/loopdesk) | 0 | Python | 2026-10-23 | 证据优先、会自我进化的企业客服 Agent 平台：RAG、工具调用、人工审批、逐句证据校验、数据飞轮与回归评测 |
| 50 | [kldhsh123/Afterglow](https://github.com/kldhsh123/Afterglow) | 319 | Python | 2026-10-23 | By combining chat histories from social media with a vector database, AI can more convincingly recreate someone’s person |
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
