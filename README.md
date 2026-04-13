# Sudikonda Revanth Kumar

```
  ██████╗ ███████╗██╗   ██╗ █████╗ ███╗   ██╗████████╗██╗  ██╗
  ██╔══██╗██╔════╝██║   ██║██╔══██╗████╗  ██║╚══██╔══╝██║  ██║
  ██████╔╝█████╗  ██║   ██║███████║██╔██╗ ██║   ██║   ███████║
  ██╔══██╗██╔══╝  ╚██╗ ██╔╝██╔══██║██║╚██╗██║   ██║   ██╔══██║
  ██║  ██║███████╗ ╚████╔╝ ██║  ██║██║ ╚████║   ██║   ██║  ██║
  ╚═╝  ╚═╝╚══════╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝
```

---

## **[→ revanthkumar-dev.vercel.app](https://revanthkumar-dev.vercel.app)**

> **Applied AI Engineer · Building production AI systems from RAG pipelines to autonomous agents.**
> Final-year B.Tech CSE (AI) · Vignan's Institute of Information Technology · Andhra Pradesh, India

[![Portfolio](https://img.shields.io/badge/Portfolio-revanthkumar--dev.vercel.app-000000?style=flat&logo=vercel&logoColor=white)](https://revanthkumar-dev.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-revanth--kumar--sudikonda-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/revanth-kumar-sudikonda)
[![Email](https://img.shields.io/badge/Email-sudikondarevanthkumar@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sudikondarevanthkumar@gmail.com)
[![PyPI](https://img.shields.io/badge/PyPI-rouge.ai--sdk-3775A9?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/rouge-ai-sdk)
[![Profile Views](https://komarev.com/ghpvc/?username=revanthkumar96&label=Profile+Views&color=0e75b6&style=flat)](https://github.com/revanthkumar96)

---

**1.5M+ records processed · 50K+ docs in RAG · 300+ concurrent users · Published to PyPI & npm**

---

## What I actually do

I build AI systems for production — not toy demos, not notebooks with `print("Hello World")`.

The problems I care about are operational: **how do you keep an AI system honest about what it's doing, how do you make it recover from failure, and how do you know when it's quietly broken?** That lens shows up across everything I've shipped — an agentic orchestration system with enforced rollback, an observability SDK for LLM chains, a RAG pipeline serving 300+ concurrent users, and backend services processing millions of records.

Most of my work runs on real infrastructure, gets used by real users, and has metrics attached to it. I believe the gap between a working demo and a working system is where most of the engineering actually lives.

---

## Projects

### [NiRo.ai](https://github.com/revanthkumar96/niro.ai) — DevOps & Agentic Testing Platform
`TypeScript` `Python` `LangGraph` `gRPC` `Docker` `Bun`

A terminal-first AI platform for autonomous DevOps — built as the cornerstone of a forward-deployed engineering philosophy.

- Centrally manages multi-provider LLM backends (Ollama, Gemini, OpenAI)
- Headless gRPC server for universal CLI/CI pipeline integration
- Autonomous agentic routing for complex DevOps workflows
- Web-fetch and documentation-parsing tools for real-time debugging

---

### [Rouge.AI SDK](https://pypi.org/project/rouge-ai-sdk) — LLM Observability on PyPI
`Python` `OpenTelemetry` `Distributed Tracing`

Published to PyPI. Instruments agentic workflows using OpenTelemetry — surfacing token usage, latency, and execution paths across 10+ providers with zero changes to existing agent logic.

- Zero-configuration tracing for LangGraph and Autogen
- Tracks token usage across heterogeneous providers
- Surfaces critical path latency in agentic hives

---

### [Iterative RLHF: Multi-Model Alignment](https://github.com/revanthkumar96/Iterative-RLHF-for-RAG-Research-paper) — Undergraduate Research
`PyTorch` `LoRA` `RAFT` `Hugging Face` `Qwen2.5`

Research pipeline for RAFT alignment evaluating Qwen2.5-1.5B, Phi-2, and TinyLlama across RAG-QA, review generation, and summarization. Each policy samples 4 candidates per prompt, scored by a local LLM-as-Judge over 3 iterations.

- Multi-model evaluation across 3 task types and 3 datasets
- Resolved LoRA adapter double-stacking and pad-token label leakage bugs
- Built real-time reward tracking and full JSON logging per iteration

---

### Open Source Contributions

| Repo | Contribution | Why it mattered |
|---|---|---|
| [browser-use](https://github.com/browser-use/browser-use) | Added CDP navigation timeout control | Agents were silently hanging on slow pages — no timeout, no error, no recovery. This gives agents configurable control over how long to wait before failing explicitly. |
| [runtm.ai](https://github.com/runtm-ai/runtm) | Fixed lint failures, unblocked GitHub Actions | CI was broken for all contributors. Fixed root lint issues so the pipeline could run cleanly. |

---

## Experience

**Freelance AI Systems Engineer** · *Apr 2025 – Present*

Building and shipping full-stack AI-powered applications for global clients across time zones. Full ownership from scoping through delivery.

- Built and shipped AI apps for summarization and transcription using Python, FastAPI, Whisper, and Groq (LLaMA); integrated multi-provider LLM backends
- Developed high-performance RAG pipelines with vector databases for contextual retrieval; implemented evaluation monitoring for system reliability
- Scoped ambiguous problems independently and shipped fast iterations based on user feedback

**AI Engineer Intern @ [Mindcres Technologies](https://mindcres.com)** · *Dec 2025 – Mar 2026 · Series A Startup*

Architected and optimized backend services for high-volume NLP and computer vision data streams in a fast-paced startup environment.

- Designed and maintained backend services processing 1.5M+ records; integrated PostgreSQL, MongoDB, and RESTful APIs handling 10K+ requests/day
- Reduced API latency by 30% through advanced query optimization and multi-layer caching
- Improved reliability via circuit breakers and retry logic across production services

**Summer Intern @ [Bharat Dynamics Limited](https://bdl-india.in)** · *Jun – Aug 2025*

Developed mission-critical data infrastructure for aerospace datasets, delivering semantic search over 50K+ documents.

- Scraped, cleaned, and structured aerospace datasets; built a domain-specific RAG pipeline enabling semantic search over 50K+ documents
- Deployed fault-tolerant services on Linux supporting 300+ concurrent users; monitored output quality through observability dashboards
- Built structured logging and tracing systems to identify bottlenecks in LLM inference paths

**Project Intern — CalmMe AI** · *Feb – Mar 2025*

Developed CalmMe — an AI mental health companion providing empathetic support for stress and anxiety.

- Integrated LLaMA-3 via GroqCloud for fast, emotionally intelligent conversational AI
- Designed a soothing UI/UX focused on clarity and calmness for users in mental overload
- Optimized model inference speed for real-time empathetic interactions

**Web Developer @ MLSC VIIT** · *Nov 2025 – Present · Volunteer*

Building and maintaining the official Microsoft Learn Student Community website.

- Built and deployed the official MLSC VIIT website showcasing club activities and resources
- Organized and led sessions on Azure cloud to enhance members' technical skills
- Mentored teams during Sushacks 3.0, fostering innovation and teamwork

---

## Research

### Iterative RLHF: Multi-Dataset × Multi-Model RAFT Alignment Pipeline
*Undergraduate Research · Vignan's Institute of Information Technology · 2025 – Present*

**What this is:** A systematic experiment asking whether iterative RLHF (via RAFT) produces consistent alignment gains across model sizes and task types — or whether the improvements are model-specific, dataset-specific, or both.

**Setup:**
- **Policy models:** Qwen2.5-1.5B-Instruct, Phi-2 (2.7B), TinyLlama-1.1B
- **Datasets:** WebGLM (RAG-QA), Yelp (review generation), XSum (summarization)
- **Method:** Each policy samples 4 candidates per prompt; a local reward model scores them; the top candidate drives LoRA fine-tuning over 3 iterations

**What made this hard:** Debugging iterative fine-tuning pipelines on constrained compute (Kaggle). Resolved 8 engineering bugs including LoRA adapter double-stacking and pad-token label leakage. Built per-iteration reward tracking, loss logging, and JSON output for full reproducibility.

This is the kind of work where half the research is just making sure the pipeline is actually doing what you think it's doing.

---

## Stack

```
Languages    Python · TypeScript · JavaScript · SQL
Backend      FastAPI · RESTful APIs · PostgreSQL · ETL Pipelines
AI / ML      PyTorch · Hugging Face · LangChain · LangGraph · RAG · Vector DBs · LoRA fine-tuning
DevOps       Docker · GitHub Actions · OpenTelemetry · Linux
Platforms    Claude API · OpenAI · Groq · AWS Bedrock · ClickHouse · MongoDB
```

---

## Achievements

- 🏆 Top 10 — Sushacks'25 Hackathon
- 🏆 Top 10 — GDG GenAI Hackathon
- 📦 Published open-source SDK on PyPI
- 🔬 Undergraduate research on iterative RLHF / RAFT alignment

---

## GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=revanthkumar96&show_icons=true&theme=transparent&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&bg_color=00000000)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=revanthkumar96&layout=compact&theme=transparent&hide_border=true&title_color=58a6ff&text_color=c9d1d9&bg_color=00000000)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=revanthkumar96&theme=transparent&hide_border=true&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff)

</div>

## Outside work

**Cooking** — I genuinely enjoy cooking, not just eating. Experimenting with recipes, adjusting on the fly, getting the result right. Clear inputs, immediate feedback, no ambiguity about whether it worked — honestly, not that different from debugging.

**Reverse Engineering** — Taking things apart to understand how they were built. Binaries, protocols, systems. The same instinct that makes me want to know what's happening inside a model at inference time.

**Trekking** — Gets me off a screen. Andhra Pradesh has good terrain for it.

---

<div align="center">
<sub>Final year. Still shipping. · <a href="https://revanthkumar-dev.vercel.app">revanthkumar-dev.vercel.app</a></sub>
</div>
