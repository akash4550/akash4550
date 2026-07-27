# Akshay

Full-stack developer (MERN) — backend architecture, payments, real-time systems.

B.E. Information Technology, I²IT Pune (SPPU), 2026. Open to SDE-1 / full-stack roles — Pune, Mumbai, Bengaluru, Remote.

Co-author, *ICT4SD 2026* (Springer LNNS) — Vision Transformer classifier for Maratha warfield weapons, 91.12% validation accuracy on a self-published 1,787-image dataset.

[LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE) · [Email](mailto:YOUR-EMAIL@example.com)

<br>

## Projects

**[AIWorkspace](https://github.com/akash4550/AIWorkspace)** — Multi-tenant SaaS platform (project management, CRM, AI tooling) built as a modular monolith.
Tenant isolation is enforced at the schema and repository layer via `organizationId` foreign keys, indexed and scoped consistently across ~85 call sites — not just checked in middleware. Background work (analytics, AI generation, email) runs on Redis-backed BullMQ workers, keeping the HTTP API synchronous. 33 test files, CI on GitHub Actions, ~27k lines in the API alone.
*Node.js, TypeScript, Express, Prisma, PostgreSQL, Redis, BullMQ, Docker*

**[Prescripto](https://github.com/akash4550/Prescripto)** — Healthcare appointment booking with three portals (patient, doctor, admin) on one shared backend. Doctor availability is tracked per-slot with conflict checks on booking, and payments run through Razorpay. Live: [patient portal](https://prescriipto.netlify.app), [admin dashboard](https://prescriptionadmin.netlify.app).
*React, Node.js, Express, MongoDB, Razorpay*

**[Blink](https://github.com/akash4550/Blink-Chat-App)** — Real-time chat app using Socket.io for delivery and a JWT httpOnly cookie for REST auth.
*React, Node.js, Socket.io, MongoDB, JWT*

<img src="https://github.com/user-attachments/assets/cdc85643-a4ac-43be-a817-f33a03efa580" width="560" alt="Blink chat app">

<br>

<details>
<summary>More projects</summary>
<br>

| Project | Description | Stack |
|---|---|---|
| [DBT Mitra](https://github.com/akash4550/mahadbt-awareness-portal) | Scholarship-navigation portal for Maharashtra students — DB-backed eligibility quiz, community forum | React, Node.js, Express, MongoDB |
| [AI Note-Taking App](https://ai-note-taking-app-six.vercel.app) | Notes app with Gemini-powered summarization, grammar fixes, auto-tagging | Next.js, TypeScript, Drizzle, Gemini API |
| [SmartBill](https://smart-bill-theta.vercel.app) | Invoicing and billing app | Next.js, TypeScript, Prisma, PostgreSQL |
| [Product Explorer](https://github.com/akash4550/product-explorer-assignment) | Web scraper with a documented REST API | TypeScript, Node.js, Docker, Swagger |
| [Mayzax CRM](https://github.com/akash4550/Recruiter_CRM) | Recruitment/CRM API | Node.js, Express, PostgreSQL |
| [Payment Manager App](https://github.com/akash4550/Payment-Manager-App) | CRUD reference app | ASP.NET Core, Angular 16 |

</details>

<br>

## Stack

**Languages** — JavaScript, TypeScript, Python, C++, C#
**Frontend** — React, Next.js, Tailwind CSS
**Backend** — Node.js, Express, Prisma, MongoDB, PostgreSQL, Redis, BullMQ
**ML** — PyTorch, Vision Transformers
**Tools** — Docker, Git, Socket.io
