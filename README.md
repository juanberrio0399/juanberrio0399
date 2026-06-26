<h1 align="center">Hi, I'm Juan Berrio 👋</h1>
<h3 align="center">Cloud &amp; Data Engineer · building toward Cloud Architect ☁️</h3>

<p align="center">
I design <b>serverless data platforms</b> that turn messy business data into reliable, low-cost decision systems — from ETL pipelines to cloud dashboards that update themselves.
</p>

<p align="center">
  <a href="https://juanberrio0399.github.io"><img src="https://img.shields.io/badge/🌐%20Portfolio-juanberrio0399.github.io-22d3ee?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/juanberrioo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:juandyb99@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Bogot%C3%A1,%20Colombia-Remote%20·%20GMT--5-2ea44f?style=for-the-badge" alt="Location"/>
</p>

---

### 👋 About me

Hi! I'm **Juan**, a Cloud & Data Engineer from Bogotá 🇨🇴. I love taking messy, manual, Excel-driven processes and turning them into **cloud systems that run themselves** — quietly, reliably, and on almost no budget.

What that looks like in practice:

- ☁️ I think in **architecture** — separating compute, storage and presentation, choosing serverless over servers, and squeezing cost down (some of my systems run on **~$0 infrastructure**).
- 🧩 I build **end-to-end**: ETL in Python → analytical warehouses (DuckDB) → object storage (Cloudflare R2) → serverless dashboards (React + DuckDB-WASM) → CI/CD (GitHub Actions).
- 🤖 I work hands-on with **AI / LLMs and prompt engineering** to build assistive tools and automate work.
- 🎓 Right now I'm leveling up on **AWS** and **Systems Engineering**, heading toward **Cloud Solutions Architect**.

**Fun facts:** I shipped a production data platform solo · I'm also building a game from scratch in Roblox 🎮 · I'd rather automate a task once than do it twice.

> 🇪🇸 ¡Hola! Soy Juan, ingeniero Cloud & Datos. Convierto procesos manuales y caóticos en sistemas cloud que se operan solos, de bajo costo y de punta a punta. En camino a Arquitecto de Soluciones Cloud.

🌎 **Open to remote roles** (Cloud / Data Engineering) and consulting.

---

### 🛠️ Tech stack

**Cloud & DevOps**

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-(learning)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white)

**Data Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**BI, Web & Automation**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**AI / LLM**

![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-5A4FCF?style=flat-square)
![LLM Integration](https://img.shields.io/badge/LLM%20Integration-1A7F64?style=flat-square)
![AI Automation](https://img.shields.io/badge/AI%20Automation-FF6F00?style=flat-square)

---

### 📂 Featured projects

> Most repos are private (client work). Full write-ups with architecture & results live in my **[📁 portfolio](https://github.com/juanberrio0399/portfolio)**.

#### ☁️ DataForge Cloud — Serverless analytics platform
Hybrid cloud architecture: a local ETL worker publishes to **Cloudflare R2**, and a **serverless dashboard** (Cloudflare Pages + React + **DuckDB-WASM**) queries Parquet *directly in the browser* — no backend, no database to maintain, ~$0 infra. A parallel 100%-cloud path (Power Automate → R2 → GitHub Actions) ingests other sources.
`Cloudflare R2/Pages` · `React + DuckDB-WASM` · `GitHub Actions` · `Power Automate`
→ **[Read the case study](https://github.com/juanberrio0399/portfolio/blob/main/case-studies/01-dataforge-customs-reconciliation_EN.md)**

#### 🦆 DataForge — ETL pipeline & analytical warehouse
Production ETL (~4,100 lines, layered `readers → transforms → writers`) that incrementally ingests business Excel into **Parquet** and exposes a **DuckDB** warehouse. Package-level customs tax reconciliation across 5 sources. Runs unattended 3×/day.
`Python` · `Pandas` · `DuckDB` · `Parquet`

#### 🛡️ UGPP Shield Pro — Cloud web app for finance leaders
Web application aimed at CFOs for fiscal/compliance intelligence, deployed on **Cloudflare Pages**.
`JavaScript` · `Vite` · `Cloudflare Pages`

#### 🤖 Oportunia — AI-assisted freelance prospecting
A personal system that finds and qualifies freelance opportunities using AI.
`Python` · `AI / LLM`

#### ⚙️ Logistics Portal Automation (RPA) — Playwright bot
Bot that uploads/downloads documents to an e-commerce logistics portal, matching records by business rules — eliminating repetitive manual work.
`Python` · `Playwright`

#### 🎮 Hearthwood — Roblox game (side project)
A cooperative survival game built from scratch by phases — full client-server architecture across ~23 services. Shows systems design beyond data.
`Luau` · `Roblox`

---

### 📈 Currently learning

`AWS (Cloud Practitioner → Solutions Architect)` · `Systems Engineering (Uniminuto)` · `English → B2` · `dbt`

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=juanberrio0399&show_icons=true&count_private=true&hide_border=true&theme=default" alt="GitHub stats" height="160"/>
</p>

<p align="center"><i>📫 Let's build something that scales — <a href="mailto:juandyb99@gmail.com">juandyb99@gmail.com</a></i></p>
