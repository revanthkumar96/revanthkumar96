<h1 align="center">Sudikonda Revanth Kumar</h1>

<p align="center">
  <strong>Software Engineer — AI</strong> · Specializing in LLM systems, agentic architectures, and production-grade reliability at scale.
</p>

<p align="center">
  Final-year B.Tech CSE (AI) · Vignan's Institute of Information Technology · Andhra Pradesh, India
</p>

<p align="center">
  <a href="https://revanthkumar-dev.vercel.app"><img src="https://img.shields.io/badge/Portfolio-revanthkumar--dev.vercel.app-0e75b6?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/revanth-kumar-sudikonda"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@sudikondarevanthkumar"><img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="https://pypi.org/project/rouge-ai-sdk"><img src="https://img.shields.io/badge/PyPI-rouge--ai--sdk-3775A9?style=flat-square&logo=pypi&logoColor=white" alt="PyPI" /></a>
  <a href="mailto:sudikondarevanthkumar@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <code>1.5M+ records processed</code> · <code>50K+ docs in RAG pipeline</code> · <code>300+ concurrent users</code> · <code>10+ AI providers instrumented</code>
</p>

---

## What I do

I build AI systems for production — not toy demos or notebooks that stop at `print("Hello World")`.

The problems I care about are operational: **how do you keep an AI system honest about what it's doing, how do you make it recover from failure, and how do you know when it's quietly broken?** That lens shows up across everything I've shipped — voice agents with real-time orchestration, an observability SDK for LLM chains, a RAG pipeline serving 300+ concurrent users, and backend services processing millions of records.

Most of my work runs on real infrastructure, gets used by real users, and has metrics attached to it. The gap between a working demo and a working system is where most of the engineering actually lives.

---

## Featured Projects

### [Rouge.AI SDK](https://pypi.org/project/rouge-ai-sdk) — LLM Observability Platform (on PyPI)

> An OpenTelemetry-based SDK that instruments agentic workflows — surfacing execution paths, token usage, and latency across 10+ AI providers with zero changes to existing agent logic.

- Drop-in integration — no changes to existing agent logic
- Provider-agnostic token, latency, and execution-path telemetry
- Published to PyPI for production AI engineering teams

