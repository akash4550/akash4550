# Akshay

Full-stack developer (MERN) — backend architecture, payments, and real-time systems. Also do applied ML/CV work on the side.

[LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE) · [Email](mailto:YOUR-EMAIL@example.com)

B.E. Information Technology, I²IT Pune (SPPU), 2026. Open to SDE-1 / full-stack roles — Pune, Mumbai, Bengaluru, Remote.

Co-author, **ICT4SD 2026 (Springer LNNS)** — Vision Transformer classifier for Maratha warfield weapons, 91.12% validation accuracy on a self-published 1,787-image dataset.

---

## Projects

### [AIWorkspace](https://github.com/akash4550/AIWorkspace)
Multi-tenant SaaS platform — project management, CRM, AI tooling — built as a modular monolith.
- Tenant isolation enforced at the schema and repository layer via `organizationId` foreign keys, not just middleware — indexed and scoped consistently across ~85 call sites
- Background work (analytics, AI generation, email) offloaded to Redis-backed BullMQ workers so the HTTP API stays synchronous and fast
- 33 test files, CI pipeline on GitHub Actions, ~27k lines in the API alone
- `Node.js` `TypeScript` `Express` `Prisma` `PostgreSQL` `Redis` `BullMQ` `Docker`

### [Prescripto](https://github.com/akash4550/Prescripto)
Healthcare appointment booking — three portals (patient, doctor, admin) on one shared backend.
- Doctor availability tracked per-slot with real conflict checks on booking
- Razorpay for payment capture and order verification
- `React` `Node.js` `Express` `MongoDB` `Razorpay`

### [Blink](https://github.com/akash4550/Blink-Chat-App)
Real-time chat app — Socket.io for delivery, JWT in an httpOnly cookie for REST auth.
- `React` `Node.js` `Socket.io` `MongoDB` `JWT`

### [DBT Mitra](https://github.com/akash4550/mahadbt-awareness-portal)
Portal helping Maharashtra students navigate MahaDBT scholarships.
- DB-backed eligibility quiz with real scoring, plus a student community forum (posts/comments)
- `React` `Node.js` `Express` `MongoDB` `JWT`

### [AI Note-Taking App](https://github.com/akash4550/AI-Note-Taking-App) — [live](https://ai-note-taking-app-six.vercel.app)
Notes app with Gemini-powered summarization, grammar fixes, and auto-tagging.
- `Next.js` `TypeScript` `Drizzle ORM` `Gemini API`

### [SmartBill](https://github.com/akash4550/SmartBill) — [live](https://smart-bill-theta.vercel.app)
Invoicing and billing app on Prisma/PostgreSQL.
- `Next.js` `TypeScript` `Prisma` `PostgreSQL`

### [Product Explorer](https://github.com/akash4550/product-explorer-assignment)
Web scraper that extracts structured product data and serves it through a documented REST API.
- `TypeScript` `Node.js` `Docker` `Swagger`

<details>
<summary>Other repos</summary>

- **[Mayzax CRM](https://github.com/akash4550/Recruiter_CRM)** — recruitment/CRM API, Node.js + Express + PostgreSQL, JWT auth
- **[Payment Manager App](https://github.com/akash4550/Payment-Manager-App)** — CRUD reference app, ASP.NET Core Web API + Angular 16

</details>

---

## Stack

**Languages** JavaScript · TypeScript · Python · C++ · C#
**Frontend** React · Next.js · Tailwind CSS
**Backend** Node.js · Express · Prisma · MongoDB · PostgreSQL · Redis · BullMQ · JWT
**ML** PyTorch · Vision Transformers
**Other** Docker · Git · Socket.io · Razorpay
