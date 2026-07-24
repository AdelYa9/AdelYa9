# Hi there, I'm Adel Yafi 👋

### Data Engineer | Business Intelligence Analyst

I build robust data architectures, automated ETL pipelines, and AI-assisted data governance systems. I focus on solving complex upstream data issues using modern engineering patterns and observability practices. 

- 🎓 M.S. in Business Intelligence & Data Analytics (Washington State University).
- 📜 Certified in AI Fluency Framework & Foundations (Anthropic).
- 🤝 Open to remote engineering and analytics contracts.

---

## 🏆 Featured Engineering Projects

### 🛡️ [Agentic ETL Gatekeeper](https://github.com/AdelYa9/agentic-etl-gatekeeper)
An autonomous, self-healing data pipeline built to tackle upstream schema drift in Trust & Safety moderation logs.
* **Architecture:** Implements a strict Write-Audit-Publish (WAP) loop using **DuckDB** for isolated staging.
* **Agentic Healing:** Integrates a local **Llama 3** model to dynamically flatten and parse mutated JSON payloads only when drift is actively detected.
* **Governance:** Secured via native CI/CD workflows utilizing **Bandit** for Python linting and a Dockerized **TruffleHog** container for deep filesystem secret scanning.

### ❄️ Trust & Safety Analytics Engine
A cloud-native data transformation project utilizing **dbt** and **Snowflake**.
* Configured Snowflake connection profiles, built staging models, and executed automated `dbt seed` and `run` commands to orchestrate data transformations.

### 🏦 FinTech SQL Vault
A containerized financial database designed for secure data availability and reporting.
* Engineered custom data seeder scripts and implemented strict Role-Based Access Control (RBAC).
* Fully integrated with **Power BI** for downstream dashboarding and analytics.

### 🔄 Project Nexus
An automated API-to-Data Lake ETL pipeline.
* Engineered a fully version-controlled extraction process to seamlessly pull API data and sink it into a structured data lake environment.

---

## 🛠️ Tech Stack & Tools

* **Languages:** Python, SQL
* **Data Engineering:** dbt, Snowflake, DuckDB
* **Business Intelligence:** MS Power BI
* **AI & Agentic Workflows:** Llama 3, Anthropic Frameworks
* **DevOps & Security:** Git, GitHub Actions, Docker, Bandit, TruffleHog

---
