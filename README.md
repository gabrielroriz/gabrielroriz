# Hi, I'm Gabriel Roriz 👋

**Senior Software Engineer & Tech Lead** — Backend · Full-Stack · AWS Serverless · Payments & Subscriptions

I've spent 8+ years building the parts of a product that have to be right: identity, subscriptions, billing, and access control, with Node.js, TypeScript, and AWS. I'm currently Tech Lead at [NexAtlas](https://nexatlas.com), leading the Account platform behind a flight-planning app for general aviation.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gabriel--roriz-informational?style=flat&logo=linkedin&logoColor=white&color=2bbc8a)](https://www.linkedin.com/in/gabriel-roriz/)
[![Email](https://img.shields.io/badge/Email-ogabrielroriz%40gmail.com-informational?style=flat&logo=gmail&logoColor=white&color=2bbc8a)](mailto:ogabrielroriz@gmail.com)
![Location](https://img.shields.io/badge/Based_in-Brazil_%28GMT--3%29-informational?style=flat&logo=googlemaps&logoColor=white&color=2bbc8a)

---

## 🔭 What I'm working on

- ✈️ **Account platform at NexAtlas** — identity, subscriptions, billing, and access control for 100,000+ accounts and 6,000+ paying subscribers.
- 💳 **Resilient payments** — idempotent, order-tolerant webhook processing across gateways and currencies on AWS serverless ([see below](#-featured-projects)).
- 🤖 **AI-assisted engineering** — Claude Code, GitHub Copilot, and agentic workflows, plus the review habits that keep quality high.

## 🏗️ Highlights

- **Zero-downtime subscription re-architecture** · *NexAtlas* — Redesigned the subscription schema from a single-market model to multi-country, multi-language, and multi-pricing, migrating 20,000+ historical subscriptions through dual writes and reversible migrations.
- **Capability-based entitlements** · *NexAtlas* — Designed an RBAC + ABAC access model that enforces limits per product and per device.
- **Account Office & business metrics** · *NexAtlas* — Built a NestJS + React 19 back office that replaced direct phpMyAdmin operations with audited workflows and atomic batch license grants, plus the company's metrics system with versioned SQL definitions, an immutable fact table, and nightly extraction.
- **Serverless membership platform** · *BARCA* — As sole technical owner, rebuilt a Wix MVP into an AWS serverless platform for ~8,000 active subscribers (company-reported), and built the renewal automation behind a campaign the company reports brought in R$1M+.
- **Payments that survive failure** · *BARCA* — Idempotent webhooks, saga-based compensation, SQS pipelines with dead-letter queues and audit checkpoints, and the full Cognito identity lifecycle with refresh-token rotation and RBAC.
- **Earlier** — Led a frontend team on a React gaming-rewards platform at Joysticket, built Django REST APIs for agricultural irrigation monitoring at Irricontrol, and paired operations leadership with Node.js and Go automation at Invisible.

## 🚀 Featured projects

### 💳 [aws-resilient-payment-flow](https://github.com/gabrielroriz/aws-resilient-payment-flow) — *payment webhooks that stay correct*

Payment providers deliver webhooks late, twice, or out of order; this project makes sure that never grants access without payment, credits a customer twice, or loses a refund. It targets multiple gateways and currencies on AWS serverless. The foundation is in place: hexagonal architecture with dependency injection, Terraform-provisioned Lambdas behind API Gateway, and CI on GitHub Actions. The event pipeline is in progress.
`TypeScript · AWS Lambda · API Gateway · Terraform · Vitest`

### 🎯 [focusd](https://github.com/gabrielroriz/focusd) — *deep-work mode for Linux*

Blocks distracting sites by managing `/etc/hosts` in two tiers: domains that stay blocked, and ones you can unlock from the CLI for up to 10 minutes before they re-lock automatically. Runs as a systemd service that watches user sessions, with domain lists organized by category.
`Bash · systemd · D-Bus · Linux`

---

## 🛠️ Tech I work with

![TypeScript](https://img.shields.io/badge/Code-TypeScript-informational?style=flat&logo=typescript&logoColor=white&color=2bbc8a)
![Node.js](https://img.shields.io/badge/Code-Node%2Ejs-informational?style=flat&logo=nodedotjs&logoColor=white&color=2bbc8a)
![NestJS](https://img.shields.io/badge/Code-NestJS-informational?style=flat&logo=nestjs&logoColor=white&color=2bbc8a)
![Python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=2bbc8a)
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=openjdk&logoColor=white&color=2bbc8a)
![React](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&logoColor=white&color=2bbc8a)
![Next.js](https://img.shields.io/badge/Code-Next%2Ejs-informational?style=flat&logo=nextdotjs&logoColor=white&color=2bbc8a)
![AWS](https://img.shields.io/badge/Cloud-AWS-informational?style=flat&logo=amazonwebservices&logoColor=white&color=2bbc8a)
![Serverless](https://img.shields.io/badge/Cloud-Serverless-informational?style=flat&logo=serverless&logoColor=white&color=2bbc8a)
![Terraform](https://img.shields.io/badge/IaC-Terraform-informational?style=flat&logo=terraform&logoColor=white&color=2bbc8a)
![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=2bbc8a)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-informational?style=flat&logo=githubactions&logoColor=white&color=2bbc8a)
![PostgreSQL](https://img.shields.io/badge/DB-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=2bbc8a)
![MySQL](https://img.shields.io/badge/DB-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=2bbc8a)
![DynamoDB](https://img.shields.io/badge/DB-DynamoDB-informational?style=flat&logo=amazondynamodb&logoColor=white&color=2bbc8a)
![Redis](https://img.shields.io/badge/DB-Redis-informational?style=flat&logo=redis&logoColor=white&color=2bbc8a)
![Linux](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=2bbc8a)
![Claude Code](https://img.shields.io/badge/AI-Claude_Code-informational?style=flat&logo=claude&logoColor=white&color=2bbc8a)
