# Augusto Silva

**Full Stack Developer — internal systems, integrations, and automation for ISP operations.**

Santo Estêvão, BA · Brazil
[Portfolio](https://portfolioaugusto.vercel.app) · [LinkedIn](https://www.linkedin.com/in/augusto-px-silva/) · augustopxsilva@gmail.com

---

## What I work on

I build the software that keeps an internet provider running — and I work inside the
operation while I build it. Sales funnel, contracts, service orders, billing, overdue
accounts: I know these flows because I use them, not because I read a spec.

Most of my work is integration. Provider ERPs (IXC Soft, OPA Suite) expose a lot and
guarantee little, so the interesting problems are usually about error handling, retries,
partial failures, and making an unreliable upstream feel stable to the person clicking
the button.

**Currently:** Full Stack Developer at Power Telecom · Software Engineering student at Estácio · English C2

---

## Open source

### [DevOps Command Center](https://github.com/GuguPx/devops-command-center)

A wallpaper that turns into a live DevOps dashboard. Wallpaper Engine scenes run
sandboxed — no file, network, or process access — so they can only ever fake metrics.
This pairs the wallpaper with a zero-dependency Node agent on localhost that collects
real data and serves it as JSON.

- Collectors for CPU/memory/disk/network (`os` + WMI), `docker ps/stats`, git across
  multiple repos, and Claude Code transcripts — each on its own timer with in-memory caching
- Security model is explicit: localhost-only bind, CORS restricted to the wallpaper
  origin, allowlisted static routes, size-capped POST body
- Falls back to animated demo data when the agent isn't running, so it stays usable
  for anyone installing from the Steam Workshop

`Node.js` · `JavaScript` · `PowerShell/WMI` · `Docker` · `GitHub Actions`

### [devsheet](https://github.com/GuguPx/Dev-sheets-Wallpaper)

A dev/DevOps cheat-sheet terminal, also built as a wallpaper. 224 commands across 10
technologies, with search and keyboard navigation, fully offline.

- Plain TypeScript, no framework — tmux-style tabs, Neovim-style statusline, fzf-style
  search, man-page detail view
- Content is one JSON per technology, validated with Zod at build time; CI runs lint,
  types, content validation, tests, and build
- Ships as a single self-contained HTML file (`vite-plugin-singlefile`) — nothing fetched
  at runtime
- The terminal is visual only: no eval, no shell, no file access. Destructive commands
  are flagged and require double confirmation to copy

`TypeScript` · `Vite` · `Zod` · `Vitest` · `GitHub Actions`

---

## Work

**Power Telecom** — Full Stack Developer · Feb 2026 – present
*(Tier 1 Technical Support, internship · Nov 2025 – Feb 2026)*

Internal systems for the sales, finance, and HR sides of an internet provider:

- **Sales CRM** integrated with the IXC ERP — lead-to-contract funnel, draggable Kanban,
  georeferenced lead map, guided drawer forms, contract creation and service-order opening
- **Contract management** with digital signature, identity validation, and renewal/cancellation flows
- **HR platform** for employee management, plus headquarters inventory management
- **Six production bots** — overdue-payment monitoring, commercial routines, payment-error
  triage, ticket reporting, open-sales sync — on node-cron and PM2 with structured logging
- Integrations with IXC Soft, OPA Suite, ZapSign, WhatsApp, and Google Sheets

Detailed case studies — problem, architecture, trade-offs, what broke — are on the
[portfolio](https://portfolioaugusto.vercel.app).

---

## Stack

**Frontend**
![React](https://img.shields.io/badge/React-0E7C7B?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0E7C7B?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-0E7C7B?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-0E7C7B?style=flat-square&logo=vite&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-0E7C7B?style=flat-square&logo=reactquery&logoColor=white)

**Backend & data**
![Node.js](https://img.shields.io/badge/Node.js-115E5C?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-115E5C?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-115E5C?style=flat-square&logo=mysql&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-115E5C?style=flat-square&logo=zod&logoColor=white)

**Ops & tooling**
![Docker](https://img.shields.io/badge/Docker-1F3F42?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-1F3F42?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1F3F42?style=flat-square&logo=githubactions&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-1F3F42?style=flat-square&logo=pm2&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-1F3F42?style=flat-square&logo=vitest&logoColor=white)

I use AI tooling (Claude Code) for scaffolding, refactoring, and documentation — always
with human review and technical validation before anything ships.

---

## Open to

Remote roles building ERP, CRM, or operational software — especially for the ISP and
telecom segment, where the domain knowledge transfers directly.

**augustopxsilva@gmail.com** · [Portfolio](https://portfolioaugusto.vercel.app) · [LinkedIn](https://www.linkedin.com/in/augusto-px-silva/)
