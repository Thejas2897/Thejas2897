# Thejas Manjunath — AI/ML Specialist

I build end-to-end GenAI systems: Retrieval-Augmented Generation pipelines, agentic orchestration, and cloud-deployed LLM applications — grounded by 2 years of production operations experience as a differentiator, not a detour.

**What I work on:**

- RAG pipeline design — chunking strategy, retrieval tuning, anti-hallucination prompting
- LangChain & LangGraph — LCEL, Runnables, agentic tool-calling loops, conversational memory (checkpointing)
- LangSmith — tracing, per-step debugging and latency analysis
- AWS Bedrock — Knowledge Bases, multi-format ingestion, model selection & debugging
- Serverless LLM deployment — AWS Lambda, API Gateway, least-privilege IAM
- Vector databases — ChromaDB

**Current focus:** Targeting AI/ML and GenAI Engineering roles where retrieval-grounded system design, agentic orchestration, and production reliability instinct are core engineering values.

---

## Featured Project

| Project | What it demonstrates |
|---|---|
| [log-intelligence-assistant](https://github.com/Thejas2897/log-intelligence-assistant) | End-to-end RAG-based AIOps pipeline — local (ChromaDB/LangChain) and cloud (AWS Bedrock) implementations, a debugged and serverless-deployed chatbot, and an agentic LangGraph workflow with LangSmith tracing |

This single repo covers three components, each documented on its own:

- **Core RAG pipeline** — built from scratch (ChromaDB, LangChain LCEL, Gemini API) over system logs and runbooks; chunking strategy (chunk_size=500, overlap=50, top_k=3) validated against empirical retrieval quality, with 3 deliberately documented production failure modes as a reusable debugging reference.
- **AWS Bedrock RAG Chatbot** — multi-format Knowledge Base (PDF, HTML, CSV) with S3 Vectors and Titan embeddings; a controlled 100/500/800-token chunking comparison using real tiktoken-measured counts; a reproducible RetrieveAndGenerate failure isolated and resolved through systematic elimination; deployed as a public, authenticated HTTPS endpoint via Lambda + API Gateway with a custom authorizer.
- **Agentic Orchestration** — a LangGraph agent with a tool-calling loop (retrieval + escalation) routed via conditional edges and a bounded iteration guard rail, with thread-scoped conversational memory and LangSmith tracing for per-step debugging.

---

## Also on this profile

The Redis performance engineering work referenced above (QiCAP Markets) is documented in its own repo:

| Project | What it demonstrates |
|---|---|
| [redis-performance-toolkit](https://github.com/Thejas2897/redis-performance-toolkit) | Empirical Redis benchmarking and tuning — 9× latency reduction, 371% throughput increase, production-grade backup/restore/migration toolkit |

---

## Production Numbers Worth Knowing

- **9× p50 write latency reduction** — Redis appendfsync tuning, measured on bare-metal hardware (QiCAP Markets)
- **371% SET throughput increase** — same tuning exercise, 100k mixed-workload benchmark
- **99,601 req/s throughput ceiling** — 6-node Redis Cluster simulation, zero request loss after resolving a connection flood
- **BGSAVE fork spike eliminated (49 ms)** — diagnosed and resolved via 14-parameter tuning across 6 Redis config groups; identified the architectural ceiling where config cannot resolve HGETALL latency on 1 GB+ hashes (fix requires HSCAN with bounded batch sizes)
- **100/500/800-token chunking comparison** — empirically identified optimal RAG chunk size using real tiktoken-measured counts

---

## Stack

**GenAI & LLM Engineering:** RAG · LangChain · LangGraph · LangSmith · Vector Databases (ChromaDB)
**Cloud & AI Infrastructure:** AWS Bedrock · AWS Lambda · API Gateway · Terraform · Docker & Docker Compose · Linux
**Languages:** Python · Bash · Go

---

*Open to AI/ML and GenAI Engineering roles. Based in Bengaluru.*
*GitHub: [Thejas2897](https://github.com/Thejas2897)*
