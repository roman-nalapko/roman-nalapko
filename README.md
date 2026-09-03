# Roman Nalapko — AI Engineer | Python Backend | LLM Applications

Building production-oriented LLM applications with Python, FastAPI, vector databases, and scalable AI infrastructure.

Open to **AI Engineer**, **LLM Engineer**, and **Python Backend** opportunities with high-impact teams.

---

## 📄 Resume

[![Resume](https://img.shields.io/badge/Download_CV-PDF-007ACC?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](./Roman_Nalapko_AI_Engineer_CV_Public.pdf)

---

## 🎯 Focus Areas

- **RAG Architecture:** End-to-end multi-tenant document intelligence with hybrid retrieval (Dense Vectors + BM25/FTS via RRF), strict context grounding, and streaming citations.
- **LLM Applications & Agents:** Multi-provider abstractions (OpenAI-compatible, LM Studio, Ollama), structured JSON tool use, and automated evaluation pipelines.
- **Backend Engineering:** High-performance async APIs with FastAPI, PostgreSQL 17, asyncpg, SQLAlchemy 2.0, connection pooling, and durable job queues.
- **AI Automation & Infrastructure:** Zero-downtime migrations with Alembic, Docker containerization, and automated GitHub Actions CI/CD.

---

## 🛠️ Tech Stack

| Area | Technologies |
| :--- | :--- |
| **Backend & APIs** | Python 3.14 · FastAPI · asyncio · Pydantic v2 · SQLAlchemy async · asyncpg · Alembic · bcrypt |
| **AI & LLMs** | RAG · Hybrid Search (RRF) · LLM-as-a-Judge · Context Grounding · OpenAI API · LM Studio · Ollama · SSE Streaming |
| **Vector Stores** | Qdrant (Cosine Distance, Payload Filters) · ChromaDB |
| **Databases** | PostgreSQL 17 (Full-Text Search, JSONB, Advisory Locks) |
| **Observability & DevOps** | Prometheus Metrics · Structured JSON Logging (`X-Request-ID`) · Docker Compose · GitHub Actions CI |

---

## ⚡ Featured Project

### [AI RAG Platform](https://github.com/roman-nalapko/ai-rag-platform) `v1.1.0`

> **Production-oriented local-first & cloud RAG platform demonstrating real AI engineering patterns: hybrid retrieval, streaming generation, grounded evaluation, and multi-tenancy.**

[![CI](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml)
[![Release](https://img.shields.io/badge/Release-v1.1.0-blue.svg)](https://github.com/roman-nalapko/ai-rag-platform/releases/tag/v1.1.0)
[![Python 3.14](https://img.shields.io/badge/python-3.14-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.125+-009688.svg?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![PostgreSQL 17](https://img.shields.io/badge/PostgreSQL-17-336791.svg?logo=postgresql&logoColor=white)](https://www.postgresql.org)
[![Qdrant](https://img.shields.io/badge/Qdrant-Vector%20DB-dc2626.svg?logo=qdrant&logoColor=white)](https://qdrant.tech)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/roman-nalapko/ai-rag-platform/blob/main/LICENSE)

<p align="center">
  <a href="https://github.com/roman-nalapko/ai-rag-platform">
    <img src="https://raw.githubusercontent.com/roman-nalapko/ai-rag-platform/main/docs/screenshots/rag-chat-flow.png" alt="AI RAG Platform Dashboard Preview" width="100%" />
  </a>
</p>

#### 🌟 Key Architecture & Capabilities:
- **🔀 Hybrid Retrieval & RRF:** Combines Qdrant dense vector similarity search with PostgreSQL 17 full-text search via **Reciprocal Rank Fusion (RRF)** for optimal recall.
- **⚡ Grounded Streaming Chat:** Real-time Server-Sent Events (SSE) emitting structured source chunk citations and confidence scores before generation tokens begin, with strict anti-hallucination fallback.
- **📊 Automated Quality Suite (LLM-as-a-Judge):** Dual-mode evaluation engine scoring answer faithfulness and relevance (0–10) via LLM, measuring retrieval hit rate against comprehensive test datasets.
- **🔐 Production Multi-Tenant Security:** Full user authentication with `bcrypt` password hashing, timing-attack protection, JWT session management, and tenant-isolated knowledge bases.
- **☁️ Multi-Provider Support:** Pluggable runtime switching between local offline models (LM Studio) and cloud production hosting (OpenAI `gpt-4o-mini`, `text-embedding-3-small`) without code modifications.
- **📈 Native Observability:** Zero-dependency Prometheus metrics exporter (`/metrics`) tracking latency histograms, throughput, and end-to-end `X-Request-ID` correlation.
- **💻 Interactive Web Dashboard:** Modern themeable browser interface (`/demo/`) with dark/light themes, loading states, and `localStorage` session persistence.
- **🧪 Rigorous Verification:** 118 automated tests passing in GitHub Actions CI with live PostgreSQL 17 and Qdrant service containers.

🔗 **Explore:** [Repository](https://github.com/roman-nalapko/ai-rag-platform) · [Latest Release Notes](https://github.com/roman-nalapko/ai-rag-platform/releases/tag/v1.1.0) · [Architecture Guide](https://github.com/roman-nalapko/ai-rag-platform/blob/main/docs/ARCHITECTURE.md) · [Cloud Deployment Guide](https://github.com/roman-nalapko/ai-rag-platform/blob/main/docs/DEPLOYMENT_CLOUD.md)

---

## 💡 Engineering Approach

I prioritize:
1. **Clean architectural boundaries**: Clear separation between HTTP routing, business services, vector operations, and LLM clients.
2. **Deterministic grounding**: Defending against hallucinations by enforcing strict context-only prompting and explicit refusal policies.
3. **Reproducible environments**: Versioned Alembic migrations, pinned lockfiles, non-root Docker builds, and live infrastructure in CI.
4. **Quantifiable evaluation**: Testing semantic quality and retrieval hit rate with verifiable metrics, not just checking HTTP status codes.

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-roman--nalapko-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/roman-nalapko-aa70b9327)
[![GitHub](https://img.shields.io/badge/GitHub-roman--nalapko-181717?style=for-the-badge&logo=github)](https://github.com/roman-nalapko)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=roman-nalapko&color=6C5CE7&style=flat" alt="Profile views" />
</p>
