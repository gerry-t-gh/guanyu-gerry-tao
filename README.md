# Gerry

**CS Graduate Student @ Northeastern University**  
Full-Stack · Backend · AI  
Also: Architecture & Design

---

## Skills

<p>
  <img alt="Java" src="https://img.shields.io/badge/-Java-f3951f?style=flat-square&logoColor=black"/>
  <img alt="Spring Boot" src="https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
  <img alt="FastAPI" src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img alt="Go" src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img alt="Node.js" src="https://img.shields.io/badge/-Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img alt="Express.js" src="https://img.shields.io/badge/-Express.js-87cf30?style=flat-square&logoColor=white"/>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=PostgreSql&logoColor=white"/>
  <img alt="MySQL" src="https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white"/>
  <img alt="Redis" src="https://img.shields.io/badge/-Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>
  <img alt="Kafka" src="https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img alt="Kubernetes" src="https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img alt="AWS" src="https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img alt="OpenAI" src="https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img alt="LangChain" src="https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img alt="LangGraph" src="https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img alt="Weaviate" src="https://img.shields.io/badge/-Weaviate-3dc4a7?style=flat-square&logoColor=white"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-f7df1c?style=flat-square&logo=javascript&logoColor=black"/>
  <img alt="React" src="https://img.shields.io/badge/-React.js-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img alt="Next.js" src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
</p>

---

## Projects

**[Wolf — AI Job Hunter](https://github.com/guanyu-gerry-tao/wolf)**  
AI-powered job hunting CLI tool and MCP server — finds roles, tailors resumes, fills application forms, and drafts outreach automatically.
- Covers the full job application pipeline: discovery, resume tailoring, form auto-fill, and cold outreach
- Runs as both a CLI and MCP server, invokable by other agents such as OpenClaw
- Stack: TypeScript · Node.js · Claude API · Playwright · SQLite · Gmail API

**[PromptOps Studio](https://github.com/guanyu-gerry-tao/promptops-studio)**  
Full-stack platform for testing and evaluating RAG pipelines and AI applications.
- Upload knowledge base documents, trigger indexing into Weaviate with hybrid search (vector + BM25 + reranking)
- Run batch evaluations asynchronously via Kafka; inspect node-level LangGraph execution traces and audit logs
- Three-service architecture: Next.js frontend · Spring Boot platform API · FastAPI + LangChain AI runtime
- Stack: TypeScript · Java · Python · LangGraph · Weaviate · MySQL · Redis · Kafka · Docker

**[OrderFlow](https://github.com/guanyu-gerry-tao/OrderFlow)**  
Reliable e-commerce order workflow system built around checkout correctness, async recovery, and operator visibility.
- Implements idempotent order creation, inventory reservation, payment authorization, transactional outbox, retries, and DLQ recovery
- Splits synchronous REST traffic from async event publishing/consumption through an API and worker runtime
- Stack: Java · Spring Boot · PostgreSQL · Redis · Redpanda/Kafka · React · Docker · Kubernetes

**[ServiceObs](https://github.com/guanyu-gerry-tao/ServiceObs)**  
Cloud-native observability platform for telemetry ingestion, service health read models, incident detection, and timelines.
- Ingests logs, metrics, and trace-like events, then aggregates latency, throughput, error, retry, and DLQ signals
- Builds incident timelines and dashboard views for service health, trace evidence, and troubleshooting workflows
- Stack: Go · PostgreSQL · Redpanda/Kafka · React · TypeScript · Docker · Playwright

**[OperationAssistant](https://github.com/guanyu-gerry-tao/OperationAssistant)**  
AI operations assistant for incident investigation with retrieval, diagnostic tools, guardrails, and evaluation reports.
- Combines RAG over runbooks with read-only service diagnostic tools, citation checks, and human approval gates
- Includes retrieval, tool-use, safety, and full-quality eval runners with deterministic and provider-backed modes
- Stack: Python · FastAPI · PostgreSQL/pgvector · Redis · React · TypeScript · Docker · OpenAI-compatible APIs

**[DataPulse](https://github.com/guanyu-gerry-tao/DataPulse)**  
Serverless-style event-driven data pipeline for file ingestion, job tracking, validation, and result summaries.
- Models S3-style file events, job lifecycle state, duplicate file detection, processing errors, and dead-letter evidence
- Defines a shared storage contract with MySQL and DynamoDB adapters for local-first pipeline development
- Stack: Python · MySQL · DynamoDB-style storage · pytest · API Gateway/Lambda-ready handler contracts

---

## Research

Independent researcher at the intersection of **computational design and architecture**.  
Published in *Journal of Building Engineering* (2024) — [doi:10.1016/j.jobe.2024.111621](https://doi.org/10.1016/j.jobe.2024.111621)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/taoguanyu/) · [gerry.tao@outlook.com](mailto:gerry.tao@outlook.com) · [Portfolio](https://gerrytao.com/)

---

*Actively seeking Summer 2026 Software Engineering internships.*
