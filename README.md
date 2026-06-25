<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Syne&weight=700&size=26&pause=800&color=0ABFBC&center=true&vCenter=true&width=750&lines=Product+Engineer+%C2%B7+Full-Stack;Building+real+systems+%40+SOCIO;Next.js+%C2%B7+Supabase+%C2%B7+Valkey+%C2%B7+Capacitor;Open+to+Internships+%26+Freelance" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="https://linkedin.com/in/suryachalam">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://suryachalam.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="mailto:suryachalam18@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=sgk18&style=for-the-badge&color=0abfbc&label=PROFILE+VIEWS"/>
</div>

---

I build production systems — not tutorial projects. Right now I'm shipping features for **SOCIO**, a hybrid campus event platform with real users, real events, and a backend that holds up under load. My work spans the full stack: frontend interfaces people enjoy using, backend architectures that don't fall over, offline-first mobile systems, and push infrastructure that actually delivers. I care about the details — the cache hit rate, the sync conflict resolution, the 200ms QR scan that works without Wi-Fi.

---

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sgk18&theme=tokyonight&no-frame=true&row=1&column=6&margin-w=10"/>
</div>

---

## Currently Building

| What | Where | Status |
|---|---|---|
| Offline-first QR + push notification infra | SOCIO — Internship | Active |
| Studio TFA creative e-commerce platform | Freelance client | In progress |
| Atlas — Career management platform + recruiter CRM | Personal project | Shipped |
| System design & distributed systems | Self-study | Ongoing |

---

## Featured — SOCIO

> **Product Engineering Intern · Apr 2026 – Present · Selected via CICF · On-site, Bengaluru**

A full-scale hybrid campus event platform — event discovery, QR ticketing, offline-first scanning, push notifications, and role-based dashboards. Ships simultaneously as a web app, PWA, and native Android APK.

**What I own end-to-end:**

| Ownership Area | Details |
|---|---|
| Offline-first QR attendance scanner | IndexedDB/Dexie sync, duplicate detection — zero-connectivity operation |
| Push notification infrastructure | OneSignal, Firebase FCM, and VAPID/Web Push across all client types |
| In-memory caching & session layer | Valkey — cache management and session lifecycle |
| Role-based dashboards | Organizer, admin, and attendee views with scoped permissions |
| Native Android APK | Capacitor build maintained alongside the web client |

**Stack:**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Valkey](https://img.shields.io/badge/Valkey-DC382D?style=flat-square&logo=redis&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![OneSignal](https://img.shields.io/badge/OneSignal-E54B4D?style=flat-square&logo=onesignal&logoColor=white)

[View Repo](https://github.com/sgk18/socio2026v2) · [Mobile Client](https://github.com/sgk18/sociomobilev2)

---

## Featured — Atlas

> **Personal Project · Career Management Platform + Recruiter CRM**

A production-grade, centralized career management system — consolidating professional branding, recruiter relationship management, application pipelines, and proactive deadline tracking. Combines an immersive WebGL portfolio with a telemetry-driven admin console, a two-way email CRM, and an automated background deadline auditing daemon.

**What's under the hood:**

| Subsystem | Implementation |
|---|---|
| Recruiter CRM & threading | Two-way SMTP threading via Resend webhooks (`In-Reply-To` header matching) |
| Telemetry analytics | SHA-256 IP hashing for privacy-preserving unique visitor tracking |
| Deadline intelligence engine | Automated expiry detection, IST-aligned digest emails at 8AM/8PM |
| GitHub caching engine | In-memory TTL cache with rate-limit fallback across top 20 repos |
| Security layer | Honeypot + IP rate limiter + Zod validation + sessionless header auth |
| Database | 17 Prisma models on SQLite/LibSQL — zero-code upgrade path to Turso edge |

**Stack:**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-1B222D?style=flat-square&logo=prisma&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat-square&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

[View Repo](https://github.com/sgk18/SGK18_Portfolio) · [Live](https://sgk-18-portfolio.vercel.app)

---

## Projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **Studio TFA** | Creative studio e-commerce — modular frontend, adaptive layouts, Razorpay payments | React · TypeScript · Next.js · Supabase · Razorpay | [Repo](https://github.com/sgk18/Studio-TFA) |
| **FacultyApp** | Institutional workflow system — role-based access, academic data management | Next.js · Flutter · Supabase | [Repo](https://github.com/sgk18/Facultyapp) |
| **NoteNova Backend** | Multi-user academic resource sharing — REST APIs, institutional-scale PostgreSQL | Node.js · Express · PostgreSQL | [Repo](https://github.com/sgk18/NoteNova_Backend) |
| **Stockox** | AI-powered investment intelligence — multi-agent committee with Research, Technical, News, and Risk agents | Next.js · Go/Gin · Supabase · Redis · LangGraph · CrewAI | [Live](https://stockox.vercel.app) |
| **Aegis** | Modular productivity platform — scalable frontend architecture | React · TypeScript · Supabase | [Repo](https://github.com/sgk18/aegis-web) |

---

## Tech Stack

### Languages

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) | ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |

### Frontend

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) | ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black) |
| ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) | ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white) | | | | | |

### Backend & Infrastructure

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) | ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) | ![Go/Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white) | ![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white) | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

