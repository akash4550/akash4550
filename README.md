<h1 align="center">Akshay</h1>
<p align="center">Full-stack developer (MERN) — backend architecture, payments, real-time systems</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE">LinkedIn</a> ·
  <a href="mailto:YOUR-EMAIL@example.com">Email</a>
</p>

<p align="center">
B.E. Information Technology, I²IT Pune (SPPU), 2026 · Open to SDE-1 / full-stack roles — Pune, Mumbai, Bengaluru, Remote
</p>

<p align="center"><sub>Co-author, <b>ICT4SD 2026 (Springer LNNS)</b> — Vision Transformer classifier for Maratha warfield weapons, 91.12% validation accuracy on a self-published 1,787-image dataset</sub></p>

<br>

## Projects

### AIWorkspace
Multi-tenant SaaS platform — project management, CRM, AI tooling — built as a modular monolith.

- Tenant isolation enforced at the schema and repository layer via `organizationId` foreign keys, not just middleware — indexed and scoped consistently across ~85 call sites
- Background work (analytics, AI generation, email) offloaded to Redis-backed BullMQ workers, keeping the HTTP API synchronous
- 33 test files, CI on GitHub Actions, ~27k lines in the API alone

`Node.js` `TypeScript` `Express` `Prisma` `PostgreSQL` `Redis` `BullMQ` `Docker`
**[Repo →](https://github.com/akash4550/AIWorkspace)**

<br>

### Prescripto
Healthcare appointment booking — three portals (patient, doctor, admin) on one shared backend, live on Netlify + Render.

- Doctor availability tracked per-slot with conflict checks on booking
- Razorpay for payment capture and order verification

`React` `Node.js` `Express` `MongoDB` `Razorpay`
**[Patient Portal →](https://prescriipto.netlify.app)** · **[Admin Dashboard →](https://prescriptionadmin.netlify.app)** · **[Repo →](https://github.com/akash4550/Prescripto)**

<br>

### Blink
Real-time chat app — Socket.io for delivery, JWT in an httpOnly cookie for REST auth.

<img src="https://github.com/user-attachments/assets/cdc85643-a4ac-43be-a817-f33a03efa580" width="600" alt="Blink chat app screenshot">

`React` `Node.js` `Socket.io` `MongoDB` `JWT`
**[Repo →](https://github.com/akash4550/Blink-Chat-App)**

<br>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | Description | Stack |
|---|---|---|
| [DBT Mitra](https://github.com/akash4550/mahadbt-awareness-portal) | Scholarship-navigation portal for Maharashtra students — DB-backed eligibility quiz, community forum | React · Node.js · Express · MongoDB |
| [AI Note-Taking App](https://ai-note-taking-app-six.vercel.app) | Notes app with Gemini-powered summarization, grammar fixes, auto-tagging | Next.js · TypeScript · Drizzle · Gemini API |
| [SmartBill](https://smart-bill-theta.vercel.app) | Invoicing and billing app | Next.js · TypeScript · Prisma · PostgreSQL |
| [Product Explorer](https://github.com/akash4550/product-explorer-assignment) | Web scraper with a documented REST API | TypeScript · Node.js · Docker · Swagger |
| [Mayzax CRM](https://github.com/akash4550/Recruiter_CRM) | Recruitment/CRM API | Node.js · Express · PostgreSQL |
| [Payment Manager App](https://github.com/akash4550/Payment-Manager-App) | CRUD reference app | ASP.NET Core · Angular 16 |

</details>

<br>

## Stack

<p>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
</p>
