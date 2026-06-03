<h1 align="center">Sudikonda Revanth Kumar</h1>

<p align="center">
  <strong>Applied AI Engineer</strong> · Building production AI systems — from RAG pipelines to autonomous agents.
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
  <code>1.5M+ records processed</code> · <code>50K+ docs in RAG</code> · <code>300+ concurrent users</code> · <code>Published to PyPI &amp; npm</code>
</p>

---

## What I do

I build AI systems for production — not toy demos or notebooks that stop at `print("Hello World")`.

The problems I care about are operational: **how do you keep an AI system honest about what it's doing, how do you make it recover from failure, and how do you know when it's quietly broken?** That lens shows up across everything I've shipped — an agentic orchestration system with enforced rollback, an observability SDK for LLM chains, a RAG pipeline serving 300+ concurrent users, and backend services processing millions of records.

Most of my work runs on real infrastructure, gets used by real users, and has metrics attached to it. The gap between a working demo and a working system is where most of the engineering actually lives.

---

## Featured Projects

### [NiRo.ai](https://github.com/revanthkumar96/rogue.ai-secops) — DevOps & Agentic Testing Platform

> A terminal-first AI platform for autonomous DevOps, built around a forward-deployed engineering philosophy.

- Centrally manages multi-provider LLM backends (Ollama, Gemini, OpenAI)
- Headless gRPC server for universal CLI / CI pipeline integration
- Autonomous agentic routing for complex DevOps workflows
- Web-fetch and documentation-parsing tools for real-time debugging

<sub>`TypeScript` · `Python` · `LangGraph` · `gRPC` · `Docker` · `Bun`</sub>

### [Rouge.AI SDK](https://pypi.org/project/rouge-ai-sdk) — LLM Observability (on PyPI)

> Instruments agentic workflows with OpenTelemetry — surfacing token usage, latency, and execution paths across 10+ providers with zero changes to existing agent logic.

- Zero-configuration tracing for LangGraph and AutoGen
- Tracks token usage across heterogeneous providers
- Surfaces critical-path latency in agentic hives

<sub>`Python` · `OpenTelemetry` · `Distributed Tracing`</sub>

### [Iterative RLHF: Multi-Model Alignment](https://github.com/revanthkumar96/Iterative-RLHF-for-RAG-Research-paper) — Undergraduate Research

> A RAFT alignment pipeline evaluating Qwen2.5-1.5B, Phi-2, and TinyLlama across RAG-QA, review generation, and summarization. Each policy samples 4 candidates per prompt, scored by a local LLM-as-Judge over 3 iterations.

- Multi-model evaluation across 3 task types and 3 datasets
- Resolved LoRA adapter double-stacking and pad-token label leakage bugs
- Built real-time reward tracking and full JSON logging per iteration

<sub>`PyTorch` · `LoRA` · `RAFT` · `Hugging Face` · `Qwen2.5`</sub>

---

## Open Source

| Repository | Contribution | Why it mattered |
|---|---|---|
| [browser-use](https://github.com/browser-use/browser-use) | CDP navigation timeout control | Agents were silently hanging on slow pages — no timeout, no error, no recovery. Now agents can configure how long to wait before failing explicitly. |
| [runtm.ai](https://github.com/runtm-ai/runtm) | Fixed lint failures, unblocked CI | GitHub Actions was broken for all contributors. Fixed root lint issues so the pipeline could run cleanly. |

---

## Experience

**Applied AI Engineer — [Quantum Gandiva AI](https://www.quantumgandivaai.com/)** · *Present · Visakhapatnam, India*
Building the autonomy stack — core intelligent systems engineered for reliability, observability, and long-horizon reasoning.
- Develop primitives across the autonomy stack: orchestration, planning & task graphs, memory fabric, and tool/environment connectors
- Build observability and evaluation harnesses so agent behavior is measurable and changes are gated before promotion
- Work in an evaluation-first culture focused on scientific rigor, reproducibility, and safe autonomous systems

**Freelance AI Systems Engineer** — *Apr 2025 – Present*
Full-stack AI applications for global clients, with full ownership from scoping through delivery.
- Shipped AI apps for summarization and transcription using Python, FastAPI, Whisper, and Groq (LLaMA); integrated multi-provider LLM backends
- Built high-performance RAG pipelines with vector databases and evaluation monitoring for reliability
- Scoped ambiguous problems independently and shipped fast iterations on user feedback

**AI Engineer Intern — [Mindcres Technologies](https://mindcres.com/)** · *Dec 2025 – Mar 2026 · Series A*
Architected and optimized backend services for high-volume NLP and computer-vision data streams.
- Designed services processing 1.5M+ records; integrated PostgreSQL, MongoDB, and REST APIs handling 10K+ requests/day
- Reduced API latency 30% via query optimization and multi-layer caching
- Improved reliability with circuit breakers and retry logic across production services

**Summer Intern — [Bharat Dynamics Limited](https://bdl-india.in)** · *Jun – Aug 2025*
Mission-critical data infrastructure for aerospace datasets, with semantic search over 50K+ documents.
- Built a domain-specific RAG pipeline over 50K+ scraped and structured aerospace documents
- Deployed fault-tolerant Linux services supporting 300+ concurrent users with observability dashboards
- Built structured logging and tracing to identify bottlenecks in LLM inference paths

**Project Intern — CalmMe AI** · *Feb – Mar 2025*
An AI mental-health companion providing empathetic support for stress and anxiety.
- Integrated LLaMA-3 via GroqCloud for fast, emotionally intelligent conversation
- Designed a calm, clarity-focused UI/UX for users in mental overload
- Optimized inference speed for real-time empathetic interactions

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
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Backend & Frameworks**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FE4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Data**
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405e?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase&logoColor=white)

**Infra & Tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)

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
