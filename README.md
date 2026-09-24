# Sohaib Ahsan

**Lead Technical Architect** — production distributed systems, and the infrastructure that lets AI agents work on them safely.

Manchester, UK · [forenax.com](https://forenax.com) · [LinkedIn](https://www.linkedin.com/in/sohaib-ahsan/) · [sohaibahsan007@live.com](mailto:sohaibahsan007@live.com)

Eight years shipping backend systems across fintech, Web3 and AI infrastructure. Sole engineer on a multi-tenant cloud platform running in five data centres, measured at 99.95% availability over 90 days. Six merged PRs into LoopBack 4. Co-author of three IEEE-formatted papers.

## Now

**STORE Cloud** — a self-hosted multi-tenant cloud platform across five data centres (Santa Clara, Ashburn, Toronto, Melbourne, Sydney). I own architecture through to on-call: a 20-module NestJS monorepo, 15 LoopBack 4 microservices, a 5-node private IPFS cluster, PostgreSQL 16, Redis, RabbitMQ, Kubernetes, Cloudflare edge routing, and OpenTelemetry tracing end to end. In Q1 2026 that meant nine platform modules and four protocols shipped, including a single payment pipeline across Stripe, BitGo, Persona KYC and Adobe Sign that passed community testing at 9.5/10 with zero production bugs.

**AI development infrastructure** — an internal governance framework built on Claude: 83 enforceable gates, 87.9% verified human control, a designated adversarial reviewer, and a post-hoc audit gate. It is now the standard for production work at STORE. Alongside it, an autonomous software factory where each project runs in an isolated container that clones, branches, implements, tests and opens PRs, with a human approving every merge.

## What's public

Most of what I ship lives in private production repositories — the contribution graph below and 2,900+ merged pull requests are the trace. What you can read:

- **LoopBack 4** — [six merged PRs](https://github.com/loopbackio/loopback-next/pulls?q=is%3Apr+author%3Asohaibahsan007+is%3Amerged) into the framework's CLI: model discovery options, relation generation, a read-only CRUD generator, and an OpenAPI URL resolution fix. A [Redis cache example](https://github.com/loopbackio/loopback-next/pull/8397) (49 files) is still open upstream. The same framework now runs five STORE production services.
- [**d3Charts**](https://github.com/storecloudproject/d3Charts) — ECharts treasury chart library for STORE's public site. 328 commits, sole author.
- [**metric-aggregator-service**](https://github.com/sohaibahsan007/metric-aggregator-service) — metric ingestion and aggregation over an API. LoopBack 4, Swagger, Docker.
- [**org-chart**](https://github.com/Forenax-Technologies/org-chart) — D3 org chart, extended with Angular, React and Vue integrations.

## Research

- [Enabling Autonomous Computing Through Decentralized Cloud ID Generation](https://doi.org/10.36227/techrxiv.172418072.28723931/v1) — CUID2 with ECDSA-secp256k1 binding and BlockFinBFT consensus. Productionised as STORE's Cloud ID service. With Chris McCoy and Rag Bhagavatha; IEEE TechRxiv.
- *Gasless and Multi-currency Payments in Decentralized Computing* and *CLEAR: Compliance and Legal Economy Architecture Rails* — IEEE-formatted, with Chris McCoy. CLEAR is where the 99.95% figure comes from, alongside 55.6 seconds end to end against 6–15 business days for the equivalent banking process.

## Before this

Founded **Forenax Technologies**, a UK consultancy — profitable from year two, 12+ client engagements including Midtrans, Zed Run, Mintel and DOiFund. Built SMIELS, a B2B SaaS on eight LoopBack 4 microservices that reached 30 paying customers. Three years as a full-stack developer at Community Software Group, a US enterprise SaaS vendor whose products serve 200+ government and social-service agencies.

## Get in touch

I'm interested in hard backend and platform problems at staff level, and in talking to founders building infrastructure. Email is fastest.
