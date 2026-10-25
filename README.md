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

> ⏰ Last updated: 2026-10-25 10:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [dongshu710/doc-qa-assistant](https://github.com/dongshu710/doc-qa-assistant) | 0 | Python | 2026-10-25 | 零第三方依赖的文档问答（RAG）原型：只依据资料作答、逐条标注出处，答不出转人工。含 L1 断言 / L3 语义评分 / 召回评测与可离线导出的汇报页。 |
| 2 | [jamiezigelbaum/expert-agents](https://github.com/jamiezigelbaum/expert-agents) | 6 | TypeScript | 2026-10-25 | Machinery for creating and operating cited expert agents on OpenClaw (plugin + Vertex RAG worker) |
| 3 | [trick77/rongo](https://github.com/trick77/rongo) | 1 | Go | 2026-10-25 | Turns a codebase into something the rest of the company can ask. Plain-language questions, answers in domain terms, flow |
| 4 | [TsSerV/chapter-and-verse](https://github.com/TsSerV/chapter-and-verse) | 0 | Python | 2026-10-25 | Question answering for UK legislation, citing the exact provision behind every claim at the version in force on the date |
| 5 | [xr843/Master-skill](https://github.com/xr843/Master-skill) | 472 | Python | 2026-10-25 | FoJin-powered Buddhist AI persona framework — source-grounded, boundary-aware, fidelity-tested, runtime-ready. |
| 6 | [muetaek0321/ek-chat](https://github.com/muetaek0321/ek-chat) | 0 | Python | 2026-10-25 | FastAPI × Next.js による RAG・マルチLLM対応チャットUI。Gemini API、Ollama、Speculative Decoding（Transformers）や GGUF（llama-cpp）ローカル推論の動的切 |
| 7 | [epqlffltm/ai-trpg](https://github.com/epqlffltm/ai-trpg) | 0 | Python | 2026-10-25 | LLM이 게임 상태를 바꾸지 못하게 설계한 AI TRPG 플랫폼 · 엔진이 판정하고 LLM은 구조화된 제안과 서술만 · 서버 4개(Django·FastAPI·NestJS·Go), RAG, 서비스 간 서명, 원장 기반 |
| 8 | [onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx) | 32966 | Python | 2026-10-25 | Open Source AI Platform - AI Chat with advanced features that works with every LLM |
| 9 | [mloda-ai/mloda-registry](https://github.com/mloda-ai/mloda-registry) | 6 | Python | 2026-10-25 | Registry of official plugins for mloda.ai |
| 10 | [Vidhaath622/MUJ](https://github.com/Vidhaath622/MUJ) | 0 | TypeScript | 2026-10-25 | When a RAG answer is wrong, RAGSeal proves whether the retriever or the generator caused it via counterfactual replay. |
| 11 | [PRINCE2-AI/nano-agentrl](https://github.com/PRINCE2-AI/nano-agentrl) | 0 | Python | 2026-10-25 | From-scratch PyTorch re-implementation of Search-R1: multi-turn GRPO that teaches an LLM to reason and use a search engi |
| 12 | [cyberlife-coder/VelesDB](https://github.com/cyberlife-coder/VelesDB) | 100 | Rust | 2026-10-25 | The explainable, local-first memory engine for AI agents. One ~9 MB binary fuses vector + graph + columnar under VelesQL |
| 13 | [Marker-Inc-Korea/AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG) | 5187 | TypeScript | 2026-10-25 | Your Personal Librarian Agent. Ask anything on your computer, organize files, remember important info and files. |
| 14 | [makoy-daniot2001/agent-session-mirror](https://github.com/makoy-daniot2001/agent-session-mirror) | 0 | HTML | 2026-10-25 | Best AI Coding Agent Observability Tool 2026 - Self-Bench & Semantic Search |
| 15 | [suhaib0764/miRNA-Enrichment-Insight-Engine](https://github.com/suhaib0764/miRNA-Enrichment-Insight-Engine) | 1 | HTML | 2026-10-25 | AI-Powered miRNA Analysis & Experiment Design Tool 2026 🧬🔍 |
| 16 | [tom1030507/OpenNotebookLM](https://github.com/tom1030507/OpenNotebookLM) | 69 | Python | 2026-10-25 | Self-hosted alternative to Google's NotebookLM: import PDFs, web pages and YouTube transcripts, then get answers with ci |
| 17 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 102936 | TypeScript | 2026-10-25 | Persistent Context Across Sessions for Every Agent –  Captures everything your agent does during sessions, compresses it |
| 18 | [IHUI-INF-AI/IHUI-AI](https://github.com/IHUI-INF-AI/IHUI-AI) | 31 | TypeScript | 2026-10-25 | Eight-platform full-stack AI operating system - unifies 176 LLMs via LangGraph + MCP + A2A. Multi-tenant RLS over 340 ta |
| 19 | [abdulmdev/sentinel-incident-copilot](https://github.com/abdulmdev/sentinel-incident-copilot) | 0 | Python | 2026-10-25 | Agentic incident-response copilot: alerts open incidents, a LangGraph agent investigates via MCP, a human approves, a si |
| 20 | [PersonalClaw/PersonalClaw](https://github.com/PersonalClaw/PersonalClaw) | 7 | Python | 2026-10-25 | Your self-hosted personal AI agent — an agentic OS for one person: chat, autonomous goal loops, memory, knowledge base,  |
| 21 | [ranjan-del/ragfabric](https://github.com/ranjan-del/ragfabric) | 0 | Python | 2026-10-25 | RagFabric: self hosted, measurement first RAG platform. Four retrieval strategies (Traditional, Agentic, Graph, Vectorle |
| 22 | [karthik-dixith/thesis-rag-assistant](https://github.com/karthik-dixith/thesis-rag-assistant) | 0 | Python | 2026-10-25 | RAG question-answering assistant over an M.Sc. thesis on AR indoor navigation — semantic retrieval, grounded answers wit |
| 23 | [nukilev/tenant-shield](https://github.com/nukilev/tenant-shield) | 0 | JavaScript | 2026-10-25 | Full-stack legal RAG application for analyzing Israeli residential lease agreements using FastAPI, React, ChromaDB, and  |
| 24 | [xueyufish/hecate](https://github.com/xueyufish/hecate) | 7 | Python | 2026-10-25 | Enterprise-grade, multi-tenant, model-agnostic, MCP-first Agent platform. |
| 25 | [abhay-patil-cse27/concord-ikms](https://github.com/abhay-patil-cse27/concord-ikms) | 1 | Python | 2026-10-25 | Context-Oriented Institutional Knowledge Management System (IKMS). Features Adaptive Hybrid RRF Retrieval (BM25 + Chroma |
| 26 | [AdamBaranyi/Evidarium](https://github.com/AdamBaranyi/Evidarium) | 0 | TypeScript | 2026-10-25 | Ask questions about your own documents and get answers with citations you can open and verify. |
| 27 | [SanHsien/khoj](https://github.com/SanHsien/khoj) | 1 | Python | 2026-10-25 | Your AI second brain. Self-hostable. Windows-first maintenance fork of khoj-ai/khoj. |
| 28 | [shakibweg/infera-notebook](https://github.com/shakibweg/infera-notebook) | 0 | TypeScript | 2026-10-25 | Transform your documents into interactive knowledge bases with AI-powered chat, notes, and multimedia content generation |
| 29 | [kgiannopoulou/opspilot](https://github.com/kgiannopoulou/opspilot) | 0 | Python | 2026-10-25 | AI-powered application support platform that correlates support tickets, logs and metrics to assist incident investigati |
| 30 | [yadava5/ai-augmented-auto-ml-toolchain](https://github.com/yadava5/ai-augmented-auto-ml-toolchain) | 0 | TypeScript | 2026-10-25 | Agentic AutoML Platform. Upload a CSV and a LangGraph agent writes the Python, runs it in a sandboxed Docker Jupyter ker |
| 31 | [VecturaDB/VecturaDB](https://github.com/VecturaDB/VecturaDB) | 0 | Rust | 2026-10-25 | Vector database compatible with the Chroma API, bringing Chroma Cloud's features to open source. |
| 32 | [Abdullah-AbuHatab/jo-tax-law-rag](https://github.com/Abdullah-AbuHatab/jo-tax-law-rag) | 0 | Python | 2026-10-25 | Arabic question answering over Jordanian tax laws with article-level citations: FastAPI, Gemini embeddings, pgvector, re |
| 33 | [syshin0116/syshin0116.dev](https://github.com/syshin0116/syshin0116.dev) | 0 | Python | 2026-10-25 | Personal tech blog, portfolio, and AI chatbot — built with Next.js 15, Nuartz, and LangGraph |
| 34 | [Bideng-Warrior/hukumpekerja-chatbot](https://github.com/Bideng-Warrior/hukumpekerja-chatbot) | 0 | Jupyter Notebook | 2026-10-25 | An AI-powered RAG chatbot helping Indonesian workers understand their legal rights under national labor laws. Built with |
| 35 | [NTidal/nekro_persona](https://github.com/NTidal/nekro_persona) | 0 | Python | 2026-10-25 | NekroAgent 插件：角色人格层——阶梯式背景记忆（常驻/检索/世界知识三档）+ 好感度关系状态与披露门控 |
| 36 | [deepakpradhan1021/docRag](https://github.com/deepakpradhan1021/docRag) | 0 | Python | 2026-10-25 | Zero-Budget Document RAG System: Upload PDFs, ask questions, and receive grounded answers with verified source citations |
| 37 | [cgaeking/rootmind](https://github.com/cgaeking/rootmind) | 1 | Python | 2026-10-25 | Local document search with an agentic LLM loop (SQLite FTS5, no embeddings). Answers cite the page. MCP server, Windows  |
| 38 | [pixeltable/pixeltable](https://github.com/pixeltable/pixeltable) | 1647 | Python | 2026-10-25 | The backend agents build with - Multimodal database, orchestration, and serving in one file |
| 39 | [metadist/synaplan](https://github.com/metadist/synaplan) | 253 | PHP | 2026-10-25 | Open-source, self-hosted AI platform (PHP/Symfony): chat with any model, RAG over your docs, embeddable widget, MCP — se |
| 40 | [HamzaAhmedSharif/My-Portfolio](https://github.com/HamzaAhmedSharif/My-Portfolio) | 0 | — | 2026-10-25 | AI engineering portfolio — RAG, multi-agent systems, and applied ML. 7 completed projects with verified results and 2 li |
| 41 | [krizaka/orazaka-ai-engine](https://github.com/krizaka/orazaka-ai-engine) | 0 | Java | 2026-10-25 | Orazaka — the cognitive SDK: provider mesh, interceptor pipeline, tools (MCP · RAG · sandbox), use-case orchestration an |
| 42 | [cortexkit/aft](https://github.com/cortexkit/aft) | 332 | Rust | 2026-10-25 | Give your agent a proper IDE and OS. The sensorimotor cortex for coding agents (OpenCode + Pi), part of CortexKit: symbo |
| 43 | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 43863 | Python | 2026-10-25 | Build resilient agents. |
| 44 | [zhangqi77ok-sys/claude-stealth-mode](https://github.com/zhangqi77ok-sys/claude-stealth-mode) | 0 | PowerShell | 2026-10-25 | Windows stealth toolkit for Claude: Fixes WebRTC STUN leaks, CLI subprocess proxy bypass, timezone mismatch, and wipes A |
| 45 | [brekkylab/backlot](https://github.com/brekkylab/backlot) | 259 | Python | 2026-10-25 | A local emulator for enterprise SaaS APIs — Slack, Gmail, Google Drive, GitHub, Jira, Notion, S3 and more — with the rea |
| 46 | [olafurjohannsson/kjarni](https://github.com/olafurjohannsson/kjarni) | 37 | Rust | 2026-10-25 | Native and Private ML inference engine, embeddings, classification, reranking, search, and text generation running on CP |
| 47 | [rxmna8502/vybe-intelligence-vault](https://github.com/rxmna8502/vybe-intelligence-vault) | 22 | — | 2026-10-25 | An auto-updating open-source vault for AI agents, RAG systems, MCP servers, prompts, tools, templates, and next-generati |
| 48 | [takeshy/gemihub](https://github.com/takeshy/gemihub) | 7 | TypeScript | 2026-10-25 | AI secretary powered by Gemini and Google Drive — chat with streaming & function    calling, visual workflow builder, Dr |
| 49 | [negativexq/knowledge-base-rag](https://github.com/negativexq/knowledge-base-rag) | 1 | Python | 2026-10-25 | Agentic document research with PydanticAI: typed workflows, scoped tools, cited answers, chart and table extraction, che |
| 50 | [srezai-team/srezai-web-search-pro-skill](https://github.com/srezai-team/srezai-web-search-pro-skill) | 3 | JavaScript | 2026-10-25 | Claude Code / DSH skill: web search, page reading, site crawling and claim verification through the srezai MCP server. W |
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
