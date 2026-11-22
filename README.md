<h1 align="center">Shahnawas Adeel · Software Portfolio</h1>

<p align="center">
  <strong>Full-Stack Web Platforms · Developer Tools · Open Source</strong><br/>
  A curated index of production-grade projects — marketplaces, SaaS platforms, AI systems, and Linux tools — built with TypeScript, React, Next.js, Node.js, Rust, and Python.
</p>

<p align="center">
  <a href="https://mdadeel.me/"><img src="https://img.shields.io/badge/Portfolio-mdadeel.me-7F5AF0?style=for-the-badge&logo=vercel&logoColor=white" alt="Shahnawas Adeel Portfolio — mdadeel.me" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/shahnawasadee1/"><img src="https://img.shields.io/badge/LinkedIn-Shahnawas_Adeel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Shahnawas Adeel on LinkedIn" /></a>&nbsp;
  <a href="mailto:shahnawasadeel@gmail.com"><img src="https://img.shields.io/badge/Email-shahnawasadeel%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Shahnawas Adeel" /></a>
</p>

---

**What is this repository?** This is the official project portfolio of **Shahnawas Adeel** (`@mdadeel`), a full-stack software engineer based in **Chattogram, Bangladesh**, available remotely worldwide. It organizes every shipped product into two tracks — **full-stack web platforms** (B2B trade, EdTech, e-commerce, fintech) and **open-source developer tools** (static analysis, design systems, Linux utilities, AI agents) — with live demos, tech stacks, and engineering highlights for each. Client/server builds are presented as one product per project.

---

## Projects at a Glance

