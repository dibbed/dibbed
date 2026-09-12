<!-- Header Banner -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=2200&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Resilient+Backend+Systems+%7C+Telegram+Orchestration+%7C+Agentic+Tooling">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=2200&pause=1000&color=0284C7&center=true&vCenter=true&width=650&lines=Resilient+Backend+Systems+%7C+Telegram+Orchestration+%7C+Agentic+Tooling" alt="Resilient Backend Systems | Telegram Orchestration | Agentic Tooling" />
  </picture>
</p>

<!-- Quick Contacts & Badges -->
<p align="center">
  <a href="https://t.me/dibbed">
    <img src="https://img.shields.io/badge/Telegram-@dibbed-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:ali0.0kh1380@gmail.com">
    <img src="https://img.shields.io/badge/Email-ali0.0kh1380%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/dibbed">
    <img src="https://img.shields.io/badge/GitHub-dibbed-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://wakatime.com/@dibbed">
    <img src="https://wakatime.com/badge/user/1cafc019-2a3d-4fb8-8581-07c0caa1c7e5.svg" alt="WakaTime coding activity">
  </a>
</p>

<p align="center">
  Senior-leaning builder focused on high-concurrency event loops, network resilience, automated orchestration, and agent tooling.
</p>

---

### 🚀 Featured Engineering Projects

#### 🤖 [windows-agent-mcp](https://github.com/dibbed/windows-agent-mcp)
> **MCP server providing Windows OS automation, background subprocess supervisors, and remote LLM tunnels.**
- **OS Automation & Control:** Process lifecycle management, Windows Registry queries, and filesystem operations via native APIs.
- **Subprocess Supervisor:** Non-blocking asynchronous task execution with live stdout/stderr stream capture and process supervision.
- **Remote LLM Tunnel:** Secure tunnel bridge enabling external LLM runners to execute local MCP tools across authenticated endpoints.
- `Python` · `FastMCP` · `Windows API` · `OpenAI SDK`

#### 📡 [tg-vc-player-saas](https://github.com/dibbed/tg-vc-player-saas)
> **Distributed WebRTC voice engine handling multi-session userbot pooling, FFmpeg pipelines, and Redis queue orchestration.**
- **Userbot Session Pool:** Dynamic allocation and load-balancing of Telegram userbots across concurrent group voice chats.
- **Real-Time Audio Pipelines:** Low-latency WebRTC streaming via PyTgCalls integrated with tuned FFmpeg transcoding processes.
- **Distributed State & Queues:** Redis-backed playback queues, priority scheduling, and multi-tenant access control.
- `Python` · `PyTgCalls` · `Pyrogram` · `Redis` · `WebRTC` · `Docker`

#### 🔁 [cli-orchestrator](https://github.com/dibbed/cli-orchestrator)
> **Dual-agent execution harness featuring hierarchical task routing, isolated worker subshells, and verification loops.**
- **Hierarchical Task Routing:** Coordinator agent decomposes complex objectives, dispatches scoped sub-tasks, and evaluates convergence criteria.
- **Isolated Worker Subshells:** Sandboxed subprocess execution environments for code generation, AST-aware diffing, and tool execution.
- **Verification & Rollback Loops:** Automated regression test execution, linting validation, and checkpoint rollbacks upon verification failure.
- `Python` · `Claude API` · `OpenAI API` · `Subprocess Isolation`

#### 🎙️ [TTSKit-multi-engine-tts](https://github.com/dibbed/TTSKit-multi-engine-tts)
> **Multi-engine async TTS service with Persian text normalization and FastAPI/Telegram interfaces.**
- **Multi-Engine Abstraction:** Unified asynchronous interface spanning Edge-TTS, Google TTS, and Piper-TTS with automatic fallback handling.
- **Persian Text Normalization:** Text pre-processing pipeline handling diacritics inference, RTL bidirectional formatting, and phonetic conversion.
- **Dual API Surfaces:** Asynchronous REST microservice built on FastAPI alongside an interactive Telegram bot client.
- `FastAPI` · `Python` · `Edge-TTS` · `Pyrogram` · `Docker`

#### 🎯 [jobvision-auto-apply](https://github.com/dibbed/jobvision-auto-apply)
> **Headless Playwright job applicant with session fingerprinting and Gemini-assisted evaluation.**
- **Fingerprinted Headless Automation:** Playwright browser automation with canvas/navigator fingerprint masking and persistent authentication storage.
- **Gemini-Assisted Evaluation:** Contextual parsing of job descriptions against applicant profiles using Google Gemini to compute match fitness.
- **Event Telemetry:** Real-time Telegram alerts delivering application dispatch reports, criteria match logs, and submission status.
- `Python` · `Playwright` · `Google Gemini API` · `Telegram Bot API`

