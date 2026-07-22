# Varun Mahajan

**AI Builder · Founder · Multi-Agent Systems · Voice AI · Platform Engineering**

Building systems that think, decide, and scale — without exposing the machinery underneath.

---

## What I'm building

- **[Niyra](https://niyra.ai)** — *"She knows you."* A personal AI assistant that lives where you already are: WhatsApp, Telegram, Discord, web, and inbound voice calls — one conversation, every channel. Persistent long-term memory of your life, proactive follow-through (daily briefs, reminders, commitments it actually tracks), 40+ tools across email, docs, calendar, and the open web, with multi-provider LLM routing and failover underneath. Built solo, end to end: Go agent runtime on Fly.io, Next.js on Vercel, Postgres + pgvector.
- **[Avuvo](https://avuvo.com)** — intent-driven execution platform. Plain language → shipped infrastructure. No YAML, no containers, no infra knowledge required.
- **[HOM-i](https://avuvo.com)** — real-time voice + AI home-loan advisor. STT → LLM → TTS pipeline built for ultra-low latency.
- **[Indya AI Labs](https://avuvo.com)** — AI orchestration and fintech automation initiatives.

**OSS tools from the trenches** — small, zero-dependency primitives, each extracted from a real production incident while building Niyra and other agent systems:

*LLM operations*

| Package | What it does |
|---|---|
| [llm-meter](https://github.com/varunmahajan1/llm-meter) | Token cost tracking with cache-token accounting + billing-drift detection — born from a metered bill that was an order of magnitude below the real invoice |
| [llm-failover](https://github.com/varunmahajan1/llm-failover) | Go: provider-portable failover chains with circuit breakers — including the cross-provider `tool_call_id` fix that silently breaks tool-turn failover |

*Agent safety*

| Package | What it does |
|---|---|
| [agent-runtime](https://github.com/varunmahajan1/agent-runtime) | Go: Watchdog for stalled agents, role-based Tool Enforcer, risk-classified tools + human approval gates |
| [promptshield](https://github.com/varunmahajan1/promptshield) | Prompt injection defense for LLM agents — zero deps, pattern-based |
| [ssrfguard](https://github.com/varunmahajan1/ssrfguard) | Go: SSRF-safe fetching for user/webhook URLs — resolved-IP dial guard that defeats DNS rebinding |

*Streaming & UX*

| Package | What it does |
|---|---|
| [agent-stream](https://github.com/varunmahajan1/agent-stream) | Typed SSE events for multi-agent orchestration, with a terminal-event guarantee — no stream ever ends without telling the client |
| [timeanchor](https://github.com/varunmahajan1/timeanchor) | Deterministic time grounding for LLM prompts — because your agent thinks today is Tuesday |
| [channelfmt](https://github.com/varunmahajan1/channelfmt) | Markdown → WhatsApp/Telegram-native formatting, so users never see literal `**stars**` on their phones |

---

## Currently focused on

- Personal AI — long-term agent memory, proactive (not just reactive) assistants, one agent across every chat channel
- Multi-agent orchestration — agent-to-agent ecosystems, DAG scheduling, MoE routing
- Voice-first AI pipelines — STT → LLM → TTS under 500ms
- Platform engineering — execution layers that abstract infra from intent
- Fintech automation — credit, risk, onboarding workflows
- Cloud infra for AI services at enterprise scale

---

## Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)

**Frameworks & Runtimes**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)

**Data & AI**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Nginx](https://img.shields.io/badge/NGINX-009639?style=flat&logo=nginx&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=varunmahajan1&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varunmahajan1&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</p>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=varunmahajan1&theme=github-dark-blue&hide_border=true" />

> Most work lives in private repos. Behind the scenes: 500+ hours of production AI engineering across 6–8 projects, 4–5 enterprise pilots, 3 full launches, 100k+ end users served via agentic systems, sub-500ms latency targets across voice-AI pipelines.

---

## Open to

Voice AI · real-time agent systems · fintech automation · AI platform architecture · fractional CTO / technical advisor roles

---

## A few things

- I automate things I probably shouldn't — because someone has to.
- I believe most problems can be solved with an AI agent. The rest, with a cron job.
- I run multiple side projects in parallel and keep my dev stack cleaner than my wardrobe.

---

**India** · [vm@avuvo.com](mailto:vm@avuvo.com) · [avuvo.com](https://avuvo.com) · [linkedin.com/in/varunm1](https://www.linkedin.com/in/varunm1)