| Project | Domain | Core Stack | Links |
| :--- | :--- | :--- | :--- |
| [Import Export Hub (IEHub)](#import-export-hub-iehub) | B2B Commodity Trading | React 19, Node.js, Firebase | [Live](https://iehub.vercel.app/) · [Source (client)](https://github.com/mdadeel/iehub-client) |
| [e-TuitionBD (e-TuitionHub)](#e-tuitionbd-e-tuitionhub) | EdTech Marketplace | React 19, Node.js, MongoDB | [Live](https://e-tuitionhub.vercel.app/) · [Source (frontend)](https://github.com/mdadeel/etuitionhub-frontend) |
| [AyashTech (E-Commerce Storefront)](#ayashtech-e-commerce-storefront) | E-Commerce | Next.js 16, Express | [Live](https://ayash-tech.vercel.app/) |
| [Metro Optics (Eyewear E-Commerce)](#metro-optics-eyewear-e-commerce) | E-Commerce | React 19, Firebase | [Live](https://metro-optics.vercel.app/) · [Source](https://github.com/mdadeel/metro-optics) |
| [ToyTopia (Toy Marketplace)](#toytopia-toy-marketplace) | E-Commerce | React 18, Firebase | [Source](https://github.com/mdadeel/ToyTopia) |
| [ApplyFlow (AI Job-Application Platform)](#applyflow-ai-job-application-platform) | AI Productivity | React, TypeScript, Node.js, Ollama | Private |
| [Tong (Creator Monetization Platform)](#tong-creator-monetization-platform) | Creator Economy / Fintech | Next.js 14, SQLite, Drizzle | Private |
| [Arbor (Codebase Intelligence)](#arbor-codebase-intelligence) | Developer Tooling | Next.js, tRPC, PostgreSQL, Redis | [Live](https://arborgit.vercel.app/) · [Source](https://github.com/mdadeel/Arbor) |
| [easyui (React Component Library)](#easyui-react-component-library) | Design System | TypeScript, React, pnpm, Cloudflare | [Playground](https://easyui.mdadeel125.workers.dev/) · [Source](https://github.com/mdadeel/easyui) |
| [Preen (Linux System Utility)](#preen-linux-system-utility) | Linux Desktop | Python 3, GTK 3 | [Source](https://github.com/mdadeel/Preen) · [Releases](https://github.com/mdadeel/Preen/releases) |
| [Cliplet (GNOME Shell Extension)](#cliplet-gnome-shell-extension) | Linux Desktop | GJS, GNOME Shell 50 | [Source](https://github.com/mdadeel/cliplet) |
| [Friday / EDITH (Local-First AI Assistant)](#friday--edith-local-first-ai-assistant) | AI Agents | Rust, SQLite, axum, MCP | [Source](https://github.com/mdadeel/friday) |
| [Pinflow (Pinterest Automation Pipeline)](#pinflow-pinterest-automation-pipeline) | Marketing Automation | Python, Next.js 16, SQLite | [Source](https://github.com/mdadeel/pinflow) |

---

## Full-Stack Web Platforms

### Import Export Hub (IEHub)

**B2B commodity-trading SPA — request-for-quote desks, cryptographic trade documents, and arbitration-ready dispute flows.**

IEHub digitizes the import–export workflow for institutional buyers and suppliers: buyers post RFQs, negotiate through a structured pipeline, and close deals against a SHA-256–verified document vault holding bills of lading and assay certificates. The result is a trading desk that stays auditable end to end.

[![Live Demo](https://img.shields.io/badge/Live_Demo-iehub.vercel.app-16a34a?style=for-the-badge&logo=vercel&logoColor=white)](https://iehub.vercel.app/)
[![Source Code](https://img.shields.io/badge/Source_Code-client-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/iehub-client)
![Backend](https://img.shields.io/badge/Backend-Node.js_%2F_Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Stack:** React 19 · Vite 7 · Tailwind CSS 4 · React Router 7 · Framer Motion · Recharts · Firebase Auth · Node.js · Express

- **4-stage RFQ negotiation pipeline** with one-click purchase-order conversion and Incoterm / HS-code filtering
- **Cryptographic document vault** — SHA-256–verified bills of lading and assay certificates for every shipment
- **ICC Tribunal dispute arbitration UI** backed by an escrow-style settlement model
- Zero frontend secrets and a hand-tuned Rollup chunk-splitting strategy for fast first loads

**Why it stands out:** the client and server are built as strict, separate codebases around one auditable trade workflow — not a generic CRUD admin.

---

### e-TuitionBD (e-TuitionHub)

**Multi-role tuition marketplace connecting students, verified tutors, and administrators across Bangla, English, Cambridge, and IB curricula.**

e-TuitionBD is a full EdTech SaaS: role-based dashboards, real-time messaging with WebRTC video session rooms, tutor verification workflows, and mobile-money payments verified through an admin queue. It ships with **172 passing Vitest tests**, a PWA build, and full English/Bengali localization.

[![Live Demo](https://img.shields.io/badge/Live_Demo-e--tuitionhub.vercel.app-16a34a?style=for-the-badge&logo=vercel&logoColor=white)](https://e-tuitionhub.vercel.app/)
[![Source Code](https://img.shields.io/badge/Source_Code-frontend-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/etuitionhub-frontend)
![Backend](https://img.shields.io/badge/Backend-Node.js_%2F_MongoDB-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Stack:** React 19 · Vite 7 · Tailwind CSS · Radix UI / shadcn · Firebase Auth & Storage · Socket.IO · WebRTC · Node.js · Express · MongoDB · PWA (Workbox) · i18next (EN/BN) · Vitest

- **Role-based dashboards** for Student, Tutor, and Admin with granular RBAC and a multi-step tutor verification flow
- **Real-time infrastructure** — Socket.IO chat with typing indicators and reactions, plus WebRTC video session rooms
- **bKash / Nagad / Rocket payment integration** with a manual verification queue for the Bangladeshi market
- **Global Cmd+K search** with URL-synced filters and an onboarding tour for first-time users

**Why it stands out:** production concerns are handled in code — 172 unit tests, dark mode, PWA offline support, and demo credentials for reviewers.

---

### AyashTech (E-Commerce Storefront)

**Modern e-commerce storefront built on the Next.js App Router with a decoupled Express API.**

AyashTech is a full-stack commerce build where the Next.js 16 storefront talks to a separate RESTful Express backend — a clean client/server split with repository-pattern storage, full product CRUD, and an admin panel for inventory.

[![Live Demo](https://img.shields.io/badge/Live_Demo-ayash--tech.vercel.app-16a34a?style=for-the-badge&logo=vercel&logoColor=white)](https://ayash-tech.vercel.app/)
![Source](https://img.shields.io/badge/Source-Private-6B7280?style=for-the-badge&logo=lock&logoColor=white)

**Stack:** Next.js 16 (App Router) · React 19 · Tailwind CSS 4 · Express · Node.js · Vercel

- Product catalog with filtering, search, and admin add-product form with validation
- Dark / light mode, toast notifications, and a fully responsive UI
- Decoupled architecture: Routes → Services → Repository layers on the server

---

### Metro Optics (Eyewear E-Commerce)

**Premium eyewear storefront with prescription management and real-time Firebase inventory.**

Metro Optics is a live retail build for an optics shop: browsable catalog with advanced filtering, per-customer prescription records, and an admin panel with role-based access wired to Firestore's real-time updates.

[![Live Demo](https://img.shields.io/badge/Live_Demo-metro--optics.vercel.app-16a34a?style=for-the-badge&logo=vercel&logoColor=white)](https://metro-optics.vercel.app/)
[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/metro-optics)

**Stack:** React 19 · Firebase / Firestore · Tailwind CSS · Vite · React Router · Radix UI · Zod

- Real-time inventory powered by Firestore listeners
- Prescription management per customer account
- Admin panel with role-based access control and Zod-validated forms

---

### ToyTopia (Toy Marketplace)

**Warm, playful marketplace for local toy discoveries — curated feeds, age-based browsing, and a persistent cart.**

ToyTopia is a consumer storefront focused on discovery: a trending feed, shop-by-age tiles, category-filtered catalog with search and sort, and local cart/wishlist persistence. All assets are bundled locally, so the app works offline.

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/ToyTopia)

**Stack:** React 18 · Vite 7 · Tailwind CSS · Framer Motion · Firebase Auth

- Trending feed and shop-by-age tiles for quick discovery
- Product pages with related-toy suggestions and localStorage cart / wishlist
- Firebase email + Google authentication and AA-contrast accessible palette

---

### ApplyFlow (AI Job-Application Platform)

**AI-assisted job-application dashboard — resume library, job-description scoring, interview prep, and honest ATS checking.**

ApplyFlow orchestrates 16 backend subsystem engines around a local-first AI gateway: it parses resumes (including hyperlinks embedded in PDF annotations), scores them against job descriptions, tailors resumes with a prompt compiler tuned for small local models, and exports to PDF / DOCX / Markdown.

![Source](https://img.shields.io/badge/Source-Private-6B7280?style=for-the-badge&logo=lock&logoColor=white)
![Status](https://img.shields.io/badge/Status-Local--First-F59E0B?style=for-the-badge&logo=cpu&logoColor=white)

**Stack:** React 18 · TypeScript · Vite · Tailwind · Node.js · Express · MongoDB (Mongoose) · Ollama (qwen2.5:3b) · pdfjs-dist

- **16 subsystem engines** — AI gateway, interview intelligence, skill-gap analysis, document validation, and an ATS honesty checker
- **Link-aware PDF parsing** that extracts hyperlink URLs from PDF annotations
- **Local-first AI** via Ollama with an OpenAI option — no data leaves the machine by default
- Kanban + list application trackers and a glassmorphism dark-mode UI

---

### Tong (Creator Monetization Platform)

**Bangladesh's independent creator-tipping and live Super Chat ecosystem — টং — pay creators with a cup of tea via bKash, Nagad, or Rocket.**

Tong combines a fintech-grade backend with creator tooling: a Chrome extension overlays a tipping HUD on YouTube Live and Twitch, five OBS stream-alert overlays run on the client, and a double-entry immutable ledger settles every tip with a 1.5% flat fee and TOTP-2FA KYC backoffice. Verified by **98/98 unit tests and 20/20 Playwright E2E tests**.

![Source](https://img.shields.io/badge/Source-Private-6B7280?style=for-the-badge&logo=lock&logoColor=white)

**Stack:** Next.js 14 (App Router) · Tailwind CSS · SQLite + Drizzle ORM · SSE · Chrome Manifest V3 · Vitest · Playwright

- **Manifest V3 browser extension** overlaying a tipping HUD on YouTube Live / Twitch with one-click chat integration
- **5 OBS stream-alert overlays** — goal bar, ticker, QR badge, dock — with Bengali TTS and procedural Web Audio sounds
- **Double-entry immutable ledger** with 1.5% flat fee, 24-hour settlement holds, and TOTP-2FA KYC backoffice
- Bengali + English profanity shield for live chat moderation

**Why it stands out:** a payments product designed for a market Stripe underserves — mobile-money-native, culturally grounded, and covered by a full test suite.

---

## Open Source & Developer Tools

### Arbor (Codebase Intelligence)

**Self-hostable codebase intelligence portal — GitHub repo in, architecture map and health score out.**

Arbor statically analyzes repositories with Babel AST parsing to produce an interactive React Flow dependency map, a six-dimension health score, and evidence-linked findings in about 30 seconds. Core analysis is deterministic; AI is bring-your-own-key and review-only, never mutating repo state. Ships with SARIF 2.1.0 export for GitHub Code Scanning and a verified record of **0 type errors and 315 passing Vitest tests**.

[![Live App](https://img.shields.io/badge/Live_App-arborgit.vercel.app-16a34a?style=for-the-badge&logo=vercel&logoColor=white)](https://arborgit.vercel.app/)
[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/Arbor)

**Stack:** Next.js · React 18 · TypeScript (strict) · tRPC v11 · PostgreSQL 16 + Prisma (30 models) · BullMQ + Redis 7 · Docker Compose · AGPL-3.0

- Deterministic Babel AST analysis with evidence-linked, six-dimension health scoring
- Interactive dependency maps (React Flow + dagre) rendered from real import graphs
- SARIF 2.1.0 export that plugs straight into GitHub Code Scanning
- Consultant-grade audit PDF generated via headless Chromium

---

### easyui (React Component Library)

**Themeable React UI component library with runtime theming, design tokens, and an interactive playground.**

easyui is a `pnpm` monorepo publishing `@easyui/react` (accessible React primitives) and `@easyui/tokens` (JSON design tokens compiled to CSS custom properties). Its playground lets users restyle accent, radius, and fonts at runtime while inspecting the TSX source of every component.

[![Playground](https://img.shields.io/badge/Playground-easyui.mdadeel125.workers.dev-16a34a?style=for-the-badge&logo=cloudflare&logoColor=white)](https://easyui.mdadeel125.workers.dev/)
[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/easyui)

**Stack:** TypeScript · React · pnpm monorepo · CSS Custom Properties · Cloudflare Workers · Vitest

- Runtime theming playground — accent, radius, and typography restyled live
- Every gallery component ships inspectable TSX source
- Design-token pipeline: JSON → CSS custom properties, shared across apps
- Accessibility + unit tests and a static SEO build with sitemap and Open Graph tags

---

### Preen (Linux System Utility)

**Native GTK 3 desktop app for Linux setup, deep cleaning, and system tuning — simulate before you act.**

Preen installs and removes APT / Flatpak apps, drag-and-drops AppImage and `.deb` installs with menu entries, deep-cleans disks with measured size previews, and manages systemd services and power profiles. Every destructive action runs through a **Simulate (dry-run) mode** first.

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/Preen)
[![Releases](https://img.shields.io/badge/Releases-v0.7.1-8B5CF6?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/mdadeel/Preen/releases)
![License](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge)

**Stack:** Python 3 · GTK 3 / PyGObject · apt · Flatpak · systemd · Debian packaging (.deb, wheel, AppImage)

- Deep Clean with measured, previewed disk-space savings before anything is deleted
- systemd service inspection, power profiles, ZRAM, and UFW toggles
- Config backup / restore with Timeshift integration
- Full docs suite: architecture, roadmap, privacy, and security

---

### Cliplet (GNOME Shell Extension)

**Clipboard history and emoji picker in one keyboard-first popup for GNOME Shell 50 — offline and memory-first.**

Cliplet is a Wayland-native GJS extension that merges clipboard management and emoji picking into a single popup: MultiCopy queues, nine undoable text transforms, snippets, OCR via local Tesseract, and a jot pad. It performs zero network requests and never stores password-manager secrets.

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/cliplet)
![Platform](https://img.shields.io/badge/GNOME_Shell-50_%2F_Wayland-4A86CF?style=for-the-badge&logo=gnome&logoColor=white)
![Privacy](https://img.shields.io/badge/Network-Zero_Telemetry-3DA639?style=for-the-badge&logo=shieldcheck&logoColor=white)

**Stack:** GJS (JavaScript) · GNOME Shell 50 ESM · Wayland · local Tesseract OCR · Node test harness (52 assertions)

- One popup, two modes: clipboard history and emoji search
- MultiCopy queue and 9 undoable text transforms
- OCR from screen regions via local Tesseract — no cloud calls
- Virtual-keyboard paste injection that never overwrites the clipboard

---

### Friday / EDITH (Local-First AI Assistant)

**A local-first AI assistant platform written in Rust — agent runtime, MCP tools, voice, and memory in a 15-crate workspace.**

Friday (product name EDITH) runs as a background daemon plus CLI: an event-bus agent runtime executes MCP tools against SQLite-backed memory, with voice input, search, and an axum HTTP API. It is early-development open source, built to show Rust systems design, not just prompts.

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/friday)
![Status](https://img.shields.io/badge/Status-Early_Development-F59E0B?style=for-the-badge&logo=flask&logoColor=white)
![License](https://img.shields.io/badge/License-MIT_%2F_Apache--2.0-3DA639?style=for-the-badge)

**Stack:** Rust (edition 2021) · 15-crate Cargo workspace · SQLite · axum · MCP (Model Context Protocol)

- Agent runtime over an event bus with tool execution and persistent memory
- MCP integration for extensible tooling
- Ships as background daemon + CLI with an axum HTTP API

---

### Pinflow (Pinterest Automation Pipeline)

**Watch-folder → AI vision metadata → scheduling → auto-publish: an end-to-end Pinterest content pipeline.**

Pinflow scans a watch folder, generates pin metadata with AI vision models (OpenRouter / Gemini), schedules pins on a Kanban queue and visual calendar, and auto-publishes through Pinterest API v5 — with SHA-256 duplicate detection and a restart-safe SQLite state machine with retry and backoff.

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mdadeel/pinflow)
![License](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge)

**Stack:** Python · SQLite · Pinterest API v5 · OpenRouter / Gemini vision · Next.js 16 dashboard · pytest · ruff

- AI vision metadata generation for every pin
- Kanban queue + visual calendar with a WebSocket live analytics feed
- Restart-safe SQLite state machine with retry / backoff — pipelines survive crashes
- SHA-256 duplicate detection before publish

---

## Production Tech Stack

| Layer | Technologies | Applied In |
| :--- | :--- | :--- |
| **Languages** | TypeScript (strict), JavaScript (ES2024), Python 3, Rust, SQL, Bash | Web platforms, AI agents, Linux desktop apps, CLI pipelines |
| **Frontend** | Next.js (App Router), React 19 / 18, Vite, Tailwind CSS, Radix UI / shadcn, Framer Motion, React Flow, Recharts | All web platforms and dashboards |
| **Backend & APIs** | Node.js, Express, tRPC v11, Socket.IO, WebRTC, BullMQ, axum (Rust), Firebase Auth | Marketplaces, real-time chat, worker queues, agent APIs |
| **Data** | PostgreSQL 16 + Prisma, MongoDB (Mongoose), SQLite + Drizzle, Redis 7, Firebase / Firestore | 30+ model relational schemas, ledgers, job queues, real-time inventory |
| **AI & Automation** | Ollama, OpenRouter / Gemini vision, MCP, Pinterest API v5, AI provider abstraction | Local-first AI, content pipelines, code analysis |
| **DevOps & Testing** | Docker Compose, Cloudflare Workers, Vercel, Playwright, Vitest, Jest, pytest, pnpm monorepos | Self-hosting, E2E suites (315+ / 172 / 98+20 tests across projects), CI-ready layouts |
| **Desktop & Systems** | GTK 3 / PyGObject, GJS, GNOME Shell 50, Wayland, systemd, Debian packaging | Linux utilities and extensions |

---

## Frequently Asked Questions

<details>
<summary><strong>Who is Shahnawas Adeel?</strong></summary>
<br/>
Shahnawas Adeel (<code>@mdadeel</code>) is a <strong>full-stack software engineer based in Chattogram, Bangladesh (UTC+6)</strong>, working remotely worldwide. He builds type-safe web platforms, developer tools, design systems, and Linux desktop utilities, shipping end-to-end software across TypeScript, React, Next.js, Node.js, PostgreSQL, MongoDB, Redis, Docker, Rust, and Python.
</details>

<details>
<summary><strong>Which projects have live demos?</strong></summary>
<br/>
Six projects are deployed and live right now: <a href="https://iehub.vercel.app/">Import Export Hub</a>, <a href="https://e-tuitionhub.vercel.app/">e-TuitionBD</a>, <a href="https://ayash-tech.vercel.app/">AyashTech</a>, <a href="https://metro-optics.vercel.app/">Metro Optics</a>, <a href="https://arborgit.vercel.app/">Arbor</a>, and the <a href="https://easyui.mdadeel125.workers.dev/">easyui playground</a>. Desktop tools (Preen, Cliplet) ship installable releases instead.
</details>

<details>
<summary><strong>Which projects are open source?</strong></summary>
<br/>
The open-source track includes <a href="https://github.com/mdadeel/Arbor">Arbor</a> (AGPL-3.0), <a href="https://github.com/mdadeel/easyui">easyui</a>, <a href="https://github.com/mdadeel/Preen">Preen</a> (MIT), <a href="https://github.com/mdadeel/cliplet">Cliplet</a>, <a href="https://github.com/mdadeel/friday">Friday / EDITH</a> (MIT / Apache-2.0), <a href="https://github.com/mdadeel/pinflow">Pinflow</a> (MIT), <a href="https://github.com/mdadeel/ToyTopia">ToyTopia</a>, <a href="https://github.com/mdadeel/metro-optics">Metro Optics</a>, and the IEHub / e-TuitionBD frontends. Client-server products marked <strong>Private</strong> are closed-source; their cards describe architecture and stack only.
</details>

<details>
<summary><strong>What is the strongest project for each engineering discipline?</strong></summary>
<br/>
<ul>
  <li><strong>Full-stack architecture:</strong> <a href="#arbor-codebase-intelligence">Arbor</a> — tRPC end-to-end type safety, 30-model Prisma schema, BullMQ + Redis workers, Docker self-hosting.</li>
  <li><strong>Product & marketplace engineering:</strong> <a href="#e-tuitionbd-e-tuitionhub">e-TuitionBD</a> — multi-role RBAC, Socket.IO + WebRTC, payments, 172 unit tests.</li>
  <li><strong>Systems programming:</strong> <a href="#friday--edith-local-first-ai-assistant">Friday / EDITH</a> — Rust 15-crate workspace, event-bus agent runtime.</li>
  <li><strong>Desktop & Linux:</strong> <a href="#preen-linux-system-utility">Preen</a> and <a href="#cliplet-gnome-shell-extension">Cliplet</a> — GTK 3 app packaging and Wayland-native GJS extensions.</li>
</ul>
</details>

<details>
<summary><strong>Is Shahnawas Adeel available for hire or collaboration?</strong></summary>
<br/>
Yes — open to <strong>full-time software engineer roles (remote worldwide or onsite in Bangladesh)</strong> and select contract work. Reach out via <a href="https://mdadeel.me/">mdadeel.me</a>, <a href="https://www.linkedin.com/in/shahnawasadee1/">LinkedIn</a>, or <a href="mailto:shahnawasadeel@gmail.com">shahnawasadeel@gmail.com</a>.
</details>

---

## Contact & Links

- **Portfolio site:** [https://mdadeel.me](https://mdadeel.me/)
- **GitHub profile:** [github.com/mdadeel](https://github.com/mdadeel)
- **LinkedIn:** [linkedin.com/in/shahnawasadee1](https://www.linkedin.com/in/shahnawasadee1/)
- **Email:** [shahnawasadeel@gmail.com](mailto:shahnawasadeel@gmail.com)

---

<p align="center"><sub><strong>Last updated: November 2026</strong> · Maintained by <a href="https://github.com/mdadeel">@mdadeel</a> · Client/server products are presented as one product per project; private-source projects are described without repository links.</sub></p>
