# 🚶‍♂️ PilgrimStack

**Walking the line between code and consciousness.**

I go by **PilgrimStack**.
To me, being a developer isn't about reaching 
a final destination — it's about the journey: 
constant iteration, late-night debugging 
pilgrimages, and the discipline of building 
systems that actually hold up.

I build tools where **human intuition and 
machine intelligence meet** — without either 
getting in the way.

---

## 🌌 Flagship Project: Atlarix
**A Privacy-First, Native AI Coding Copilot**
*v3.9 — Live & Apple Notarized ✅*

Atlarix is my current mission: a desktop-native 
AI copilot built to give developers agentic 
power without cloud lock-in or privacy trade-offs.

This isn't a chat box that suggests code.
It's a copilot that **understands your entire 
system architecture** and builds inside your 
real dev environment — visually.

👉 https://atlarix.dev

### What's New in v3.9
- **❓ AI Clarifying Questions**
  All models can now ask up to 4 targeted 
  questions before proceeding on complex or 
  ambiguous tasks. Answered once per chat — 
  never repetitive.

- **↩ Conversation Revert + Message Edit**
  Edit any previous message and re-prompt 
  from that point. Conversation truncates 
  cleanly. File revert ships in v4.0.

- **📡 Stream Tools**
  `stream_terminal_output` and 
  `stream_pipeline_logs` — AI watches live 
  data for exactly what it needs instead of 
  reading full output dumps. Significant 
  token reduction on noisy output.

- **⚙️ GitHub Actions Panel**
  View workflow runs, stream live logs, 
  and send output to AI — without leaving 
  Atlarix. Lives in the left panel (Pro).

- **↔️ Resizable Panels + Shortcuts**
  Drag to resize left panel. Cmd/Ctrl+I 
  and Cmd/Ctrl+O to toggle panels at 30% 
  width. Width persisted across sessions.

- **💬 Chat Tab When Panels Cover Screen**
  When both panels are open and the chat 
  area is hidden, a full Chat tab appears 
  in the right panel — same session, 
  same tools, compact model search.

### Core Architecture: RTE + RAG
```
Traditional AI coding:
  Ask question → scan codebase → 
  100K tokens → slow, expensive, resets

Atlarix v3.9:
  Parse once → Blueprint graph cached → 
  query relevant nodes → ~5K tokens
  File watcher → incremental updates only
```
**Parse Once. Query Forever.**

### Feature Highlights
- **🗺 Blueprint Canvas** — React Flow 
  visual architecture designer. Design 
  containers, beacons, edges. Generate 
  ATLARIX_PLAN.md. AI implements task by 
  task with your review at each step.

- **🤖 Four-Agent System** — Research, 
  Architect, Builder, Reviewer. 
  Direct / Guided / Autonomous modes. 
  Ask (read-only) vs Build (write + execute) 
  permissions independent of mode.

- **🔐 Privacy-First & BYOK** — OpenAI, 
  Anthropic, Gemini, Groq, xAI, Mistral, 
  Together AI, OpenRouter, AWS Bedrock, 
  Ollama, LM Studio. Your keys, your data, 
  your machine.

- **🛠 59 Intelligent Tools** — File ops, 
  terminal execution, web search, semantic 
  code search, architecture diagrams, 
  DB queries, stream tools, scaffolding.

- **🔄 Permission Queue** — AI proposes 
  every change. You approve before 
  anything runs.

- **🚀 Live Dev Previews** — Vite, Next.js, 
  CRA, Nuxt, Astro. Auto-starts dev server, 
  renders in-app.

- **💰 Token Budget System** — Per-provider 
  caps, real-time color-coded bar, 
  warnings at 80% and 90%.

- **🗄 DB Extension (Pro)** — Full CRUD 
  for PostgreSQL, MySQL, and SQLite. 
  AI tools: db_query, db_schema, 
  db_list, db_mutate.

- **⚙️ GitHub Actions (Pro)** — Pipeline 
  runs, job logs, live streaming, 
  Send to AI. No tab switching.

### Currently Competing 🏆
Entered in 1 hackathons simultaneously:
- **Amazon Nova AI Hackathon** — $40,000 pool

---

## 🌍 The African AI Initiative

Atlarix is built in Nairobi. The next chapter 
is building *for* African developers.

Most AI coding tools assume a $20/month 
subscription to a Western provider. That's 
not the reality for most developers on this 
continent. Atlarix is open-model by design — 
you bring any AI, including locally-built ones.

We're actively integrating African-built models 
as first-class providers:
- **Awarri** (Nigeria) — N-ATLAS multilingual LLM
- **Lelapa AI** (South Africa) — InkubaLM 
  in Swahili, Hausa, isiZulu, isiXhosa, Yoruba
- **LLM Labs Kenya** — LLMs for the Kenyan context

The goal: a developer in Nairobi opens Atlarix, 
picks a locally-built model, and ships software. 
No Western subscription required.

---

## 🔭 Atlarix Roadmap

### v3.x — PIVOT (In Progress)
Full ANTLR4 parsing across TypeScript, Python, 
Java, Go, Rust, C/C++. SQLite persistence for 
the Blueprint graph. AI clustering into 
containers. Live vs Blueprint comparison. 
Generate code from architecture.

### v4.0 — Atlarix Workforce (Planned)
Taking Atlarix beyond the individual developer 
into team and automation workflows:

- **Slack Integration** — AI agent accessible 
  directly from your team's Slack
- **GitHub Actions Integration** — Atlarix 
  agents as CI/CD steps
- **File Revert** — Restore codebase to 
  pre-exchange state on conversation revert
- **Supabase Native Integration** — Auth, 
  storage, realtime, edge functions as 
  first-class Blueprint nodes
- **Multi-Repo Workspace** — One Blueprint 
  across your entire org's repos
- **Team Memory** — Shared memory.md 
  synced across team members via Git

### Beyond v4.0
Voice input · Timeline export · 
Atlarix Vanguard · Enterprise SSO

---

## 🧠 The Neural Network

| Category | Stack |
| :--- | :--- |
| **Desktop** | Electron · TypeScript · React |
| **Canvas** | React Flow · SQLite |
| **AI** | OpenAI · Anthropic · Gemini · Groq · Mistral · xAI · Ollama · LM Studio |
| **Backend** | Node.js · Express · PostgreSQL |
| **Infrastructure** | GitHub Actions · Vercel · AWS · Docker |
| **Monitoring** | Sentry · PostHog |
| **Design** | TailwindCSS · Figma |

---

## 📊 Vital Signs
![](https://github-readme-stats.vercel.app/api?username=AmariahAK&theme=midnight-purple&hide_border=false&include_all_commits=true&count_private=true)

![](https://nirzak-streak-stats.vercel.app/?user=AmariahAK&theme=midnight-purple&hide_border=false)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=AmariahAK&theme=midnight-purple&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---

## 🌐 Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/amariah-kamau-3156412a6/)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?logo=firefox-browser&logoColor=white)](https://portfolio-pied-five-61.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:amariah.abish@gmail.com)
[![Atlarix](https://img.shields.io/badge/Atlarix-10b981?style=flat&logoColor=white)](https://atlarix.dev)

**Code smart. Stay authentic.**
See you in the next one 🚀

**Fuel the journey:**

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/amariahak)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/amariahak)

---

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
