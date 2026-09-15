# Hi, I'm Shardar Rahman

**Senior Software Engineer · Technical Lead · Backend Architect — Fintech & Banking**

## About me

I'm a Senior Software Engineer and Technical Lead with 10+ years of experience building secure, scalable, and compliant platforms for fintech and banking. I design cloud-native, microservices-based systems on **.NET 10**, Java, Kotlin, and Angular, and I've delivered mission-critical services handling **1M+ daily transactions** in regulated UK financial environments (KYC, AML, GDPR, FCA).

- **Leading engineering at Mortgage Magic in London** — owning backend architecture, database design and API implementation across the platform
- **Currently migrating a legacy .NET Framework monolith to 12+ .NET 10 microservices**, alongside Java / Spring Boot services on AWS
- Built mortgage **origination, sourcing and lender-integration** platforms for the UK market — including automated affordability and regulated document generation (ESIS/KFI, evidence of research, recommendation letters)
- Designed the **commission reconciliation and distribution engine** — remittance matching with confidence scoring, clawback reversal across multi-level adviser / team-leader / director splits, self-billing, and a full FCA-grade audit trail
- **Built the engineering function from scratch** — established the development, QA and design teams, mentored engineers and grew several into team leaders
- **Own the cloud platform end to end** — self-managed AWS and GCP, networking, database replication, backup and disaster recovery, configuration and release management
- Comfortable across the stack: domain-driven backend architecture through to Angular / React front ends and AWS / GCP / IBM Cloud deployments

**Open to Senior, Technical Lead, Backend Architect and Lead Engineer roles in banking, fintech, mortgage technology, core banking and payments — London or remote.**

## Portfolio projects

Five hands-on projects that show how I actually design and build things. Each one is Clean Architecture, dockerised, CI-enabled, with a README that documents the trade-offs.

| Project | Stack | What it demonstrates |
|---|---|---|
| ⭐ **[core-banking-platform](https://github.com/hafiz5007/core-banking-platform)** | Java 21 · Kotlin · Spring Boot 3 · Kafka (KRaft) · gRPC · PostgreSQL · Testcontainers · Docker | **12-service reference banking architecture.** Immutable double-entry ledger with balancing invariant, transactional outbox → Kafka for effectively-once event delivery, JWT-secured gRPC between services, saga-based payments with compensating reversal, KYC/AML screening, per-service audit. `docker compose up` to full stack in under 3 min. **196 tests including 22 Testcontainers integration classes + CI smoke test asserting all 4 Kafka topics.** 17 ADRs + 12 service walkthroughs. |
| **[auth-dotnet](https://github.com/hafiz5007/auth-dotnet)** | .NET 10 · OpenIddict · Postgres · Redis · Docker | OAuth 2.0 / OIDC identity provider with immediate JWT revocation via tv-claim + Redis. Refresh-token rotation with reuse detection. Five-project Clean Architecture (Domain / Application / Infrastructure / Server / Resource-Api). |
| **[payments-ledger-demo](https://github.com/hafiz5007/payments-ledger-demo)** | Java 21 · Spring Boot 3 · Postgres · Kafka · Testcontainers | Double-entry accounting ledger with balancing invariant enforced in the type system. Effectively-once payment processing via idempotency + outbox pattern. Kafka consumer with DLT + relay worker. Four Gradle modules. |
| **[kyc-screening-service](https://github.com/hafiz5007/kyc-screening-service)** | Kotlin · Spring Boot 3 · MongoDB · Docker | Sanctions + PEP screening with framework-free domain sub-module (compiler-enforced dependency rule). Jaro-Winkler scoring with token-sort symmetry, DOB + country weighting. Explainable REVIEW / HIT decisions. |
| **[uk-address-lookup-service](https://github.com/hafiz5007/uk-address-lookup-service)** | .NET 10 · Minimal APIs · Docker | High-performance UK address lookup service — the same shape as a 30M+ record system I built at scale, rebuilt as a public reference. |

## Tech stack

<!-- Keep your existing badge blocks here — Languages & Frameworks, Cloud & DevOps, Databases & Data, Architecture & Practice -->

**Languages & Frameworks** — Java · Spring Boot · Kotlin · C# · .NET 10 · ASP.NET Core · TypeScript · React · Angular

**Cloud & DevOps** — AWS · GCP · Docker · Kubernetes · **GitHub Actions** · Azure DevOps · CI/CD · **Ubuntu Server** · **Nginx** · **HAProxy** · Cloudflare · **Certbot / Let's Encrypt** · Backup & DR

**Databases & Data** — **PostgreSQL (incl. AWS Aurora)** · SQL Server · Oracle · MySQL · **MongoDB (replica sets)** · **Redis (Sentinel)** · Elasticsearch · **Apache Kafka** · RabbitMQ

**Observability & Operations** — **Sentry** · Micrometer · Prometheus · Correlation-ID propagation · Structured logging · SLO / burn-rate alerting

**Architecture & Practice** — Microservices · Distributed Systems · Event-Driven Architecture · Domain-Driven Design · Clean Architecture · **gRPC** · **Outbox Pattern** · **Saga Pattern** · **JWT Service-to-Service** · Legacy Modernisation · Monolith Decomposition · **Test-Driven Development (TDD)** · **Testcontainers**

## Career highlights

Production systems shipped over 10+ years, primarily at Mortgage Magic in London:

| Domain | What I built | Scale & impact |
|---|---|---|
| **Legacy Modernisation** | Migration of a legacy .NET Framework monolith to .NET 10 microservices | 12+ services, regulated platform |
| **Mortgage & Lending** | End-to-end origination and sourcing platforms integrated with major UK lenders | Live across multiple UK lenders |
| **Commission Reconciliation** | Remittance matching, clawback reversal across multi-level splits, self-billing, audit trail | FCA-grade, production |
| **High-Volume Transactions** | Distributed, fault-tolerant payment & processing platform | 1M+ transactions / day, 99.9%+ uptime |
| **UK Address Lookup** | High-performance lookup service across the full UK address graph | 30M+ records, sub-100ms |
| **KYC & AML** | Identity verification, PEP and sanctions screening, audit-ready workflows | FCA / GDPR aligned |
| **Financial Data Integrations** | TransUnion, Experian, Twenty7Tec, iPipeline, Assureweb | Production integrations |
| **Cloud & Infrastructure** | Self-managed AWS + GCP — networking, replication, backup & DR, release management | Automated end to end |
| **Engineering Leadership** | Built the development, QA and design teams from scratch | Engineers grown into team leaders |
| **UAE VAT Compliance** | Accounting and VAT filing platform (VATBOX), delivered ahead of the UAE's January 2018 VAT regime | Business scaled to three branches |

## GitHub stats

<!-- Keep your existing stats cards here -->

## Get in touch

I'm currently open to **Senior, Technical Lead, Backend Architect and Lead Engineer** roles in banking, fintech, mortgage technology, core banking and payments.

- **LinkedIn** — [linkedin.com/in/hafizrahmanuk](https://www.linkedin.com/in/hafizrahmanuk)
- **Email** — smhrcse@gmail.com
- **LeetCode** — [leetcode.com/hafiz5007](https://leetcode.com/hafiz5007)
