---
type: asset
status: current
tags: [cv, resume, final, en, ready-to-send]
created: 2026-11-12
updated: 2026-11-12
note: Final English version for international applications. No unfilled slots — `tools/kb-placeholders` green, `tools/kb-gate` green.
---

# Oleg Rodionov — AI Automation Engineer

**Saint Petersburg, Russia (GMT+3)** · Remote · Telegram: [@ninelegsdog](https://t.me/ninelegsdog) · GitHub: [github.com/ninelegsdog](https://github.com/ninelegsdog) · ninelegsdog@gmail.com

---

## About Me

Software developer with 14+ years of experience (since 2003): server-side, web, mobile, multimedia, and industrial systems.

Specializing in Python, Telegram bots, AI agents, and business process automation.

Design and lead software development with AI coding agents: formulating requirements and user scenarios, designing agent harness, managing context and decomposition, organising the cycle «specification → generation → launch → verification → fix → acceptance», controlling quality, testing, documentation, and launch.

### How I work with AI agents

Code in new projects is produced by AI coding agents in a configured agent harness that I set up. My work:

- product formulation and user scenarios;
- context engineering: instructions, constraints, and working rules;
- result control;
- infrastructure control: project configuration, documentation, and reproducible launches.

Experience with Python, Java, PHP, JavaScript, SQL, and Linux allows me to critically evaluate AI-generated code and bring solutions to production. Process described openly: [agentic-development-playbook](https://github.com/ninelegsdog/agentic-development-playbook).

---

## Portfolio

### «9 Bots» Series — typical business tasks in Telegram

All nine bots run in production: webhook, TLS, health-check, autorestart, observability. **Over 1000 tests** implemented.

| Bot | Task | Live |
|---|---|---|
| BookingBot | booking and slots, payment acceptance, double-booking protection | [@SaasBookingKitBot](https://t.me/SaasBookingKitBot) |
| LeadGenBot | lead collection and qualification, escalation, manager notifications | [@LeadgenKitBot](https://t.me/LeadgenKitBot) |
| StoreBot | catalog, cart, order placement, purchase history | [@StoreKitBot](https://t.me/StoreKitBot) |
| SupportBot | tickets, FAQ, SLA tracking by business hours | [@SaasSupportKitBot](https://t.me/SaasSupportKitBot) |
| MembershipBot | subscriptions, payment, access control, trial period | [@MembershipKitBot](https://t.me/MembershipKitBot) |
| ReminderBot | reminders and broadcasts by schedule with segmentation | [@ReminderKitBot](https://t.me/ReminderKitBot) |
| DocuFlowBot | document request, PDF generation, result delivery | [@DocuflowKitBot](https://t.me/DocuflowKitBot) |
| PriceSentryBot | scheduled price monitoring, change alerts | [@PricesentryKitBot](https://t.me/PricesentryKitBot) |
| DeliveryBot | delivery statuses, incoming webhook events from external systems | [@DeliveryKitBot](https://t.me/DeliveryKitBot) |

Message any of them to see how they work. Code is open: [github.com/ninelegsdog](https://github.com/ninelegsdog).

All nine bots run on a shared library, not nine copies: **1537 autotests on the line**, coverage 72–92%, separate observability stack. One phrase: a new scenario is assembled from ready-made parts in days.

### What surrounds the bots

- **Observability:** Prometheus, Grafana, Loki, Tempo, Alertmanager, OpenTelemetry, MinIO.
- **CI/CD:** linter → types → tests → build → deploy with auto-rollback on health-check failure.
- **Secrets:** age encryption, gitleaks gate in CI, no secrets in repositories or commit history.
- **Infrastructure:** 9 bots in Docker with unprivileged user, read-only rootfs, dropped capabilities.

### Stack

Python 3.12+ · aiogram 3.30 · SQLAlchemy 2 (async) · PostgreSQL / SQLite · Redis · APScheduler · Alembic · Docker / Compose · GitHub Actions · Prometheus · Sentry · aiohttp · reportlab · YooKassa · TypeScript · MCP (Model Context Protocol) · Playwright · browser automation · quality engineering · evidence pipeline · Obsidian/vault-lint

---

## Services

| Service | What's included |
|---|---|
| Micro-MVP | one key feature, working: 3–5 days |
| Bot turnkey | scenarios, database, admin panel, payments or integrations, VPS deployment, documentation |
| Existing bot rework & audit | code and logic review, problems and risks list, prioritised plan, fixes |
| VPS deployment | server, environment, database, autorun, monitoring, maintenance instructions |
| Audit & test automation | evidence-first browser QA (Playwright), normalised defect artefacts, quality gate, MCP server |
| Integrations | Telegram ↔ CRM, spreadsheets, external APIs, webhook event ingestion |
| Support | monitoring, fixes, new features, agreed response time |
| Automation consultation | process analysis, automation options with effect estimate and roadmap |

---

## Experience

**Independent Developer · AI Automation / Telegram bots and engineering tools** · 2026
Design and launch of nine Telegram bots in an AI-native process: specifications, agent harness, decomposition, iterations, acceptance. DevOps: deployment, webhook and TLS, backups with integrity verification, monitoring (Prometheus/Grafana/Loki/Tempo/Alertmanager), alerts, incident analysis (UFW LIMIT, shadow-copy, TTM).
Additionally: public npm package QualityForge (evidence-first browser QA, MCP server), book «Дзен и агентная архитектура» (AI-native development method).

**Programmer · ООО «Новотех XXI век», Saint Petersburg** · 02.2020 — 10.2020
Automatic dosing line software for pharma products: Java, EtherCAT, Modbus RTU, SMSD-4.2LAN, Linux/Openbox. Equipment and software integration, shop-floor debugging.

**Web Developer · Digital Security, Saint Petersburg** · 05.2017 — 07.2018
Web client for the main application, integration projects, business automation.

---

## Skills

**Core:** Python · Telegram Bot API · AI agents and LLM integrations · context engineering · agent harness · SQLAlchemy · PostgreSQL · MySQL · SQL · Redis · REST API · Docker · Git / GitHub · Linux · server deployment · Prometheus · Grafana · Loki · Tempo · Alertmanager · OpenTelemetry · Sentry · Playwright · browser automation · quality engineering · MCP (Model Context Protocol) · evidence pipeline · Obsidian/vault-lint

**Additional:** Java · JavaScript · PHP · UML · prototyping · technical documentation · system integration · industrial protocols (EtherCAT, Modbus RTU) · AmneziaWG/VPN · network topology · incident response

**Previously in projects:** ActionScript, Adobe AIR/Flex, Flash Media Server, AWS, Drupal

---

## Projects and Channel

- Repositories: [github.com/ninelegsdog](https://github.com/ninelegsdog) (15+ public)
- AI development process: [agentic-development-playbook](https://github.com/ninelegsdog/agentic-development-playbook)
- Project review channel: [Ботоград · @BotogradPress](https://t.me/BotogradPress)

### «9 Bots» Series — typical business tasks in Telegram (production)

All nine bots run in production: webhook, TLS, health-check, autorestart, observability, backups. **Over 1000 tests** implemented.

| Bot | Task | Live |
|---|---|---|
| BookingBot | booking and slots, payment acceptance, double-booking protection | [@SaasBookingKitBot](https://t.me/SaasBookingKitBot) |
| LeadGenBot | lead collection and qualification, escalation, manager notifications | [@LeadgenKitBot](https://t.me/LeadgenKitBot) |
| StoreBot | catalog, cart, order placement, purchase history | [@StoreKitBot](https://t.me/StoreKitBot) |
| SupportBot | tickets, FAQ, SLA tracking by business hours | [@SaasSupportKitBot](https://t.me/SaasSupportKitBot) |
| MembershipBot | subscriptions, payment, access control, trial period | [@MembershipKitBot](https://t.me/MembershipKitBot) |
| ReminderBot | reminders and broadcasts by schedule with segmentation | [@ReminderKitBot](https://t.me/ReminderKitBot) |
| DocuFlowBot | document request, PDF generation, result delivery | [@DocuflowKitBot](https://t.me/DocuflowKitBot) |
| PriceSentryBot | scheduled price monitoring, change alerts | [@PricesentryKitBot](https://t.me/PricesentryKitBot) |
| DeliveryBot | delivery statuses, webhook event ingestion from external systems | [@DeliveryKitBot](https://t.me/DeliveryKitBot) |

Message any of them to see how they work.

### QualityForge — evidence-first browser QA

Public npm package `qualityforge@0.2.0`: normalised defect artefacts (trace, screenshot, video) in one schema, quality gate with thresholds, console/network/page-error signal capture, read-only MCP server. Evidence pipeline between a failing run and any agent. 15 test files, 13 documents, CI, four npm releases.

Repository: [github.com/ninelegsdog/qualityforge](https://github.com/ninelegsdog/qualityforge)

### «Дзен и агентная архитектура» — methodology book

Book about AI-native development method: context engineering, agent harness, verification and validation, drift, working with primary sources. 23 chapters and Prolog, 52,011 words, 35 sources, 2,149 links without broken ones, own build gate.

Repository closed until publication: edition provided on request.

---

## Work Format

- Task analysis and scope fixation before work begins.
- 50% prepayment, remainder upon acceptance.
- Turnkey work: scenarios, development, integrations, deployment, documentation.
- Support by agreement, with agreed response time.
