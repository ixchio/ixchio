# Aman Kumar Pandey

**Final year CS student. AI Engineer at Qubicsquare Technologies.**  
*Building production systems that serve 1200+ users daily.*

---

## Open Source

### OpenHands (65k ⭐) — 5 Merged PRs

| PR | What I Did | Impact |
|---|---|---|
| [#1614](https://github.com/OpenHands/software-agent-sdk/pull/1614) | Fixed race condition in `EventLog.append()`. File-based locking, patched **CVE-2025-68146**. 263 additions, 15 commits, 2-round maintainer review | Eliminated data corruption in concurrent multi-agent setups |
| [#1433](https://github.com/OpenHands/software-agent-sdk/pull/1433) | Built early stopping/pruner system for behavior tests — 6 pruner classes, 17 unit tests, integrated across 3 test suites. 15 commits | Cuts LLM cost per test run by terminating on first failure signal |
| [#1538](https://github.com/OpenHands/software-agent-sdk/pull/1538) | Improved tool matching on agent resume | Fixed broken agent state after session restore |
| [#1539](https://github.com/OpenHands/software-agent-sdk/pull/1539) | Added pause/resume to workspace classes | Full lifecycle control for long-running agent tasks |
| [#1564](https://github.com/OpenHands/software-agent-sdk/pull/1564) | DeepSeek v3.2 model support | Expanded model compatibility for the SDK |

### Astro (47k ⭐) — 1 Merged PR

**[#15017](https://github.com/withastro/astro/pull/15017)** — `fix(css): prevent CSS double-bundling`  
CSS imported in both a page's frontmatter and a component script tag was being bundled twice in production builds. Added content-based deduplication across the style pipeline. 121 additions across 9 files. Reviewed and merged by core team member **Princesseuh**. Shipped in **Astro v5.16.11**.

### multigres/multigres — "Vitess for Postgres" (1.9k ⭐) — 1 Merged PR

**[#353](https://github.com/multigres/multigres/pull/353)** — `fix: use safe port range for local cluster postgres instances`  
Postgres instances were binding to 5432–5434, colliding with local dev installations. Remapped backend to 25432–25434, fixed broken multigateway zone port assignments for zones 2 and 3. 10 commits, 7 files changed, 100% coverage on new lines. Reviewed and merged by **@rafael**.

---

## What I've Shipped

**[aum.sitrai.com](https://aum.sitrai.com) — Safe Agent Sandbox Runtime**  
Autonomous AI agents executing code in Docker sandboxes. 1000+ daily runs, 99.9% uptime. Multi-provider LLM fallback chain (OpenAI → Claude → Ollama). Self-correcting Reflexion Loop bumps task success from ~60% → **92%**. Cut costs $400/month, reduced failures 60%.

**[n0x-three.vercel.app](https://n0x-three.vercel.app) — The Full AI Stack. One Browser Tab. Zero Backend.**  
First fully in-browser autonomous agent. ReAct reasoning loop via WebGPU inference (MLC/WebLLM), tool use, RAG (transformers.js + voy-search), Python execution (Pyodide/WASM), persistent memory (IndexedDB). 16 quantized models hitting 35–50 tokens/sec on consumer hardware. Zero API keys. Zero data leaves your machine.

**[groq-coder.vercel.app](https://groq-coder.vercel.app) — AI Code Generation with Groq LPU**  
Natural language → React/HTML with real-time streaming, multi-stage validation, and instant live preview.

**[ixchio/agent-sandbox-runtime](https://github.com/ixchio/agent-sandbox-runtime) — Secure Execution Runtime for AI Agents** ⭐6  
Open-source Docker sandbox with hard resource caps (512MB RAM / 0.5 CPU / 5s timeout), LangGraph state with reflection history and checkpointing. Swarm of 4 specialized agents: Architect, Coder, Critic, Security.

**[ixchio/AutoPR-AI](https://github.com/ixchio/AutoPR-AI) — Autonomous PR Generation**  
Benchmarks Llama / Mistral / GPT to auto-generate production-ready PRs with human-like commit messages.

**[ixchio/go-resilient-commerce](https://github.com/ixchio/go-resilient-commerce) — Anti-Fragile Distributed Order Engine** ⭐1  
Financial-grade order processing in Go. Zero data loss guarantee, built for failure tolerance.

---

## Stack

**AI/ML:** Agent systems · LLM orchestration (GPT / Claude / Llama / DeepSeek) · LangChain · LangGraph · RAG · Vector DBs · Evaluation pipelines · Production LLMOps  
**Backend:** Python · FastAPI · Go · Node.js · PostgreSQL · Redis  
**Frontend:** React · TypeScript · Next.js · WebGPU / WASM  
**Infrastructure:** Docker · Kubernetes / EKS · AWS · CI/CD  
**Monitoring:** Prometheus · Grafana · Weights & Biases

---

## Work

**Qubicsquare Technologies** — Full Stack AI Engineer *(Nov 2024 – Present)*  
Data pipelines · ML infrastructure · Distributed systems

---

## What I'm Looking For

Graduating **May 2026**. Available for full-time.

**Target:** Founding engineer / AI engineer — 0→1, not legacy maintenance.

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-amanxxpandey-blue)](https://www.linkedin.com/in/amanxxpandey/)
[![Email](https://img.shields.io/badge/Email-amankumarpandeyin%40gmail.com-red)](mailto:amankumarpandeyin@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-nightowne-purple)](https://discord.com/users/nightowne)
