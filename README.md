# Amariah Abishai
**AI Engineer · Full Stack Architect · Founder @ NorahLabs**

Building production AI systems from Nairobi, Kenya. Coding-agent harnesses, agentic orchestration, and native desktop applications — designed for developers who want serious AI tooling that runs on open-weight and local models, without cloud lock-in.

---

## Flagship: Atlarix

> **The Open-Weight Frontier Harness** — the agent workstation built for open-weight frontier labs, where a weaker local model performs like it knows your codebase.

macOS / Linux / Windows · [atlarix.dev](https://atlarix.dev)

Atlarix is built *for* the open-weight frontier labs — **DeepSeek, Qwen, Kimi, MiniMax** — not just compatible with them. The bet: durable open-weight labs, not specific model versions. What makes a weaker model punch above its weight isn't a bigger prompt — it's the **harness**. Enforced tool approvals, an OS-level execution sandbox, and verified edits mean the model's mistakes are caught by the system, not trusted on faith. Any-model BYOK, local-first execution, every destructive action behind your approval.

**What makes it different:**
- **Built for open-weight, not retrofitted** — DeepSeek / Qwen / Kimi / MiniMax as first-class, plus broad BYOK (OpenAI, Anthropic, Gemini, OpenRouter, Groq, Together, Mistral, xAI, Hugging Face) and local Ollama / LM Studio.
- **Harness-managed agent control** — tool approvals, background commands, waits, and sub-agents are enforced by the harness, not the prompt, so a weaker model can't emit a premature completion or mismanage a wait.
- **Verified edits** — in Build / Debug the agent runs the project's *own* checks (`tsc`/`eslint`/`ruff`/`mypy`/`pytest`) through a sandboxed terminal and can't declare a task done while they fail.
- **OS-level execution sandbox** — per-OS write-confining command execution (Linux Landlock, Windows AppContainer, macOS Seatbelt), an approval queue with hunk-level diff accept/reject, a danger gate, and committable permission + hook rules at a single execution funnel.
- **Fast search, no index** — bundled-ripgrep `grep` and `glob` over your workspace: no index to build, no background watcher, constant low memory at any repo size.
- **Atlarix Core** — managed open-weight models with a pay-as-you-go credit wallet; no API key required, full BYOK / local on the free tier.
- **Parallel sub-agents** — the `task` tool fans out up to five concurrent read-only scouts per turn, live thinking streamed per agent.
- **Token-efficient by design** — on-demand tool-driven retrieval and model-triggered `compress_context`; provider-native tool blocks and prompt caching lift weak / local model performance.
- **Real workspace** — interactive PTY terminal (persists across restarts), in-app browser, `@` file/folder mentions scoped to the current workspace, per-workspace MCP.

**Work modes:** Explore (read-only) · Plan · Build · Debug · Review (correctness + security)

**As an open-source contributor,** I've landed quality work into major repos using Atlarix on open-weight models — including **Qwen Code** and **Kilo Code**, a directly competing coding agent.

**Achievements:** Winner — Amazon Nova AI Hackathon (Devpost × AWS, 2026) · GDG Nairobi Agentathon (2026) · Lua × Antler (Nairobi, 2026) · Red Bull Basement Global Innovation Programme

---

## Research

**Blueprint: Section-Scoped Structural Graph Retrieval and Post-Turn Compression for Agentic LLM Coding in Multi-Repository Workspaces**
Amariah Kamau, NorahLabs — 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)

Documents the Blueprint architecture — a section-scoped structural index (Universal Ctags symbol graph + ast-grep edges + SQLite FTS5) that handed the agent structural understanding in ~6,500 tokens instead of a whole-repo dump — alongside post-turn tool-result summarisation and benchmark results from a controlled A/B evaluation on a production multi-repository workspace, including a counterintuitive finding: structural confidence lets the agent explore *more*, using more total context but producing stronger results.

---

## Open Source

**[atlarix-skills](https://github.com/AmariahAK/atlarix-skills)** — Community Agent Behaviors registry. SKILL.md files teaching agents language patterns and framework conventions across React, Next.js, Python, TypeScript, Go, Rust, Docker, MCP, and more. Apache 2.0.

**[atlarix-mcps](https://github.com/AmariahAK/atlarix-mcps)** — MCP server registry for Atlarix. One-click connections to Gmail, Calendar, Drive, and more from within the agent environment. Apache 2.0.

**[atlarix-releases](https://github.com/AmariahAK/atlarix-releases)** — Desktop app release builds for macOS, Linux, and Windows.

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript · Python · JavaScript · SQL · Bash |
| **AI / ML** | Agentic Systems · Coding-Agent Harness Design · Multi-Agent Orchestration · Lexical Retrieval (ripgrep / BM25 / FTS5) · Context Compression · MCP · Hugging Face |
| **Open-Weight Labs** | DeepSeek · Qwen · Kimi · MiniMax |
| **Desktop** | Electron · React · React Flow · SQLite |
| **Backend** | Node.js · Django DRF · FastAPI · PostgreSQL · Redis · Celery |
| **Infrastructure** | AWS · GCP · Docker · GitHub Actions · Supabase · Vercel |
| **Auth & Billing** | Auth0 · Token Vault · LemonSqueezy |
| **Monitoring** | Sentry · PostHog · Prometheus · Grafana |

---

## Other Projects

**[Praxia](https://github.com/AmariahAK/Praxia_Backend)** — AI healthcare assistant with MONAI X-ray analysis (pneumonia, fractures, tumours), multilingual symptom diagnosis, real-time WebSocket chat, and a Docker/Nginx/Celery production stack.

**[Commit Checker](https://github.com/AmariahAK/commit-checker)** — Open source CLI for Git commit analysis.

---

## Stats

![](https://github-readme-stats.vercel.app/api?username=AmariahAK&theme=midnight-purple&hide_border=true&include_all_commits=true&count_private=true)
![](https://nirzak-streak-stats.vercel.app/?user=AmariahAK&theme=midnight-purple&hide_border=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=AmariahAK&theme=midnight-purple&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/amariah-kamau-3156412a6/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:amariah.abish@gmail.com)
[![Atlarix](https://img.shields.io/badge/Atlarix-2563EB?style=flat&logoColor=white)](https://atlarix.dev)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak)
</file_text>
