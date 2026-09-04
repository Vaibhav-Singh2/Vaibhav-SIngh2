<h1 align="center">Vaibhav Singh</h1>

<h3 align="center">Full Stack Developer | React.js / Next.js | Node.js / Express.js | AWS</h3>

<p align="center">
  Open to <b>Full Stack Developer</b> roles — <b>Bengaluru (Hybrid / Onsite)</b>.  
  I build production-grade web, mobile, and AI-integrated platforms end-to-end — <b>React.js/Next.js frontends</b> and <b>Node.js/Express backends</b> — with MongoDB, Redis, Docker, and AWS.
</p>

<p align="center">
  <b>Available for freelance, contract, and full-time opportunities.</b>
</p>

<div align="center">
  <a href="https://drive.google.com/file/d/1fiQ90lUM58gTRukPd_BPRsjdRD-pj1a6/view?usp=sharing" target="_blank"><img src="https://img.shields.io/static/v1?message=Resume&logo=readme&color=6A5ACD&style=for-the-badge" height="28" /></a>
  <a href="https://vaibhav-fullstack-dev.vercel.app" target="_blank"><img src="https://img.shields.io/static/v1?message=Portfolio&logo=googlechrome&color=4285F4&style=for-the-badge" height="28" /></a>
  <a href="https://www.linkedin.com/in/vaibhav-singh-o-o" target="_blank"><img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&color=0077B5&style=for-the-badge" height="28" /></a>
  <a href="https://github.com/Vaibhav-Singh2" target="_blank"><img src="https://img.shields.io/static/v1?message=GitHub&logo=github&color=181717&style=for-the-badge" height="28" /></a>
  <a href="mailto:vaibhav.fullstack.dev@gmail.com" target="_blank"><img src="https://img.shields.io/static/v1?message=Email&logo=gmail&color=D14836&style=for-the-badge" height="28" /></a>
  <a href="https://wa.me/917906115972" target="_blank"><img src="https://img.shields.io/static/v1?message=WhatsApp&logo=whatsapp&color=25D366&style=for-the-badge" height="28" /></a>
</div>

---

### 🚀 Summary

Full Stack Developer with **1 year 9 months** of hands-on experience shipping production systems end-to-end — from **React.js/Next.js frontends** to **Node.js/Express backends** — across startup environments. Sole-built **Drishti**, an omnichannel AI customer engagement platform, ground-up: frontend, backend, and infra — 3,652 messages processed, 40–70% cost reduction vs. BSPs, lead response time cut from 12 hours to 30 seconds. Also built and deployed **ObservabilityOS** — a live AI-native observability SaaS with a published npm SDK, 4-tier LLM failover pipeline, and Z-score statistical anomaly detection. Comfortable owning the full request lifecycle: REST API design, database/caching layer, Docker + AWS deployment, and CI/CD — alongside the reusable, accessible UI that consumes those APIs. Currently based in Mathura, actively looking for **Bengaluru (Hybrid / Onsite)** roles.

---

### 🏆 Top Achievements

- Architected and sole-built **Drishti** end-to-end — Next.js SSR frontend, Node.js/Express backend — an omnichannel AI platform replacing third-party BSPs, cutting monthly messaging costs **40–70%** while sustaining **99.8% delivery reliability** across 3,652 messages.
- Shipped user-facing **Next.js SSR** pages with UTM-based attribution tracking, driving a **35% increase in user engagement**.
- Engineered **ObservabilityOS** — AI-native observability SaaS with npm SDK, 4-tier LLM failover, and Z-score anomaly detection.
- Published **create-saas-app-cli** on npm scaffolding production-ready SaaS monorepos in under 60 seconds across 36+ permutations.
- Built **Sentinel** — distributed HTTP reverse proxy sustaining ~6,800 req/s at p99 41ms with Redis-based circuit breaking.
- Reduced P95 API latency from 800ms to 480ms (40% improvement) via MongoDB index optimization and Redis caching at Vize.
- Achieved **99.9% uptime** and **zero-downtime releases** with Docker + GitHub Actions CI/CD on AWS EC2.

