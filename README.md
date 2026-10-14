### Matheo Telesca

Full stack & AI engineer. I design and ship systems that run in production: AI agents that talk to real customers, retrieval pipelines you can audit, and multi-tenant SaaS with the guarantees pushed down to the database.

Currently building AI agents, automations and custom systems for US and LATAM businesses at **Telesca Solutions**. Also: AI & automation engineer on an internal CRM platform (lead-capture chatbot, AI email agent with human review). Before that, full stack developer on a 5-person team shipping billing, reporting and internal tools in PHP, React and MySQL.

📍 Mar del Plata, Argentina · remote, US/EU hours · English C1

---

#### Featured work

| Project | What it is | Engineering worth a look | Try it |
|---|---|---|---|
| **[Cuotaflow](https://github.com/MatheoTe/cuotaflow)** | AI agent on WhatsApp that qualifies loan applicants and runs a collections funnel, with its own CRM | Claude structured outputs + code-level guardrails the model can't override · webhook signature verification and idempotency · 142 tests and an offline eval suite | [Live demo](https://cuotaflow.vercel.app) |
| **[Citevia](https://github.com/MatheoTe/citevia)** | RAG over your documents where every claim links to the exact passage | Hybrid search (Postgres FTS + pgvector, fused with RRF) · per-stage traces with latency and cost · eval harness in CI: recall@k, MRR, citation precision, LLM-judged faithfulness | [Live demo](https://citevia.vercel.app) |
| **[Slotsmith](https://github.com/MatheoTe/slotsmith)** | Multi-tenant booking SaaS for service businesses | Tenant isolation with Postgres row-level security under a non-bypass role · double booking impossible via an exclusion constraint · DST-safe availability engine (100+ tests) · idempotent Stripe webhooks + transactional outbox | [Live demo](https://slotsmith.vercel.app) |
| **[Echolytics](https://github.com/MatheoTe/echolytics)** | Tracks how ChatGPT, Claude, Gemini and Perplexity mention a brand vs. its competitors | FastAPI + arq workers · Redis token-bucket rate limiting and circuit breakers per provider · idempotent fan-out · versioned re-analysis · load test: 6,000 simulated model calls in 28.7 s | [Live demo](https://echolytics.vercel.app) |

In production for clients (private code): a WhatsApp agent that answers patients and books appointments for a two-location healthcare group, plus the system they use to audit insurer billing.

---

#### How I work

- Model the problem before writing code; put invariants where they can't be skipped (constraints, RLS, typed boundaries).
- Treat LLMs as untrusted components: structured outputs, guardrails in code, evals before shipping, traces after.
- Small commits, tests that prove behavior, READMEs that explain the trade-offs.

#### Stack

**Languages** TypeScript · Python · PHP · SQL
**Backend** Node.js · Next.js · FastAPI · PostgreSQL (RLS, pgvector) · Redis · Supabase
**AI** Claude / OpenAI / Gemini APIs · RAG · agents & tool use · evals
**Infra** Vercel · Railway · Docker · GitHub Actions
**Integrations** WhatsApp Business API · Stripe · webhooks · n8n / Make

---

[LinkedIn](https://www.linkedin.com/in/matheo-telesca-084a20209/) · [Book a 15-minute call](https://calendar.app.google/LJRnCnT5S3ucadfb7)
