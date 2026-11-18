<h1 align="center">Jose Sleiter Rios</h1>

<p align="center">
  <strong>Senior Software Engineer</strong> · Distributed systems, cloud &amp; full-stack<br/>
  Bucaramanga, Colombia (GMT-5) · Remote for teams in 🇺🇸 🇲🇽 🇨🇱 🇨🇴 🇪🇸 🇬🇧
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jose-sleiter-rios/">LinkedIn</a> ·
  <a href="mailto:sleiter.js@gmail.com">Email</a> ·
  <a href="https://github.com/JoseSleiter/ai-cv-tailor">CV</a>
</p>

---

Eight years building systems that stay up and stay fast. I like the unglamorous half of
the job: the migration that can't drop a request, the query that was costing 400ms, the
test suite that has to be trusted enough to block a merge.

### What I've actually shipped

- **Multi-tenant platform for 50k+ active users** — leading the rewrite of a university
  management system onto Ruby on Rails 8 and Python microservices. Designed
  **schema-per-tenant isolation in PostgreSQL** resolved by subdomain, so no request can
  read another institution's data.
- **8s → 1.5s page load (81% faster)** — rebuilt a corporate e-learning partner portal in
  Next.js with static generation. SEO score 85 → 91.
- **~400 Playwright flows as a mandatory merge gate** — an E2E regression suite wired into
  GitLab CI / GitHub Actions, sustaining **99.8% deployment reliability**. Tests nobody
  skips are the only tests that matter.
- **35% lower API latency** — Redis caching layers and MySQL query work on a
  high-concurrency fleet management system for Carabineros de Chile.
- **Event-driven microservices in production** — Python (Flask) and Node services behind a
  Kong gateway, RabbitMQ, and the **Saga pattern** for transaction consistency.

### Stack

**Languages** &nbsp;TypeScript · Python · JavaScript · SQL · Ruby

**Backend** &nbsp;Node.js · NestJS · Express · Flask / FastAPI · Ruby on Rails · REST &amp; GraphQL · Microservices · RabbitMQ · Kong Gateway

**Frontend** &nbsp;React · Next.js · Redux · React Native · Vue.js · Tailwind CSS · Hotwire

**Data** &nbsp;PostgreSQL (multi-tenant schema isolation) · MySQL · Redis · MongoDB · Azure Cosmos DB

**Cloud &amp; DevOps** &nbsp;AWS (EC2, Lambda, S3, Textract) · Azure (Functions, Blob, API Gateway) · Docker · Kubernetes · GitHub Actions · GitLab CI/CD

**Testing** &nbsp;Playwright · Jest · Vitest · RSpec

### Things worth opening

| | What it shows |
|---|---|
| **[ai-cv-tailor](https://github.com/JoseSleiter/ai-cv-tailor)** | A local-first tool that tailors my CV to a job posting. The AI never writes markup — it emits a typed object validated by a guard that **rejects invented companies, dates or skills**. Bounding a generative model with a type contract. |
| **[pool-pass](https://github.com/JoseSleiter/pool-pass)** | Booking PWA with Pago Móvil C2P payments in VES at the official BCV rate. Capacity is held by a **Postgres advisory lock inside the reservation transaction**, so two people cannot take the last slot. |
| **[02-api-ocr](https://github.com/JoseSleiter/02-api-ocr)** | Invoice OCR in NestJS with **two interchangeable engines behind one interface** — AWS Textract and local Tesseract — and locale-aware number parsing, because `1.234,56` and `1,234.56` are the same amount. |
| **[serverless-sns](https://github.com/JoseSleiter/serverless-sns)** | Fan-out on AWS: three Lambdas chained through an SNS topic. Publish and forget; the topic routes. |
| **[rabit-send](https://github.com/JoseSleiter/rabit-send) + [rabit-receive](https://github.com/JoseSleiter/rabit-receive)** | Producer and consumer as **two separate deployables**, because that is the only way to actually show the broker doing its job. |

### Right now

Deep in a Rails 8 rewrite of a multi-tenant platform, and building tooling that puts LLMs
behind type contracts instead of trusting their prose.

**Languages:** Spanish (native) · English (B2+, professional working proficiency)

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=JoseSleiter&show_icons=true&hide_border=true&hide=contribs&card_width=420" />
</p>
