# aman

ai engineer, hardcore into retrieval, agent runtimes, browsers and local first tools

i build code search that shows its proof, agents u can undo and replay, browser automation that wont wreck ur stuff, and software that runs on ur own machine

[x](https://x.com/ixchio) · [github sponsors](https://github.com/sponsors/ixchio) · [buy me a coffee](https://buymeacoffee.com/ixchio)

## on pypi

### [ragbox core](https://github.com/ixchio/ragbox-core)

mcp server that gives claude code, cursor and other agents live context of ur codebase. dense search plus sqlite fts5 plus symbol graph retrieval, syncs when files change, and every answer comes with exact file and line citations. optional cross encoder rerank, python ast relations and a python and http query api

[![ragbox core downloads](https://static.pepy.tech/personalized-badge/ragbox-core?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/ragbox-core) · [pypi](https://pypi.org/project/ragbox-core/) · [benchmarks](https://github.com/ixchio/ragbox-core/blob/main/BENCHMARKS.md)

### [agent vcr](https://github.com/ixchio/agent-vcr)

undo button and replay for ai agents. records every run, time travel debugging, acid filesystem and state rollback, ghost replay reuses work that was already verified, and it catches agent regressions in ci. also got durable workflows, superagent policies and reliability intel

[![agent vcr downloads](https://static.pepy.tech/personalized-badge/ai-agent-vcr?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/ai-agent-vcr) · [pypi](https://pypi.org/project/ai-agent-vcr/) · [docs](https://ixchio.github.io/agent-vcr/)

## other stuff i built

* **[terx](https://github.com/ixchio/terx)** replay memory for browser agents on raw chrome devtools protocol. runs local with policy gates, a valid cache hit means zero extra model calls, sketchy or ambiguous replays get refused
* **[virgin browser](https://github.com/ixchio/virgin)** linux first browser shell in c++20 and qt 6. chromium renders the pages, virgin handles profiles, permissions, navigation policy, blocking, history and local sessions
* **[n0x](https://github.com/ixchio/n0x)** full ai workbench inside the browser with webgpu inference, wasm, hybrid doc retrieval, agent tools and local persistence
* **[tas](https://github.com/ixchio/tas)** encrypted file transport over telegram with fuse mounts, resumable sync, local sqlite index and recovery manifests
* **[agent sandbox runtime](https://github.com/ixchio/agent-sandbox-runtime)** runs ai agent workloads in isolation with controlled execution

## open source

when something breaks on me i fix it upstream

* **[openhands software agent sdk](https://github.com/OpenHands/software-agent-sdk)** async hooks, workspace pause and resume, locking, model support, behavior tests
* **[astro](https://github.com/withastro/astro)** css double bundling fix and an o(n²) memory allocation fix
* **[motus](https://github.com/lithos-ai/motus)** tool json handling, anthropic and gemini support, image passthrough
* **[superglue](https://github.com/superglue-ai/superglue)** ssrf prevention
* **[mem0](https://github.com/mem0ai/mem0)** async memory creation fix

## stack

python · typescript · c and c++ · linux · fastapi · node · react · postgres · redis · docker · webgpu · wasm · chrome devtools protocol · llm systems

## support

if my stuff saved u time [buy me a coffee](https://buymeacoffee.com/ixchio)
