# Roman Nalapko — Junior Python Backend & Automation Engineer

I build asynchronous Python backends, API integrations, and automation workflows with validated data flows, testing, observability, and explicit failure handling.

Currently pursuing a Bachelor's degree in Information Systems and Technologies. Open to **Junior Python Backend**, **Automation**, and **API Integration** opportunities in Ukraine and remote international teams.

[![Resume](https://img.shields.io/badge/Resume-PDF-007ACC?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](./Roman_Nalapko_Junior_Python_Backend_Automation_Engineer_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Roman_Nalapko-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/roman-nalapko-aa70b9327/)

## Core skills

| Area | Technologies |
| --- | --- |
| Backend & Systems | Python · FastAPI · asyncio · TypeScript · Node.js 24 · REST APIs · SSE · WebSockets · Pydantic · SQLAlchemy · Alembic |
| Automation & AI | Autonomous agents · game AI · API integrations · workflow automation · structured model output · Gemini · Whisper · RAG · hybrid retrieval |
| Data & platforms | PostgreSQL · SQL · Qdrant · Cloudflare Workers · D1 · KV · Docker · Linux |
| Quality & operations | pytest · Vitest · GitHub Actions · CI/CD · structured logging · health checks · Prometheus · chaos resilience · failure handling |

## Featured projects

### [Zoria Tournament AI & Game Headquarters](https://github.com/roman-nalapko/zoria)

Autonomous tournament game agent, real-time analytics headquarters, and live-stream client for the Zoria 2026 AI competition (Top-15 standing, 0 protocol defects).

- Real-time Champion AI bot using topological DFS crown cycle detection, 8-weight squad optimization, and dynamic auction bidding under strict 500ms tick deadlines.
- Offline fallback state charter (`nakaz.yaml`) and Level 3 Provocateur chaos resilience (100% recovery from socket severance and in-flight `SIGKILL`).
- Interactive Game Headquarters (HQ) single-page application with scrubbable Canvas/SVG replays and `ZARIA_HQ` host-guest protocol (passed 20/20 benchmark tasks).
- Tamper-proof ether streaming with HMAC-SHA256 frame verification, exponential backoff transport, and Prometheus metrics.
- 124 automated tests, strict TypeScript, Docker Compose multi-container stack, and zero protocol defects (K1: 0/9).

[![CI](https://github.com/roman-nalapko/zoria/actions/workflows/ci.yaml/badge.svg)](https://github.com/roman-nalapko/zoria/actions/workflows/ci.yaml)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-24+-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![Vitest](https://img.shields.io/badge/Vitest-124%20passed-729B1B?logo=vitest&logoColor=white)](https://vitest.dev/)

### [AI RAG Platform](https://github.com/roman-nalapko/ai-rag-platform)

A local-first document intelligence backend demonstrating reliable backend, retrieval, and automation patterns.

- Async PDF/TXT ingestion with durable indexing jobs.
- Hybrid retrieval using Qdrant dense vectors and PostgreSQL full-text search with Reciprocal Rank Fusion.
- Tenant-scoped knowledge bases, JWT authentication, SSE answers with citations, and conversation memory.
- Offline RAG evaluation, Prometheus metrics, request-correlated JSON logs, Docker, and CI.
- 118 automated tests covering API contracts, retrieval, authentication, streaming, metrics, and failure paths.

[![CI](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml)
[![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-API-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-dc244c)](https://qdrant.tech/)

### [Neovim + Ghostty Development Environment](https://github.com/roman-nalapko/nvim-dev-config)

My portable terminal development setup for macOS Apple Silicon and Debian x86-64.

- Modular Neovim 0.12+ configuration built with Lua and `lazy.nvim`.
- C/C++ workflow with clangd, clang-format, CMake/Make, LLDB-DAP, and Treesitter.
- Additional tooling for Python, Free Pascal, ARM64 assembly, and NASM x86-64.
- Ghostty configuration with Tokyo Night styling, transparency, blur, and JetBrainsMono Nerd Font.
- Reproducible installers, safe configuration backups, health checks, update scripts, and automated tests.

[![Neovim](https://img.shields.io/badge/Neovim-0.12+-57A143?logo=neovim&logoColor=white)](https://neovim.io/)
[![Ghostty](https://img.shields.io/badge/Terminal-Ghostty-3551F3)](https://ghostty.org/)
[![Lua](https://img.shields.io/badge/Config-Lua-2C2D72?logo=lua&logoColor=white)](https://www.lua.org/)
[![Platforms](https://img.shields.io/badge/macOS_ARM64-%7C_Debian_x86--64-555555?logo=linux&logoColor=white)](https://github.com/roman-nalapko/nvim-dev-config)

## Engineering principles

- Keep HTTP, business, data, and provider boundaries explicit.
- Validate model output before persistence or downstream actions.
- Design for timeouts, bounded retries, idempotency, and observable failures.
- Test behavior and failure paths, not only successful HTTP responses.
- Keep secrets out of source, logs, and prompts.

## Contact

- [LinkedIn](https://www.linkedin.com/in/roman-nalapko-aa70b9327/)
- [GitHub](https://github.com/roman-nalapko)
