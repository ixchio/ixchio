# Aman Kumar Pandey

**Final year CS student. AI Engineer at Qubicsquare Technologies.**  
*Building production systems that serve 1200+ users daily.*

*I don't write code to pad my resume. I write it because someone's business depends on it working at 5AM.*

---

## Open Source

### OpenHands (65k ⭐) — 5 Merged PRs

| PR | What I Fixed / Built | Impact |
|---|---|---|
| [#1614](https://github.com/OpenHands/software-agent-sdk/pull/1614) | Fixed race condition in `EventLog.append()` via file-based locking. Patched CVE-2025-68146. 263 additions. 15 commits. Went through deep review with 2 maintainers. | Eliminated data corruption in concurrent multi-agent setups |
| [#1433](https://github.com/OpenHands/software-agent-sdk/pull/1433) | Built early stopping/pruner system for behavior tests — 6 pruner classes, 17 unit tests, integrated across 3 test suites. 15 commits, reviewed by core team leads. | Eliminated unnecessary LLM calls on failed test trajectories |
| [#1538](https://github.com/OpenHands/software-agent-sdk/pull/1538) | Improved tool matching on resume — agents now correctly re-bind tools after session restore | Fixed broken agent state on resume |
| [#1539](https://github.com/OpenHands/software-agent-sdk/pull/1539) | Added pause/resume to workspace classes | Full lifecycle control for long-running agent tasks |
| [#1564](https://github.com/OpenHands/software-agent-sdk/pull/1564) | DeepSeek v3.2 model support | Expanded model compatibility for the SDK |
---

## What I've Shipped

**[aum.sitrai.com](https://aum.sitrai.com) — Safe Agent Sandbox Runtime**  
Autonomous AI agents executing code in Docker sandboxes. 1000+ daily runs, 99.9% uptime. Multi-provider LLM fallback chain (OpenAI → Claude → Ollama). Self-correcting Reflexion Loop: 92% task success rate vs. ~60% for a raw LLM API. Cut costs $400/month, reduced failures 60%.

**[n0x-three.vercel.app](https://n0x-three.vercel.app) — The Full AI Stack. One Browser Tab. Zero Backend.**  
The first fully in-browser autonomous agent. ReAct-style reasoning loop powered by WebGPU inference via MLC WebLLM. Tool use, RAG, Python execution (Pyodide), web search, image gen — all local, all private, zero API keys needed.

**[groq-coder.vercel.app](https://groq-coder.vercel.app) — AI Code Generation with Groq LPU**  
Production AI code generation with real-time streaming and multi-stage validation. Natural language → React/HTML with instant live preview.

**[ixchio/agent-sandbox-runtime](https://github.com/ixchio/agent-sandbox-runtime) — Secure Execution for AI Agents** ⭐6  
Open-source Docker sandbox runtime. Ephemeral containers, hard resource caps (512MB RAM / 0.5 CPU), 5s timeouts, no network access. LangGraph-based state with checkpointing and reflection history.

**[ixchio/AutoPR-AI](https://github.com/ixchio/AutoPR-AI) — Autonomous PR Generation**  
Autonomous code refactoring agent. Evaluates and compares Llama/Mistral/GPT performance to generate production-ready PRs with human-like commit messages.

**[ixchio/go-resilient-commerce](https://github.com/ixchio/go-resilient-commerce) — Anti-Fragile Distributed Order Engine** ⭐1  
Financial-grade order processing in Go. Zero data loss guarantee, built for resilience under failure.

---

## Stack

**AI/ML:** Agent systems · LLM orchestration (GPT / Claude / Llama / DeepSeek) · LangChain · LangGraph · RAG · Vector DBs · Prompt engineering · Evaluation pipelines · Production LLMOps  
**Backend:** Python (expert) · FastAPI · Go · Node.js · PostgreSQL · Redis · Celery  
**Infrastructure:** Docker · Kubernetes / EKS · AWS (EC2, S3) · CI/CD  
**Frontend:** React · TypeScript · WebGPU / WebAssembly  
**Monitoring:** Prometheus · Grafana · Weights & Biases

---

## Work

**Qubicsquare Technologies** — Full Stack AI Engineer *(Nov 2024 – Present)*  
Data pipelines · ML infrastructure · Distributed systems

---

## What Makes Me Different

Most students build side projects. I build systems that handle real traffic, real money, real consequences.

- Shipped a security fix (CVE-2025-68146) to a 65k-star repo — found the race condition, designed the locking architecture, got it through two rounds of maintainer review
- Built the early-stopping system that saves OpenHands thousands of dollars in LLM costs per test run
- Run 1000+ autonomous agent executions daily without waking up to fire alarms
- Built a fully in-browser autonomous agent — no backend, no API keys, runs entirely on your GPU
- Zero Kubernetes knowledge → production EKS deployment in one week

Not because a bootcamp told me to. Because production systems don't care about your feelings.

---

## Looking For

Graduating **May 2026**. Available for full-time roles.

**Target:** Founding engineer / AI engineer roles — 0→1, not legacy maintenance.

**What I bring:** Production AI systems experience · Startup velocity · End-to-end ownership · Open source contributor mindset · Comfortable with ambiguity

**What I need:** High ownership · Low bureaucracy · Problems that matter
 Open to remote + relocation

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/amanxxpandey/)
[![Email](https://img.shields.io/badge/Email-Contact-red)](mailto:amankumarpandeyin@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-nightowne-purple)](https://discord.com/users/nightowne)
[![GitHub](https://img.shields.io/badge/GitHub-ixchio-black)](https://github.com/ixchio)

---

*Most students write projects. I ship production systems.*
