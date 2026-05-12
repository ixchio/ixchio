# Aman

I build tools I want to use.

Right now I'm building [**n0x**](https://github.com/ixchio/n0x) — the full AI stack running in one browser tab. LLM inference, agents, RAG, code execution, image gen. No backend, no API keys, no data leaving your machine. WebGPU + WASM, shipping today.

**Other things I've shipped:**

[**agent-vcr**](https://github.com/ixchio/agent-vcr) — time-travel debugging for AI agents. Record, replay, edit, resume from any point.

[**tas**](https://github.com/ixchio/tas) — Telegram as Storage. Free encrypted cloud storage using Telegram's infra. Mount it like a drive.

[**ragbox-core**](https://github.com/ixchio/ragbox-core) — zero-config RAG that builds itself. Drop files in, ask questions.

---

### Open-Source Contributions

**[OpenHands/software-agent-sdk](https://github.com/OpenHands/software-agent-sdk)** — 9 merged PRs
| PR | What |
|---|---|
| [#2688](https://github.com/OpenHands/software-agent-sdk/pull/2688) | feat: make `health_check_timeout` configurable on DockerWorkspace & ApptainerWorkspace |
| [#2383](https://github.com/OpenHands/software-agent-sdk/pull/2383) | fix: use `asyncio.Event()` for thread-safe initialization state |
| [#2251](https://github.com/OpenHands/software-agent-sdk/pull/2251) | fix: add `security_risk` and `summary` to tool examples for non-native function calling |
| [#1849](https://github.com/OpenHands/software-agent-sdk/pull/1849) | feat: add async hook execution support |
| [#1614](https://github.com/OpenHands/software-agent-sdk/pull/1614) | fix: add file-based locking to `EventLog.append()` |
| [#1564](https://github.com/OpenHands/software-agent-sdk/pull/1564) | feat: add DeepSeek v3.2 model support |
| [#1539](https://github.com/OpenHands/software-agent-sdk/pull/1539) | feat: add `pause()` and `resume()` methods to workspace classes |
| [#1538](https://github.com/OpenHands/software-agent-sdk/pull/1538) | feat: relax tool matching on resume |
| [#1433](https://github.com/OpenHands/software-agent-sdk/pull/1433) | feat: add early stopping/pruner for behavior tests cost optimization |

**[OpenHands/OpenHands-CLI](https://github.com/OpenHands/OpenHands-CLI)** — 1 merged, 2 open
| PR | What |
|---|---|
| [#581](https://github.com/OpenHands/OpenHands-CLI/pull/581) | ✅ tui: add tab navigation hint to footers |
| [#615](https://github.com/OpenHands/OpenHands-CLI/pull/615) | 🟡 feat: add Planning Mode support with `/plan` and `/code` commands |
| [#612](https://github.com/OpenHands/OpenHands-CLI/pull/612) | 🟡 fix: support AWS IAM credentials for Bedrock models without `LLM_API_KEY` |

**[withastro/astro](https://github.com/withastro/astro)** — 2 merged
| PR | What |
|---|---|
| [#15017](https://github.com/withastro/astro/pull/15017) | fix(css): prevent CSS double-bundling |
| [#14973](https://github.com/withastro/astro/pull/14973) | fix: prevent O(n²) memory allocation in content lookup map generation |

**[superglue-ai/superglue](https://github.com/superglue-ai/superglue)** — 1 merged, 1 open
| PR | What |
|---|---|
| [#679](https://github.com/superglue-ai/superglue/pull/679) | ✅ fix(security): prevent SSRF via incomplete URL validation and unvalidated webhook URLs |
| [#681](https://github.com/superglue-ai/superglue/pull/681) | 🟡 fix: prevent zombie Deno processes and add defensive `callAxios` return |

**[mem0ai/mem0](https://github.com/mem0ai/mem0)** — 1 merged
| PR | What |
|---|---|
| [#4886](https://github.com/mem0ai/mem0/pull/4886) | fix: add missing `text_lemmatized` in `AsyncMemory._create_memory` |

**[lithos-ai/motus](https://github.com/lithos-ai/motus)** — 1 merged, 1 open
| PR | What |
|---|---|
| [#31](https://github.com/lithos-ai/motus/pull/31) | ✅ fix: pass `base64_image` downstream in LLM clients |
| [#36](https://github.com/lithos-ai/motus/pull/36) | 🟡 fix: FunctionTool JSON crash, Anthropic tool-result image loss, Gemini empty-response crash |

**Other notable PRs:**
[google-gemini/gemini-cli#25643](https://github.com/google-gemini/gemini-cli/pull/25643) ·
[lmnr-ai/lmnr#1590](https://github.com/lmnr-ai/lmnr/pull/1590) ·
[multigres/multigres#353](https://github.com/multigres/multigres/pull/353) ✅ ·
[langchain-ai/langgraph#7588](https://github.com/langchain-ai/langgraph/pull/7588) ·
[mem0ai/memory-benchmarks#5](https://github.com/mem0ai/memory-benchmarks/pull/5) ·
[oven-sh/bun#25383](https://github.com/oven-sh/bun/pull/25383) ·
[SigNoz/signoz#9892](https://github.com/SigNoz/signoz/pull/9892)

> ✅ = merged · 🟡 = open

---

*infrastructure over hype...always shipping*
