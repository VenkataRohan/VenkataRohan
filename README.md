<h1 align="center">Hi 👋, I'm Venkata Rohan Kambhampati</h1>
<h3 align="center">Staff AI Engineer @ Equinix | Enterprise AI Agents, MCP & RAG</h3>

<p align="center">
  <a href="mailto:venkatarohank@gmail.com"><b>Email</b></a> •
  <a href="https://venkatarohan.vercel.app"><b>Portfolio</b></a> •
  <a href="https://linkedin.com/in/venkata-rohan"><b>LinkedIn</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Staff%20AI%20Engineer-Equinix-371e77?style=flat" />
  <img src="https://img.shields.io/badge/Google%20ADK-Agentic%20AI-371e77?style=flat&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-Tool%20Servers-371e77?style=flat" />
  <img src="https://img.shields.io/badge/RAG-Production-371e77?style=flat" />
</p>

---

## 🚀 About

I build enterprise AI agents you can trust with real permissions.

At Equinix, I lead development of the **DIO Agent**, a multi-agent system on **Google ADK** and **Gemini (Vertex AI)** that handles procurement, finance, and IT requests in production, from approving purchase requests to pulling vendor statements. Because these agents act on real systems, most of my effort goes into making them trustworthy: authorization re-checked against live data before every write, verified user identity instead of caller-supplied context, human confirmation before consequential actions, and PII-safe logging.

Before that, I built Equinix's internal RAG assistant and the multi-agent Sidekick assistant on Azure, and measured retrieval quality with a proper evaluation harness instead of guesswork.

---

## 📊 Highlights

| Area | What I did | Result |
|---|---|---|
| **Agents in production** | DIO Agent: Google ADK orchestrator + 4 sub-agents (ServiceNow, Coupa, Oracle ERP, SAP Fieldglass) over 29 MCP tools, running on GKE | 7K+ enterprise actions per month |
| **Procurement MCP server** | Primary author of the Coupa MCP server (11 tools) with live authorization re-validation and human-in-the-loop confirmation | 2.4K+ approvals per month |
| **Agent security** | Verified-identity attribution, signed-session verification across MCP servers, OAuth 2.0 token introspection and exchange (RFC 7662 / 8693) | Fail-closed tool gating |
| **RAG quality** | Hybrid retrieval + semantic reranking on Azure AI Search over 15K+ documents (44K chunks), 181-query golden set | 0.90 Hit@5, 0.74 MRR@10 (95% CI 0.69-0.79), +56% over BM25 |
| **RAG performance** | Parallel retrieval, server-side vectorization, query decomposition | Latency 8.5s to 2.5s (70%), answer completeness +60% |
| **LLM cost** | Prompt compression and output-token limits | Monthly spend $12K to $5.4K (55%) |
| **Multi-agent routing** | GPT-4 intent classification for HR / IT / Legal agents (Sidekick) | 95% accuracy, 2s P95, 1,000+ employees |

---

## 🏢 Experience

### Equinix | Staff AI Engineer *(Mar 2026 - Present)*
🧠 **Google ADK · Gemini (Vertex AI) · MCP · A2A · Python · GKE · Helm · PostgreSQL**

- Lead the DIO Agent on Equinix's Agentic Platform; own root routing and the Coupa sub-agent
- Primary author of the Coupa procurement MCP server, including a PO-change diff engine covering 38 fields
- Built PII/secret redaction and correlation-ID logging across the agent and 4 MCP servers
- Shipped the agent and all 4 MCP servers to production on GKE via Helm GitOps and change-gated CI/CD, with HPA autoscaling
- Built a Teams Adaptive Card rendering engine for the Action Broker (Node.js/TypeScript)

### Equinix | Senior Associate Software Engineer *(Jun 2023 - Mar 2026)*
🧠 **Python · FastAPI · Node.js · Azure OpenAI · OpenAI Agents SDK · Azure AI Search**

