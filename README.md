<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,35:312E81,70:6D28D9,100:A855F7&text=Augusto%20Silva&fontColor=FFFFFF&fontSize=52&fontAlignY=38&desc=DevOps%20%7C%20Full-Stack%20%7C%20Automation&descAlignY=58&descSize=18&animation=fadeIn" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code\&weight=600\&size=24\&duration=2800\&pause=900\&color=A855F7\&center=true\&vCenter=true\&width=750\&lines=DevOps+Engineer;Full-Stack+Developer;Automation+%26+Observability;Building+Reliable+Software)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-GuguPx-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/GuguPx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Augusto%20Silva-6D28D9?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/augusto-px-silva/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Projects-A855F7?style=for-the-badge\&logo=vercel\&logoColor=white)](https://github.com/GuguPx?tab=repositories)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=GuguPx\&style=flat-square\&color=7C3AED\&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/GuguPx?style=flat-square\&logo=github\&label=FOLLOWERS\&color=6D28D9)
![Stars](https://img.shields.io/github/stars/GuguPx?affiliations=OWNER\&style=flat-square\&logo=github\&label=STARS\&color=A855F7)

</div>

---

## About

```yaml
name: Augusto Silva
role:
  - DevOps Engineer
  - Full-Stack Developer

mission: "Ship reliable software"

focus:
  - DevOps & Infrastructure
  - Full-Stack Engineering
  - Automation
  - Observability
  - Developer Tooling
```

I build software with an engineering mindset focused on **automation, reliability, observability and maintainability**.

My work spans the full delivery lifecycle — from application development and APIs to databases, containers, CI/CD pipelines, reverse proxies and Linux environments.

I enjoy transforming repetitive operational tasks into automated workflows and building tools that give developers better visibility into their systems.

My current ecosystem includes **TypeScript, JavaScript, React, Node.js, PostgreSQL, Redis, MySQL, Docker, GitHub Actions, Nginx, PM2, Linux and Zabbix**.

### Open To

* DevOps engineering challenges
* Full-Stack projects
* Backend and API development
* Automation and internal tooling
* Open-source collaboration
* Developer experience projects

---

## Tech Stack

### Languages

<div align="center">

[![Languages](https://skillicons.dev/icons?i=ts,js,html,css,bash\&theme=dark)](https://skillicons.dev)

</div>

### Frontend

<div align="center">

[![Frontend](https://skillicons.dev/icons?i=react,vite,tailwind\&theme=dark)](https://skillicons.dev)

</div>

### Backend & Databases

<div align="center">

[![Backend](https://skillicons.dev/icons?i=nodejs,postgres,mysql,redis\&theme=dark)](https://skillicons.dev)

</div>

### Cloud, DevOps & Tooling

<div align="center">

[![DevOps](https://skillicons.dev/icons?i=docker,linux,git,github,githubactions,nginx,vscode\&theme=dark)](https://skillicons.dev)

</div>

---

## AI / Automation Expertise

| Domain                        | Proficiency | Details                                                                             |
| :---------------------------- | :---------: | :---------------------------------------------------------------------------------- |
| **AI-Assisted Engineering**   |  Practical  | AI-assisted development workflows integrated into daily engineering tooling         |
| **LLM Tooling Observability** |  Practical  | Local collection and visualization of Claude Code usage, tokens and cost data       |
| **Developer Automation**      |    Strong   | APIs, automated tasks, integrations and operational tooling                         |
| **System Observability**      |    Strong   | CPU, memory, disk, network, process, Docker and Git telemetry                       |
| **Local-First Tooling**       |    Strong   | Developer tools designed to operate against local system data without external APIs |
| **Workflow Automation**       |    Strong   | CI/CD pipelines, quality gates, packaging and deployment workflows                  |

---

## Featured Projects

<details>
<summary><strong>DevOps Command Center — Live Developer & Infrastructure Observability</strong></summary>

<br/>

A live **Full-Stack / DevOps command station** that transforms Wallpaper Engine into a real-time developer operations dashboard.

Instead of displaying simulated metrics, a lightweight Node.js agent collects information directly from the local machine and exposes it to the interface.

|                  |                                                                                        |
| :--------------- | :------------------------------------------------------------------------------------- |
| **Stack**        | Node.js · JavaScript · HTML · CSS · Docker · Git · WMI                                 |
| **Data**         | CPU · Memory · Disk · Network · Processes · Docker · Git · Claude Code                 |
| **Architecture** | Local Node agent + cached collectors + HTTP interface                                  |
| **Performance**  | Independent collector timers prevent slow operations from blocking UI updates          |
| **Security**     | `127.0.0.1` binding, scoped CORS, request-size limits and static route allowlisting    |
| **Automation**   | ESLint · Prettier · GitHub Actions                                                     |
| **Impact**       | Turns real developer infrastructure telemetry into a persistent desktop command center |
| **Repository**   | [GuguPx/devops-command-center](https://github.com/GuguPx/devops-command-center)        |

### Engineering Highlights

* Reads actual machine metrics instead of relying only on demo data.
* Monitors running Docker containers and resource consumption.
* Aggregates Git activity across multiple repositories.
* Tracks Claude Code token and cost usage locally.
* Detects operational events between telemetry snapshots.
* Uses cached collectors to keep expensive operations away from HTTP request handling.
* Includes automatic demo/live data switching.
* Ships with CI validation on pushes and pull requests.
* Runs without requiring external API tokens.

</details>

<br/>

<details>
<summary><strong>DevSheet — Interactive DevOps Knowledge Terminal</strong></summary>

<br/>

An interactive **terminal-inspired developer reference system** built as a Web Wallpaper.

The interface combines concepts inspired by **Tmux, Neovim, FZF and Linux man pages** to create a keyboard-driven environment for consulting development and DevOps commands.

|                  |                                                                                |
| :--------------- | :----------------------------------------------------------------------------- |
| **Stack**        | TypeScript · Vite · Zod · Vitest · HTML · CSS                                  |
| **Content**      | 10 technologies · 224 commands                                                 |
| **Coverage**     | Git · Docker · Compose · Linux · Bash · SSH · Nginx · PM2 · PostgreSQL · Redis |
| **Architecture** | Offline-first single-page application                                          |
| **Quality**      | Type checking · schema validation · tests · lint · formatting                  |
| **Security**     | Command whitelist; no shell execution, filesystem access or `eval`             |
| **Delivery**     | Automated single-file Wallpaper Engine build                                   |
| **Repository**   | [GuguPx/Dev-sheets-Wallpaper](https://github.com/GuguPx/Dev-sheets-Wallpaper)  |

### Engineering Highlights

* 224 curated development and DevOps commands.
* Structured JSON content validated using Zod.
* Fuzzy-search inspired navigation.
* Terminal-style keyboard controls.
* Favorites, history and local notes.
* Multiple terminal themes and CRT effects.
* Full offline operation.
* Automated GitHub Actions pipeline running formatting, linting, types, content validation, tests and build.
* Destructive commands require additional confirmation before copying.
* The application never executes operating-system commands.

</details>

<br/>

<details>
<summary><strong>Conecta SUS — Modern React Frontend</strong></summary>

<br/>

A frontend application currently structured around a modern React and TypeScript ecosystem.

|                  |                                                             |
| :--------------- | :---------------------------------------------------------- |
| **Stack**        | React 19 · TypeScript · Vite 8 · Tailwind CSS 4             |
| **State**        | Zustand                                                     |
| **Routing**      | React Router                                                |
| **Animation**    | Framer Motion                                               |
| **Quality**      | ESLint · TypeScript build validation                        |
| **Architecture** | Modern client-side React application                        |
| **Stage**        | Active development                                          |
| **Repository**   | [GuguPx/conecta-sus](https://github.com/GuguPx/conecta-sus) |

The project demonstrates a modern frontend foundation focused on component-driven development, client-side state management and production builds through Vite.

</details>

---

## Experience

### DevOps & Full-Stack Engineering

**Independent Engineering Projects**

Focused on designing, building and operating developer tools and full-stack systems across application and infrastructure layers.

#### Scope

* Development of frontend applications using React and TypeScript.
* Backend and automation services using Node.js.
* REST API and integration development.
* PostgreSQL, Redis and MySQL environments.
* Containerized workflows with Docker.
* Reverse proxy configuration with Nginx.
* CI/CD pipelines using GitHub Actions.
* Linux environment administration.
* Process management with PM2.
* Monitoring and operational visibility.
* Developer tooling and workflow automation.

#### Core Skills

![TypeScript](https://img.shields.io/badge/TypeScript-18181B?style=flat-square\&logo=typescript\&logoColor=A855F7)
![React](https://img.shields.io/badge/React-18181B?style=flat-square\&logo=react\&logoColor=A855F7)
![Node.js](https://img.shields.io/badge/Node.js-18181B?style=flat-square\&logo=nodedotjs\&logoColor=A855F7)
![Docker](https://img.shields.io/badge/Docker-18181B?style=flat-square\&logo=docker\&logoColor=A855F7)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-18181B?style=flat-square\&logo=postgresql\&logoColor=A855F7)
![Linux](https://img.shields.io/badge/Linux-18181B?style=flat-square\&logo=linux\&logoColor=A855F7)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-18181B?style=flat-square\&logo=githubactions\&logoColor=A855F7)
![Nginx](https://img.shields.io/badge/Nginx-18181B?style=flat-square\&logo=nginx\&logoColor=A855F7)

---

## Achievements

<div align="center">

| Recognition                           | Details                                                                                           |
| :------------------------------------ | :------------------------------------------------------------------------------------------------ |
| **Real-Time DevOps Telemetry**        | Built tooling that reads live CPU, memory, disk, network, Docker, Git and developer-usage metrics |
| **224-Command DevOps Knowledge Base** | Structured developer reference covering 10 core technologies                                      |
| **Local-First Architecture**          | Built developer tooling capable of operating locally without external API dependencies            |
| **Automated Quality Gates**           | Implemented CI pipelines covering formatting, linting, types, validation, tests and builds        |
| **Security-Focused Local Agent**      | Restricted telemetry APIs to localhost with scoped CORS and protected static resources            |
| **Cross-Disciplinary Engineering**    | Projects spanning frontend, backend, DevOps, automation, observability and DX                     |

</div>

---

## Certifications

<div align="center">

![Verified](https://img.shields.io/badge/Credentials-Verified%20Only-6D28D9?style=for-the-badge\&logo=checkmarx\&logoColor=white)

</div>

Only publicly verifiable credentials are included in this profile. Certification details can be added when available.

---

## Coding Profiles

<div align="center">

[![GitHub](https://img.shields.io/badge/GITHUB-GuguPx-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/GuguPx)

</div>

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=GuguPx&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9&icon_color=7C3AED" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GuguPx&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9" />

<br/>

<img src="https://streak-stats.demolab.com?user=GuguPx&hide_border=true&background=0D1117&stroke=30363D&ring=A855F7&fire=7C3AED&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=A855F7&sideLabels=C9D1D9&dates=8B949E" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=GuguPx&theme=discord&no-frame=true&no-bg=true&margin-w=10&margin-h=10&column=7" />

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=GuguPx&bg_color=0d1117&color=c9d1d9&line=8b5cf6&point=a855f7&area=true&hide_border=true" width="100%" />

</div>

---

## Contribution Snake

<div align="center">

> Contribution snake generation can be enabled through GitHub Actions without adding external credentials.

</div>

---

## Current Focus

```yaml
learning:
  - Advanced DevOps practices
  - System design
  - Observability
  - Infrastructure automation

building:
  - Developer tooling
  - Automation systems
  - Full-Stack applications
  - Reliable delivery pipelines

exploring:
  - AI-assisted engineering
  - Local-first software
  - Developer experience
  - System telemetry

open_to:
  - DevOps challenges
  - Full-Stack projects
  - Open-source collaboration
  - Automation projects
```

---

## Connect

<div align="center">

### Let's build reliable software.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-CONNECT-6D28D9?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/augusto-px-silva/)
[![GitHub](https://img.shields.io/badge/GitHub-FOLLOW-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/GuguPx)
[![Portfolio](https://img.shields.io/badge/Portfolio-EXPLORE-A855F7?style=for-the-badge\&logo=vercel\&logoColor=white)](https://github.com/GuguPx?tab=repositories)

</div>

---

<div align="center">

### “Ship reliable software. Automate what repeats. Observe what matters.”

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:A855F7,40:6D28D9,70:312E81,100:0D1117" />
