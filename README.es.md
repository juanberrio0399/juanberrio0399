<h1 align="center">Hola, soy Juan Berrio 👋</h1>
<h3 align="center">Cloud &amp; Data Engineer · en camino a Cloud Architect ☁️</h3>

<p align="center">
Diseño <b>plataformas de datos serverless</b> que convierten datos de negocio desordenados en sistemas de decisión confiables y de bajo costo — desde pipelines ETL hasta dashboards cloud que se actualizan solos.
</p>

<p align="center">
  <a href="https://juanberrio0399.github.io"><img src="https://img.shields.io/badge/🌐%20Portafolio-juanberrio0399.github.io-22d3ee?style=for-the-badge" alt="Portafolio"/></a>
  <a href="https://www.linkedin.com/in/juanberrioo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:juandyb99@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Bogot%C3%A1,%20Colombia-Remoto%20·%20GMT--5-2ea44f?style=for-the-badge" alt="Ubicación"/>
</p>

<p align="center"><a href="README.md">English</a> · <b>🌐 Español</b></p>

---

### 👋 Sobre mí

¡Hola! Soy **Juan**, **Ingeniero de Datos** de Bogotá 🇨🇴 con 6+ años en ETL, modelado dimensional y warehouses analíticos. Me gusta convertir datos manuales y caóticos (de Excel) en **sistemas confiables que se operan solos** — y llevarlos a la nube, a casi cero costo.

Cómo se ve eso en la práctica:

- ☁️ Pienso en **arquitectura** — separo cómputo, almacenamiento y presentación, elijo serverless sobre servidores y bajo el costo al mínimo (algunos de mis sistemas corren con **~$0 de infraestructura**).
- 🧩 Construyo **de punta a punta**: ETL en Python → warehouses analíticos (DuckDB) → almacenamiento de objetos (Cloudflare R2) → dashboards serverless (React + DuckDB-WASM) → CI/CD (GitHub Actions).
- 📊 Hoy mis pipelines procesan **más de 30M de registros** (creciendo ~2M/mes).
- 🤖 Trabajo directamente con **IA / LLMs y prompt engineering** para construir herramientas asistidas y automatizar trabajo.
- 🎓 Actualmente subo de nivel en **AWS** e **Ingeniería de Sistemas**, en camino a **Arquitecto de Soluciones Cloud**.

**Datos curiosos:** desplegué una plataforma de datos en producción yo solo · también construyo un juego desde cero en Roblox 🎮 · prefiero automatizar una tarea una vez antes que hacerla dos veces.

🌎 **Abierto a roles remotos** (Cloud / Data Engineering) y consultoría.

---

### 🛠️ Stack técnico

**Cloud & DevOps**

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-(en%20formación)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white)

**Data Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**BI, Web & Automatización**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**IA / LLM**

![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-5A4FCF?style=flat-square)
![LLM Integration](https://img.shields.io/badge/LLM%20Integration-1A7F64?style=flat-square)
![AI Automation](https://img.shields.io/badge/AI%20Automation-FF6F00?style=flat-square)

---

### 📂 Proyectos destacados

> La mayoría de repos son privados (trabajo de cliente). Los write-ups completos con arquitectura y resultados están en mi **[📁 portafolio](https://github.com/juanberrio0399/portfolio)**.

#### ☁️ DataForge Cloud — Plataforma de analítica serverless
Arquitectura cloud híbrida: un worker ETL local publica en **Cloudflare R2**, y un **dashboard serverless** (Cloudflare Pages + React + **DuckDB-WASM**) consulta Parquet *directo en el navegador* — sin backend, sin base de datos que mantener, ~$0 de infra. Un camino paralelo 100% nube (Power Automate → R2 → GitHub Actions) ingiere otras fuentes.
`Cloudflare R2/Pages` · `React + DuckDB-WASM` · `GitHub Actions` · `Power Automate`
→ **[Ver el case study](https://github.com/juanberrio0399/portfolio/blob/main/case-studies/01-dataforge-customs-reconciliation_ES.md)**

#### 🦆 DataForge — Pipeline ETL y warehouse analítico
ETL en producción (~4.100 líneas, arquitectura `readers → transforms → writers`) que ingiere Excel de negocio de forma incremental a **Parquet** y expone un warehouse **DuckDB**. Conciliación tributaria guía a guía sobre 5 fuentes. Corre solo 3×/día.
`Python` · `Pandas` · `DuckDB` · `Parquet`

#### 🛡️ UGPP Shield Pro — Web app cloud para líderes financieros
Aplicación web orientada a CFOs para inteligencia fiscal y de cumplimiento, desplegada en **Cloudflare Pages**.
`JavaScript` · `Vite` · `Cloudflare Pages`

#### ⚙️ Automatización de portal logístico (RPA) — Bot Playwright
Bot que sube/descarga documentos a un portal logístico de e-commerce, emparejando registros por reglas de negocio — elimina trabajo manual repetitivo.
`Python` · `Playwright`

#### 🎮 Hearthwood — Juego de Roblox (side project)
Juego cooperativo de supervivencia construido desde cero por fases — arquitectura cliente-servidor en ~23 servicios. Demuestra diseño de sistemas más allá de datos.
`Luau` · `Roblox`

---

### 📈 Aprendiendo ahora

✅ Completé **AWS Cloud Practitioner Essentials** (AWS Training & Certification · jun. 2026) — preparando el examen de certificación Cloud Practitioner.

`AWS (Cloud Practitioner → Solutions Architect)` · `Ingeniería de Sistemas (Corporación Universitaria Americana)` · `Inglés → B2` · `dbt`

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=juanberrio0399&show_icons=true&count_private=true&hide_border=true&theme=default" alt="GitHub stats" height="160"/>
</p>

<p align="center"><i>📫 Construyamos algo que escale — <a href="mailto:juandyb99@gmail.com">juandyb99@gmail.com</a></i></p>