- Contributed to Sidekick, a multi-agent assistant (HR, IT, Legal) on the OpenAI Agents SDK
- Built the Equinix GPT RAG pipeline and its evaluation harness, and audited all 44K chunks to surface stale, duplicate, and mis-split content, each mapped to a fix
- Built incremental ingestion with Azure Functions (5K+ ServiceNow updates daily, 99.9% freshness)
- Added guardrails: PII detection (200+ potential leaks prevented) and RBAC-based context filtering
- Automated ERP workflows (SAP Fieldglass, Coupa, Teams approvals): 15K+ monthly tasks, approval cycles from 5 days to 6 hours

### Equinix | Software Developer Intern *(Feb 2023 - Jun 2023)*
- React Flow DAG visualizer (30% fewer deployment errors) and an Oracle Integration Cloud automation saving 24 hours of manual work per month

---

## 🔥 Featured Project

### 📈 Distributed Stock Exchange Simulation
Full-stack real-time trading simulator built as 4 microservices.

**Tech:** TypeScript, Node.js, React, RabbitMQ, PostgreSQL, Prisma, Docker, Nginx

- Async order processing through RabbitMQ with retries, acknowledgements, and idempotent consumers
- Real-time updates over WebSockets with Nginx load balancing
- 🔗 Repo: https://github.com/VenkataRohan/stock_exchange

---

## 🌍 Open Source Contributions

| Project | Contribution |
|---|---|
| **Lightdash** | Alert links open the threshold edit modal directly ([#12119](https://github.com/lightdash/lightdash/pull/12119)) |
| **Cal.com** | Fixed booking-question ordering to preserve custom sequencing ([#18192](https://github.com/calcom/cal.com/pull/18192)) |
| **Rocket.Chat** | "Notify on Reactions" feature ([#32475](https://github.com/RocketChat/Rocket.Chat/pull/32475)) |

---

## 🧰 Tech Stack

### 🤖 Agentic AI & LLM
![Google ADK](https://img.shields.io/badge/Google%20ADK-371e77?style=flat&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20(Vertex%20AI)-371e77?style=flat&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-371e77?style=flat)
![A2A](https://img.shields.io/badge/A2A-371e77?style=flat)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-371e77?style=flat&logo=microsoftazure&logoColor=white)
![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI%20Agents%20SDK-371e77?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-371e77?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-371e77?style=flat)
![RAG](https://img.shields.io/badge/RAG-371e77?style=flat)
![Azure AI Search](https://img.shields.io/badge/Azure%20AI%20Search-371e77?style=flat&logo=microsoftazure&logoColor=white)

### 🧠 Backend / Systems
![Python](https://img.shields.io/badge/Python-371e77?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-371e77?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-371e77?style=flat&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-371e77?style=flat&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-371e77?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-371e77?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-371e77?style=flat&logo=mongodb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-371e77?style=flat&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-371e77?style=flat&logo=apachekafka&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-371e77?style=flat&logo=prisma&logoColor=white)

### ☁️ Cloud / DevOps
![Google Cloud](https://img.shields.io/badge/Google%20Cloud%20(GKE)-371e77?style=flat&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-371e77?style=flat&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-371e77?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-371e77?style=flat&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-371e77?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-371e77?style=flat&logo=githubactions&logoColor=white)

### 🔐 Security
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-371e77?style=flat)
![SAML SSO](https://img.shields.io/badge/SAML%20SSO-371e77?style=flat)
![RBAC](https://img.shields.io/badge/RBAC-371e77?style=flat)
![PII Redaction](https://img.shields.io/badge/PII%20Redaction-371e77?style=flat)

### 🎨 Frontend
![React](https://img.shields.io/badge/React-371e77?style=flat&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-371e77?style=flat&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-371e77?style=flat&logo=tailwindcss&logoColor=white)

---

## 📌 What I'm Exploring

- Authorization and identity patterns for agents that act on enterprise systems
- Evaluation frameworks for agent and RAG quality
- Multi-agent orchestration with MCP and A2A

---

## 📫 Connect With Me

- 💼 LinkedIn: https://linkedin.com/in/venkata-rohan
- 🌐 Portfolio: https://venkatarohan.vercel.app
- 📧 Email: venkatarohank@gmail.com

⭐ Happy to talk about agent security, retrieval evaluation, and getting LLM systems through enterprise production.
