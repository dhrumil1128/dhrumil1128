### Dhrumil Pawar
**Applied AI & Full-Stack Systems Engineer** · Building autonomous agent runtimes, grounded RAG pipelines, and zero-bloat web infrastructure.

Currently building **[KAIROS](https://github.com/dhrumil1128)** — an open-source autonomous agent harness with MCP tool orchestration, tiered state persistence, and sandboxed self-healing execution.

[Portfolio](https://datascienceportfol.io/dhrumilpawar) · [LinkedIn](https://linkedin.com/in/YOUR-HANDLE) · [Email](mailto:YOUR-EMAIL@example.com)

---

### Selected Systems & Architecture

| System | What It Solves | Architecture & Stack |
| :--- | :--- | :--- |
| **[KAIROS](https://github.com/dhrumil1128)** | Deterministic orchestration and safety guardrails for multi-step AI agents | Intent-routing LLM bridge, Universal MCP hub, tiered memory, sandboxed execution |
| **[NexusForge](https://github.com/dhrumil1128)** | High API quota burn and latency in multi-agent workflows | Dynamic intent routing (CrewAI + MCP), FastAPI backend, Next.js frontend |
| **[AI-IntelHub](https://github.com/dhrumil1128)** | Low-precision retrieval over dense technical knowledge bases | Hybrid semantic search, vector embeddings, Google GenAI SDK |
| **[TrustLens AI](https://github.com/dhrumil1128)** | Unverified LLM outputs in production workflows | Grounded RAG pipeline, automated hallucination checks, Docker / K8s |
| **[WaterClassify](https://github.com/dhrumil1128)** | Unlabeled time-series anomalies across 159K+ IoT sensor records | Automated Python / scikit-learn K-Means clustering pipeline |

---

### Engineering Principles
* **Context & Token Budgeting First:** Treat context windows and inference calls like memory and CPU cycles—route cheap/discriminative tasks locally before hitting frontier models.
* **End-to-End Ownership:** A model in a notebook isn't a product. Every system above pairs Python/FastAPI inference backends with typed Next.js/React interfaces and containerized deployments.
* **Boring Reliability:** Prefer strict schema validation, deterministic fallback paths, and observable state over prompt-chaining magic.

---

### Core Stack
* **AI & Retrieval:** PyTorch, LoRA / Unsloth, LangGraph, CrewAI, Model Context Protocol (MCP), RAG, PostgreSQL (`pgvector`), FAISS
* **Backend & Data:** Python, FastAPI, SQL, Redis, Docker, Kubernetes, GitHub Actions
* **Frontend:** Next.js, React, TypeScript, Tailwind CSS
