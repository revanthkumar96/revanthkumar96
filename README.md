# Sudikonda Revanth Kumar

```
  ██████╗ ███████╗██╗   ██╗ █████╗ ███╗   ██╗████████╗██╗  ██╗
  ██╔══██╗██╔════╝██║   ██║██╔══██╗████╗  ██║╚══██╔══╝██║  ██║
  ██████╔╝█████╗  ██║   ██║███████║██╔██╗ ██║   ██║   ███████║
  ██╔══██╗██╔══╝  ╚██╗ ██╔╝██╔══██║██║╚██╗██║   ██║   ██╔══██║
  ██║  ██║███████╗ ╚████╔╝ ██║  ██║██║ ╚████║   ██║   ██║  ██║
  ╚═╝  ╚═╝╚══════╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-revanth--kumar--sudikonda-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/revanth-kumar-sudikonda)
[![Email](https://img.shields.io/badge/Email-sudikondarevanthkumar@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sudikondarevanthkumar@gmail.com)
[![PyPI](https://img.shields.io/badge/PyPI-rouge.ai--sdk-3775A9?style=flat&logo=pypi&logoColor=white)](https://pypi.org/project/rouge-ai-sdk)
[![Profile Views](https://komarev.com/ghpvc/?username=revanthkumar96&label=Profile+Views&color=0e75b6&style=flat)](https://github.com/revanthkumar96)

---

## What I actually do

I'm a second-year B.Tech CSE (AI specialization) student at Vignan's, and I build AI systems for production — not toy demos, not notebooks with `print("Hello World")`.

The problems I care about are operational: **how do you keep an AI system honest about what it's doing, how do you make it recover from failure, and how do you know when it's quietly broken?** That lens shows up across everything I've shipped — an agentic orchestration system with enforced rollback, an observability SDK for LLM chains, a RAG pipeline serving 300+ concurrent users, backend services processing millions of records.

Most of my work runs on real infrastructure, gets used by real users, and has metrics attached to it. I believe the gap between a working demo and a working system is where most of the engineering actually lives.

---

## Projects

### [ROUGE](https://github.com/revanthkumar96/rouge) — 10-Agent CI/CD Orchestration System
`Python` `TypeScript` `LangGraph` `Docker` `Kubernetes` `OpenTelemetry` `SQLite`

**The problem:** AI agents running CI/CD pipelines fail in ways that are hard to catch — they execute unsafe bash, don't roll back, and leave no trace of what went wrong.

**What I built:** A 10-agent LangGraph system covering the full DevOps loop: test generation, deployment, monitoring, and rollback. Every agent enforces safety checks before execution. Every step is logged with structured JSON. Bad outputs get rejected before they reach production.

- **−40%** test generation time
- **−50%** debugging time
- Webhook-driven, JSON-validated, with bash safety parsing at the boundary

This isn't a demo of LangGraph — it's a system built around the assumption that agents will produce bad output and need guardrails by default.

---

### [Rouge.AI SDK](https://pypi.org/project/rouge-ai-sdk) — LLM Observability on PyPI
`Python` `OpenTelemetry` `Distributed Tracing`

**The problem:** Once you chain multiple LLM calls together, you lose visibility — which model ran, what it returned, where latency came from, which step in the chain failed.

**What I built:** An OpenTelemetry-based SDK that instruments agentic workflows without touching the agent logic itself. It surfaces execution paths, token usage, and per-step latency across 10+ AI providers. Drop-in integration — no refactoring required.

Published to PyPI. Built because I kept running into this problem in my own projects before any good tooling existed.

---

### Open Source Contributions

| Repo | Contribution | Why it mattered |
|---|---|---|
| [browser-use](https://github.com/browser-use/browser-use) | Added CDP navigation timeout control | Browser automation agents were silently hanging on slow pages — no timeout, no error, no recovery. This gives agents configurable control over how long to wait before failing explicitly. |
| [runtm.ai](https://github.com/runtm-ai/runtm) | Fixed lint failures, unblocked GitHub Actions | CI was broken for all contributors. Fixed the root lint issues so the pipeline could run cleanly. |

---

## Experience

**Freelance AI Systems Engineer** · *Apr 2025 – Present*

Client work across time zones: full-stack AI apps for summarization, transcription, and RAG. Also built enterprise automation on Microsoft Graph APIs and Intune — not glamorous, but high-stakes and used in production. Async-first delivery across every engagement.

**AI & Backend Engineer Intern @ [Mindcres Technologies](https://mindcres.com)** · *Dec 2025 – Mar 2026*

Backend services at non-trivial scale — 1.5M+ records across NLP and CV pipelines, 10K+ req/day. Cut API latency by 30% through query optimization and caching. Added circuit breakers and retry logic to make services resilient rather than just fast.

**AI Engineering Intern @ [Bharat Dynamics Limited](https://bdl-india.in)** · *Jun – Aug 2025*

Built a domain-specific RAG pipeline over 50K+ MOSDAC aerospace documents — scraped, cleaned, structured, and layered with semantic search. Deployed on Linux, fault-tolerant, supporting 300+ concurrent users. Built the observability stack too, because running it blind wasn't an option.

---

## Research

### Iterative RLHF: Multi-Dataset × Multi-Model RAFT Alignment Pipeline
*Undergraduate Research · Vignan's Institute of Information Technology · 2025 – Present*

**What this is:** A systematic experiment asking whether iterative RLHF (via RAFT) produces consistent alignment gains across model sizes and task types — or whether the improvements are model-specific, dataset-specific, or both.

**Setup:**
- **Policy models:** Qwen2.5-1.5B-Instruct, Phi-2 (2.7B), TinyLlama-1.1B
- **Datasets:** WebGLM (RAG-QA), Yelp (review generation), XSum (summarization)
- **Method:** Each policy samples 4 candidates per prompt; a local reward model scores them; the top candidate drives LoRA fine-tuning over 3 iterations

**What made this hard:** Debugging iterative fine-tuning pipelines on constrained compute (Kaggle). Resolved 8 engineering bugs including LoRA adapter double-stacking (LoRA being applied on top of itself across iterations due to improper adapter unwrapping) and pad-token label leakage (padding tokens being counted in the loss). Built per-iteration reward tracking, loss logging, and JSON output for full reproducibility.

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
<sub>Second year. Still shipping. Andhra Pradesh, India.</sub>
</div>
