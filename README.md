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

> ⏰ Last updated: 2026-08-27 07:15 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [shin13/nhi-knowledge-extractor](https://github.com/shin13/nhi-knowledge-extractor) | 0 | Python | 2026-08-27 | Pipeline that converts Taiwan NHI medication regulation DOCX/ODT documents into RAG-ingestion-ready CSV chunks with stab |
| 2 | [QA-AU/claim-validator](https://github.com/QA-AU/claim-validator) | 0 | Python | 2026-08-27 | Independently validates whether an external tool's claims are actually supported by a reference document — ontology + RA |
| 3 | [FuRongJun-1999/dsh-memory](https://github.com/FuRongJun-1999/dsh-memory) | 39 | TypeScript | 2026-08-27 | AGI 的长期记忆基础设施。让 AI Agent 拥有不可遗忘的自我。跨会话记忆 · 持续学习 · 可审计信任（智能论 v3.2） |
| 4 | [Shoko-official/StudentLLM](https://github.com/Shoko-official/StudentLLM) | 0 | TypeScript | 2026-08-27 | Local-first learning workspace for recording, understanding, and revising university lectures with traceable AI. |
| 5 | [valpere/session-indexer](https://github.com/valpere/session-indexer) | 36 | Go | 2026-08-27 | Per-project semantic search over Claude Code session history. Indexes JSONL transcripts into SQLite; retrieves via bge-m |
| 6 | [Mr-strom/AETHER](https://github.com/Mr-strom/AETHER) | 0 | TypeScript | 2026-08-27 | Offline multimodal RAG engine with FAISS, BGE-M3, and GGUF models. Privacy-first document analysis. |
| 7 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 89356 | Go | 2026-08-27 | RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capa |
| 8 | [Scarlet-S/medical-device-test-rag](https://github.com/Scarlet-S/medical-device-test-rag) | 0 | Python | 2026-08-27 | Medical device software testing knowledge base and RAG evaluation workbench built with RAGFlow. |
| 9 | [ziphow/rag-chat-assistant](https://github.com/ziphow/rag-chat-assistant) | 1 | JavaScript | 2026-08-27 | 基于 FastAPI + LangChain + RAG 的 AI 智能对话助手，支持多轮对话记忆、图片分析、流式回复、知识库 RAG 检索、上传定义知识库。 |
| 10 | [initial-d/me_fasttext](https://github.com/initial-d/me_fasttext) | 1 | C++ | 2026-08-27 | Memory-efficient FastText with exact trie n-gram IDs, mark-compact layout, and mmap serving for large-vocabulary NLP/RAG |
| 11 | [Rumeasiyan/askwell](https://github.com/Rumeasiyan/askwell) | 0 | TypeScript | 2026-08-27 | Local AI over your own files and databases. Asks when it's unsure, remembers your answers, cites every claim. Runs entir |
| 12 | [2026-Unithon/AskBuddy](https://github.com/2026-Unithon/AskBuddy) | 0 | Python | 2026-08-27 | 카페 인수인계를 대신하는 AI — 근거가 없으면 답하지 않고 점주에게 넘긴다. FastAPI · Next.js 16 · PostgreSQL+pgvector \| 2026 유니톤 해커톤 |
| 13 | [wuWhite688/ResumeLens](https://github.com/wuWhite688/ResumeLens) | 0 | Java | 2026-08-27 | 基于本地 ONNX 向量检索与大模型生成的 JD-简历智能匹配系统：Spring Boot 3.5 + Lucene 向量索引 + Hybrid RAG 证据链 + Next.js |
| 14 | [skygazer42/MimirQ](https://github.com/skygazer42/MimirQ) | 444 | Python | 2026-08-27 | 中文优先的企业 RAG 知识库：可控解析、治理、切块、混合检索、重排、引用、图谱、评测与 Dify 接入。 |
| 15 | [langbot-app/LangBot](https://github.com/langbot-app/LangBot) | 17565 | Python | 2026-08-27 | Production-grade platform for building agentic IM bots - 生产级多平台智能机器人开发平台/ Agent、知识库编排、插件系统 / Bots for Discord / Slack /  |
| 16 | [aghasalim/eu-ai-act-rag](https://github.com/aghasalim/eu-ai-act-rag) | 2 | Python | 2026-08-27 | Grounded QA over the EU AI Act where the evaluation harness is the deliverable: retrieval, faithfulness and hallucinatio |
| 17 | [milvus-io/milvus](https://github.com/milvus-io/milvus) | 45814 | Go | 2026-08-27 | Milvus is a high-performance, cloud-native vector database built for scalable vector ANN search |
| 18 | [designer-coderajay/enterprise-agentic-ai-platform](https://github.com/designer-coderajay/enterprise-agentic-ai-platform) | 2 | Python | 2026-08-27 | Production-grade multi-agent AI platform with LangGraph v0.3, MCP servers, hybrid RAG (Qdrant + LlamaIndex), FastAPI Web |
| 19 | [xberg-io/xberg](https://github.com/xberg-io/xberg) | 9224 | Rust | 2026-08-27 | A polyglot document intelligence framework with a Rust core. Extract text, metadata, images, and structured data from 10 |
| 20 | [wish-maker/minder](https://github.com/wish-maker/minder) | 4 | Python | 2026-08-27 | Self-hosted, 100% local AI platform — LLM inference, RAG, and knowledge graphs in one Docker stack. No API keys. |
| 21 | [DnlSQ/AI-Document-Intelligence](https://github.com/DnlSQ/AI-Document-Intelligence) | 0 | Python | 2026-08-27 | A local AI assistant for processing and retrieving technical documentation. |
| 22 | [kenchengkc/the-financial-document-retrieval-engine](https://github.com/kenchengkc/the-financial-document-retrieval-engine) | 2 | Python | 2026-08-27 | Point-in-time SEC filing retrieval: hybrid search, citation-verified answers with abstention, typed financial facts, fil |
| 23 | [NVIDIA-AI-Blueprints/video-search-and-summarization](https://github.com/NVIDIA-AI-Blueprints/video-search-and-summarization) | 1825 | C++ | 2026-08-27 | NVIDIA AI Blueprint for video search and summarization (VSS) is a GPU-accelerated reference architecture for building vi |
| 24 | [bilals2008/convio-ai](https://github.com/bilals2008/convio-ai) | 1 | TypeScript | 2026-08-27 | AI Chatbot & Agent Management Platform — build, deploy, and manage AI chatbots across Web, WhatsApp, Telegram, Discord,  |
| 25 | [123xpw/truthful-resume-agent](https://github.com/123xpw/truthful-resume-agent) | 0 | Python | 2026-08-27 | Evidence-grounded resume workflow: AI advises, deterministic code constrains, and the candidate authorizes every claim. |
| 26 | [AnalyseDeCircuit/oxideterm](https://github.com/AnalyseDeCircuit/oxideterm) | 1349 | Rust | 2026-08-27 | AI-native workspace for local shells and remote machines.Zero Electron, zero OpenSSL, zero telemetry, and no app subscri |
| 27 | [Kaynaaf/NanoRAG](https://github.com/Kaynaaf/NanoRAG) | 2 | Python | 2026-08-27 | A RAG app to breakdown complex technical documents  |
| 28 | [zeweihan/aiworkdeck](https://github.com/zeweihan/aiworkdeck) | 79 | Java | 2026-08-27 | AI-native IDE workspace for legal and document-heavy workflows: files, agents, plugins, WPS editing, OCR, evidence chain |
| 29 | [dataease/SQLBot](https://github.com/dataease/SQLBot) | 6691 | JavaScript | 2026-08-27 | 🔥 基于大模型和 RAG 的智能问数系统，对话式数据分析神器。Text-to-SQL Generation via LLMs using RAG. |
| 30 | [benjsmith/switchbay](https://github.com/benjsmith/switchbay) | 1 | Python | 2026-08-27 | Local, single-user agentic workbench over your knowledge bases (curiosity-engine substrate). |
| 31 | [vespa-engine/vespa](https://github.com/vespa-engine/vespa) | 7070 | Java | 2026-08-27 | The AI search platform |
| 32 | [pigking9527-cmyk/kunpeng-reader](https://github.com/pigking9527-cmyk/kunpeng-reader) | 1 | Rust | 2026-08-27 | 高性能、本地优先的跨平台电子书阅读器，基于 Rust + Tauri 2，支持 EPUB/PDF/TXT/MOBI/AZW3、全文与语义搜索、批注、TTS、RAG 问答和轻数据同步。 |
| 33 | [dev-boffin-io/mind-forge-pro](https://github.com/dev-boffin-io/mind-forge-pro) | 0 | Dart | 2026-08-27 | An offline, autonomous Agentic AI personal assistant for Android. Powered by native llama.cpp, Flutter, and local RAG ar |
| 34 | [kuliantnt/qq-maid-bot](https://github.com/kuliantnt/qq-maid-bot) | 114 | Rust | 2026-08-27 | 通用女仆机器人本地版 Rust 服务 |
| 35 | [helixml/helix](https://github.com/helixml/helix) | 802 | Go | 2026-08-27 | ♾️ Private Agent Fleet with Spec Coding. Each agent gets their own GPU-accelerated desktop. Run Claude, Codex, Gemini an |
| 36 | [zhifengjin050-arch/enterprise-ai-agent-platform](https://github.com/zhifengjin050-arch/enterprise-ai-agent-platform) | 0 | Python | 2026-08-27 | Enterprise AI Agent Platform with RAG, Knowledge Graph, Workflow Automation, Multi-Tenant Security and Cloud Native Depl |
| 37 | [shno-labs/mem-forge](https://github.com/shno-labs/mem-forge) | 4 | Python | 2026-08-27 | Self-evolving, evidence-based memory layer for coding agents and development teams. |
| 38 | [tanushi1289/rag-legal-documents](https://github.com/tanushi1289/rag-legal-documents) | 0 | Jupyter Notebook | 2026-08-27 | RAG system over legal agreements (NDAs, contracts) for clause extraction and question answering. |
| 39 | [The-Geek-Freaks/NEOTH](https://github.com/The-Geek-Freaks/NEOTH) | 5 | Rust | 2026-08-27 | Local-first personal AI daemon in Rust — five-tier memory, consent-gated tools, WASM plugin sandbox, multi-provider LLM  |
| 40 | [tanushi1289/hybrid-rag-finetuning](https://github.com/tanushi1289/hybrid-rag-finetuning) | 0 | Jupyter Notebook | 2026-08-27 | Comparing baseline, naive RAG, and LoRA fine-tuned hybrid RAG for customer support intent routing across a seven-noteboo |
| 41 | [cortexkit/aft](https://github.com/cortexkit/aft) | 262 | Rust | 2026-08-27 | Give your agent a proper IDE and OS. The sensorimotor cortex for coding agents (OpenCode + Pi), part of CortexKit: symbo |
| 42 | [Asadali-Github/IADS-Agentic-SQL-Agent](https://github.com/Asadali-Github/IADS-Agentic-SQL-Agent) | 0 | Python | 2026-08-27 | Agentic text-to-SQL on Oracle Cloud — 5-stage pipeline (Planner → Schema Retriever → SQL Generator → Validator → Safe Ex |
| 43 | [kc-ml2/MARU-Lang](https://github.com/kc-ml2/MARU-Lang) | 28 | Python | 2026-08-27 | MARU-Lang is an open-source RAG chatbot engine. |
| 44 | [linny006/vector-db-live](https://github.com/linny006/vector-db-live) | 3 | Python | 2026-08-27 | Live-updating landscape of vector database projects, integrations, and benchmarks — refreshed every  |
| 45 | [linny006/rag-radar](https://github.com/linny006/rag-radar) | 3 | Python | 2026-08-27 | Live tracker of new RAG implementations, tools, and patterns — updated every 15 minutes |
| 46 | [bibinprathap/VeritasGraph](https://github.com/bibinprathap/VeritasGraph) | 313 | Python | 2026-08-27 | VeritasGraph — open-source Knowledge Graph & GraphRAG framework on GitHub. Build multi-hop reasoning, ontology-aware ret |
| 47 | [VBlackJack/Datacron](https://github.com/VBlackJack/Datacron) | 0 | Python | 2026-08-27 | Local-first MCP server to query and maintain a Markdown vault from Claude, Cursor, Gemini, Codex & other AI clients - no |
| 48 | [MagicIndex135731/Komachi-qq-aibot](https://github.com/MagicIndex135731/Komachi-qq-aibot) | 3 | Python | 2026-08-27 | 基于 LLBot/OneBot 的 QQ 群聊 AI 小町，支持分层长期记忆、人物画像与关系、图片理解、联网检索、主动插话和 GPU 向量检索；兼容 OpenAI API，使用 WSL2 + Docker 部署。 |
| 49 | [TsingyuL/multi-hop-rag-survey](https://github.com/TsingyuL/multi-hop-rag-survey) | 0 | Python | 2026-08-27 | Research hub for challenge-centered multi-hop RAG: five-challenge taxonomy, 208-work review snapshot, and seven-survey r |
| 50 | [elizaOS/eliza](https://github.com/elizaOS/eliza) | 19181 | TypeScript | 2026-08-27 | Open source agentic operating system |
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