#### 🧰 Production CLI Utilities
- **[redis-mongo-backup-tool](https://github.com/dibbed/redis-mongo-backup-tool)** — Automated backup daemon for Redis & MongoDB featuring gzip compression, SHA-256 integrity verification, cron rotation, and remote sync.
- **[nginx-ssl-auto](https://github.com/dibbed/nginx-ssl-auto)** — Nginx reverse proxy provisioner with automated Let's Encrypt SSL lifecycle management, OCSP stapling, and auto-reload hooks.

#### 🔬 Exploratory & Fullstack
- **[smart-periodic-table-fullstack](https://github.com/dibbed/smart-periodic-table-fullstack)** — Interactive 3D chemical visualization engine and elemental database. Features WebGL/Three.js atomic orbitals, thermodynamic phase simulation across 118 elements, and a Node.js/SQLite backend.

---

### 🏛️ System Architecture & Private Highlights

> Unlisted distributed systems engineered for strict operational constraints, adversarial network environments, and high-concurrency throughput:

- **🔐 Multi-Tenant VPN Infrastructure & Edge Sync**
  - Synchronized distributed edge nodes across multiple cloud regions using Redis pub/sub pipelines and MongoDB document stores.
  - Implemented dynamic routing, automated TLS certificate lifecycles, and censorship-resistant tunneling under strict network firewalls and DPI environments.
  - Built non-custodial crypto settlement hooks (USDT TRC-20 / TRX) with multi-node webhook verification and idempotent transaction ledgering.

- **🛡️ Distributed Telegram Automation & Anti-Abuse Networks**
  - Managed multi-client worker pools (Pyrogram/Telethon) handling coordinated event dispatching and community orchestration.
  - Implemented distributed token-bucket rate limiters sustaining 100+ requests/sec across Redis instances with adaptive jitter and backoff.
  - Engineered anti-ban session rotation routines, payload randomizers, and connection pooling to ensure persistent uptime.

- **🎫 High-Concurrency Ticket & Booking Sniper**
  - Engineered automated reservation engines operating with sub-300ms checkout reaction loops targeting high-demand ticketing platforms (*e.g., honarticket.com*, core scanner open-sourced in [`iranconcert_scanner`](https://github.com/dibbed/iranconcert_scanner)).
  - Deployed headless Chromium session pools with DOM mutation listeners and anti-bot challenge evasion during sudden traffic surges.
  - Dispatched instant checkout signals through low-latency audio alarms and webhook-driven Telegram alerts.

- **📈 High-Volume Engagement & Financial Ledger Platform**
  - Engineered distributed priority queues handling 50k+ daily asynchronous interaction tasks (reactions, polls, and view distribution pipelines).
  - Integrated fiat payment gateways (Zibal) and crypto settlement rails with strict double-entry ledgering and idempotent transaction verification.
  - Structured multi-tier affiliate tracking trees with automated reconciliation workers.

- **🔧 Server Telemetry & Self-Healing Watchdogs**
  - Deployed standalone system daemons tracking memory pressure, CPU saturation, open socket limits, and I/O bottlenecks at 5-second polling intervals.
  - Automated rule-based process termination, sub-2-second zero-downtime service resuscitation, diagnostic crash-dump generation, and Telegram alerts.

---

### 🧰 Tech Stack & Tooling

- **Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
- **Backend & Networks:** ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![aiohttp](https://img.shields.io/badge/aiohttp-2C5BB4?style=flat-square&logo=aiohttp&logoColor=white)
- **Databases & Caching:** ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
- **Agents & Automation:** ![MCP](https://img.shields.io/badge/MCP-6366F1?style=flat-square&logo=anthropic&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

### 📊 GitHub Metrics

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api?username=dibbed&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-fast.vercel.app/api?username=dibbed&show_icons=true&theme=default&hide_border=true" />
    <img src="https://github-readme-stats-fast.vercel.app/api?username=dibbed&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" height="165" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=dibbed&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=dibbed&layout=compact&theme=default&hide_border=true" />
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=dibbed&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" height="165" />
  </picture>
</p>

---

<p align="center">
  <sub>Designed & built with precision by <b>Ali (<a href="https://github.com/dibbed">@dibbed</a>)</b></sub>
</p>
