# Roman Nalapko — Python Backend & Applied AI Engineer

I build reliable Python APIs, RAG systems, LLM integrations, and automation workflows with explicit validation, testing, and observable failure handling.

Currently pursuing a Bachelor's degree in Information Systems and Technologies. Open to **Software Engineering**, **Python Backend**, and **Applied AI** internship and early-career opportunities in Europe.

[![Resume](https://img.shields.io/badge/Resume-PDF-007ACC?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](./Roman_Nalapko_Python_Backend_Applied_AI_Engineer_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Roman_Nalapko-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/roman-nalapko-aa70b9327/)

## Core skills

| Area | Technologies |
| --- | --- |
| Backend | Python · FastAPI · asyncio · REST APIs · Pydantic · SQLAlchemy · Alembic |
| Applied AI | RAG · hybrid retrieval · embeddings · semantic search · LLM evaluation · OpenAI-compatible APIs |
| Data & cloud | PostgreSQL · Qdrant · Cloudflare Workers · D1 · KV |
| Delivery | pytest · Ruff · Docker · GitHub Actions · structured logging · Prometheus · Linux |

## Featured projects

### [AI RAG Platform](https://github.com/roman-nalapko/ai-rag-platform)

A local-first document intelligence backend that demonstrates production-oriented Applied AI patterns.

- Async PDF/TXT ingestion with durable indexing jobs.
- Hybrid retrieval using Qdrant dense vectors and PostgreSQL full-text search with Reciprocal Rank Fusion.
- Tenant-scoped knowledge bases, JWT authentication, SSE answers with citations, and conversation memory.
- Offline RAG evaluation, Prometheus metrics, structured JSON logs, Docker, and CI.
- 118 automated tests covering API contracts, retrieval, authentication, and failure paths.

[![CI](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/roman-nalapko/ai-rag-platform/actions/workflows/ci.yml)
[![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-API-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-dc244c)](https://qdrant.tech/)

## Engineering principles

- Keep HTTP, business, data, and provider boundaries explicit.
- Validate model output before persistence or downstream actions.
- Design for timeouts, bounded retries, idempotency, and observable failures.
- Test behavior and failure paths, not only successful HTTP responses.
- Keep secrets out of source, logs, and prompts.

## Contact

- [LinkedIn](https://www.linkedin.com/in/roman-nalapko-aa70b9327/)
- [GitHub](https://github.com/roman-nalapko)
