<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:0891b2,100:22c55e&height=220&section=header&text=Sajid%20Miya&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20%2F%20LLM%20Engineer%20%E2%80%A2%20Agentic%20Systems%20%E2%80%A2%20RAG&descAlignY=59&fontAlign=50" alt="Sajid Miya — AI / LLM Engineer" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=20&pause=1100&center=true&vCenter=true&width=850&lines=I+build+useful+AI+systems%2C+not+just+demos.;Agentic+workflows+%7C+RAG+%7C+LLM+evaluation;Local-first+AI+%7C+Multi-tenant+systems+%7C+MCP;Researching+speech+and+pronunciation+assessment" alt="Animated introduction" />
</p>

<p align="center">
  <a href="https://sajidmiya.com.np"><img src="https://img.shields.io/badge/Portfolio-sajidmiya.com.np-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:miyasajid19@gmail.com"><img src="https://img.shields.io/badge/Email-Let's%20talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/sajidmiya/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/miyasajid19"><img src="https://img.shields.io/badge/GitHub-miyasajid19-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=miyasajid19&label=Profile%20views&color=0ea5e9&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/miyasajid19?label=Followers&style=flat-square" alt="GitHub followers" />
</p>

---

## About me

I'm an **AI / LLM Engineer** interested in turning research and emerging AI techniques into dependable software. I work across agentic systems, retrieval-augmented generation, backend engineering, and evaluation—with a particular interest in systems that are useful, measurable, and privacy-conscious.

- 🎓 B.E. Computer Science, Thapar Institute of Engineering & Technology (2023–2027)
- 🧠 Focus areas: agentic workflows, advanced RAG, tool-using systems, and LLM evaluation
- 🔬 Research: multi-granularity pronunciation assessment on SpeechOcean762
- 🛠️ Building with Python, FastAPI, LangGraph, PostgreSQL, and local inference tools
- 🌏 Based in Patiala, India; open to relevant AI / LLM engineering opportunities

## What I build

| Area | What interests me |
|---|---|
| **Agentic systems** | Stateful workflows, tool use, multi-agent orchestration, MCP |
| **Retrieval systems** | Agentic RAG, GraphRAG, Self-RAG, corrective retrieval, reranking |
| **LLM quality** | Evaluation with DeepEval and Ragas, groundedness, retrieval quality |
| **AI products** | FastAPI services, multi-tenant architecture, reliable integrations |
| **Local-first AI** | Private inference, on-device workflows, user-controlled data |

## Featured work

Five full-stack AI products built end-to-end, plus a separate local-first assistant.

### SaviraCortex — Evidence-aware agentic AI platform

A full-stack AI platform for conversational AI, document intelligence, and image generation, with an evidence-aware RAG pipeline designed to retrieve, validate, and organize supporting information before generation.

- Conversational AI chat and image generation through a unified application
- Document OCR and retrieval workflows, including cloud-dependent OCR and RAG capabilities
- Hybrid retrieval combining dense embeddings with Qdrant and BM25, followed by result fusion and reranking
- LangGraph-coordinated retrieval evaluation: checks evidence sufficiency, adaptively adjusts top-k, excludes weak chunks, and can expand retrieval for up to three attempts
- Accumulates and deduplicates evidence across attempts, then compresses context when it exceeds 15 unique documents
- Preserves chunk IDs, document order, metadata, and provenance; hypothetical answers are used only to guide retrieval, never as factual evidence or citations
- Dedicated API gateway with model-provider routing, plus Firebase-backed authentication and organization workflows
- **Quality:** 393 passing tests reported for the RAG pipeline
- **Stack:** Python, Next.js, FastAPI, Firebase, LangGraph, Qdrant, BM25, PostgreSQL, API Gateway

### SaviraNexus — Human-in-the-loop agent orchestration

A platform connecting autonomous agents with human operators through task coordination, messaging, and secure file exchange across isolated development environments.

- Human-in-the-loop agent workflows and operator-assistance tickets
- Daytona sandbox integration through a custom MCP server
- Redis-backed agent inbox, human responses, and task updates
- Web and mobile PWA interfaces for task monitoring, messaging, and secure file exchange
- **Stack:** Python, FastAPI, Redis, MCP, Daytona, Next.js, React, Vercel, Render

### [SaviraNous](https://synapselearn.sajidmiya.com.np) — Conversational AI tutor

A desktop conversational AI tutor with secure multi-user workflows, PDF and web RAG, four-layer memory, and persistent conversations.

