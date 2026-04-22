<h1 align="center">Vaibhav Singh</h1>

<h3 align="center">Full Stack Developer | Backend Engineer | DevOps</h3>

<p align="center">
  Open to <b>Full Stack / Backend Engineer</b> roles (India / Remote).  
  I build production-grade web and mobile platforms using <b>Next.js, Node.js, TypeScript, MongoDB, Redis, Docker, AWS, and React Native</b>.
</p>

<p align="center">
  <b>Available for freelance, contract, and full-time opportunities.</b>
</p>

<div align="center">
  <a href="https://drive.google.com/file/d/1qu8EdqezS16O354El1y1QRM80c7AA9F-/view?usp=sharing" target="_blank"><img src="https://img.shields.io/static/v1?message=Resume&logo=readme&color=6A5ACD&style=for-the-badge" height="28" /></a>
  <a href="https://vaibhav-fullstack-dev.vercel.app" target="_blank"><img src="https://img.shields.io/static/v1?message=Portfolio&logo=googlechrome&color=4285F4&style=for-the-badge" height="28" /></a>
  <a href="https://www.linkedin.com/in/vaibhav-singh-o-o" target="_blank"><img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&color=0077B5&style=for-the-badge" height="28" /></a>
  <a href="https://github.com/Vaibhav-Singh2" target="_blank"><img src="https://img.shields.io/static/v1?message=GitHub&logo=github&color=181717&style=for-the-badge" height="28" /></a>
  <a href="mailto:vaibhav.fullstack.dev@gmail.com" target="_blank"><img src="https://img.shields.io/static/v1?message=Email&logo=gmail&color=D14836&style=for-the-badge" height="28" /></a>
  <a href="https://wa.me/917906115972" target="_blank"><img src="https://img.shields.io/static/v1?message=WhatsApp&logo=whatsapp&color=25D366&style=for-the-badge" height="28" /></a>
</div>

---

### 🚀 Summary

Full-stack developer with 1.5+ years of production experience building and shipping end-to-end web and mobile applications — from React.js/Next.js frontends and React Native mobile apps to scalable Node.js backends, cloud infrastructure, and developer tooling. Delivered measurable results across the full stack: 50% API latency reduction at Vize (P95: 800ms → 480ms), AI report infrastructure at MaxFate handling 500+ daily requests at 99.9% uptime, and a 35% lift in user engagement through SSR and SEO optimization. Most recently shipped an open-source CLI (create-saas-app-cli) to scaffold production SaaS monorepos faster.

---

### 🏆 Top Achievements

- Improved backend throughput by **40%** using BullMQ + Redis based asynchronous job processing at MaxFate.
- Reduced API response time by **50%** through MongoDB optimization and Redis caching at Vize.
- Built and shipped **30+ secure REST APIs** powering production booking, payment, and user workflows.
- Achieved **99.9% uptime** and **zero-downtime releases** with Docker + GitHub Actions CI/CD on AWS EC2.
- Increased user engagement by **35%** through SSR and SEO optimization on Next.js frontend.

---

### 💼 Professional Experience

#### Full Stack Developer — MaxFate Private Limited _(June 2025 – Present)_

- Architected Node.js/Bun backend with OpenAI integration for automated AI report and PDF generation, processing 500+ daily requests; achieved 99.9% uptime tracked via AWS CloudWatch.
- Reduced job queue latency by 40% (measured via BullMQ metrics) by implementing asynchronous processing with BullMQ and Redis, replacing synchronous API calls.
- Built and maintained Docker + GitHub Actions CI/CD pipeline on AWS EC2, enabling zero-downtime releases across all production deployments.
- Led Next.js/TypeScript frontend with SSR and SEO optimization; integrated GA4 and Meta Conversions API (CAPI) for full attribution tracking, increasing measured user engagement by 35%.
- Integrated Razorpay payment gateway and Zoho CRM with UTM attribution and duplicate prevention logic, automating end-to-end lead-to-payment workflows.

#### App Developer (React Native & MERN) — Vize _(October 2024 – June 2025)_

- Designed and deployed 30+ RESTful APIs using Node.js, Express.js, and MongoDB, handling 1,000+ daily requests for a consultation platform serving 200+ active users.
- Reduced P95 API response time from 800ms to 480ms (50%) by optimizing MongoDB schemas with Mongoose ORM and layering Redis caching on hot query paths.
- Implemented JWT and OAuth2 authentication flows securing 200+ user accounts; added Firebase Auth with Google OAuth and phone OTP for cross-platform login.
- Integrated Razorpay payment gateway processing 100+ monthly transactions, with webhook verification, order reconciliation, and automated invoice generation.
- Built and shipped cross-platform React Native mobile app (iOS & Android) with Redux Toolkit state management, shared authentication flow (Google OAuth2, phone OTP, JWT), and 15+ screens covering booking, consultation history, and user profile; deployed to both platforms with a single codebase alongside the React.js web client.

