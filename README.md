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

> ⏰ Last updated: 2026-10-22 07:00 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [xiaozhameng/CitePilot](https://github.com/xiaozhameng/CitePilot) | 0 | HTML | 2026-10-22 | 带出处的垂直知识问答 Agent —— 双路召回 + RRF + 精排 + 自纠正重检 + 引用校验；Python 内核 (FastAPI/SSE) + Java 网关 (Spring Boot WebFlux) |
| 2 | [Opedd/opedd-mcp](https://github.com/Opedd/opedd-mcp) | 1 | TypeScript | 2026-10-22 | Licensed, rights-cleared content for AI agents — verifiable license keys, on-chain proof, EU AI Act attestation. The MCP |
| 3 | [JEen-wang/Adaptive-rag](https://github.com/JEen-wang/Adaptive-rag) | 128 | Python | 2026-10-22 | 涵盖简历写法和项目面试拷打的按问题复杂度自动分流的电商客服 RAG：简单问题直接回答；复杂问题经过多跳检索并自我纠错；查单、退改通过工具调用完成，且高风险写操作必须先经人工确认。基于 FastAPI 和 LangGraph，混合检索并附带引 |
| 4 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 92629 | Go | 2026-10-22 | RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capa |
| 5 | [maniesh-lab/Hearth](https://github.com/maniesh-lab/Hearth) | 0 | Python | 2026-10-22 | Discord bot for community servers: onboarding, self-serve roles, moderation with a mod log, a deadline board, and thank- |
| 6 | [mylgtab/budget-rag](https://github.com/mylgtab/budget-rag) | 0 | Python | 2026-10-22 | 成本感知的长文档问答检索：简单问题走便宜路径，难题才升级。给出 Recall / 成本权衡的评测基线。 |
| 7 | [J0Jng/book-rag-mcp](https://github.com/J0Jng/book-rag-mcp) | 0 | Python | 2026-10-22 | 接入各种 AI Agent 的书籍 RAG MCP 服务 — FastMCP + LangChain，PDF/EPUB/TXT/Markdown，本地 embedding + FAISS，增量索引，语义检索，MCP 双传输 |
| 8 | [YunfeiSHU/ai-assistant](https://github.com/YunfeiSHU/ai-assistant) | 0 | Python | 2026-10-22 | 个人智能 Agent 平台｜Go + Python 分层架构：Go 侧负责 API 网关、用户与会话台账、AI 调用编排与配额限流；Python 侧（FastAPI + LangChain/LangGraph）负责 LLM 编排、Agent |
| 9 | [Abhishek-Rnjn/Evals.si](https://github.com/Abhishek-Rnjn/Evals.si) | 4 | Python | 2026-10-22 | A highly scalable and pluggable evaluations repository that works with all environments to provide an unified experience |
| 10 | [YunanJeong/rag-git-docs](https://github.com/YunanJeong/rag-git-docs) | 0 | Python | 2026-10-22 | Collects markdown scattered across GitLab/GitHub repos and makes it searchable via vector DB. |
| 11 | [XinbaoQiao/XinbaoWiki](https://github.com/XinbaoQiao/XinbaoWiki) | 1 | JavaScript | 2026-10-22 | A bilingual academic wiki with searchable knowledge, citation-grounded LLM answers, and agent-readable OKF exports. |
| 12 | [wangzhengpengjay/AI-Health-Steward](https://github.com/wangzhengpengjay/AI-Health-Steward) | 64 | Python | 2026-10-22 | Self-hosted, private family AI health steward. Multimodal AI structures health data into a person-centric profile with d |
| 13 | [developer47-ai/dba-poc](https://github.com/developer47-ai/dba-poc) | 0 | Python | 2026-10-22 | Local multi-agent AI troubleshooting assistant POC - LangGraph, MCP, RAG, Ollama, fully open-source and Docker-based |
| 14 | [Sallyn0225/eidolon-sc](https://github.com/Sallyn0225/eidolon-sc) | 195 | Python | 2026-10-22 | 和《偶像大师 闪耀色彩》偶像实时语音/文字对话的 AI 分身：日语原声 + 中文字幕、回忆原作剧情、跨角色共享记忆；支持 Google/GitHub 登录与自带密钥，Docker Compose 一键部署（参考 LAPLACE Eidolo |
| 15 | [Nitesh050/rag-pdf-analyzer](https://github.com/Nitesh050/rag-pdf-analyzer) | 1 | Python | 2026-10-22 |  |
| 16 | [KJLavender/agentic-rag-es](https://github.com/KJLavender/agentic-rag-es) | 2 | TypeScript | 2026-10-22 | Full-stack agentic RAG on Elasticsearch: four retrieval modes behind a read-only MCP server, a decision layer, a CRAG lo |
| 17 | [IHUI-INF-AI/IHUI-AI](https://github.com/IHUI-INF-AI/IHUI-AI) | 31 | TypeScript | 2026-10-22 | Eight-platform full-stack AI operating system - unifies 176 LLMs via LangGraph + MCP + A2A. Multi-tenant RLS over 340 ta |
| 18 | [CSE-Sudo/on-care](https://github.com/CSE-Sudo/on-care) | 0 | Dart | 2026-10-22 | AI Platform for Trainer-Member Diet & Exercise Coaching |
| 19 | [Gnatnaituy/echo_lint](https://github.com/Gnatnaituy/echo_lint) | 0 | Java | 2026-10-22 | Call-recording compliance audit platform: local whisper.cpp transcription → DFA keyword screening → DeepSeek semantic re |
| 20 | [eullm/eullm-agent](https://github.com/eullm/eullm-agent) | 0 | Python | 2026-10-22 | A complete AI newsroom on your own server. Self-hosted, multi-tenant AI agent platform in Rust: Editor Mode analyses you |
| 21 | [william-laverty/ato-mcp](https://github.com/william-laverty/ato-mcp) | 12 | TypeScript | 2026-10-22 | Your AI agent, fluent in Australian tax. |
| 22 | [nfekete82/mlx-nobby](https://github.com/nfekete82/mlx-nobby) | 0 | Python | 2026-10-22 | Local AI workspace for Apple Silicon powered by MLX — chat, agents, RAG, image generation and more. |
| 23 | [xiaofang142/hivemtk](https://github.com/xiaofang142/hivemtk) | 133 | Go | 2026-10-22 | 开源私域 AI 营销 SCRM 系统，Martech 获客引流利器！全渠道聚合（抖音/小红书/快手/微信/WhatsApp/TikTok/Telegram）统一收件箱与 CDP 客户管理。🤖核心功能：1. ReAct 自主 AI 智能体（4 |
| 24 | [keylorpineda/RAG-Research-Engine](https://github.com/keylorpineda/RAG-Research-Engine) | 0 | Python | 2026-10-22 | Retrieval-augmented question answering over your own documents: pgvector + hybrid search, a retrieval gate that abstains |
| 25 | [amazingLH/trialtrust-agent-rehearsal](https://github.com/amazingLH/trialtrust-agent-rehearsal) | 1 | Python | 2026-10-22 | 试托是一个让AI先试办、再由你检查的工具。你填好要办的事、数量和预算，让AI在模拟资料中查价格、算费用、提出方案，再查看它有没有漏算费用、超过预算或尝试你没允许的操作，帮助你决定正式使用AI时哪些步骤需要自己把关。 |
| 26 | [Raxorr/ragornot](https://github.com/Raxorr/ragornot) | 0 | TypeScript | 2026-10-22 | Does RAG actually earn its cost? ragornot runs the same query through four retrieval modes (Flat/BM25, Hierarchical, LLM |
| 27 | [jrhahn/ai-trainer](https://github.com/jrhahn/ai-trainer) | 1 | Python | 2026-10-22 | AI-powered cycling coach with Strava integration, RAG-based training knowledge, and support for OpenAI & Gemini — built  |
| 28 | [sjsu-masters-projects/medi-agent](https://github.com/sjsu-masters-projects/medi-agent) | 0 | Python | 2026-10-22 | Patient app and clinician dashboard over a FastAPI backend, where LangGraph agents triage incoming chat, pull structured |
| 29 | [archestack/best-of-ai](https://github.com/archestack/best-of-ai) | 4 | — | 2026-10-22 | Open-source AI, ranked: apps, agents, models and the tools around them, each with strengths, weaknesses and a score from |
| 30 | [yook11/Vector](https://github.com/yook11/Vector) | 1 | Python | 2026-10-22 | 海外テックニュースを自動収集し、AIで翻訳・要約・投資文脈を分析するリサーチダッシュボード |
| 31 | [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26805 | Python | 2026-10-22 | Open-source AI orchestration framework for building context-engineered, production-ready LLM applications. Design modula |
| 32 | [prathameshnium/Kusanagi-AI](https://github.com/prathameshnium/Kusanagi-AI) | 0 | JavaScript | 2026-10-22 | A toolkit of local, privacy-focused AI applications built with Python. Includes a RAG-powered research assistant for PDF |
| 33 | [sandoralvari84-max/local-pocket-rocket-pack](https://github.com/sandoralvari84-max/local-pocket-rocket-pack) | 1 | Python | 2026-10-22 | A tuning kit for small local LLMs (1-8B): swappable expert knowledge bases, tools and profiles, with a reproducible accu |
| 34 | [diillson/chatcli](https://github.com/diillson/chatcli) | 93 | Go | 2026-10-22 | ChatCLI is a command-line application that utilizes LLMs—such as those from Anthropic, OpenAI, and others—to facilitate  |
| 35 | [MrPeppersDev/agent-infrastructure-landscape](https://github.com/MrPeppersDev/agent-infrastructure-landscape) | 5 | HTML | 2026-10-22 | AI agent memory & infrastructure landscape — comparative catalog of 912 systems × 68 columns covering memory layers, age |
| 36 | [CodeCortex/finresearch-qwen](https://github.com/CodeCortex/finresearch-qwen) | 0 | Python | 2026-10-22 | An end-to-end Financial AI platform that combines parameter-efficient LLM fine-tuning, financial numerical reasoning, do |
| 37 | [ModelEngine-Group/nexent](https://github.com/ModelEngine-Group/nexent) | 6007 | Python | 2026-10-22 | Nexent is a zero-code platform for auto-generating production-grade AI agents using Harness Engineering principles — uni |
| 38 | [Yigtwxx/Yigtwxx](https://github.com/Yigtwxx/Yigtwxx) | 3 | — | 2026-10-22 |  |
| 39 | [scszcoder/eCan.ai](https://github.com/scszcoder/eCan.ai) | 22 | Python | 2026-10-22 | Privacy-first, AI native agents For E-Commerce (and beyond), create skill (langgraph based workflow), tasks, agents, gra |
| 40 | [PersonalClaw/PersonalClaw](https://github.com/PersonalClaw/PersonalClaw) | 7 | Python | 2026-10-22 | Your self-hosted personal AI agent — an agentic OS for one person: chat, autonomous goal loops, memory, knowledge base,  |
| 41 | [KanenasInGreece/Shared_Memory](https://github.com/KanenasInGreece/Shared_Memory) | 1 | Python | 2026-10-22 | Memory Framework based on the idea of Architectural Decision Records, shared knowledge between AI agents (Claude Code, C |
| 42 | [Yurken/xiaoyan](https://github.com/Yurken/xiaoyan) | 6 | TypeScript | 2026-10-22 | 小妍是一款面向科研学习与论文工作的 AI 研究助手。面对纷繁复杂的论文与信息，她帮你厘清研究脉络：输入一个主题，多 Agent 协作拆解学习路径、筛选必读论文，并生成结构化综述。 PDF 拖入即可分析，图表识别、复现建议与引用溯源无缝衔接； |
| 43 | [lukislp/studylife-ai](https://github.com/lukislp/studylife-ai) | 0 | Python | 2026-10-22 | AI service for StudyLife — RAG-powered study assistant with agentic actions (LangGraph + FastAPI), source-cited answers  |
| 44 | [sammsulhoq/labs-agentic-ai](https://github.com/sammsulhoq/labs-agentic-ai) | 0 | Python | 2026-10-22 | Hands-on labs exploring agentic AI, LangChain, LangGraph, RAG, LLM integrations, tools, agents, and AI application patte |
| 45 | [jee3m/augmentative-knowledge-hooks](https://github.com/jee3m/augmentative-knowledge-hooks) | 1 | HTML | 2026-10-22 | Semantic Search for Pi 2026: Local Knowledge Base & AI Tool |
| 46 | [quberi/quberi](https://github.com/quberi/quberi) | 0 | Python | 2026-10-22 | AI knowledge base with document-level permissions: per-document access rules, deny wins, filtered inside the vector inde |
| 47 | [asimkhaniqbal/apify-actor-examples](https://github.com/asimkhaniqbal/apify-actor-examples) | 0 | HTML | 2026-10-22 | Runnable Apify Actor examples and reference documentation from Vexaloom Labs. |
| 48 | [Osmantic/ODS](https://github.com/Osmantic/ODS) | 7641 | Python | 2026-10-22 | ODS V3 Pre-Release: Public testing and refinement ahead of the official V3 launch. Turn your PC, Mac, or Linux box into  |
| 49 | [sakshipatole28/MailPilot](https://github.com/sakshipatole28/MailPilot) | 0 | Python | 2026-10-22 | Chrome extension + FastAPI: sorts student email, tracks deadlines, drafts replies with hybrid RAG. Never sends mail. |
| 50 | [Hh681Hh/x-second-brain](https://github.com/Hh681Hh/x-second-brain) | 0 | Python | 2026-10-22 | 免费 X 书签知识助手：浏览器收藏、本地全文知识库、自动分类、可溯源问答与 Codex Skill。 |
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
