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

### [SaviraNous](https://synapselearn.sajidmiya.com.np) — Local-first AI tutor

A desktop learning platform built around hierarchical memory, adaptive retrieval, and multi-agent reasoning. Designed to keep models, data, and memory on the user's machine unless external access is enabled.

- **Hierarchical memory:** active chat, Hippocampus, Prefrontal Cortex (PFC), and Long-Term Memory
- **Path Judger:** routes turns across 13 processing paths, including vision, web search, hybrid retrieval, and council reasoning
- **Hierarchical RAG:** resource selection, adaptive `k_alloc`, cross-encoder reranking, and labelled context construction
- **AI Council:** parent agent coordinates analytical, evidence-first, and sceptical sub-agents with a supervisory merger
- **Personalisation:** per-topic mastery model updated using EMA (α = 0.7), with cold-start defaults
- **Evaluation:** 0.978 faithfulness, 0.990 answer relevancy, and 0.945 contextual precision on a 38-item DeepEval benchmark
- **Stack:** Python, FastAPI, LangGraph, PostgreSQL + pgvector, Redis, FAISS, ChromaDB, Ollama, Electron

### [NexHire](https://nexhire.sajidmiya.com.np) — AI-native hiring platform

An end-to-end recruitment product that helps teams screen applicants, compare shortlisted candidates, and coordinate hiring workflows. Recruiters retain the final decision.

- **Resume screening:** job-description alignment scores with configurable thresholds and review stages
- **Candidate comparison:** pairwise ranking with written rationale
- **Recruiter workflow:** Kanban pipeline, structured scorecards, and bulk actions
- **Communication:** configurable candidate email templates and status-based notifications
- **Privacy and tenancy:** tenant-scoped data access and anonymised screening mode
- **Integrations:** Google Calendar, Gmail, Slack, and Stripe
- **Stack:** React, FastAPI, PostgreSQL, Redis, Docker, JWT, LangChain, Stripe

### [commit2connect-mcp](https://github.com/miyasajid19) — GitHub & LinkedIn MCP server

A FastMCP server that brings GitHub repository workflows and LinkedIn publishing behind one MCP connection.

- 56 tools, 26 prompts, and 4 resources
- Tool annotations, response caching, and rate limiting
- Supports long-running media uploads
- Used with Claude Code and Codex for workflows spanning code changes, pull requests, and publishing
- **Stack:** Python, FastMCP, `uv`, OAuth 2.0, GitHub REST API, LinkedIn API

### Portfolio Agent — Local-first AI assistant

A privacy-focused assistant built around local inference and human approval.

- Local model execution with no required external API dependency
- Vision and tool-calling workflows
- Human-in-the-loop approvals
- Persistent memory
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