---

### 📚 Projects

#### AI-Powered Personalized Report Platform · Next.js, Node.js, TypeScript, MongoDB, Redis, BullMQ, AWS

- Built multi-service SaaS platform with Next.js frontend and Express.js/TypeScript API; BullMQ workers handle automated multi-language AI report generation with 500+ daily requests and 99.9% uptime.
- Integrated Razorpay (webhook verification, order reconciliation) and Zoho CRM with UTM attribution; deployed report hosting on Cloudflare R2 with structured logging via Winston and AWS CloudWatch.
- Implemented GA4 and Meta Conversions API (CAPI) for full attribution integrity; SSR and SEO optimization on Next.js frontend increased measured user engagement by 35%.
- Designed modular OpenAI prompt pipeline with per-user context injection, enabling multi-language report generation (English, Hindi) with consistent formatting across 10+ report types.
- Architected multi-environment deployment strategy on AWS EC2 with environment-specific Secrets Manager configs and CloudWatch alarms, cutting mean time to detect (MTTD) production anomalies from hours to under 5 minutes.

#### Drone & Aero E-Commerce Platform · Next.js, TypeScript, Prisma, MongoDB, Razorpay, Clerk, Vercel Blob

- Built full-stack e-commerce platform with separate customer storefront and admin dashboard; complete shopping journey — category browsing, cart, checkout, and account management via Next.js App Router, Tailwind CSS, and Radix UI.
- Designed scalable Prisma + MongoDB schema (users, products, variants, orders, cart, addresses, reviews); integrated Razorpay end-to-end with order creation, signature verification, and webhook-driven payment status updates.
- Implemented Clerk auth with JWT-based admin middleware; integrated Vercel Blob Storage for media uploads; built custom service modules for repair and 3D printing orders with quote-request lifecycle tracking.
- Built real-time admin dashboard with order management, inventory tracking, and analytics views; implemented server-side pagination and filtering for product catalogs handling 500+ SKUs efficiently.
- Optimized Prisma query performance with selective field projection and compound indexes, reducing average dashboard load time by 30% under concurrent admin sessions.

#### create-saas-app-cli · Node.js, TypeScript, Turborepo, BullMQ, Drizzle, Prisma, Mongoose, Docker

- Published open-source CLI tool on npm (npx create-saas-app-cli) that scaffolds a production-ready Multi-Tenant SaaS Turborepo monorepo in seconds; 147kB unpacked across 23 files.
- Supports interactive prompts for 4 database/ORM combinations (PostgreSQL + Drizzle, PostgreSQL + Prisma, MongoDB - Mongoose, SQLite + Drizzle), 3 package managers (bun, pnpm, npm), and optional BullMQ worker, Redis-backed rate limiting, JWT auth, and Prometheus + Grafana observability stack.
- Generates a structured monorepo with shared packages for config, database, logger, auth, queue, redis, and TypeScript types; includes optional GitHub Actions CI/CD workflow and Docker Compose infrastructure out of the box.

---

### 🛠️ Technical Skills

**Core Stack:** Node.js · React.js · Next.js · TypeScript · MongoDB · Redis · AWS · Docker · Express.js · React Native

**Backend & APIs:** Bun, RESTful API Design, API Versioning, WebSocket, Microservices Architecture, BullMQ, Webhook Handling, Background Job Processing

**Frontend & Mobile:** JavaScript (ES6+), Redux Toolkit, Tailwind CSS, Radix UI, React Hook Form, Zod, HTML5, CSS3, SSR, Responsive Design

**Cloud & DevOps:** AWS (EC2, S3, IAM, VPC, CloudWatch, Secrets Manager), Cloudflare R2, Vercel Blob, Kubernetes, Nginx, GitHub Actions, CI/CD Pipelines, Git, Linux, SSH

**Databases:** MongoDB (Aggregation Pipeline, Indexing, Sharding, Replica Sets), Redis (Caching, Pub/Sub, Rate Limiting), MySQL, Prisma ORM, Mongoose ORM, Query Optimization

**Auth & Security:** JWT, OAuth2, Firebase Auth, Clerk, API Key Authentication, OWASP Top 10, Input Validation

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

**Bachelor of Computer Applications (BCA) – Computer Science**  
GLA University Mathura, Uttar Pradesh (2023 – 2026)
