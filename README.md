<div align="center">

# Khai · `@dokhaidfc`

### Full-Stack Software Engineer — **DFC Flow**

*Building the AMOIQ commerce & ERP platform: multi-tenant APIs, data layer, and operator-facing web apps.*

[![Organization](https://img.shields.io/badge/Org-DFCflow-0A0A0A?style=for-the-badge&logo=github)](https://github.com/DFCflow)
[![Role](https://img.shields.io/badge/Role-Full--Stack%20Engineer-2563EB?style=for-the-badge)](#-role-in-the-team)
[![Focus](https://img.shields.io/badge/Focus-ERP%20%C2%B7%20Commerce%20%C2%B7%20CMS-16A34A?style=for-the-badge)](#-platform-ownership)

</div>

---

## 🧭 Role in the Team

I work across the full delivery path at **DFC Flow** — from database schema to the screen an operator clicks — on the **AMOIQ** platform that runs commerce, fulfillment, CRM and content operations for multiple brands (tenants).

| Area | What I own |
|---|---|
| **Backend & APIs** | Design and ship REST endpoints on the core Express API; contract-first changes, tenant isolation, auth & visibility rules |
| **Data layer** | PostgreSQL schema, PostgREST views and migrations; query performance and safe, reversible rollouts |
| **ERP frontend** | Feature delivery on the EIOS web app (Next.js / React / TypeScript) — workflows, boards, dashboards |
| **CMS** | Headless CMS admin and page renderer used by tenant storefronts |
| **Automation** | Scheduled jobs, background processing, and AI-assisted engineering workflows |
| **Release quality** | Code review, impact analysis, staging verification and release management |

---

## 🏗️ Platform Ownership

```text
┌──────────────────────┐     ┌──────────────────────┐     ┌────────────────────┐
│  EIOS ERP (Next.js)  │     │  CMS Admin / Render  │     │  Brand Storefronts │
└──────────┬───────────┘     └──────────┬───────────┘     └─────────┬──────────┘
           │                            │                           │
           └──────────────┬─────────────┴───────────────┬───────────┘
                          ▼                             ▼
              ┌───────────────────────┐     ┌───────────────────────┐
              │   Core API (Express)  │◄───►│  Scheduler / Workers  │
              └───────────┬───────────┘     └───────────────────────┘
                          ▼
              ┌───────────────────────┐
              │ PostgreSQL + PostgREST│
              └───────────────────────┘
```

---

## ⚙️ How I Ship

- **Evidence first** — every bug fix starts with a traced root cause, not a guess.
- **Impact analysis before edit** — check cross-repo consumers and affected features before touching shared code.
- **Small, reviewable slices** — one shippable change per PR, squash into `develop`, linear cherry-pick release branches into `main`.
- **Verified on staging** — reviewed, tested and smoke-checked on a deployed environment before it is called done.
- **Safe data changes** — migrations proven inside transactions, with snapshot & restore on shared environments.

---

## 🧰 Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostgREST](https://img.shields.io/badge/PostgREST-2E7D32?style=flat-square)
![Typesense](https://img.shields.io/badge/Typesense-D52E5C?style=flat-square)

**Infra & Tooling**
![Fly.io](https://img.shields.io/badge/Fly.io-7B3FE4?style=flat-square&logo=flydotio&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Claude Code](https://img.shields.io/badge/AI--assisted-Claude_Code-D97757?style=flat-square)

---

## 📊 Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=dokhaidfc&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=github_dark" alt="GitHub stats" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=dokhaidfc&hide_border=true&theme=github-dark-blue" alt="Streak" />

</div>

---

<div align="center">

**Open to collaboration on ERP, commerce platforms and developer tooling.**

<sub>Most of my work lives in private DFC Flow repositories — this page summarizes the scope.</sub>

</div>