---

### 💼 Professional Experience

#### Full Stack Developer — MaxFate Private Limited _(June 2025 – Present)_

- Owned and shipped user-facing **Next.js SSR** pages end-to-end — from UI implementation through backend and production support — adding UTM-based attribution tracking that drove a **35% increase in user engagement**.
- Architected and sole-developed **Drishti** — omnichannel AI customer engagement platform (WhatsApp, Facebook, Instagram) built directly on Meta APIs, replacing WATI/AISensy BSPs and achieving **40–70% monthly cost reduction**; processed **3,652 messages at 99.8% delivery reliability** with 24.6M LLM tokens in 16 days live.
- Engineered multi-LLM AI agent (Claude 3.5 Sonnet / GPT-4o / Gemini 1.5 Pro) with agentic tool-calling loop and Qdrant RAG pipeline surfacing live Zoho CRM/Books data — **89.7% AI auto-pilot rate** (245/273 threads), lead response time cut from **12 hours to 30 seconds**.
- Diagnosed and resolved live hallucination bug by rebuilding pipeline with typed tool calls enforcing real data fetches before any reply; zero hallucination incidents in 16 days post-fix.
- Implemented queue-first webhook architecture (BullMQ + Redis) meeting Meta's 2-second SLA; 3-stage Docker build with Bun runtime; GitHub Actions FIFO deployment lock — **zero interrupted deployments** across 163 commits.
- Refactored sync report API to async BullMQ pipeline, reducing latency by **40%**; system processes **500+ daily requests at 99.9% uptime**.

#### App Developer (React Native & MERN) — Vize _(October 2024 – June 2025)_

- Implemented full-stack auth (JWT, OAuth2, Firebase Google Sign-In, phone OTP) across React web and React Native; **sole mobile developer** — shipped cross-platform app (iOS & Android) with 15+ screens end-to-end.
- Designed and owned **30+ production REST APIs** serving 1,000+ daily requests for a consultation platform with 200+ active users.
- Resolved P95 latency regression (800ms → 480ms, **40% improvement**) via MongoDB index optimization and Redis caching — independently identified root cause without senior support.
- Integrated Razorpay handling 100+ monthly transactions with webhook signature verification and idempotent order reconciliation.

---

### 📚 Projects

