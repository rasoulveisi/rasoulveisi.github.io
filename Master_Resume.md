# Rasoul Veisi

**Full-Stack Engineer | Angular, TypeScript, C#/.NET, PostgreSQL**

Yerevan, Armenia | rasoulveisidev@gmail.com | +374-98089113
Portfolio: [rasoulveisi.github.io](https://rasoulveisi.github.io) | LinkedIn: [linkedin.com/in/rasoulveisi](https://www.linkedin.com/in/rasoulveisi) | GitHub: [github.com/rasoulveisi](https://github.com/rasoulveisi)

*Open to relocation to the Netherlands, the UK and the EU with employer visa sponsorship (Highly Skilled Migrant / Skilled Worker).*
*Also open to remote roles on European hours (UTC+4).*

---

## Professional Summary

Full-stack engineer with 5+ years of professional experience building web applications, including 4 years on pharmacy logistics and dispensing platforms used daily by pharmacists, pharmacy staff and dispatchers. Promoted twice at Pharmabits, from Mid-Level Frontend Developer to Full-Stack Developer. Builds Angular and TypeScript interfaces and C#/ASP.NET Core services on PostgreSQL, and owns features from API contract design through deployment and production monitoring of 5+ live applications. Planned and delivered a staged Angular 12-to-17 migration of a live application, built a .NET service from the first commit, and moved frontend delivery to a shared GitLab CI/CD pipeline. Reviews code and mentors engineers across the stack.

---

## Technical Skills

- **Frontend:** Angular (12–21), TypeScript, JavaScript (ES6+), RxJS, Signals, HTML5, CSS3, SCSS/Sass, Tailwind CSS, PrimeNG, Nx monorepos, and frontend architecture.
- **Backend & Data:** C#, ASP.NET Core, EF Core, MediatR, MassTransit with RabbitMQ, Hangfire, FluentValidation, RESTful API design, OpenAPI, SQL, and PostgreSQL.
- **Angular Architecture:** Angular routing, route guards (CanActivate, CanMatch), HTTP interceptors, reactive forms, dynamic forms, component lifecycle, and state management with Signals and RxJS.
- **Web Security:** XSS prevention, CSRF protection, Content Security Policy (CSP), input sanitization, secure HTTP headers, SSO, RBAC, and 2FA.
- **Mobile & Responsive:** Responsive web development, mobile-first design, Progressive Web Apps (PWA), Ionic, and cross-browser compatibility.
- **Architecture & Patterns:** Clean Architecture, CQRS, microservices, Micro-Frontends, BFF (Backend-for-Frontend), dependency injection, and the Repository pattern.
- **Testing & Quality:** xUnit, Testcontainers, Moq, Jasmine/Karma, Cypress, Playwright, Postman, SonarQube, automated visual regression tests, and code reviews.
- **Delivery & Operations:** Docker, Kubernetes with Helm charts, GitLab CI/CD, Git, production deployments, Serilog, Graylog, and Sentry.
- **Performance:** Virtual scrolling, paginated data streams, client-side caching, RxJS debounce/throttle patterns, and optimistic UI updates.
- **Working Knowledge:** React, Node.js, Express.js, NestJS, Cloudflare Workers, and SQLite/Cloudflare D1.

---

## Languages

- **English:** Professional working proficiency (CEFR B2–C1); daily written and spoken work with international distributed teams.

---

## Professional Experience

### Full-Stack Developer | Pharmabits
*Pharmacy logistics, dispensing and healthcare operations platform for pharmacies in the Netherlands*

Yerevan, Armenia / Remote | Sep 2022 – Present

*Mid-Level Frontend Developer (Sep 2022 – 2023) → Senior Frontend Developer (2023 – Jul 2024) → Full-Stack Developer (Jul 2024 – Present)*

**Stack:** Angular, Signals, Tailwind CSS, Leaflet, PWA, ASP.NET Core, .NET, EF Core, MassTransit/RabbitMQ, Hangfire, OpenAPI, PostgreSQL, Docker, Helm, GitLab CI/CD, Graylog, Sentry, Postman

- Built the Recipe Status .NET service from the first commit, with a PostgreSQL schema and startup migrations, MassTransit/RabbitMQ consumers, Hangfire-scheduled link expiry, health checks and OpenAPI documentation.

- Designed the Recipe Status overview API contract and built the patient-facing overview in the Angular client page, so frontend and backend could be developed in parallel.

- Made patient notifications reliable in the communication service with idempotent email-result handling and per-day message deduplication, covered by unit and integration tests.

- Extended the logistics service with stock-value reports, a medicine sync endpoint, and 409 Conflict handling for concurrent stock picks using EF Core concurrency checks.

- Wrote background jobs that encrypt sensitive patient identifiers in PostgreSQL, using advisory locks and a tested rollback path.

- Connected medication-machine workflows to the logistics services over ASP.NET Core, with barcode normalization, versioned shared contract packages and correlation-ID logging across services.

- Integrated third-party prescription ingestion across ASP.NET Core microservices and Angular interfaces, so external prescriptions enter pharmacy processing workflows automatically.

- Added barcode-validation overrides with persisted audit flags across Angular dispensing interfaces and ASP.NET Core services.

- Reduced non-actionable 5xx alerts by tracing user journeys through Angular interfaces and .NET services with Graylog and Sentry, then fixing the causes so real application and third-party failures stood out.

- Planned and delivered a staged Angular 12-to-17 migration of a live application, adding XSS, CSRF and CSP protections, route guards and HTTP interceptors, with a route-by-route regression test plan.

- Kept large medication catalog and prescription views responsive with paginated API queries, client-side caching, debounced search streams and virtual scrolling.

- Built a dynamic-forms application from scratch, enabling pharmacy staff to enter and manage complex medication data.

- Delivered a mobile-first handheld PWA for pharmacy cabinet operations using Angular Signals, with hardware barcode and prescription scanning and two-factor authentication.

- Implemented keyboard shortcuts across high-frequency pharmacy interfaces, so pharmacists complete common dispensing actions without switching to a mouse.

- Integrated QR-code scanning into prescription workflows, letting pharmacists retrieve prescriptions and orders from scanned codes.

- Improved Leaflet-based delivery routing, so dispatchers can find the nearest delivery points and plan routes.

- Built the product, address and order flows of an Angular SSR ordering application for medical devices.

- Migrated the logistics frontend to Tailwind CSS with AI-assisted development and custom CLI tooling, validating every change with automated visual regression tests and manual checks.

- Moved frontend applications to a shared GitLab CI/CD pipeline with Docker images, Helm charts and staged deployments, and monitored 5+ live pharmacy applications in production.

- Strengthened release checks with Postman API integration tests, backend tests with mocked dependencies, and scenario-based pre-release validation of pharmacy workflows.

- Wrote technical architecture proposals applying Clean Architecture, CQRS and Micro-Frontends to set clear boundaries between pharmacy microservices and modular Angular interfaces.

- Reviewed frontend changes and mentored backend-focused engineers on Angular architecture, reactive patterns and component conventions.

- Delivered features in 2-week Agile/Scrum sprints with cross-functional teams, including planning, estimation, backlog refinement and retrospectives.

### Frontend Developer | Ketab.ir / BazarKetab
*Digital publishing marketplace*

Tehran, Iran | Dec 2021 – Sep 2022

**Stack:** Angular, Ionic, PWA, SCSS, Nx

- Extended an existing Angular desktop application to mobile with Ionic and PWA, refactoring the shared codebase with a mobile-first SCSS approach while preserving desktop functionality.

- Integrated SSO authentication, route guards, profile management, and bookstore search and filters across desktop and mobile.

- Built a dedicated vendor application from scratch, enabling vendors to add inventory and manage discounts within the publishing marketplace.

- Enabled reuse across multiple client applications by building shared UI components and translation libraries within an existing Nx monorepo.

- Resolved UI breakages caused by mixed Persian and English content, establishing styling conventions for reliable mixed-direction (RTL/LTR) interfaces.

### Frontend Developer | Zagros System
*Software house and digital agency*

Tehran, Iran | Mar 2020 – Feb 2021

**Stack:** React, REST APIs

- Built responsive React client applications in an Agile team, integrated backend REST APIs, and contributed to frontend asset-bundling optimisation.

---

## Featured Engineering Projects

### Job Craft | AI-Powered Job Application Platform
*React 19, TypeScript, Cloudflare Workers, D1 SQLite, Zod, OpenRouter*

- Built a personal job-application assistant that tailors resumes to job descriptions, with source-grounding checks that block claims the candidate profile does not support.
- Built an edge application on Cloudflare Workers with asynchronous queue processing, retry handling and D1 persistence.

### Task Management API & Integration Test Suite
*ASP.NET Core, C#, EF Core, PostgreSQL, MediatR, xUnit*

- Built an ASP.NET Core REST API on PostgreSQL with EF Core, MediatR-based CQRS, filtered pagination and an xUnit integration test suite covering key endpoints.

### Letterwise | Multi-Script Language Learning Platform
*Angular 21, NestJS 11, Nx monorepo, Supabase (PostgreSQL), RxJS, Zod*

- Built a multi-script learning platform in an Nx monorepo, separating UI components, shared domain contracts and API services.
- Implemented guest-to-account progress synchronisation, connecting local guest progress to authenticated cloud state with shared validation across the frontend and API.

### OT-Assistant | Occupational Therapy Planning Workspace
*Angular 21, PrimeNG 21, Express.js 5 on Cloudflare Workers, D1 SQLite, Clerk Auth, OpenRouter*

- Built an authenticated occupational-therapy workspace for client records, therapy plans, progress tracking and practitioner messaging.
- Designed D1-backed role-based access controls and contextual AI drafting tools for therapy planning.

### PhysioCoach AI | Workout Planning Platform
*React 19, Express.js 5 on Cloudflare Workers, PostgreSQL, Drizzle ORM, Zod, OpenRouter*

- Built a full-stack fitness platform with dynamic intake workflows and multi-stage LLM generation pipelines.
- Validated generated recommendations against exercise-catalogue rules and runtime schemas with API-side Zod checks.

### PricePulse Yerevan | Grocery Price Intelligence Platform
*React, Vite, Express.js 5 on Cloudflare Workers, Drizzle ORM, D1 SQLite, Cloudflare R2*

- Built catalogue ingestion pipelines with automated product normalisation, deduplication and asset storage in Cloudflare R2.

### Cloudflare Full-Stack Starter | Edge Architecture Template
*React 19, Vite, Express.js 5 on Cloudflare Workers, PostgreSQL, Drizzle ORM, Hyperdrive*

- Built a reusable full-stack scaffold with connection-pooled PostgreSQL through Cloudflare Hyperdrive and modular authentication handlers.

---

## Research & Applied Science Experience

### Graduate Research Engineer | Isfahan University of Technology
*Collaboration with Danfoss on data-driven modelling and predictive control of fluid and refrigeration systems*

Isfahan, Iran | 2020 – 2022

- Built a Python data-processing pipeline using Sparse Identification of Nonlinear Dynamics (SINDy) to identify candidate governing equations from experimental sensor time-series data.

- Formulated and tuned Model Predictive Control (MPC) and adaptive control algorithms in MATLAB/Simulink for multi-variable systems under dynamic operating constraints.

- Validated models and real-time control algorithms on hardware-in-the-loop simulation testbeds with Danfoss engineers.

---

## Education

### M.Sc. in Mechanical Engineering (Mechatronics & Dynamic Systems Control)
Isfahan University of Technology | 2019 – 2022

*Thesis: AI-Based Predictive Control using Machine Learning for Dynamic Systems, in collaboration with Danfoss.*

### B.Sc. in Biosystems Engineering
Razi University | 2015 – 2019
