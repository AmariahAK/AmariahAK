# Amariah Abishai
**AI Engineer · Full Stack Architect · Founder @ NorahLabs**

Self-taught engineer from Nairobi, Kenya, building production AI systems: coding-agent harnesses, agentic orchestration, and tooling that runs on your own machine, on any model you bring, without cloud lock-in.

---

## Flagship: Atlarix

> **The private AI workstation: desktop, browser, and PR review.** One agent your team drives to plan, build, review, debug and test real projects, in the app, the terminal, your editor, your browser, and on your pull requests. It keeps notes on your codebase and gets sharper on your system the longer you use it.

macOS / Linux / Windows · Terminal · VS Code · Zed · JetBrains · Chrome · GitHub · Slack · [atlarix.dev](https://atlarix.dev)

Atlarix is a workstation you bring any AI model into. It uses AI; it doesn't make it. What lets a weaker or local model punch above its weight isn't a bigger prompt, it's the **harness**: enforced tool approvals, an OS-level execution sandbox, and verified edits mean the model's mistakes are caught by the system, not trusted on faith. Run a local model and your code never leaves the machine.

**One product, every surface:**
- **Desktop app** — the full workstation: plan, build, debug, review and test with a real terminal, a sandbox, and hunk-by-hunk approval.
- **Terminal** — the same agent as a CLI: `curl -fsSL https://atlarix.dev/install | sh`, `brew install amariahak/atlarix/atlarix`, or `npm i -g atlarix`.
- **Your editor** — an extension for VS Code, Cursor, Kiro, Windsurf and VSCodium, and an [Agent Client Protocol](https://agentclientprotocol.com) agent for Zed and JetBrains (`atlarix acp`).
- **Chrome extension** — the agent in the browser you're already signed into: it reads pages, works across tabs, fills forms (never submits without asking), and hands your real session to the other surfaces when a task needs your logins.
- **Atlarix Reviewer** — a GitHub App that reviews pull requests on repositories you choose and posts findings as a review (file, line, what's wrong, and the fix). It never writes to your code and never runs it.
- **Slack and the cloud agent** — hand Atlarix a task from a conversation, or let it work in your own GitHub Actions.

Sessions talk to each other, so a task started in the terminal can hand off to the app or the browser.

**What makes it different:**
- **The harness, not the model** — a weaker or local model performs reliably because the system enforces correctness. Bring your own key across 220+ providers and 6,500+ tool-capable models, run local models through Ollama or LM Studio, or use Atlarix Auto and skip keys entirely.
- **Atlarix Auto** — picks the right model for each step (exploring, building, planning, reviewing, reading a screenshot or PDF) instead of running a whole session on one model. Free with a daily allowance in the app, the terminal and your editor; private on Pro or credit.
- **42,000+ MCP servers** — the marketplace is the official MCP Registry, searched live, with verified one-click connectors on top. Any Agent Skill drops straight in.
- **Verified edits** — in Build / Debug the agent runs the project's *own* checks (`tsc`/`eslint`/`ruff`/`mypy`/`pytest`) through a sandboxed terminal and can't declare a task done while they fail.
- **OS-level execution sandbox** — per-OS write-confining command execution (Linux Landlock, Windows AppContainer, macOS Seatbelt), hunk-level diff approval, a danger gate, and committable permission rules at a single execution funnel. It can't reach past the project you opened.
- **Fast search, no index** — bundled-ripgrep `grep` and `glob`: no index to build, no embeddings, no background watcher, constant low memory at any repo size.
- **Parallel sub-agents** — up to five workers per turn: read-only scouts plus implementers whose edits come back as proposals for the main agent to review.
- **Long sessions that hold up** — compaction that summarises before it deletes anything, plus `session_search` so the agent can look back through the full transcript.
- **Automations** — put it on a schedule or an MCP trigger (a nightly test run, a weekly dependency review); it runs, then reports back.

**Work modes:** Explore (read-only) · Plan · Build · Debug · Review (correctness + security)

**Pricing:** the app is free, with every feature, on every surface. Free Atlarix Auto, your own keys and local models cost nothing. **Pro ($19/month)** adds Atlarix Reviewer and included managed inference, from one shared balance.

**As an open-source contributor,** I've landed production code into major repositories using Atlarix across a range of models, mostly open-weight: **[Remix](https://github.com/remix-run/remix/pull/11591)** (merged by its co-creator), **[Caddy](https://github.com/caddyserver/caddy/pull/7910)** (merged by its creator), **[Traefik](https://github.com/traefik/traefik/pull/13476)**, **[pnpm](https://github.com/pnpm/pnpm/pull/13215)**, **[Valkey](https://github.com/valkey-io/valkey/pull/4341)**, **[TanStack Query](https://github.com/TanStack/query/pull/11036)**, **[Apollo Client](https://github.com/apollographql/apollo-client/pull/13329)**, **[Crawlee](https://github.com/apify/crawlee/pull/3831)**, and **[vim](https://github.com/vim/vim/commit/a20071113aa9bec2d47924e6af0269b6e1929ac5)**, plus documentation merged into **[AWS CDK](https://github.com/aws/aws-cdk/pull/38461)** and **[Sentry](https://github.com/getsentry/sentry-docs/pull/19055)**. Each is a public, verifiable merge: AI use is disclosed in the commits, and every change was reviewed and merged by the project's own maintainers.

---

## Research

**Blueprint: Section-Scoped Structural Graph Retrieval and Post-Turn Compression for Agentic LLM Coding in Multi-Repository Workspaces**
Amariah Abishai, NorahLabs — 2026 · *published research*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)

A peer-reviewed paper documenting the Blueprint architecture — a section-scoped structural index (Universal Ctags symbol graph + ast-grep edges + SQLite FTS5) that handed the agent structural understanding in ~6,500 tokens instead of a whole-repo dump — alongside post-turn tool-result summarisation and results from a controlled A/B evaluation on a production multi-repository workspace, including a counterintuitive finding: structural confidence lets the agent explore *more*, using more total context but producing stronger results. Blueprint was a research effort; Atlarix's current retrieval takes a different, lexical approach.

---

## Open Source

**[atlarix-skills](https://github.com/AmariahAK/atlarix-skills)** — Community Agent Behaviors registry. SKILL.md files teaching agents language patterns and framework conventions across React, Next.js, Python, TypeScript, Go, Rust, Docker, MCP, and more. Apache 2.0.

**[atlarix-releases](https://github.com/AmariahAK/atlarix-releases)** — Desktop app release builds for macOS, Linux, and Windows.

**[atlarix-mcps](https://github.com/AmariahAK/atlarix-mcps)** — *Archived.* The original MCP server index for Atlarix; the marketplace now runs on the official MCP Registry. Apache 2.0.

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript · Python · JavaScript · SQL · Bash |
| **AI / ML** | Agentic Systems · Coding-Agent Harness Design · Multi-Agent Orchestration · Model Routing · Lexical Retrieval (ripgrep / BM25 / FTS5) · Context Compression · MCP · Agent Client Protocol · Open-Weight & Local Model Integration · Hugging Face |
| **Desktop, Terminal & Browser** | Electron · React · Node CLI / TUI · VS Code Extensions · Chrome Extensions (MV3, CDP) · SQLite |
| **Backend** | Node.js · Django DRF · FastAPI · PostgreSQL · Redis · Celery |
| **Infrastructure** | AWS · GCP · Docker · GitHub Actions · GitHub Apps · Slack Apps · Supabase · Vercel |
| **Auth & Billing** | Supabase Auth · LemonSqueezy |
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

[![Atlarix](https://img.shields.io/badge/Atlarix-2563EB?style=flat&logoColor=white)](https://atlarix.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/amariah-abishai-3156412a6/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:amariah@atlarix.dev)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20381860.svg)](https://doi.org/10.5281/zenodo.20381860)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak)