#### Drishti — AI-Powered Customer Engagement Automation Platform · TypeScript, Node.js, Bun, Next.js, BullMQ, Redis, MongoDB, Qdrant, OpenAI/Claude/Gemini APIs, Meta Business APIs, AWS EC2, Docker
[GitHub](https://github.com/Vaibhav-Singh2/drishti-marketing-os-showcase) · [Demo video](https://drive.google.com/file/d/1qsN0ZLRJXgkSQzIgWk0Hy7fjwcmx8TiG/view?usp=sharing)

A production WhatsApp/Facebook/Instagram operator platform built directly on Meta Business APIs (no BSP), replacing WATI/AISensy subscriptions. Built and maintained as three connected pieces:

- **Drishti Chat (AI Engine):** Multi-LLM AI switchboard via Abstract Factory pattern (`IAIProvider`) for runtime Claude/GPT-4o/Gemini swap; agentic tool-calling loop fetches live Zoho CRM/Books data before composing replies; Qdrant RAG pipeline with Redis-cached CRM lookups (30-min TTL). Processed **3,652 messages** at **99.8% delivery rate** with 24.6M LLM tokens in 16 days live, **89.7% AI auto-pilot rate** — **40–70% monthly cost reduction** vs. BSPs.
- **Drishti Website & Core Backend:** Next.js web funnels and backend automating the full post-purchase lifecycle — Razorpay payment verification → Zoho CRM/Books sync → report generation → discovery-call scheduling.
- **Drishti Mobile App & Backend Integration:** Cross-platform Vedic astrology app (Expo/React Native) with its dedicated mobile backend — WhatsApp OTP auth, reusable birth profiles, live-slot consultation booking, automated push notifications, and a resilient two-stage Razorpay payment verification flow.
- Shipped TOTP 2FA, HttpOnly Secure JWT cookies, bcrypt hashing; MCP-standard analytics endpoint; FIFO CI deployment lock. 163 commits, one developer — first live message delivered **6 days after first commit**.

#### ObservabilityOS — Monitoring, Logging & AI-Powered Incident Resolution Suite · TypeScript, Next.js, React 19, MongoDB, Redis, BullMQ, Anthropic Claude / OpenAI GPT-4o, Turborepo, Docker, Stripe, Razorpay, Resend, Zod
[GitHub](https://github.com/Vaibhav-Singh2/ObservabilityOS) · [observabilityos.in](https://www.observabilityos.in) · [npm](https://www.npmjs.com/package/@observability-os/sdk)

- Built and deployed a full AI-native observability SaaS in a Turborepo monorepo (dashboard, docs, chaos simulator apps + 4 shared packages), featuring AI-generated incident descriptions and resolution suggestions alongside real-time monitoring and structured logging; published `@observability-os/sdk` to npm — a production TypeScript logger SDK with in-memory batching, configurable flush intervals, concurrency-safe `activeFlushPromise` guard, retry-on-failure log reinsertion, and `timer.unref()` for process lifecycle hygiene.
- Engineered a **Z-score statistical anomaly engine** computing rolling standard deviations over **12 consecutive 5-minute windows** for error rate, CPU, and latency simultaneously; correlates anomaly spikes with recent deployment commits and enforces incident deduplication with 15-minute cooldown logic.
- Designed a **4-tier LLM failover pipeline** (AICredits gateway → Anthropic Claude 3.5 Haiku → OpenAI GPT-4o-mini → deterministic heuristics) with per-provider stateful circuit breakers, `AbortController` request timeouts, exponential backoff with jitter, per-token cost accounting, and plan-aware free-tier bypass.
- Implemented Redis sorted-set sliding-window rate limiting with in-memory fallback; dual-layer caching (Redis L2 + in-memory L1); Redis Pub/Sub real-time log streaming; dual payment billing (Stripe + Razorpay) with plan-gated quota enforcement.
- Maintained 72 automated tests across 14 suites (Vitest + Playwright E2E) and enforced Lighthouse CI performance/accessibility gates on every PR.

#### Sentinel — Adaptive Load Control & Fault-Tolerant Reverse Proxy (Kubernetes) · TypeScript, Bun, Fastify, Redis, Docker, Kubernetes, Prometheus, OpenTelemetry, Jaeger, Pino
[GitHub](https://github.com/Vaibhav-Singh2/sentinel-resilience-gateway)

- Built open-source HTTP reverse proxy sustaining **~6,800 req/s at p99 41ms** (Bun + Fastify); hybrid rate limiter (in-memory token bucket fast-path + Redis sliding window via atomic Lua scripts) correctly **blocked 99.5% of burst-overload traffic** (13,749 of 13,820 requests under 200-connection load).
- Distributed circuit breaker with Redis Pub/Sub cross-pod synchronization; once tripped, **fast-failed 99.6% of requests** (17,500 blocked, ~42ms avg); weighted adaptive pressure model stable at **pressure score 0.28 under 1,500 req/s sustained load** with zero false throttling events.
- Full observability pipeline: Prometheus RED metrics + SLO violation counters, OpenTelemetry OTLP traces to Jaeger, Pino structured logging with correlation IDs; Kubernetes deployment with HPA; validated across 5 autocannon scenarios, 75+ seconds, 145,000+ requests.

#### create-saas-app-cli · Node.js, TypeScript, Turborepo, BullMQ, Redis, PostgreSQL, MongoDB, Drizzle ORM, Prisma, Docker, GitHub Actions

- Published open-source CLI (`npx create-saas-app-cli`) with **40+ npm downloads**; scaffolds a production-ready multi-tenant SaaS Turborepo monorepo in under 60 seconds across **36+ permutations** (4 DB/ORM combos, 3 package managers, BullMQ, Redis, JWT auth, Prometheus + Grafana, Razorpay).
- Template-as-code architecture (pure TypeScript template functions, zero static assets); composable feature toggles per prompt; publish gate enforcing `build` → `test:ci` → `pack --dry-run` before any `npm publish` — eliminates **1–3 days of SaaS setup boilerplate** per project.

#### AeroForge Labs — eCommerce Platform · TypeScript, Next.js 16 (App Router), React 19, Redux Toolkit, Tailwind CSS v4, Radix UI, Prisma / MongoDB Atlas, Razorpay
[GitHub](https://github.com/Vaibhav-Singh2/aeroforge-ecommerce) · [Live Demo](https://aeroforge-labs.vercel.app/)

- Built a full-stack eCommerce web application — catalog, cart, checkout, account dashboard — across **19 responsive pages**, **23 Server Actions**, and **13 REST API routes** on Prisma/MongoDB Atlas.
- Built a mobile-first, cross-browser storefront UI with **55 reusable components** (Radix UI + Tailwind) and a Redux Toolkit cart; integrated Razorpay checkout with HMAC-SHA256 webhook verification and Zod/React Hook Form validation.

---

### 🛠️ Technical Skills

**Core Stack:** Node.js · TypeScript · JavaScript (ES6+) · React.js · Next.js · Express.js · Fastify · Bun · MongoDB · Redis · PostgreSQL · MySQL · AWS · Docker · React Native · Flutter (Dart)

**Frontend & Mobile:** React.js · Next.js (SSR) · Redux Toolkit · Tailwind CSS · Radix UI · React Hook Form · Zod · HTML5 · CSS3 · Component-Based & Reusable UI Architecture · Responsive Design · Accessibility (WCAG, ARIA) · Figma-to-Code

**Backend & System Design:** RESTful API Design · API Versioning · Scalable Architecture · Async Job Processing · BullMQ · WebSockets/Socket.io · Webhook Handling · Rate Limiting · Circuit Breaking · Microservices · System Design · OpenAI / Claude / Gemini API Integration · RAG Pipelines · Agentic Tool-Calling · MCP SDK · Payment Gateway Integration

**Databases & Caching:** MongoDB (Aggregation Pipeline, Indexing, Sharding, Replica Sets) · Redis (Caching, Pub/Sub, Rate Limiting, Sorted Sets) · PostgreSQL · MySQL · Qdrant (Vector DB) · Prisma ORM · Mongoose ORM · Drizzle ORM · Query Optimization

**Cloud, DevOps & Observability:** AWS (EC2, S3, ECR, IAM, VPC, CloudWatch, Secrets Manager) · Docker · Docker Compose · Kubernetes (K8s, HPA) · GitHub Actions · CI/CD Pipelines · Nginx · Linux · Zero-Downtime Deployment · Cloudflare R2 · Vercel Blob · Prometheus · Grafana · OpenTelemetry · Turborepo · Winston · Structured Logging · SLO Monitoring · Monorepo Architecture

**Auth & Security:** JWT · OAuth2 · Firebase Auth · Clerk · API Key Authentication · TOTP 2FA · HttpOnly Secure Cookies · bcrypt · OWASP Top 10 · Input Validation · PII Scrubbing

**Testing & QA:** Jest · Vitest · Playwright (E2E) · Lighthouse CI · Postman

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Vaibhav-Singh2&theme=dracula&hide_border=false&border_radius=5" height="160" alt="streak graph" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Vaibhav-Singh2&theme=dracula" height="160" alt="github stats" />
</div>

---

### 🏅 Certifications

- Full Stack Development (MERN) – Cisco thingQbator @ IIT BHU
- React & Redux Certification – Complete Coding

---

### 🎓 Education

**Master of Computer Applications (MCA)** – GLA University (Distance / Correspondence)
2026 – 2028

**Bachelor of Computer Applications (BCA) – Computer Science** · CGPA: 7.87  
GLA University Mathura, Uttar Pradesh (2023 – 2026)
