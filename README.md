# Amariah Kamau
**AI Engineer · Full Stack Architect · Founder @ NorahLabs**

I build production AI systems — agentic orchestration engines, RAG pipelines, and native desktop applications. Based in Nairobi, Kenya. Currently focused on making serious AI tooling accessible to developers who don't want cloud lock-in or privacy trade-offs.

`AWS Certified Data Engineer` · `Google Cloud Professional Data Engineer` · `AWS Certified Developer`

---

## Flagship: Atlarix

> A native desktop AI coding environment for developers who want real architectural understanding — not just autocomplete.

**v8.2.0** · Mac + Linux · [atlarix.dev](https://atlarix.dev)

Atlarix parses your codebase into a live Blueprint graph via Round-Trip Engineering using **oxc-parser** (Rust, ~2× faster than SWC) for TypeScript/JS and **WASM tree-sitter** for Python, Go, and Rust — then uses that graph as RAG for every AI query, reducing token usage from ~100K to ~5K per query.

**v8.2.x highlights:**
- `oxc-parser` for TS/JS/JSX/TSX — Rust-based, 256KB per-file cap, cooperative yield every 10 files
- `WASM tree-sitter` — Python, Go, Rust via `web-tree-sitter` + `tree-sitter-wasms`, packaged via `extraResources`
- Parser worker pool — 2–4 dedicated workers with timeout and crash recovery
- `get_repo_overview` — lightweight cold-session orientation without full Blueprint parse
- Secret path denylist — `.env*`, `*.pem`, `*.key`, service account files blocked from all read paths

**v8.1.x highlights:**
- Blueprint restored lazy — graph schema, IPC, click-to-load canvas (500-node cap)
- Tool consolidation 60+ → 28 — unified `search` (auto/text/semantic/structural), `edit_file`, on-demand MCP (`list_available_mcps` + `mcp_call`), Skills via ToolRegistry
- `compress_context` — model-triggered, not pre-dispatch; removes latency from every standard turn
- `get_workspace_overview` + `read_attachment_summary` macro tools
- Streaming guarantee — every exit path emits `chat:response:end` exactly once
- ~50% token reduction per turn — 6 pre-dispatch injections converted to tool-driven retrieval (verified via OpenRouter logs)

**v7.x foundations:**
- Parallel agents: Research · Architect · Builder · Reviewer · Debugger · Explore
- DelegationMonitor — cyclic and runaway delegation detection with bus abort
- Compass managed tier — no API key required (Fast / Balanced / Thinking)
- Full CI/CD with Apple Notarisation + Linux packaging (.deb / .rpm / .AppImage)
- Three-tier subscription (Free / $0 · Pro / $19mo · Workforce / $79mo)
- ResearchLedger-driven deep research with BM25 relevance filtering

Multi-provider: OpenAI · Anthropic · Google Gemini · Groq · Mistral · xAI · OpenRouter · Together AI · Ollama · LM Studio

**Achievements:** Winner — Amazon Nova AI Hackathon (Devpost × AWS) · Red Bull Basement Global Innovation Programme · GDG Nairobi Agentathon (May 2026)

---

## Open Source

**[atlarix-skills](https://github.com/AmariahAK/atlarix-skills)** — Community skill registry for Atlarix. Skills teach agents language patterns, framework conventions, and developer workflows across React, Next.js, Python, TypeScript, Go, Rust, Docker, MCP, testing, and more. Apache 2.0.

**[atlarix-mcps](https://github.com/AmariahAK/atlarix-mcps)** — MCP marketplace index for Atlarix. One-click server connections from the in-app marketplace.

**[atlarix-releases](https://github.com/AmariahAK/atlarix-releases)** — Desktop app release builds for Mac and Linux.

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript · Python · JavaScript · SQL · Bash |
| **AI / ML** | Agentic Systems · RAG · Graph RAG · Multi-Agent Orchestration · Context Compression · LangChain · Hugging Face · oxc-parser · Tree-sitter (WASM) |
| **Desktop** | Electron · React · React Flow · SQLite |
| **Backend** | Node.js · Django DRF · FastAPI · PostgreSQL · Redis · Celery |
| **Infrastructure** | AWS · GCP · Docker · GitHub Actions · Supabase · Vercel |
| **Auth & Billing** | Auth0 · Token Vault · LemonSqueezy |
| **Monitoring** | Sentry · PostHog · Prometheus · Grafana |

---

## Other Projects

**[Praxia](https://github.com/AmariahAK/Praxia_Backend)** — AI healthcare assistant with MONAI X-ray analysis (pneumonia, fractures, tumours), multilingual symptom diagnosis, real-time WebSocket chat, and Docker/Nginx/Celery production stack.

**[Commit Checker](https://github.com/AmariahAK/commit-checker)** — Open source CLI tool for Git commit analysis.

---

## African AI

Atlarix is built in Nairobi. Most serious AI developer tooling assumes a Western cloud subscription. Atlarix is open-model by design — bring any provider, including locally-built African models. Currently piloting with African AI labs for native MansaLLM integration.

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
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak)
