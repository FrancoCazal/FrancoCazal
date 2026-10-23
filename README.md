<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1200&color=58A6FF&center=true&vCenter=true&width=600&height=80&lines=Hi%2C+I'm+Franco+%F0%9F%91%8B;AI+%26+ML+Engineer" alt="Typing SVG" />
</p>

<p align="center">
  <strong>AI & ML Engineer · applied AI: agentic systems & RAG in production on AWS.</strong><br>
  I take applied AI from prototype to production: agents and RAG measured with evals, ML models measured against baselines, and the Python backends and AWS infrastructure they run on.
</p>

<p align="center">📍 Lambaré, Paraguay · GMT-3 · remote</p>

<p align="center">
  <a href="https://francocazal.com">
    <img src="https://img.shields.io/badge/Visit_my_Portfolio-francocazal.com-58A6FF?style=for-the-badge&labelColor=0d1117" alt="francocazal.com" />
  </a>
</p>

---

### 🚀 About Me

**`$ whoami`**

> I'm Franco Cazal, an AI & ML engineer. I build applied AI that holds up in production, and I own it end to end, from the data model and the evals to the deploy. I co-founded [Focal Point](https://github.com/FrancoCazal/focalpoint-case-study) and led its engineering from 2023 to 2026. Outside coding: music · philosophy · psychology.

**`$ stack --by-domain`**

| | What | Proof |
|---|---|---|
| **ai** | LangGraph agents, hybrid RAG (pgvector + BM25), golden-set evals, cost-aware model routing (Bedrock and Vertex AI in WhisperDocs) | [Focal Point](https://github.com/FrancoCazal/focalpoint-case-study) · [WhisperDocs](https://github.com/FrancoCazal/WhisperDocs) · [SilentOps](https://github.com/FrancoCazal/SilentOps) |
| **ml** | scikit-learn, gradient boosting (LightGBM), conformal prediction, rolling-origin backtests with leakage tests | [Blindside](https://github.com/FrancoCazal/Blindside) · [AgroBuy](https://github.com/FrancoCazal/AgroBuy) |
| **backend** | Python (FastAPI, Django, Celery), PostgreSQL, Redis, schema-per-tenant isolation | [Focal Point](https://github.com/FrancoCazal/focalpoint-case-study) · [WhisperDocs](https://github.com/FrancoCazal/WhisperDocs) · [Urban Attic](https://github.com/FrancoCazal/UrbanAttic) |
| **cloud** | AWS (EC2, RDS, S3, SES) provisioned with Terraform, Docker, GitHub Actions | [Focal Point](https://github.com/FrancoCazal/focalpoint-case-study) · [WhisperDocs](https://github.com/FrancoCazal/WhisperDocs) · [Urban Attic](https://github.com/FrancoCazal/UrbanAttic) |
| **front** | React + TypeScript, when the product needs a front | [Focal Point](https://github.com/FrancoCazal/focalpoint-case-study) · [Blindside](https://github.com/FrancoCazal/Blindside) · [Urban Attic](https://github.com/FrancoCazal/UrbanAttic) |

**`$ available`**

> Based in Lambaré, Paraguay (GMT-3), working remote; most of my work is async with US and Spanish-speaking teams. Open to AI & ML, AI backend and cloud engineering roles. English (C2) · Spanish (native).

---

### 🛠️ Tech Stack

**Backend & AI**

![Python](https://img.shields.io/badge/python-3670A8?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Celery](https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

**Cloud, Ops & Tooling**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

---

### 🧭 How I work

Every feature moves through the same loop: spec first, then code, review and CI. Only green tests deploy; then I measure and start again. Each practice below links to the public artifact that shows it.

- **Spec before code** · SilentOps: the [spec](https://github.com/FrancoCazal/SilentOps/blob/main/SILENTOPS.md), the frozen contracts and the [file-ownership map](https://github.com/FrancoCazal/SilentOps/tree/main/team-docs) four people built against in parallel.
- **Evals as tests** · WhisperDocs: a 50-query suite, [96% on the last full run](https://github.com/FrancoCazal/WhisperDocs/blob/main/eval/reports/2026-04-28_b2b0899a.md) · SilentOps: [15 golden cases](https://github.com/FrancoCazal/SilentOps/tree/main/packages/loop-core/evals), 5/15 on a live model · Blindside: [leakage tests](https://github.com/FrancoCazal/Blindside/blob/main/tests/test_leakage.py) in CI.
- **CI and infra as code** · GitHub Actions runs the tests on WhisperDocs, SilentOps, Blindside and Urban Attic; Focal Point's AWS stack is [Terraform modules](https://github.com/FrancoCazal/focalpoint-case-study).
- **Decisions written down** · WhisperDocs: [four ADRs](https://github.com/FrancoCazal/WhisperDocs/tree/main/docs/adr), from LangGraph to dual-provider routing.
- **AI-augmented, on my own harness** · Claude Code with my own sub-agents, hooks, MCP servers and skills: the harness these repos were built with.

---

### 🚧 Now

- ☁️ Preparing the AWS Solutions Architect Associate (SAA-C03). Cloud Practitioner and AI Practitioner done in 2026.
- 🧠 Finished the FIUNA Machine Learning & Deep Learning diploma. Capstone: [Blindside](https://github.com/FrancoCazal/Blindside), perishable demand forecasting that recovers stockout-censored demand and turns the forecast into an order quantity.
- 🏆 Two AI Tinkerers hackathons in 2026: [AgroBuy](https://github.com/FrancoCazal/AgroBuy), 1st place at San Lorenzo x FIUNA Deep Dive (April), and [SilentOps](https://github.com/FrancoCazal/SilentOps) at the *Agents, Everywhere* global hackathon (September).
- 🤝 Community: AI Tinkerers San Lorenzo · FIUNA computing club · volunteer at AWS User Group Paraguay · attendee at AI Tinkerers Asunción and GDG Asunción.

---

### 📊 GitHub Stats

<p align="center">
  <img height="180em" src="https://streak-stats.demolab.com?user=FrancoCazal&theme=tokyonight&hide_border=true&card_width=420" />
</p>

---

### 📫 Let's Connect

<p align="center">
  <a href="https://francocazal.com"><img src="https://img.shields.io/badge/Website-francocazal.com-0d1117?style=for-the-badge&logo=safari&logoColor=white" /></a>
  <a href="https://github.com/FrancoCazal"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/francocazal/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:contact@francocazal.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
