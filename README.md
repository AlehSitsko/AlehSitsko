# Aleh Sitsko

**Operations-Focused Full Stack Developer** · Philadelphia, PA

Building practical, workflow-driven web applications and internal tools from real operational experience.

[![Portfolio](https://img.shields.io/badge/Portfolio-alehsitsko.dev-2563eb?style=flat)](https://alehsitsko.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-alehsitsko-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alehsitsko/)
[![Email](https://img.shields.io/badge/Email-sitskoaleh%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:sitskoaleh@gmail.com)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)

---

## About

I’m a full stack developer based in Philadelphia, PA, with a background in EMS dispatch and operations management.

Before software, I worked in operational environments where reliability, speed, structured workflows, and clear information flow were critical. That experience shapes how I build software: practical tools designed around real workflow problems — and engineered like production software, not demos, with security, multi-tenancy, and thorough automated testing built in.

My focus is workflow-driven applications, internal tools, structured data entry, operational dashboards, scheduling and dispatch systems, and process-oriented software.

---

## Current Focus

* Full stack development with **React, Python, and Flask**
* **Production architecture** — PostgreSQL, Redis, Docker, Nginx, Gunicorn, CI/CD
* **Security & data protection** — session auth, RBAC, multi-tenant isolation, encryption at rest
* **Realtime systems** — Server-Sent Events with a Redis broker across workers
* Cross-platform delivery — containerized web *and* offline Windows desktop (Electron)

---

## 🚑 Flagship Project — EMS Workflow System

[![License](https://img.shields.io/github/license/AlehSitsko/ems-workflow-system?style=flat)](https://github.com/AlehSitsko/ems-workflow-system/blob/main/LICENSE)
[![Latest release](https://img.shields.io/github/v/release/AlehSitsko/ems-workflow-system?style=flat)](https://github.com/AlehSitsko/ems-workflow-system/releases/latest)
[![Last commit](https://img.shields.io/github/last-commit/AlehSitsko/ems-workflow-system?style=flat)](https://github.com/AlehSitsko/ems-workflow-system)

A **production-grade, multi-tenant EMS/NEMT operations platform** — built from three years of real EMS dispatch and operations management experience. It ships two ways from one codebase: a containerized web app (PostgreSQL · Redis · Nginx) and a standalone, **offline-capable Windows desktop app** (Electron + SQLite).

**Engineering highlights**

* 🔒 **AES-256-GCM field-level encryption at rest** — per-organization envelope keys, AAD binding, and blind-index columns for exact-match search without decryption. A stolen database dump is useless without the master key.
* 🏢 **Runtime multi-tenant isolation** — every query org-scoped, every write org-stamped from the trusted session; invite-only onboarding, per-device session revocation, password policy, and owner recovery codes.
* ⚡ **Multi-worker realtime** — a broker abstraction fans Server-Sent Events across Gunicorn workers via Redis, with a fail-closed guard against unsafe configs.
* 🗂️ **Full operations suite** — live dispatch board, guided call intake, operational calendar & recurring trips, crew planning, fleet, time/payroll/PTO/leave, tasks, notifications, audit log, and supervisor analytics.
* 🧪 **1,400+ automated tests** (pytest · Vitest · Playwright); CI boots the entire production stack (PostgreSQL · Redis · Gunicorn×3 · Nginx · MinIO) and smoke-tests migrations, realtime, and S3 storage on every push.
* 📦 **Two deployment profiles** — web (React 19 + Flask) and Windows desktop (Electron + Waitress), no server or Python/Node needed for the desktop build.

**Tech:** React 19 · Flask · Python · SQLAlchemy · PostgreSQL · Redis · Docker · Nginx · Gunicorn · Electron · pytest · Playwright · GitHub Actions

[⬇ **Download for Windows**](https://github.com/AlehSitsko/ems-workflow-system/releases/latest/download/EMS-Workflow-System-Setup.exe) · [📖 **Case study**](https://alehsitsko.dev/#/ems) · [💻 **Repository**](https://github.com/AlehSitsko/ems-workflow-system)

> Portfolio project. Not intended for production medical use and should not be used with real patient data.

---

### Call Taking Form — React Demo

Frontend EMS call-intake prototype — an early version of the workflow concepts later expanded into the EMS Workflow System.

**Tech:** React · Vite · JavaScript · Bootstrap · localStorage · GitHub Pages

[Live demo](https://alehsitsko.github.io/Call-Taking-Form-React/) · [Repository](https://github.com/AlehSitsko/Call-Taking-Form-React)

### Nexvora Group Website

Responsive business website for a wholesale and e-commerce company — professional presentation, service sections, contact structure, and mobile-friendly layout.

**Tech:** React · Vite · JavaScript · CSS · Vercel

[Live demo](https://nexvora-group.vercel.app/) · [Repository](https://github.com/AlehSitsko/Nexvora_Group)

---

## Tech Stack

**Frontend:** React, JavaScript ES6+, HTML5, CSS, Bootstrap, Vite, React Router
**Backend:** Python, Flask, Flask Blueprints, REST APIs, SQLAlchemy, session auth, CSRF, RBAC
**Data & Infra:** PostgreSQL, SQLite, Alembic migrations, Redis, Docker, Nginx, Gunicorn, S3-compatible storage
**Quality & CI:** pytest, Vitest, Playwright, GitHub Actions, integration & load testing, Postman
**Concepts:** REST API design, client-server architecture, multi-tenant isolation, encryption at rest, realtime (SSE), CI/CD

---

## 📊 GitHub Stats

![Aleh's GitHub stats](https://github-readme-stats.vercel.app/api?username=AlehSitsko&show_icons=true&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AlehSitsko&layout=compact&hide_border=true&langs_count=8)

---

## Certification

**IBM Full Stack Software Developer Professional Certificate** — Coursera / IBM Skills Network, 2026
[View credential](https://www.coursera.org/account/accomplishments/specialization/NMZB7BRO9C6E)

---

## Contact

[Portfolio](https://alehsitsko.dev) · [LinkedIn](https://www.linkedin.com/in/alehsitsko/) · [GitHub](https://github.com/AlehSitsko) · [Email](mailto:sitskoaleh@gmail.com)
