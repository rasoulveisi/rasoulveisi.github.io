# Rasoul Veisi

**Full-Stack Engineer | Angular, TypeScript, C#/.NET, PostgreSQL**

Yerevan, Armenia | [rasoulveisidev@gmail.com](mailto:rasoulveisidev@gmail.com) | +374-98089113
Portfolio: [rasoulveisi.github.io](https://rasoulveisi.github.io) | LinkedIn: [linkedin.com/in/rasoulveisi](https://www.linkedin.com/in/rasoulveisi) | GitHub: [github.com/rasoulveisi](https://github.com/rasoulveisi)

*Open to relocation to the Netherlands, the UK and the EU with employer visa sponsorship (Highly Skilled Migrant / Skilled Worker). Also open to remote roles on European hours (UTC+4).*

> Short version of [Master_Resume.md](Master_Resume.md). Edit the master first, then update this file.

---

## Professional Summary

Full-stack engineer with 5+ years of professional experience building web applications, including 4 years on pharmacy logistics and dispensing platforms used daily by pharmacists, pharmacy staff and dispatchers. Promoted twice at Pharmabits, from Mid-Level Frontend Developer to Full-Stack Developer. Builds Angular and TypeScript interfaces and C#/ASP.NET Core services on PostgreSQL, and owns features from API contract design through deployment and production monitoring of 5+ live applications.

---

## Technical Skills

- **Frontend:** Angular (12–21), TypeScript, RxJS, Signals, SCSS, Tailwind CSS, PrimeNG, Nx monorepos, PWA, Ionic.
- **Backend & Data:** C#, ASP.NET Core, EF Core, MediatR, MassTransit with RabbitMQ, Hangfire, OpenAPI, SQL, PostgreSQL.
- **Architecture & Security:** Clean Architecture, CQRS, microservices, Micro-Frontends, XSS/CSRF/CSP protection, SSO, RBAC, 2FA.
- **Testing & Delivery:** xUnit, Testcontainers, Moq, Jasmine/Karma, Cypress, Playwright, Postman, Docker, Kubernetes with Helm, GitLab CI/CD, Graylog, Sentry.
- **Working Knowledge:** React, Node.js, Express.js, NestJS, Cloudflare Workers, SQLite/Cloudflare D1.
- **Languages:** English, professional working proficiency (CEFR B2–C1).

---

## Professional Experience

### Full-Stack Developer | Pharmabits
*Pharmacy logistics, dispensing and healthcare operations platform for pharmacies in the Netherlands*
Yerevan, Armenia / Remote | Sep 2022 – Present
*Mid-Level Frontend Developer → Senior Frontend Developer (2023) → Full-Stack Developer (Jul 2024)*

- Built the Recipe Status .NET service from the first commit, with a PostgreSQL schema and startup migrations, MassTransit/RabbitMQ consumers, Hangfire-scheduled link expiry, health checks and OpenAPI documentation.
- Designed the Recipe Status overview API contract and built the patient-facing overview in the Angular client page, so frontend and backend could be developed in parallel.
- Made patient notifications reliable with idempotent email-result handling and per-day message deduplication, covered by unit and integration tests.
- Extended the logistics service with stock-value reports, a medicine sync endpoint, and 409 Conflict handling for concurrent stock picks using EF Core concurrency checks.
- Planned and delivered a staged Angular 12-to-17 migration of a live application, adding XSS, CSRF and CSP protections, route guards and HTTP interceptors, with a route-by-route regression test plan.
- Delivered a mobile-first handheld PWA for pharmacy cabinet operations using Angular Signals, with hardware barcode and prescription scanning and two-factor authentication.
- Reduced non-actionable 5xx alerts by tracing user journeys through Angular interfaces and .NET services with Graylog and Sentry, then fixing the causes.
- Migrated the logistics frontend to Tailwind CSS with AI-assisted development and custom CLI tooling, validating every change with automated visual regression tests.
- Moved frontend applications to a shared GitLab CI/CD pipeline with Docker images, Helm charts and staged deployments, and monitored 5+ live pharmacy applications in production.
- Reviewed frontend changes and mentored backend-focused engineers on Angular architecture, reactive patterns and component conventions.

### Frontend Developer | Ketab.ir / BazarKetab
*Digital publishing marketplace* | Tehran, Iran | Dec 2021 – Sep 2022

- Extended an existing Angular desktop application to mobile with Ionic and PWA, using a mobile-first SCSS approach while preserving desktop functionality.
- Built a dedicated vendor application from scratch, enabling vendors to add inventory and manage discounts.
- Built shared UI components and translation libraries in an existing Nx monorepo, and set styling conventions for mixed-direction (RTL/LTR) interfaces.

### Frontend Developer | Zagros System
*Software house and digital agency* | Tehran, Iran | Mar 2020 – Feb 2021

- Built responsive React client applications in an Agile team, integrated backend REST APIs, and contributed to frontend asset-bundling optimisation.

---

## Featured Engineering Projects

- **Job Craft** (React 19, Cloudflare Workers, D1, Zod, OpenRouter): job-application assistant that tailors resumes to job descriptions, with source-grounding checks and queue processing with retries.
- **Letterwise** (Angular 21, NestJS 11, Nx, Supabase): multi-script learning platform with guest-to-account progress synchronisation and shared validation.
- **OT-Assistant** (Angular 21, PrimeNG 21, Express.js 5 on Workers, D1, Clerk): occupational-therapy workspace with role-based access controls and AI drafting tools.
- **Task Management API** (ASP.NET Core, EF Core, PostgreSQL, MediatR, xUnit): REST API with CQRS, filtered pagination and an integration test suite.

---

## Research Experience

### Graduate Research Engineer | Isfahan University of Technology
*Collaboration with Danfoss* | Isfahan, Iran | 2020 – 2022

- Built a Python SINDy pipeline to identify governing equations from experimental sensor data, and tuned MPC and adaptive control algorithms in MATLAB/Simulink, validated on hardware-in-the-loop testbeds.

---

## Education

- **M.Sc. in Mechanical Engineering (Mechatronics & Dynamic Systems Control)**, Isfahan University of Technology, 2019 – 2022. Thesis with Danfoss: AI-Based Predictive Control using Machine Learning for Dynamic Systems.
- **B.Sc. in Biosystems Engineering**, Razi University, 2015 – 2019.
