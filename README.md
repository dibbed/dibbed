# Ali Khalili

**Backend & Systems Automation Engineer**  
[Telegram](https://t.me/dibbed) · [Email](mailto:ali0.0kh1380@gmail.com) · [GitHub](https://github.com/dibbed)

Backend and systems automation engineer specializing in asynchronous Python services, MTProto automation, and Redis-backed task queues. Builds local MCP tooling, service automation utilities, and proxy routing pipelines for network-constrained deployments.

## Core Engineering Areas

**Backend & Async:** Python, asyncio, FastAPI, Django  
**Messaging & Telegram:** MTProto, Pyrogram, Telethon, Telegram Bot API  
**Databases & Caching:** PostgreSQL, Redis, MongoDB, SQLite  
**Agents & Automation:** Model Context Protocol (MCP), Playwright  
**Infrastructure & Systems:** Linux, systemd, Docker, Nginx  

## Featured Engineering Projects

### [tg-vc-player-saas](https://github.com/dibbed/tg-vc-player-saas)
Voice-chat audio streaming and playback management platform for Telegram groups using MTProto userbot session pools.

- Routes userbot sessions across concurrent group calls using Pyrogram, PyTgCalls WebRTC streaming, and FFmpeg audio transcoding.
- Coordinates playback queues and state transitions using Redis-backed short-lived locks (`SET NX PX`) alongside asynchronous PostgreSQL.
- Restricts worker concurrency with bounded semaphores and handles Telegram `FloodWait` responses via exponential backoff.

### [windows-agent-mcp](https://github.com/dibbed/windows-agent-mcp)
Model Context Protocol (MCP) server providing Windows OS automation, background job execution, and remote agent connectivity.

- Exposes Windows filesystem, Registry, and process management tools through the Python MCP SDK, secured by token-authenticated loopback endpoints.
- Supervises long-running subprocesses with non-blocking async stream capture, SQLite job state persistence, and clean process-tree termination.

### [cli-orchestrator](https://github.com/dibbed/cli-orchestrator)
Dual-agent execution harness managing task delegation between an orchestrator model and an isolated worker subprocess.

- Isolates worker subshells in dedicated directories using subprocess stdin decoupling (`subprocess.DEVNULL`) and fenced JSON message contracts.
- Catches command timeouts, rate limits, and malformed outputs through mapped exit codes and regex stream inspection.

### [TTSKit-multi-engine-tts](https://github.com/dibbed/TTSKit-multi-engine-tts)
Asynchronous text-to-speech service and Telegram bot supporting multi-engine routing with first-class Persian text handling.

- Unifies Edge-TTS, Google TTS, and Piper-TTS behind an async interface with language-based engine routing and FFmpeg audio transcoding.
- Normalizes Persian text via diacritics inference and RTL formatting, serving requests through FastAPI endpoints and Telegram bot adapters backed by Redis caching.

### [iranconcert_scanner](https://github.com/dibbed/iranconcert_scanner)
Automated seat detection and reservation scanner for ticket checkout flows using Playwright.

- Analyzes venue seating layouts via injected DOM scripts to detect contiguous available seat blocks matching party-size requirements.
- Preserves authenticated browser session state and recovers from transient network failures through configurable retry loops.

## Production / Private Systems

### Knowledge Graph & Educational Content Engine
Relational backend powering structured domain knowledge graphs, comparative entities, and student study workflows.

- Modeled relational domain graphs in Django using composite indexing and integrity constraints preventing direct self-referential edges.
- Maintained database performance via PostgreSQL connection persistence (`CONN_MAX_AGE`), query budgets to eliminate N+1 regressions, and cached graph materialization.

### Proxy Infrastructure & Network Routing Automation
Configuration automation and management backends for multi-node proxy panels operating under restricted network environments.

- Built SingBox and Xray configuration pipelines generating dynamic routing rules, outbound protocol selections, and configuration distribution across nodes.
- Reconciled non-custodial TRC-20 payments via Tronpy using persisted transaction tracking and Redis duplicate-processing guards (`SET NX`).

### Telegram MTProto Automation & Multi-Session Worker Pools
Worker pools coordinating messaging and channel administration across concurrent MTProto client sessions.

- Managed concurrent Pyrogram and Telethon client sessions with per-account proxy routing and automated session lifecycle management.
- Dispatched background tasks through Redis priority queues, applying token-bucket rate limiting and adaptive backoff to handle Telegram `FloodWait` responses.

### Host Monitoring & Process Supervision Daemons
Background service watchdogs tracking host health and recovering failed application processes.

- Monitored CPU and memory saturation, open file descriptors, and socket availability using `psutil` polling loops.
- Handled threshold-based process recovery, diagnostic crash logging, and failure alerting to administrative Telegram channels.

## Other Projects

- [jobvision-auto-apply](https://github.com/dibbed/jobvision-auto-apply) — Headless Playwright automation pipeline for job application filtering with stored session state and Gemini API candidate matching.
- [nginx-ssl-auto](https://github.com/dibbed/nginx-ssl-auto) — Automated Nginx reverse proxy configuration and Let's Encrypt TLS certificate provisioning CLI.
- [redis-mongo-backup-tool](https://github.com/dibbed/redis-mongo-backup-tool) — Environment-driven CLI for pattern-based Redis keyspace exports and MongoDB database backups.
- [smart-periodic-table-fullstack](https://github.com/dibbed/smart-periodic-table-fullstack) — Interactive 3D chemical element explorer built with React, Three.js, Node.js, and SQLite.
