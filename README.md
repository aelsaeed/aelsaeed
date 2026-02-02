# <FULL_NAME>

<ROLE_TAGLINE>

- 📍 <CITY, COUNTRY>
- Building: production-grade LLM apps with measurable quality and latency targets
- Open to: senior AI/ML, LLM platform, or applied ML roles

[Email](mailto:<EMAIL>) · [LinkedIn](<LINKEDIN_URL>) · [Website](<WEBSITE_URL>)

![Python](https://img.shields.io/badge/Python-3.10%2B-1f6feb?logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerized-0db7ed?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud-232f3e?logo=amazonaws&logoColor=white)
![CI](https://img.shields.io/badge/CI-Status%20Placeholder-6f42c1)

![Profile banner](assets/banner.svg)

## What to check first
1. **RAG API + evaluation** → [`rag-api-eval-starter`](https://github.com/<GITHUB_USERNAME>/rag-api-eval-starter): end-to-end retrieval, eval harness, and quality gates.
2. **Document AI pipeline** → [`doc-ai-pipeline-starter`](https://github.com/<GITHUB_USERNAME>/doc-ai-pipeline-starter): ingestion, chunking, extraction, and verification for real-world PDFs.

## Portfolio (6 repos)

| Repo | What it demonstrates | Key features | How to run (1–2 commands) |
| --- | --- | --- | --- |
| [`rag-api-eval-starter`](https://github.com/<GITHUB_USERNAME>/rag-api-eval-starter) | RAG API with evaluation-first workflow | Retrieval quality baselines, prompt + context controls, automated evals | `make up` → `make eval` (or `docker compose up` → `python -m evals`) |
| [`doc-ai-pipeline-starter`](https://github.com/<GITHUB_USERNAME>/doc-ai-pipeline-starter) | Document AI from ingest to verification | OCR pipeline, schema extraction, confidence scoring | `make run` → `make test` (or `python -m pipeline`) |
| [`mlops-train-register-serve`](https://github.com/<GITHUB_USERNAME>/mlops-train-register-serve) | Model lifecycle with repeatable training | versioned data, model registry, deployable artifact | `make train` → `make serve` (or `python train.py`) |
| [`otel-microservice-lab`](https://github.com/<GITHUB_USERNAME>/otel-microservice-lab) | Observability in a microservice system | tracing, metrics, log correlation, SLO alerts | `make up` → `make traces` (or `docker compose up`) |
| [`dagster-gx-pipeline`](https://github.com/<GITHUB_USERNAME>/dagster-gx-pipeline) | Data pipeline with quality gates | orchestration, validation checks, lineage | `make run` → `make test` (or `dagster dev`) |
| [`llm-serving-gateway-bench`](https://github.com/<GITHUB_USERNAME>/llm-serving-gateway-bench) | LLM serving and gateway performance | rate limiting, routing, load tests, latency stats | `make up` → `make bench` (or `python bench.py`) |

## Architecture snapshots

![RAG architecture](assets/architecture-rag.svg)
![DocAI architecture](assets/architecture-docai.svg)

## Private work note
Most of my employer work is private or under NDA. These public repos are representative samples that emphasize production constraints: evaluation, reproducibility, and observability in real systems.

## Engineering principles
- Measure quality with explicit evals before optimizing prompts or models.
- Make builds reproducible: pinned deps, one-command setup, deterministic configs.
- Prefer simple, testable interfaces over clever abstractions.
- Bake in observability: traces, metrics, and structured logs from day one.
- Treat security as a default: secrets hygiene and least-privilege configs.
- Automate the boring parts with CI and quality gates.

## Tech stack
- **LLM/RAG:** OpenAI/Anthropic APIs, vector DBs, rerankers, eval harnesses
- **MLOps:** MLflow, model registries, CI/CD, containerized training
- **Data:** Dagster, Great Expectations, DuckDB, Postgres
- **Backend:** FastAPI, gRPC, Python services
- **Observability:** OpenTelemetry, Prometheus, Grafana
- **Cloud:** AWS, Docker, Terraform

<!--
## GitHub stats
- Add stats cards here.

## Talks / writing
- Add talks, posts, or papers here.

## Open-source contributions
- Add notable PRs or repos here.
-->

## Pinning suggestion
Pin these repos in order for a coherent story:
1. `rag-api-eval-starter`
2. `doc-ai-pipeline-starter`
3. `mlops-train-register-serve`
4. `dagster-gx-pipeline`
5. `otel-microservice-lab`
6. `llm-serving-gateway-bench`
