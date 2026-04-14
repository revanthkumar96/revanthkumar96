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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/revanth-kumar-sudikonda)
[![Medium](https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white)](https://medium.com/@sudikondarevanthkumar)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sudikondarevanthkumar@gmail.com)
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

## 💻 Tech Stack:
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Achievements

- 🏆 Top 10 — Sushacks'25 Hackathon
- 🏆 Top 10 — GDG GenAI Hackathon
- 📦 Published open-source SDK on PyPI
- 🔬 Undergraduate research on iterative RLHF / RAFT alignment

---

## 📊 GitHub Stats:

<div align="center">

![](https://github-readme-stats.shion.dev/api?username=revanthkumar96&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![](https://streak-stats.demolab.com/?user=revanthkumar96&theme=dark&hide_border=false)
![](https://github-readme-stats.shion.dev/api/top-langs/?username=revanthkumar96&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=revanthkumar96&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

</div>

---

## Outside work

**Cooking** — I genuinely enjoy cooking, not just eating. Experimenting with recipes, adjusting on the fly, getting the result right. Clear inputs, immediate feedback, no ambiguity about whether it worked — honestly, not that different from debugging.

**Reverse Engineering** — Taking things apart to understand how they were built. Binaries, protocols, systems. The same instinct that makes me want to know what's happening inside a model at inference time.

**Trekking** — Gets me off a screen. Andhra Pradesh has good terrain for it.

---

<div align="center">
<sub>Final year. Still shipping. · <a href="https://revanthkumar-dev.vercel.app">revanthkumar-dev.vercel.app</a></sub>
</div>
