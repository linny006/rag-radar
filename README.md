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

> ⏰ Last updated: 2026-09-24 20:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [mzquadri/insureassist-rag-mlops](https://github.com/mzquadri/insureassist-rag-mlops) | 0 | Python | 2026-09-24 | Measured RAG reference implementation over NFIP policy forms: BGE + BM25 hybrid retrieval, FastAPI, Qdrant, reproducible |
| 2 | [aureliocpr-ctrl/verimem](https://github.com/aureliocpr-ctrl/verimem) | 4 | Python | 2026-09-24 | Verified memory for AI agents: gated writes, provenance on every read, bi-temporal history, abstention instead of halluc |
| 3 | [equitek/engram](https://github.com/equitek/engram) | 1 | Rust | 2026-09-24 | Give your agents a brain. Semantic memory for AI agents — index your knowledge base, search by meaning, single binary. |
| 4 | [1ay1/agentty](https://github.com/1ay1/agentty) | 603 | C++ | 2026-09-24 | AI pair programming in your terminal — one static binary, sub-ms startup, any model |
| 5 | [alanmz-crypto/convmem](https://github.com/alanmz-crypto/convmem) | 0 | Python | 2026-09-24 | Personal, local-first conversation memory and evidence retrieval for AI coding assistants, with provenance, evaluation,  |
| 6 | [RailtownAI/railtracks](https://github.com/RailtownAI/railtracks) | 185 | Python | 2026-09-24 | An agentic framework that helps developers build resilient agentic systems |
| 7 | [connortessaro/kizuki](https://github.com/connortessaro/kizuki) | 0 | TypeScript | 2026-09-24 | Ask questions about engineering work that need both a number and a reason — git activity in DuckDB, docs in pgvector, hy |
| 8 | [xmor/ara](https://github.com/xmor/ara) | 6 | Java | 2026-09-24 | ARA — Agent Runtime Architecture: Java 21 framework for building autonomous AI agents and multi-agent systems. LLM integ |
| 9 | [i-ops-hq/assurance](https://github.com/i-ops-hq/assurance) | 1 | Python | 2026-09-24 | Your AI agent says it's done. Assurance tells you what it didn't check. uvx assurance audit — no model, no network. |
| 10 | [sjsu-masters-projects/medi-agent](https://github.com/sjsu-masters-projects/medi-agent) | 0 | Python | 2026-09-24 | Patient app and clinician dashboard over a FastAPI backend, where LangGraph agents triage incoming chat, pull structured |
| 11 | [andrelair-platform/retrieva-backend](https://github.com/andrelair-platform/retrieva-backend) | 0 | TypeScript | 2026-09-24 | Retrieva backend — Node/ESM Express + Drizzle/Postgres + LangChain RAG API for DORA TPRM (runs on the ktayl-solution min |
| 12 | [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx) | 32237 | Python | 2026-09-24 | Open Source AI Platform - AI Chat with advanced features that works with every LLM |
| 13 | [ranfysvalle02/cinematlas](https://github.com/ranfysvalle02/cinematlas) | 0 | Python | 2026-09-24 | Fuse within a unit, chunk across units: joint-vector search for video, photos, slides and any multimodal records on Mong |
| 14 | [nikolai-vysotskyi/trace-mcp](https://github.com/nikolai-vysotskyi/trace-mcp) | 182 | TypeScript | 2026-09-24 | Framework-aware code intelligence MCP server — 88 framework integrations, 81 languages, 72.7% fewer input tokens to revi |
| 15 | [covan-ai/covan](https://github.com/covan-ai/covan) | 21 | TypeScript | 2026-09-24 | A shared AI agent for your team. Everyone trains it together; everyone talks to it privately. Self-hostable, AGPL-3.0. |
| 16 | [Ozgurisikdamar/Membrane-AI](https://github.com/Ozgurisikdamar/Membrane-AI) | 0 | Go | 2026-09-24 | Real-time security and architectural guardrails for AI coding agents. |
| 17 | [xyver/daedal-map](https://github.com/xyver/daedal-map) | 2 | Python | 2026-09-24 | Open geographic query engine — ask place-based questions in natural language, get answers on a map. Covers disasters, de |
| 18 | [wrobeltomasz/OpenSparrow](https://github.com/wrobeltomasz/OpenSparrow) | 3 | JavaScript | 2026-09-24 | OpenSparrow is a nocode platform for building internal systems. Tables, forms, dashboards, and calendars are generated f |
| 19 | [shu0819-sjy/mini-rag-from-scratch](https://github.com/shu0819-sjy/mini-rag-from-scratch) | 0 | Python | 2026-09-24 | From-scratch RAG: chunking → sentence-transformers embeddings → NumPy cosine retrieval → recall@k eval, no vector DB |
| 20 | [gaurav-gandhi-2411/gg-portfolio](https://github.com/gaurav-gandhi-2411/gg-portfolio) | 0 | HTML | 2026-09-24 | AI/ML portfolio: every metric traces to a committed source, kept honest by CI gates. |
| 21 | [furuse-kazufumi/fullseye](https://github.com/furuse-kazufumi/fullseye) | 3 | HTML | 2026-09-24 | Fullseye — a numpy-native operator library for vision, 3-D and measurement: 1,500+ typed ops spanning 2-D imaging, point |
| 22 | [Het415/listinglens](https://github.com/Het415/listinglens) | 1 | TypeScript | 2026-09-24 | AI-powered Amazon seller intelligence platform — BERT sentiment, XGBoost return risk prediction, and RAG chatbot grounde |
| 23 | [smoketurner/quack](https://github.com/smoketurner/quack) | 0 | Rust | 2026-09-24 | One offline agent that answers across your tables, your documents, and the knowledge graph between them. |
| 24 | [ajschlosser/DerridAI](https://github.com/ajschlosser/DerridAI) | 1 | Python | 2026-09-24 | DerridAI is a minimal Python implementation of a Retrieval‑Augmented Generation (RAG) pipeline combined with a LoRA fine |
| 25 | [Merp4/dexicon](https://github.com/Merp4/dexicon) | 0 | C# | 2026-09-24 | Semantic search over your own code, documents and git history, for coding agents over MCP. One container on your machine |
| 26 | [GeneralTradingSarl/le-fil-d-execution](https://github.com/GeneralTradingSarl/le-fil-d-execution) | 1 | — | 2026-09-24 | Le Fil d'Execution : concevoir, exploiter et gouverner des workflows automatises avec n8n. Manuel de 104 pages, PDF libr |
| 27 | [davidgomesdev/O-Fingidor](https://github.com/davidgomesdev/O-Fingidor) | 0 | Kotlin | 2026-09-24 | An AI bot that impersonates Fernando Pessoa with his texts |
| 28 | [tukue/devsecops-platform-agent](https://github.com/tukue/devsecops-platform-agent) | 0 | Python | 2026-09-24 | AI-assisted DevSecOps advisor that classifies platform-security findings and provides actionable remediation guidance |
| 29 | [FaultMaven/faultmaven](https://github.com/FaultMaven/faultmaven) | 3 | Python | 2026-09-24 | The core API and orchestration layer for FaultMaven, connecting the browser extension and dashboard to your infrastructu |
| 30 | [ac12644/langgraph-starter-kit](https://github.com/ac12644/langgraph-starter-kit) | 23 | TypeScript | 2026-09-24 | Production-ready multi-agent starter kit for LangGraph — 7 patterns, 6 LLM providers, CLI scaffolder, MCP integration, a |
| 31 | [hadis98/NutriChat](https://github.com/hadis98/NutriChat) | 0 | Jupyter Notebook | 2026-09-24 | code for the paper "NutriChat: Evaluating Safety-Aware Retrieval-Augmented Generation for Nutrition Textbook Question An |
| 32 | [darunbjork/darun.dev](https://github.com/darunbjork/darun.dev) | 0 | TypeScript | 2026-09-24 | Production AI portfolio platform. A full-stack TypeScript monorepo with an admin dashboard, AI chat (RAG), GitHub integr |
| 33 | [luqmankhan10/rag-chatbot](https://github.com/luqmankhan10/rag-chatbot) | 0 | Python | 2026-09-24 | RAG chatbot for querying PDF and company documents, built with LangChain, FAISS/Chroma vector search, and Streamlit |
| 34 | [memvara/memvara](https://github.com/memvara/memvara) | 1 | Python | 2026-09-24 | Bitemporal memory for AI agents: deterministic contradiction resolution, provenance, and retrieval at any point in time. |
| 35 | [mmarufov/Daily](https://github.com/mmarufov/Daily) | 0 | JavaScript | 2026-09-24 | iOS news app that builds you a personal daily edition. SwiftUI + FastAPI, ten-stage pipeline, and an offline eval harnes |
| 36 | [zinverno/veynrel](https://github.com/zinverno/veynrel) | 28 | TypeScript | 2026-09-24 | AI-powered Obsidian plugin for semantic search, vault auditing, note discovery and AI writing |
| 37 | [nevenincs/vaultspec-rag](https://github.com/nevenincs/vaultspec-rag) | 2 | Python | 2026-09-24 | Search code and feature records by meaning through the command line or Model Context Protocol (MCP). Inference runs on y |
| 38 | [benzac708/askvault](https://github.com/benzac708/askvault) | 0 | Python | 2026-09-24 | Ask your vault — RAG Q&A over private docs on K3s |
| 39 | [ttoss/soat](https://github.com/ttoss/soat) | 4 | TypeScript | 2026-09-24 | SOAT — open-source infrastructure for production-ready AI agents. |
| 40 | [onhazrat/tg-workspace](https://github.com/onhazrat/tg-workspace) | 0 | Python | 2026-09-24 | Self-hosted workspace for public Telegram channels: sync into PostgreSQL, then AI summaries, semantic chat, tagging and  |
| 41 | [elmira-orooji/advanced-rag-system](https://github.com/elmira-orooji/advanced-rag-system) | 0 | Python | 2026-09-24 | Source-grounded AI workspace for secure document intelligence, OCR, retrieval, and cited team conversations. |
| 42 | [Sirad12/Chatbot-BDPP](https://github.com/Sirad12/Chatbot-BDPP) | 0 | Python | 2026-09-24 | Chatbot RAG (Retrieval-Augmented Generation) répondant aux questions administratives sur les démarches de passeport au S |
| 43 | [janr0599/n8n-templates](https://github.com/janr0599/n8n-templates) | 0 | Python | 2026-09-24 | Production n8n patterns, exported, cleaned and generalised, with the error handling left in. Documented node by node. |
| 44 | [powabase-ai/agent-skills](https://github.com/powabase-ai/agent-skills) | 9 | TypeScript | 2026-09-24 | Agent Skills that help AI coding assistants build on Powabase — the AI Backend-as-a-Service (RAG, agents, orchestration, |
| 45 | [linny006/vector-db-live](https://github.com/linny006/vector-db-live) | 3 | Python | 2026-09-24 | Live-updating landscape of vector database projects, integrations, and benchmarks — refreshed every  |
| 46 | [linny006/rag-radar](https://github.com/linny006/rag-radar) | 3 | Python | 2026-09-24 | Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes |
| 47 | [Rumeasiyan/askwell](https://github.com/Rumeasiyan/askwell) | 0 | Python | 2026-09-24 | Local AI over your own files and databases. Asks when it's unsure, remembers your answers, cites every claim. Runs entir |
| 48 | [saadr123/RAG-Bench](https://github.com/saadr123/RAG-Bench) | 0 | Python | 2026-09-24 | An evaluation and cost-optimization harness for RAG pipelines.  |
| 49 | [shlok-shinde/SAR_and_Audit](https://github.com/shlok-shinde/SAR_and_Audit) | 0 | Python | 2026-09-24 | Local-first RAG that drafts SAR narratives and audits every sentence against the case data |
| 50 | [khadir-syed/k_ai-basics](https://github.com/khadir-syed/k_ai-basics) | 1 | Python | 2026-09-24 | Beginner-facing, CLI-only repo demystifying core AI concepts through runnable code |
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
