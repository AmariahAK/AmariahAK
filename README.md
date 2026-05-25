# Amariah Kamau
**AI Engineer · Full Stack Architect · Founder @ NorahLabs**

Building production AI systems from Nairobi, Kenya. Agentic orchestration engines, RAG pipelines, and native desktop applications — designed for developers who want real architectural understanding without cloud lock-in.

---

## Flagship: Atlarix

> A native desktop AI coding environment for developers working on non-trivial codebases.

**v8.7.5** · Mac + Linux · [atlarix.dev](https://atlarix.dev)

Atlarix builds a section-scoped Blueprint graph on demand using a four-layer index stack — **Universal Ctags** (symbol index), **ast-grep** (import/call/HTTP route edges), **BM25** (semantic symbol ranking), and **ripgrep** (text fallback) — delivering ~6,500 tokens of structural understanding for a 99-file TypeScript section in a 25-section multi-repository workspace.

**Published research:** [Blueprint: Section-Scoped Structural Graph Retrieval and Post-Turn Compression for Agentic LLM Coding in Multi-Repository Workspaces](https://zenodo.org/records/20381860) · Zenodo (CERN), May 2026
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)

**v8.7.x highlights:**
- Section-scoped `get_blueprint` — `focus_path` required; preflight path validation; richness-gated hybrid merge (ctags + ast-grep → hybrid when thin)
- Blast radius BFS over Blueprint flow edges before every write/edit approval
- Inline Mermaid diagrams generated on demand from codebase scan — no stale DB snapshot
- Post-turn tool-result summarisation — 95–98% per-read compression before history persistence

**v8.6.x highlights:**
- Universal Ctags + ast-grep Blueprint stack — replaced previous parser approach
- Route edges: Express/Fastify/Next.js HTTP handlers as first-class structural edges
- ast-grep worker pool with Python/Go dynamic grammar registration
- Incremental file-watcher refresh (500ms debounce) — per-file ctags + ast-grep, not full rebuild

**v8.x foundations:**
- ~50% pre-dispatch token reduction — 6 auto-injected blocks converted to tool-driven retrieval
- `compress_context` — model-triggered, not pre-dispatch
- Tool consolidation 60+ → 28 — unified `search` (auto/text/semantic-graph/structural), `edit_file`, on-demand MCP, Skills via ToolRegistry
- Skills Marketplace — community registry at [atlarix-skills](https://github.com/AmariahAK/atlarix-skills)

**v7.x foundations:**
- Parallel agents: Research · Architect · Builder · Reviewer · Debugger · Explore
- DelegationMonitor — cyclic and runaway delegation detection
- Compass managed tier — Fast / Balanced / Thinking, no API key required
- Full CI/CD: Apple Notarisation + Linux packaging (.deb / .rpm / .AppImage)
- Three-tier subscription: Free · Pro ($19/mo) · Workforce ($79/mo)

Multi-provider: OpenAI · Anthropic · Google Gemini · Groq · Mistral · xAI · OpenRouter · Together AI · Ollama · LM Studio

**Achievements:** Winner — Amazon Nova AI Hackathon (Devpost × AWS, 2026) · GDG Nairobi Agentathon (May 2026) · Lua x Antler (Nairobi, 2026) · Red Bull Basement Global Innovation Programme

---

## Research

**Blueprint: Section-Scoped Structural Graph Retrieval and Post-Turn Compression for Agentic LLM Coding in Multi-Repository Workspaces**
Amariah Kamau, NorahLabs — May 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)

Documents the Blueprint architecture, post-turn tool-result summarisation, and benchmark results from a controlled A/B evaluation on a production multi-repository workspace. Honest findings — including a counterintuitive result about total context usage.

---

## Open Source

**[atlarix-skills](https://github.com/AmariahAK/atlarix-skills)** — Community skill registry. SKILL.md files teaching agents language patterns and framework conventions across React, Next.js, Python, TypeScript, Go, Rust, Docker, MCP, and more. Apache 2.0.

**[atlarix-mcps](https://github.com/AmariahAK/atlarix-mcps)** — MCP server registry for Atlarix. One-click connections to Gmail, Calendar, Drive, and more from within the agent environment. Apache 2.0.

**[atlarix-releases](https://github.com/AmariahAK/atlarix-releases)** — Desktop app release builds for Mac and Linux.

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript · Python · JavaScript · SQL · Bash |
| **AI / ML** | Agentic Systems · RAG · Graph RAG · Multi-Agent Orchestration · Context Compression · Universal Ctags · ast-grep · BM25 · LangChain · Hugging Face |
| **Desktop** | Electron · React · React Flow · SQLite |
| **Backend** | Node.js · Django DRF · FastAPI · PostgreSQL · Redis · Celery |
| **Infrastructure** | AWS · GCP · Docker · GitHub Actions · Supabase · Vercel |
| **Auth & Billing** | Auth0 · Token Vault · LemonSqueezy |
| **Monitoring** | Sentry · PostHog · Prometheus · Grafana |

---

## Other Projects

**[Praxia](https://github.com/AmariahAK/Praxia_Backend)** — AI healthcare assistant with MONAI X-ray analysis (pneumonia, fractures, tumours), multilingual symptom diagnosis, real-time WebSocket chat, and Docker/Nginx/Celery production stack.

**[Commit Checker](https://github.com/AmariahAK/commit-checker)** — Open source CLI for Git commit analysis.

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
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak)
