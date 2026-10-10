# Hi, I'm Berke 👋

**Software engineer — backend, data & platform.** CS + Management graduate, LUISS Guido Carli, Rome (Jul 2026).
I build REST APIs in FastAPI, Node.js and ASP.NET Core, queue-driven workers with idempotency and retries, and Airflow/dbt pipelines gated by data-quality tests.

📍 İzmir, Turkey · 🟢 open to junior roles — relocation or remote

[![Website](https://img.shields.io/badge/berketayfunakseki.com-0A0D13?style=for-the-badge&logo=googlechrome&logoColor=FFB454)](https://berketayfunakseki.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/berke-tayfun-akseki-489b842ba/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:berketayfunakseki@gmail.com)
[![CV](https://img.shields.io/badge/CV-PDF-3DDBA4?style=for-the-badge)](https://berketayfunakseki.com/BerkeTayfunAksekiCV.pdf)

---

### 🔨 Currently building

**Project PARCA** *(private — walkthrough on request)* — a deterministic rules engine and game server in C# / ASP.NET Core for a multi-day, eight-player strategy game. A seeded RNG replays an entire season exactly, the server owns the clock and the ledger, and a **146-case regression suite** passes in full.

### ⭐ Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| ⚡ **[energy-connect-platform](https://github.com/berketayfunakseki/energy-connect-platform)** | EV-charger connectivity layer: API + worker over a PostgreSQL queue with `FOR UPDATE SKIP LOCKED`, idempotency keys, retries behind a circuit breaker, Prometheus metrics, AWS CDK infra | TypeScript · Node.js · PostgreSQL · AWS CDK |
| 🏗️ **[analytics-data-platform](https://github.com/berketayfunakseki/analytics-data-platform)** | Batch pipeline: Airflow → PySpark → Parquet → PostgreSQL → dbt, with data-quality tests that fail the DAG on a bad load | Airflow · PySpark · dbt · Docker |
| 🔍 **[jobscope](https://github.com/berketayfunakseki/jobscope)** | Swiss/EU job-market tracker — aggregates 200+ live listings and ranks each 0–100 with TF-IDF cosine similarity behind a JWT-auth API | FastAPI · scikit-learn · Docker |
| 🧪 **[causal-lab](https://github.com/berketayfunakseki/causal-lab)** | A/B testing & difference-in-differences toolkit — power analysis, z-tests, SRM detection, two-way fixed-effects DiD, validated against injected ground truth | SciPy · statsmodels · FastAPI |
| 🤖 **[regulatory-rag-assistant](https://github.com/berketayfunakseki/regulatory-rag-assistant)** | RAG over regulatory PDFs — chunking, embeddings, FAISS semantic search, CI on every push | FAISS · FastAPI · Streamlit |
| 📊 **[sql-analytics-lab](https://github.com/berketayfunakseki/sql-analytics-lab)** | Cohort retention & funnel analysis in raw SQL — window functions, multi-CTE queries | SQL · SQLite |

<details>
<summary><b>More projects</b></summary>
<br>

- 📈 **[churn-ml-api-dashboard](https://github.com/berketayfunakseki/churn-ml-api-dashboard)** — churn classifier with a reproducible scikit-learn pipeline, served via FastAPI and Streamlit
- 🌍 **[oralb-geoanalytics-2026](https://github.com/berketayfunakseki/oralb-geoanalytics-2026)** — client team project for P&G: store-level campaign optimisation in KNIME + Power BI
- 📚 **[django-crud-auth-app](https://github.com/berketayfunakseki/django-crud-auth-app)** — server-rendered Django app with auth and guarded CRUD
- 🎮 **Labyscape** *(private)* — 2–8 player co-op horror game, Unity 6 + Netcode, procedural DFS mazes

</details>

### 🧰 Stack

| | |
| --- | --- |
| **Languages** | Python · TypeScript · JavaScript · C# · SQL · R |
| **Backend** | FastAPI · Node.js · ASP.NET Core · Django · SQLAlchemy · Pydantic · JWT/OAuth2 |
| **Data** | PostgreSQL · Airflow · PySpark · dbt · Parquet · Pandas |
| **ML & stats** | scikit-learn · statsmodels · SciPy · FAISS · A/B testing · difference-in-differences |
| **Cloud & DevOps** | Docker · AWS (ECS/Fargate, RDS, CDK) · GitHub Actions · Prometheus · Grafana |

### 🎓 Also

- **Thesis** — tourism dependence and regional resilience in Italy: a 2015–2024 panel of 21 NUTS-2 regions in R, difference-in-differences with an event study. The same estimator family powers `causal-lab`.
- **Languages** — Turkish (native) · English (C1) · French (B2) · Italian (B1)
- **Work authorisation** — Turkish citizen; for Italy, entitled to a 12-month post-graduation permit convertible to a work permit.