### Databases & Data

| | | | | | | | |
|---|---|---|---|---|---|---|---|
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) | ![Valkey](https://img.shields.io/badge/Valkey-DC382D?style=flat-square&logo=redis&logoColor=white) | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | ![Prisma](https://img.shields.io/badge/Prisma-1B222D?style=flat-square&logo=prisma&logoColor=white) |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white) | | | | | | |

### AI & Tooling

| | | | | | | |
|---|---|---|---|---|---|---|
| ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) | ![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat-square&logoColor=white) | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) | ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white) | ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white) | ![Numpy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | |

**Also working with:** Service Workers · IndexedDB/Dexie · Web Push/VAPID · OneSignal · SMTP Threading · WebGL

**Actively learning:** System Design · Distributed Systems · Cloud Infrastructure · AI Agent Architectures

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sgk18&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" width="49%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sgk18&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&hide=html,css" width="49%"/>
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=sgk18&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" width="60%"/>
</div>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sgk18&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

---

## Contributions

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sgk18/sgk18/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/sgk18/sgk18/output/github-snake.svg" alt="Snake animation"/>
  </picture>
</div>

---

## Background

**Experience**

| Role | Organization | Period |
|---|---|---|
| Product Engineering Intern | SOCIO — CICF, CHRIST University | Apr 2026 – Present |
| Web Developer | Centre for Peace Praxis, CHRIST University | Jul 2025 – Present |

**Education**

| Degree | Institution | Period |
|---|---|---|
| BSc Computer Science & Mathematics | CHRIST University, Bengaluru | 2025 – 2029 |

Coursework: Graph Theory · Discrete Mathematics · Madhava Mathematics Competition '26

**Certifications**

| Certification | Issuer | Year |
|---|---|---|
| Oracle Data Platform 2025 Foundations Associate (1Z0-1195-25) | Oracle | 2025 |
| SQL (Basic) | HackerRank | 2025 |

**Wins**

| Achievement | Event | Year |
|---|---|---|
| Runner-Up | Frontend Frenzy, Xactitude IT Fest 2026 | 2026 |
| 1st Place | Mathematics Premier League, SEQUENCE 2026 | 2026 |
| Finisher | 24-Hour Solo Hackathon, CHRIST × Pod.ai | 2026 |
| 3rd Prize | National Science Exhibition, CHRIST University | 2026 |

---

## Engineering Philosophy

Principles that guide every technical decision — from database schema design to how a function is named.

| # | Principle | Practice |
|---|---|---|
| 01 | **Build for the next engineer** | Code is read far more than it is written. Every abstraction and system boundary should communicate intent — not just to machines, but to the person on-call at 2am. |
| 02 | **Measure before you optimize** | Instrument first, identify the actual bottleneck, then fix it. A cache that solves the wrong problem is technical debt disguised as performance. |
| 03 | **Prefer simple, push complexity to the edges** | A boring architecture that solves the problem beats an elegant one that introduces six new failure modes. Complexity should live at the boundaries where it's most visible and testable. |
| 04 | **Security is architecture, not a checklist** | Authorization enforced only at the API layer is one bug away from a breach. Defense-in-depth means RLS at the database, scoped tokens at the API, and input validation at every boundary. |
| 05 | **Ship working software, then make it good** | A perfect system that never ships helps no one. Deliver value incrementally, with enough architecture to avoid rewriting everything in six months. |
| 06 | **Understand the why before the how** | Every technology choice carries tradeoffs. Picking a tool without understanding what problems it solves means inheriting its complexity without leveraging its strengths. |

---

## Volunteer & Leadership

| Role | Organization | Year |
|---|---|---|
| Guest Speaker & Workshop Facilitator | "Build Your Professional Identity from Day 1" — Junior Orientation, CHRIST University | Jun 2026 |
| Industry Delegate Host | Industry-Academia Conclave '26, School of Sciences, CHRIST University | 2026 |
| Moderator | inbloom eSports — Science and Technology (Chess.com tournament) | 2025 |
| Volunteer | INTERFACE 2025, Department of Computer Science, CHRIST University | 2025 |

---

## Certifications

| Certification | Issuer | Valid |
|---|---|---|
| Oracle Data Platform 2025 Foundations Associate (1Z0-1195-25) | Oracle University | Through May 2028 |
| Graph Theory | CHRIST University | 2025 |
| Python (Basic) | HackerRank | 2025 |
| SQL (Basic) | HackerRank | 2025 |
| C Programming | Infosys Springboard | 2025 |
| AI Prompt Engineering | Microsoft | 2025 |

---

## Let's Work Together

Open to **internships**, **freelance projects**, and **collaborations** — full-stack product engineering, hybrid mobile, real-time/offline-first systems, EdTech, and AI-integrated applications.

<div align="center">
  <a href="https://linkedin.com/in/suryachalam">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://sgk-18-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:suryachalam18@gmail.com">
    <img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</div>

<br/>

<div align="center">
  <em>BSc Computer Science & Mathematics · CHRIST University, Bengaluru · 2025–2029</em>
</div>
