# Islam Duishobaev

**Python Backend Developer** — APIs · Automation · Telegram Integrations

I build production-grade Python backends: REST APIs, async task pipelines, and Telegram bot integrations.
My focus is clean architecture, separated business logic, and systems that are ready for real workloads.
Currently open to remote backend roles.

**Stack:** Python · Django · DRF · FastAPI · Celery · Redis · PostgreSQL · Aiogram · Docker

---

## Featured Projects

### Real Estate CRM — Lead & Agent Pipeline

**Problem:** Real estate teams needed automated lead qualification and agent KPI visibility in one system.

**Built:** REST API with a multi-stage lead pipeline, OpenAI-powered lead scoring, SendGrid transactional email, Telegram webhook bot for agent notifications, and Railway deployment with async Celery workers.

**Result:** A production CRM with real-time AI scoring, Redis queuing, custom Django admin dashboards with KPI charts and bulk actions.

`Django` `DRF` `Celery` `Redis` `OpenAI` `SendGrid` `PostgreSQL` `Railway`

---

### Educational Testing Platform — OkurmenKids

**Problem:** Schools needed a gamified testing tool usable without student accounts or logins.

**Built:** Session-key identity system (no auth required), 4 in-browser games, XP/badge/leaderboard engine, timed exam flow, GigaChat-powered AI grading, and a vanilla JS admin dashboard.

**Result:** 16-model Django backend + React/Zustand frontend with full gamification and zero-friction student onboarding.

`Django` `DRF` `React` `Zustand` `PostgreSQL` `GigaChat API`

---

### AI Answer Grading Pipeline

**Problem:** Manual grading of open-ended exam answers was a bottleneck at scale.

**Built:** Async Celery pipeline that sends answers to a GigaChat LLM on submission (signal-driven), returns a score + feedback, and surfaces results in an admin metrics dashboard.

**Result:** Fully automated open-answer evaluation — zero manual review needed for standard responses.

`Django` `Celery` `Redis` `GigaChat API` `PostgreSQL`

---

## What I'm Building Next

**SaaS Webhook Dispatcher** — FastAPI service that receives webhooks from Stripe/GitHub/any provider, queues with Celery, retries with exponential backoff, and delivers to client URLs with a status dashboard.

**Multi-Tenant REST API Boilerplate** — Production-ready FastAPI template with JWT auth, role-based access control, multi-tenancy, rate limiting, and complete OpenAPI docs.

---

## Contact

[Telegram](https://t.me/duishobaevislam01) · [Email](mailto:duishobaevislam01@gmail.com) · [GitHub](https://github.com/Islam0122)