- PDF and web RAG with FAISS, ChromaDB, resource-aware retrieval, and cross-encoder reranking
- Four-layer conversational memory, checkpoint restoration, conversation branching and merging, and persistent threads
- Evaluated 38 curated cases with DeepEval: **0.990 answer relevancy**, **0.978 faithfulness**, and **0.925 contextual recall**
- Admin dashboard and secure multi-user conversation management
- **Stack:** Python, FastAPI, PostgreSQL, Electron, FAISS, ChromaDB, DeepEval

### [NexHire](https://nexhire.sajidmiya.com.np) — AI-native hiring platform

An end-to-end recruitment platform covering job posting through offer, with LLM-driven screening, matching, scheduling, and email.

- Automated resume screening and candidate matching using LLMs, RAG, and agentic workflows
- Interview scheduling and email generation
- Google Calendar, Gmail, Slack, and Stripe integrations
- Live subscription billing and multi-tenant data isolation
- **Stack:** React, FastAPI, PostgreSQL, Redis, Docker, JWT, Stripe

### [commit2connect-mcp](https://github.com/miyasajid19) — GitHub + LinkedIn MCP server

A single FastMCP server connecting GitHub repository management and LinkedIn publishing through one MCP connection.

- **56 tools, 26 prompts, and 4 resources**
- Long-running task support and media uploads
- 30-second response cache and rate-limit guard
- Connected to Claude Code and Codex for workflows from code changes and pull-request merges to LinkedIn announcements
- **Stack:** Python, FastMCP, uv, OAuth 2.0, GitHub REST API, LinkedIn API

### Portfolio Agent — Local-first AI assistant

A privacy-first, fully local multimodal assistant with no external API dependency.

- Local inference with Ollama and real-time streaming chat
- Vision input and tool calling
- Persistent SQLite + JSON long-term memory
- Human-in-the-loop checkpoints and approvals for sensitive actions
- Dynamic model orchestration
- **Stack:** FastAPI, LangGraph, Ollama, SQLite

## Research

### HiPPA — Hierarchical Multi-Granularity Pronunciation Assessment

A reference-conditioned pronunciation assessment pipeline built around WavLM and the SpeechOcean762 benchmark. The work extends scoring from phoneme-level assessment to word- and sentence-level metrics.

- **Architecture:** hierarchical multi-task transformer with cross-attention, CTC-derived confidence features, and score calibration
- **Pipeline:** preprocessing → training → evaluation → report generation → Streamlit analysis dashboard
- **Sentence fluency:** Pearson 0.754 (+67% relative to the 0.450 baseline)
- **Sentence prosody:** Pearson 0.737
- **Sentence total:** Pearson 0.697
- **Trade-off:** phoneme score moved from 0.450 to 0.396 while adding three sentence-level metrics

[Read the HiPPA paper (PDF)](https://ik.imagekit.io/miyasajid19/HiPPA.pdf)

## Technical toolkit

**Languages**
Python · JavaScript · C++ · C · SQL

**AI, agents & orchestration**
LangChain · LangGraph · Deep Agents · Ollama · FastMCP · Tool Calling · Prompt & Context Engineering

**Retrieval & evaluation**
Agentic RAG · GraphRAG · Self-RAG · Corrective RAG · RAPTOR · LightRAG · HippoRAG · Vector Search · Cross-Encoder Reranking · DeepEval · Ragas

**ML & data**
PyTorch · TensorFlow · Scikit-learn · Pandas · NumPy · NLP

**Backend & frontend**
FastAPI · Flask · Flask-SocketIO · REST APIs · React

**Databases & infrastructure**
PostgreSQL · MySQL · MongoDB · Redis · SQLite · FAISS · ChromaDB · Pinecone · Docker · AWS

---

## GitHub activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=miyasajid19&theme=tokyonight" alt="GitHub contribution summary" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=miyasajid19&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=miyasajid19&theme=tokyo-night&hide_border=true&area=true" alt="GitHub activity graph" />
</p>

## Find me online

- **Portfolio:** [sajidmiya.com.np](https://sajidmiya.com.np)
- **Project case study:** [NexHire](https://sajidmiya.com.np/work/nexhire)
- **Email:** [miyasajid19@gmail.com](mailto:miyasajid19@gmail.com)
- **LinkedIn:** [linkedin.com/in/sajidmiya](https://www.linkedin.com/in/sajidmiya/)

<p align="center">
  <em>Curious by default. Building, measuring, and improving—one system at a time.</em>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22c55e,50:0891b2,100:0f172a&height=110&section=footer" alt="Footer banner" />
</p>
