# Aman Kumar Pandey

Final year CS student who ships production code while everyone else is grinding LeetCode.

Currently running AI agents that serve 1000+ people daily. Not because it looks good on a resume—because someone's actual business runs on it.

---

## Real Talk

I started coding because I was bored. Stayed because I realized you can build things that actually matter.

Most of my college mates are doing DSA grind. I'm debugging why my LLM fallback chain costs $400/month and fixing it. Different priorities.

---

## Shit I've Built That Actually Works

### Safe Agent Sandbox Runtime → [aum.sitrai.com](https://aum.sitrai.com)

Ever let an AI agent run arbitrary code on your server? Yeah, bad idea. Built a proper Docker sandbox so agents can execute Python/Node without turning my server into a crypto mining rig.

- 1000+ daily agent runs (real users, real traffic)
- Multi-provider LLM setup: OpenAI → Claude → Ollama. Expensive model only when needed.
- Prometheus monitoring because I'm tired of things breaking at 3 AM
- Saved $400/month by being smart about API calls

The fun part? When the memory leaks started. Spent a weekend profiling containers, found the issue, fixed it. That's the job.

### Groq Coder → [groq-coder.vercel.app](https://groq-coder.vercel.app)

AI code generator built on Groq's LPU. Fast as hell, actually works.

Real-time streaming, multi-stage validation, live preview. Built it because I wanted to see if Groq could actually compete with OpenAI for code gen. Turns out it can.

### AutoPR-AI → [github.com/ixchio/autopr-ai](https://github.com/ixchio/autopr-ai)

Automated code refactoring agent. Analyzes your codebase, generates PRs, writes human-like commit messages.

Built an eval microservice to compare Llama vs Mistral vs GPT. Because guessing which model is better is expensive. Measuring it is smart.

### Go Anti-Fragile Commerce

Order processing engine in Go. Zero data loss guarantee through event sourcing and saga pattern.

When every dropped order costs real money, you learn to build resilient systems. Or you learn to find a new job.

Built this because I wanted to understand distributed systems properly. Reading about them in textbooks is one thing. Building one that can't lose orders is another.

---

## Open Source Contributions (The Ones That Mattered)

**OpenHands** (65k+ stars)  
Built parts of their eval infrastructure. Reduced eval costs by 35%, tripled throughput. When you're running hundreds of agent evaluations, every dollar and every second matters.

**LangChain** (100k+ stars)  
Multi-agent orchestration improvements. PR #31327. Made their agent chains actually composable instead of spaghetti code.

Not doing this for GitHub clout. Doing it because these tools have issues that annoy me, and I know how to fix them.

---

## How I Actually Learn

**Zero K8s knowledge → Production EKS in 7 days**  
Had to deploy a service. Didn't know Kubernetes. Read docs, broke things, fixed things, deployed. That's it.

**LLM Cost Optimization**  
Burned through $600 in a month on OpenAI API. Got pissed. Implemented caching, smarter prompts, provider fallback. Cut costs 70%. Learned more about LLMs in that week than in 6 months of tutorials.

**Race Conditions Are Fun**  
When 30 developers are watching you debug their "impossible" bug and it turns out to be a timing issue in async code, you either figure it out or look stupid. Figured it out.

---

## Stack (What I Actually Use)

**Languages**: Python (99% of my code), Go (when I need speed), JavaScript/Node (when I have to)

**AI/ML**: LLM orchestration, agent frameworks, prompt engineering (the real kind, not "please write better"), evaluation pipelines, cost optimization

**Backend**: FastAPI (fast to build, fast to run), PostgreSQL (it just works), Redis (for everything else), Celery (for background jobs)

**DevOps**: Docker (essential), Kubernetes (necessary evil), AWS (EC2, S3, Lambda), GitHub Actions (CI/CD)

**Monitoring**: Prometheus + Grafana (because dashboards that look good but don't help are useless)

---

## What Makes Me Different

I don't build projects to add lines to my resume. I build them because:
1. I'm solving a problem I have
2. I'm curious if something's possible
3. Someone needs it and I can build it

**What I've learned:**
- Production systems teach you more in one week than side projects teach in one year
- Optimizing costs is as important as adding features
- Good monitoring is the difference between fixing issues in 5 minutes vs 5 hours
- Open source contributions that actually help maintainers > 100 random PRs
- Shipping fast > shipping perfect (perfect doesn't exist anyway)

**Real examples:**
- Deployed production code while being the only person who could fix a critical bug. No pressure.
- Contributed to projects with 100k+ stars before they were hiring interns. Because the code was broken and I knew how to fix it.
- Run 1000+ agent executions daily without everything catching fire. That's called reliability engineering.

---

## What I'm Looking For

**Graduating May 2026. Available after.**

Looking for: **Founding Engineer / AI Engineer role**  
Type: 0→1 product building, not maintaining legacy Java from 2008

**What I bring:**
- I ship. Fast. And I own what I ship.
- Production AI systems experience (not Coursera certificates)
- Can go from idea → deployed system → monitored production in days
- Comfortable with ambiguity. Half the time we don't know what we're building until we build it.
- Open source mindset. I contribute back, I write docs, I help others.

**What I need:**
- High ownership (I build it, I run it, I fix it)
- Low bureaucracy (more building, less meetings about meetings)
- Smart people who care about solving real problems
- Team that ships products, not PowerPoints
  
---

## Contact

If you're building something real and need someone who actually ships:

📧 amankumarpandeyin@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/amanxxpandey/)  
💬 Discord: nightowne  
🎨 [CodePen](https://codepen.io/losercode)

---

## The Honest Part

I'm not the smartest engineer you'll ever meet. But I'm probably in the top 1% for "actually ships working production code."

I've shipped features with bugs. Fixed them fast. Learned from them.  
I've made systems that cost too much. Optimized them.  
I've written code at 2 AM that I had to refactor at 2 PM. That's life.

But everything I build either works in production or gets fixed until it does.

Most students build projects. I build systems that people depend on.

**That's the difference.**

---

*GitHub squares don't ship products. People do.*
