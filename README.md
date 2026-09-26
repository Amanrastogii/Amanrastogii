<h1 align="center">Hi, I'm Aman Rastogi 👋</h1>
<h3 align="center">Backend Software Engineer · Java Spring Boot · ASP.NET Core / .NET 8 · PostgreSQL</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/amanrastogi-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aman.rastogi2302@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I design and ship backend systems that real users depend on: REST APIs, relational data models, media-processing pipelines and deployment. I like clean layered architecture, measurable results and code that other engineers can maintain.

## 🧑‍💻 What I'm doing now

- 🏢 **Software Engineer at MediaMatrix (Delhi):** building an enterprise **Digital Asset Management** platform on ASP.NET Core / .NET 8 and MySQL, with a Python FastAPI + FFmpeg transcoding service, RabbitMQ messaging, and IIS / Kestrel deployments.
- 🎓 **Airtribe AI First Software Engineer program:** GenAI, scalable backend systems and AI-assisted engineering (my capstone is Prism, below).
- 📚 Deepening **system design and distributed systems**; 200+ LeetCode problems solved.

## 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[AI Video Editor](https://github.com/Amanrastogii/AI_vedio_editor)** | AI video editing platform: an 11-agent pipeline (ingestion, scene detection, story building, editing decisions, rendering, QA) with live WebSocket progress, a Premiere-style manual editor with FFmpeg transitions, captions, beat sync and learning from an editor's past cuts. | FastAPI, Celery, Redis, PostgreSQL, FFmpeg, Next.js |
| **[Prism: LLM Gateway & Semantic Cache](https://github.com/Amanrastogii/Prism_LLM_Gateway)** | OpenAI-compatible gateway with per-team virtual keys, Redis rate limiting, atomic monthly budgets, failover chains, streaming, difficulty-based auto-routing and a pgvector semantic cache. 171 unit + 30 integration tests, ~2.6 ms added latency. | .NET 8, PostgreSQL + pgvector, Redis, React, Docker |
| **[Finbud HRMS Backend](https://github.com/Amanrastogii/Finbud_HRMS_Backend)** | Production HRMS: employees, fingerprint attendance, leave workflows, payroll, JWT role-based access, Flyway migrations and an OpenAI/pgvector HR assistant. | Java 21, Spring Boot 3, PostgreSQL, Redis, Docker |
| **[Finbud Hiring Backend](https://github.com/Amanrastogii/finbud-hiring_backend)** | Hiring portal API: applications, resume storage on AWS S3, shortlist/reject workflow and JWT-secured admin endpoints, Dockerised on Render. | Java, Spring Boot, Spring Security + JWT, AWS S3, PostgreSQL |
| **[FruitStore API](https://github.com/Amanrastogii/FruitStore)** | E-commerce REST API with DTOs, repository pattern, EF Core migrations, Admin/Customer role-based auth and Swagger docs, deployed on Render. | ASP.NET Core, EF Core, PostgreSQL |
| **[MediTrack](https://github.com/Amanrastogii/Meditrack-clinic-management)** | Clinic and appointment system that demonstrates OOP, Strategy and Singleton patterns, Streams, custom exceptions and CSV persistence. | Core Java 17, Gradle |

## 📈 Impact at work

- Owned the **complete backend for finbudfinancial.com** (website, hiring portal, HRMS) serving **1000+ active users**.
- Cut API response times by **~30%** through PostgreSQL schema optimisation; CI/CD on Vercel + Render at **99%+ uptime**.
- Built .NET HRMS APIs (employees, payroll, attendance) backing **500+ employee records** during an internship at V2 Retail.

## 🧰 Tech stack

**Backend:** ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Python](https://img.shields.io/badge/Python_FastAPI-3776AB?style=flat-square&logo=fastapi&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Data & messaging:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**DevOps & tools:** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Frontend (when needed):** ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Gen AI:** RAG with OpenAI embeddings, pgvector semantic search, LLM gateways and prompt engineering.

## 🧭 How I build

- **Layered architecture:** Controller → Service → Repository, with DTOs and global exception handling.
- **Correctness under concurrency:** atomic admission (Redis Lua, conditional upserts) instead of read-then-write races.
- **Production habits:** environment-based config, Flyway migrations, JWT + RBAC, Swagger docs, health checks and tests against real databases.

## 💼 Experience

| Role | Company | When |
|---|---|---|
| Software Engineer | MediaMatrix, Delhi | Jan 2026 – Present |
| Software Engineer | Finbud Financial, Noida | Oct 2025 – Jan 2026 |
| Backend Developer Intern | V2 Retail | Sep – Oct 2025 |
| Blockchain Developer Intern | Blockseblock | Jun – Aug 2025 |

🎓 B.Tech in Computer Science Engineering, IILM University, Greater Noida (2022 – 2026)

---

<p align="center"><i>Open to conversations about backend engineering, system design and AI-first product engineering.</i></p>
