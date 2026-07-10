---

# aman / @ixchio

self-taught builder working on AI agents, local inference, browser runtimes,
RAG systems, sandboxes, storage hacks, and developer infrastructure.

i build tools that feel obvious only after they exist.

```txt
status   OSS contributor | 18 merged PRs | 8 orgs
focus    AI agents | WebGPU inference | RAG | sandboxes | infra
stack    TypeScript | Python | Next.js | WASM | Docker | Postgres
style    build the hard part first
```

## shipped

### [n0x](https://github.com/ixchio/n0x)

local-first AI workstation in one browser tab: WebGPU inference, agents, RAG,
code execution, image generation, memory, search, and optional local/cloud
providers.

### [agent-vcr](https://github.com/ixchio/agent-vcr)

time-travel debugging for AI agents. record a run, replay it, edit state, and
resume from failure.

```bash
pip install ai-agent-vcr
```

### [tas](https://github.com/ixchio/tas)

telegram as storage. encrypted cloud storage you can mount like a drive.

### [ragbox-core](https://github.com/ixchio/ragbox-core)

zero-config RAG engine. drop files in, ask questions, get retrieval without
wiring the whole stack by hand.

## open source

| repo | merged | work |
|:--|:--:|:--|
| [OpenHands/software-agent-sdk](https://github.com/OpenHands/software-agent-sdk) | 9 | async hooks, workspace pause/resume, file locking, DeepSeek v3.2, cost-optimized behavior tests |
| [withastro/astro](https://github.com/withastro/astro) | 2 | CSS double-bundling fix, quadratic memory allocation fix |
| [lithos-ai/motus](https://github.com/lithos-ai/motus) | 2 | FunctionTool JSON crash fixes, Anthropic/Gemini fixes, base64 image passthrough |
| [langchain-ai/deepagentsjs](https://github.com/langchain-ai/deepagentsjs) | 1 | unknown MIME fallback to octet-stream |
| [superglue-ai/superglue](https://github.com/superglue-ai/superglue) | 1 | SSRF prevention via URL validation |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | 1 | async memory creation fix |
| [multigres/multigres](https://github.com/multigres/multigres) | 1 | safe local cluster port range |
| [OpenHands/OpenHands-CLI](https://github.com/OpenHands/OpenHands-CLI) | 1 | TUI tab navigation hint |

[![@ixchio Astro contributions](https://astro.badg.es/v2/contributor/ixchio.svg)](https://astro.badg.es/contributor/ixchio/)

## current direction

```txt
building small, sharp systems for:

- agents that can fail, recover, and resume
- local AI that does not need a cloud account
- browser-native tools that feel impossible until they run
- infra that removes setup instead of adding more
```

---

<div align="center">

```txt
building things that should already exist
```

</div>