<sub>`Python` · `OpenTelemetry` · `Distributed Tracing` · `PyPI` · [GitHub](https://github.com/revanthkumar96/rogue.ai-sdk)</sub>

### [Iterative RLHF / RAFT Fine-Tuning Pipeline](https://github.com/revanthkumar96/Iterative-RLHF-for-RAG-Research-paper) — Undergraduate Research

> Fine-tuned Qwen2.5-1.5B, Phi-2, and TinyLlama using LoRA across three tasks, scored by a multi-model LLM-as-Judge evaluation framework over iterative rounds.

- Diagnosed and resolved 8 engineering bugs, including LoRA adapter double-stacking
- Fixed pad-token label leakage in the training pipeline
- Multi-model evaluation across three task families

<sub>`PyTorch` · `LoRA` · `RAFT` · `Hugging Face` · `Qwen2.5`</sub>

### [MLSC VIIT — Student Community Website](https://mlscviit.tech/) — Production

> Designed, built, and deployed the official Microsoft Learn Student Community website for VIIT, with CI/CD via GitHub Actions.

- Live in production at [mlscviit.tech](https://mlscviit.tech/)
- Event discovery, resources, and member communication
- Iterative improvements shipped from user feedback

<sub>`TypeScript` · `React` · `Vercel` · `GitHub Actions`</sub>

---

## Open Source

| Repository | Contribution | Why it mattered |
|---|---|---|
| [career-ops](https://github.com/revanthkumar96) · `56k+ ⭐` | Zero-auth *We Work Remotely* RSS provider | An AI job-search system needed remote listings without another API key. Shipped a dependency-free XML parser with SSRF-safe host allowlisting and full test coverage. |
| [browser-use](https://github.com/browser-use/browser-use) | CDP navigation timeout control | Agents were silently hanging on slow pages — no timeout, no error, no recovery. Now agents can configure how long to wait before failing explicitly. |
| [runtm.ai](https://github.com/runtm-ai/runtm) | Fixed lint failures, unblocked CI | GitHub Actions was broken for all contributors. Fixed root lint issues so the pipeline could run cleanly. |

---

## Experience

**Applied AI Engineer Intern — [Quantum Gandiva AI](https://www.quantumgandivaai.com/)** · *Apr 2026 – Present · Visakhapatnam, India*
Owning the voice agent stack end-to-end and building agent-to-agent protocol layers for production workflows.
- Integrated telephony, ASR/TTS providers, and orchestration for an inbound calling agent that captures leads and qualifies callers in real time
- Built an Agent-to-Agent (A2A) protocol layer connecting two in-house agentic applications with structured task handoff
- Fine-tuned Gemma 4 E4B for domain-specific use cases — low-latency, cost-efficient inference in production

**AI Systems Engineer — Freelance** · *Apr 2025 – Present*
Designing and shipping production RAG pipelines and agentic systems for clients across time zones.
- Owned architecture, evaluation harnesses, and deployment using TypeScript, Python, FastAPI, and Next.js
- Built multi-provider LLM integrations with structured fallback and output-quality monitoring
- Vector database pipelines with retrieval evaluation for evolving document corpora

**Software Engineer Intern — [Mindcres Technologies](https://mindcres.com/)** · *Dec 2025 – Mar 2026*
Contributed to an AI-powered Grievance Redressal System for the Government of Andhra Pradesh (RTGS).
- Built multilingual OCR, AI-based intent detection achieving 3× faster classification, and agentic officer-workspace workflows
- Maintained backend services processing 1.5M+ records; reduced API latency 30% via query optimization and caching
- RESTful APIs handling 10K+ requests/day across PostgreSQL and MongoDB

**Summer Intern — [Bharat Dynamics Limited](https://bdl-india.in)** · *Jun 2025 – Aug 2025*
Built a domain-specific RAG pipeline for aerospace document search at scale.
- Semantic search over 50K+ aerospace documents using vector databases and LangChain
- Deployed fault-tolerant services on Linux supporting 300+ concurrent users
- Observability dashboards monitoring LLM output quality in production

**Web Developer — MLSC VIIT** · *Nov 2025 – Present · Volunteer*
- Built and deployed the official Microsoft Learn Student Community VIIT website
- Led Azure cloud sessions to grow members' technical skills
- Mentored teams during Sushacks 3.0

---

## Research

### Iterative RLHF: Multi-Dataset × Multi-Model RAFT Alignment Pipeline
*Undergraduate Research · Vignan's Institute of Information Technology · 2025 – Present*

A systematic experiment asking whether iterative RLHF (via RAFT) produces **consistent** alignment gains across model sizes and task types — or whether improvements are model-specific, dataset-specific, or both.

- **Policy models:** Qwen2.5-1.5B-Instruct, Phi-2 (2.7B), TinyLlama-1.1B
- **Datasets:** WebGLM (RAG-QA), Yelp (review generation), XSum (summarization)
- **Method:** Each policy samples 4 candidates per prompt; a local reward model scores them; the top candidate drives LoRA fine-tuning over 3 iterations

The hard part was debugging iterative fine-tuning on constrained compute (Kaggle): 8 engineering bugs resolved, including LoRA adapter double-stacking and pad-token label leakage, plus per-iteration reward tracking, loss logging, and JSON output for full reproducibility. Half the research is just making sure the pipeline is actually doing what you think it is.

---

## Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & Cloud**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LoRA / RAFT](https://img.shields.io/badge/LoRA%20%2F%20RAFT-EE4C2C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=flat-square)
![Vector DBs](https://img.shields.io/badge/Vector%20DBs-FF6F61?style=flat-square)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**DevOps & Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## Achievements

- Top 10 — Sushacks '25 Hackathon
- Top 10 — GDG GenAI Hackathon
- Published open-source SDK on PyPI
- Undergraduate research on iterative RLHF / RAFT alignment

---

## Outside work

**Cooking** — I genuinely enjoy cooking, not just eating. Experimenting with recipes, adjusting on the fly, getting the result right. Clear inputs, immediate feedback, no ambiguity about whether it worked — honestly, not that different from debugging.

**Reverse Engineering** — Taking things apart to understand how they were built: binaries, protocols, systems. The same instinct that makes me want to know what's happening inside a model at inference time.

**Trekking** — Gets me off a screen. Andhra Pradesh has good terrain for it.

---

<p align="center">
  <sub>Final year. Still shipping. · <a href="https://revanthkumar-dev.vercel.app">revanthkumar-dev.vercel.app</a></sub>
</p>
