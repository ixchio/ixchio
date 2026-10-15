# Aman

AI engineer building **retrieval systems, agent runtimes, browser software, and local-first tools**.

I build infrastructure that goes beyond the demo — code search with verifiable evidence, recoverable agent execution, safe browser automation, and software that runs locally.

[X](https://x.com/ixchio) · [GitHub Sponsors](https://github.com/sponsors/ixchio)

## Published libraries

### [RAGBox Core](https://github.com/ixchio/ragbox-core)

Live codebase context for coding agents. An MCP server for Claude Code, Cursor, and other clients that combines **dense search + SQLite FTS5 + symbol-graph retrieval**, stays in sync with file changes, and returns exact `file:line-line` citations. Includes optional cross-encoder reranking, Python AST relationships, and a Python/HTTP query API.

[![RAGBox Core downloads](https://static.pepy.tech/personalized-badge/ragbox-core?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/ragbox-core) · [PyPI](https://pypi.org/project/ragbox-core/) · [Benchmarks](https://github.com/ixchio/ragbox-core/blob/main/BENCHMARKS.md)

### [Agent VCR](https://github.com/ixchio/agent-vcr)

The undo and replay layer for AI agents. Records execution, supports time-travel debugging and **ACID filesystem + state rollback**, reuses verified work through Ghost Replay, and gates agent regressions in CI. Also includes durable workflows, SuperAgent policies, and reliability intelligence.

[![Agent VCR downloads](https://static.pepy.tech/personalized-badge/ai-agent-vcr?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/ai-agent-vcr) · [PyPI](https://pypi.org/project/ai-agent-vcr/) · [Docs](https://ixchio.github.io/agent-vcr/)

## Selected work

- **[terx](https://github.com/ixchio/terx)** — local, policy-gated replay memory for browser agents over raw Chrome DevTools Protocol. Reuses approved semantic workflows without another model call on a valid cache hit; refuses ambiguous or unsafe replays.
- **[Virgin Browser](https://github.com/ixchio/virgin)** — Linux-first browser shell in C++20 + Qt 6. Chromium renders pages while Virgin handles profiles, permissions, navigation policy, blocking, history, and local sessions.
- **[n0x](https://github.com/ixchio/n0x)** — browser-based AI workbench with WebGPU inference, WASM, hybrid document retrieval, agent tools, and local persistence.
- **[TAS](https://github.com/ixchio/tas)** — encrypted local-first file transport over Telegram with FUSE mounts, resumable sync, local SQLite indexing, and recovery manifests.
- **[Agent Sandbox Runtime](https://github.com/ixchio/agent-sandbox-runtime)** — controlled execution and isolation for AI agent workloads.

## Open source

I contribute fixes upstream when I hit problems in the systems I use.

- **[OpenHands software-agent-sdk](https://github.com/OpenHands/software-agent-sdk)** — async hooks, workspace pause/resume, locking, model support, and behavior tests
- **[Astro](https://github.com/withastro/astro)** — CSS double-bundling and O(n²) memory-allocation fixes
- **[Motus](https://github.com/lithos-ai/motus)** — tool JSON handling, Anthropic/Gemini support, and image passthrough
- **[Superglue](https://github.com/superglue-ai/superglue)** — SSRF prevention
- **[mem0](https://github.com/mem0ai/mem0)** — async memory creation fix

## Stack

Python · TypeScript · C/C++ · Linux · FastAPI · Node.js · React · PostgreSQL · Redis · Docker · WebGPU · WASM · Chrome DevTools Protocol · LLM systems
