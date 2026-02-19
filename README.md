# 🚶‍♂️ PilgrimStack  

**Walking the line between code and consciousness.**

I go by **PilgrimStack**.  
To me, being a developer isn’t about reaching a final destination — it’s about the journey: constant iteration, late-night debugging pilgrimages, and the discipline of building systems that actually hold up.

I build tools where **human intuition and machine intelligence meet** — without either getting in the way.

---

## 🌌 Flagship Project: Atlarix
**A Privacy-First, Native AI Coding Agent**  
*v3.0 — Live*

Atlarix is my current mission: a desktop-native AI copilot built to give developers **agentic power without cloud lock-in or privacy trade-offs**.

This isn't a chat box that suggests code.  
It's an agent that **understands your entire system architecture** and builds inside your real dev environment.

👉 https://www.atlarix.dev/

### What's New in v3.0
- **🗂 Workspace Storage Overhaul**  
  Paths resolve correctly, workspaces are stable, `.atlarix/` folder ships with every project.

- **🧠 Persistent Project Memory**  
  `memory.md` + `spec.md` inside `.atlarix/` — the AI remembers your decisions, rules, and architecture across every session. No more re-explaining your project.

- **🔗 Fully Visible Flow Connections**  
  Blueprint canvas connections render cleanly across all node types.

- **📡 Telemetry Foundation**  
  OpenTelemetry + SQLite groundwork laid for the upcoming PIVOT (ANTLR4 full parsing + persistent graph).

### Core Architecture: RTE + RAG
```
Traditional AI coding:
  Ask question → scan codebase → 100K tokens → slow, expensive

Atlarix v3.0:
  Parse once → Blueprint graph cached → query relevant nodes → ~5K tokens
  File watcher → incremental updates only
```
**Parse Once. Query Forever.**

### Feature Highlights
- **🗺 Blueprint Canvas** — React Flow visual architecture designer. Design containers, beacons, edges. Generate `ATLARIX_PLAN.md`. AI implements task by task with review gates.
- **🤖 3-Tier Agent System** — Research → Architect → Builder → Reviewer. Direct / Guided / Autonomous modes. Ask (read-only) vs Build (write + execute) permissions — independent of mode.
- **🔐 Privacy-First & BYOK** — OpenAI, Anthropic, Gemini, Groq, xAI, Mistral, Together AI, AWS Bedrock, Ollama, LM Studio. Your keys, your data.
- **🛠 57 Intelligent Tools** — File ops, terminal execution, web search, semantic code search, architecture diagrams, scaffolding.
- **🔄 Permission Layer** — AI proposes every change. You approve before anything runs.
- **🚀 Live Dev Previews** — Vite, Next.js, CRA, Nuxt, Astro. Auto-starts dev server, renders in-app.
- **💰 Token Budget System** — Per-provider caps, real-time color-coded bar, warnings at 80% and 90%.

### Currently Competing
🏆 Entered in 3 hackathons simultaneously:
- **Amazon Nova AI Hackathon** — $40,000 prize pool
- **DeveloperWeek 2026 Hackathon** — $23,000 prize pool  
- **Elasticsearch Agent Builder Hackathon** — $20,000 prize pool

---

## 🔭 Atlarix Roadmap

### v3.x — PIVOT (In Progress)
Full ANTLR4 parsing across TypeScript, Python, Java, Go, Rust, C/C++. SQLite persistence for the Blueprint graph. AI clustering into containers. Live vs Blueprint comparison. Generate code from architecture.

### v4.0 — Atlarix Workforce (Planned)
Taking Atlarix beyond the individual developer into **team and automation workflows**:

- **Slack Integration** — AI agent accessible directly from your team's Slack. Ask questions about your codebase, trigger builds, get PR summaries without leaving the channel.
- **GitHub Actions Integration** — Atlarix agents as CI/CD steps. Auto-review PRs against the Blueprint, flag architectural drift, suggest fixes before merge.
- **Database Intelligence** — Connect to live databases (Supabase, PostgreSQL, MySQL). AI understands your schema, queries, and data relationships as part of the Blueprint graph.
- **Supabase Native Integration** — Auth, storage, realtime, and edge functions understood natively. Blueprint includes your Supabase schema as first-class nodes.
- **Multi-Repo Workspace** — One Blueprint across your entire org's repos. Frontend, backend, mobile, infra — unified architecture view.
- **Team Memory** — Shared `.atlarix/memory.md` synced across team members via Git. Everyone's AI has the same project context.

### Beyond v4.0
- Voice input
- Timeline export
- Workspace templates
- Enterprise SSO + audit logs

---

## 🧠 The Neural Network (Tech Stack)

| Category | Tools & Technologies |
| :--- | :--- |
| **Intelligence** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=TensorFlow&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=flat&logo=opencv&logoColor=white) |
| **Foundation** | ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white) |
| **Cloud/Ops** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) |
| **Design** | ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat&logo=figma&logoColor=white) ![Three js](https://img.shields.io/badge/threejs-black?style=flat&logo=three.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white) |

---

## 📊 Vital Signs
![](https://github-readme-stats.vercel.app/api?username=AmariahAK&theme=midnight-purple&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=AmariahAK&theme=midnight-purple&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=AmariahAK&theme=midnight-purple&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---

## 🌐 Connect & Support
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/amariah-kamau-3156412a6/) [![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?logo=firefox-browser&logoColor=white)](https://portfolio-pied-five-61.vercel.app/) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:amariah.abish@gmail.com)

**Code smart. Stay authentic.**  
I’ll see you in the next one 🚀

**Fuel the journey:**
[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak) [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/paypalme/my/profile/amariah.abish@gmail.com)

---
### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
