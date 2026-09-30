# Hi, I'm Sudarsan Srivathsun

**Software Engineer | MS Computer Science @ UC Davis**

I build backend systems and production software, with a focus on APIs, data-intensive services, performance, and reliable distributed systems. I also work on applied AI, agentic systems, and AI infrastructure.

Currently pursuing my MS in Computer Science at UC Davis, graduating June 2027. Previously spent 3+ years at AB InBev in Bengaluru as a Full Stack Software Engineer. Worked on high-throughput financial and supply chain systems across multiple regions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sudarsan%20Srivathsun-blue?style=flat-square)](https://linkedin.com/in/sudarsan-srivathsun)
[![Portfolio](https://img.shields.io/badge/Portfolio-sudarsansrivathsun.com-black?style=flat-square)](https://sudarsansrivathsun.com)
[![Email](https://img.shields.io/badge/Email-srisudarsan2000%40gmail.com-red?style=flat-square)](mailto:srisudarsan2000@gmail.com)

## What I Work On

* **Software and Backend:** Software Engineering, Backend Engineering
* **Systems:** Distributed Systems
* **AI:** Applied AI, Agentic AI

## Featured Projects

### [SDR_RDMA_UDP](https://github.com/harish876/SDR_RDMA_UDP)

Reliable file transfer protocol over UDP using Reed-Solomon erasure coding (Intel ISA-L).

* Engineered application-layer packet recovery and custom congestion control with no TCP fallback.
* Sustained ~1000 Mbps steady throughput across 0-10% packet loss on 100 MiB to 1 GiB transfers.
* **Stack:** C++, UDP, Reed-Solomon

### [Apache ResilientDB / ResQL](https://github.com/DDS-Project-Team/resilientdb-resql)

Open-source contribution to Apache ResilientDB, a Byzantine Fault Tolerant blockchain framework in C++.

* Integrated an embedded DuckDB SQL engine into the core key-value storage layer.
* Authored deployment and startup tooling for 4-replica PBFT consensus clusters.
* **Stack:** C++, PBFT consensus, DuckDB

### [Chaos-Tested LangGraph Agent](https://github.com/Burnfireblaze/ai-travel-agent)

12-node planner-executor-evaluator agent with ChromaDB memory and fault injection.

* Implemented dynamic replanning across 5 conditional edges with a custom JSONL telemetry layer tracking 8 span types.
* Designed a fault-injection harness (timeouts, exceptions, malformed LLM outputs); ran 200+ sessions, generated 10K+ log records.
* Categorized 185 failure modes, achieved 76% task completion under active failure conditions.
* **Stack:** Python, LangGraph, LangChain, ChromaDB

### [DentAI (SacHacks 2026, 1st Place / ~80 teams)](https://github.com/Burnfireblaze/dental-ai)

AI-assisted dental X-ray review and report generation platform.

* Fine-tuned a 2-model YOLOv8 detection ensemble behind an async FastAPI job queue, deduplicating overlapping boxes at IoU >= 0.5.
* Routed detections into an LLM report generator (Groq, Ollama, Hugging Face) with a 4-tier provider fallback.
* **Stack:** Python, YOLOv8, FastAPI, Groq, Hugging Face

### [Wirecracker](https://github.com/UCD-193AB-ws24/Wirecracker)

Clinical decision-support platform for epilepsy surgery planning at UC Davis Neurology.

* Built backend REST APIs for spatial brain-region queries and patient data ingestion.
* Integrated interactive visualization frontends for clinical diagnostic workflows.
* **Stack:** TypeScript, Node.js, PostgreSQL

## Experience

### AB InBev, Bengaluru (Aug 2022 to Jul 2025)

**Software Engineer II, Full Stack, promoted from Software Engineer I.** Shipped production backend, data, and full-stack systems for a global CPG platform.

#### Financial Reconciliation Platform (150M+ daily records, 100K+ accounts, 5 regions)

* Cut submit-reconciliation latency from ~50s to ~4s and cross-table query latency from ~5s to ~200ms by rewriting the query layer (predicate pushdown, deferred joins, duplicate-scan elimination) across 140+ MSSQL tables.
* Re-architected the reconciliation compute layer into 6 queue-triggered Azure Function jobs, splitting single and bulk paths to sidestep function execution limits.
* Built bulk-reconciliation rules that auto-clear ~30% of accounts per month with no manual review.

#### Supply Chain Planning Platform

* Cut customer-facing search latency from ~20s to ~200ms with a filter-pushdown query API using deferred joins and server-side pagination.
* Built Azure Data Factory ETL pipelines processing 10M+ daily rows from Snowflake to MSSQL.
* **Stack:** React, Node.js, Azure Functions, MSSQL, Snowflake, Azure Data Factory

#### Reliability and Team

* Region-level DRI on 100+ production incidents across 5 regions through month-end close cycles.
* Reviewed 50+ PRs/month across an 8-engineer team.
* Wrote the internal REST API contract registry and dependency-injection conventions the team adopted.
* Wired Snyk and Apiiro as CI/CD gates for critical vulnerabilities.

## Tech Stack

* **Languages:** C++, Python, C, JavaScript, TypeScript, SQL
* **Backend and Systems:** REST APIs, gRPC, FastAPI, Flask, Node.js, PBFT consensus, UDP, erasure coding, event-driven architectures, observability
* **Databases:** SQL Server, PostgreSQL, MySQL, MongoDB, Redis, DuckDB, ChromaDB, Snowflake
* **AI and ML:** LangGraph, LangChain, RAG, LLM agents, model inference, fine-tuning, YOLOv8, Hugging Face, PyTorch
* **Cloud and Infra:** Azure (Functions, Data Factory, DevOps), AWS, GCP, Docker, Kubernetes, Kafka
* **Frontend:** React, TypeScript
* **Currently Learning:** Rust, low-latency C++, LLM inference optimization (vLLM, SGLang)

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Burnfireblaze&show_icons=true&hide_border=true&count_private=true&theme=dark" height="165" />
  <img src="https://streak-stats.demolab.com?user=Burnfireblaze&hide_border=true&theme=dark" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Burnfireblaze&layout=compact&hide_border=true&theme=dark" height="165" />
  <img src="https://leetcard.jacoblin.cool/Burnfireblaze?theme=dark&font=Karma&ext=contest" height="165" />
</p>

---

**Available for full-time roles starting June 2027 in Software Engineering, Backend Engineering, Distributed Systems, and Applied AI / Agentic AI..**
