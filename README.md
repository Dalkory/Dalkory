# .NET Backend & AI Readiness Audits

I help teams turn difficult ASP.NET Core repositories into a clear, prioritized engineering plan.

My audits are fixed-scope and asynchronous. I review the codebase, validate the highest-risk areas, and deliver evidence-backed findings that a team can act on without a long consulting engagement.

[![Telegram](https://img.shields.io/badge/Telegram-Discuss_an_audit-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/daniildotnet)

## What I review

- architecture, boundaries, dependency direction, and maintainability;
- ASP.NET Core composition, DI, configuration, error handling, and logging;
- EF Core and SQL usage, query shape, transactions, indexes, and data-access risks;
- performance, concurrency, background processing, and reliability;
- authentication, authorization, secrets, dependencies, and baseline security hygiene;
- unit/integration tests, CI/CD, Docker, and local reproducibility;
- repository readiness for Codex, Copilot, and other AI coding agents.

## What you receive

1. A concise architecture map.
2. Prioritized findings with evidence, impact, and recommended action.
3. A backlog grouped into **fix now**, **next sprint**, and **later**.
4. An implementation-effort estimate for every finding.
5. A written report and a recorded walkthrough.

The service is a technical codebase audit, not penetration testing or a guarantee that every security vulnerability will be found.

[View a public sample audit report](https://github.com/Dalkory/PadelTrialSchedule/blob/main/docs/sample-audit-report.md)

## A practical first step

**Pilot audit**

- one ASP.NET Core service or repository, usually up to 30â€“50k lines;
- 5â€“7 high-value findings;
- short report and video walkthrough;
- delivery in three business days;
- no code changes and no long-term commitment.

Deeper audits and implementation work can follow only when the pilot shows clear value.

## Selected .NET work

| Repository | What it demonstrates |
|---|---|
| [PadelTrialSchedule](https://github.com/Dalkory/PadelTrialSchedule) | ASP.NET Core 10, EF Core, PostgreSQL, React, Docker, CI, accessibility, and Testcontainers integration tests |
| [MarketDataAggregator](https://github.com/Dalkory/MarketDataAggregator) | WebSocket ingestion, normalization, bounded deduplication, batching, reconnect behavior, PostgreSQL, and load-focused tests |
| [PromoOS](https://github.com/Dalkory/PromoOS) | ASP.NET Core notification service with JWT, EF Core, background email delivery, validation, and integration tests |
| [StrideFlow](https://github.com/Dalkory/StrideFlow) | ASP.NET Core 8, PostgreSQL, Redis, SignalR, token rotation, rate limiting, and end-to-end tests |

## AI readiness is more than adding a prompt file

I check whether an AI coding agent can safely understand, build, test, and change the repository:

- clear architecture and ownership boundaries;
- a reproducible local setup;
- deterministic build, test, lint, and migration commands;
- focused repository instructions and conventions;
- fast feedback through tests and CI;
- safe configuration and secret handling;
- tasks that can be decomposed and verified without hidden context.

## Working style

```text
Communication: asynchronous first
Response time: within 4 business hours
Meetings: by appointment
Project updates: once per business day
```

I am a C#/.NET backend developer with product and international development experience. My core stack includes ASP.NET Core, EF Core, PostgreSQL, Redis, RabbitMQ, Kafka, Docker, Kubernetes, and CI/CD.

If you want a second opinion before a refactor, migration, hiring push, or AI-assisted development rollout, [message me on Telegram](https://t.me/daniildotnet) with the repository size, .NET version, and the three problems you care about most.

