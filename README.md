# Yazid Aloui – Data Analyst | Data Engineering & Machine Learning

Ottawa, Ontario
alouiyaz78@gmail.com | 514-242-7895
[LinkedIn](https://www.linkedin.com/in/yazidaloui/) | [GitHub](https://github.com/alouiyaz78)

---

## About Me
Bilingual Data Analyst (FR/EN) with a strong background in mathematics and hands-on experience in Python, SQL, BI, and data automation. I focus on building reliable data pipelines and end-to-end data products, combining Data Engineering, Machine Learning, applied AI, and business-driven decision making.

---

## Skills
- **Programming & Data Tools:** Python (advanced), SQL (advanced), MongoDB, Power BI (advanced), Tableau, Excel (advanced), Java
- **Data Engineering & Orchestration:** dbt, Apache Airflow, Docker & Docker Compose, Databricks, Delta Lake, Spark (PySpark), Hadoop (HDFS, Streaming MapReduce), ETL Pipelines, medallion architecture (bronze/silver/gold)
- **AI & LLM Applications:** LangChain, Retrieval-Augmented Generation (RAG), pgvector, agentic tool-calling (Text-to-SQL), Ollama, OpenAI/Anthropic/Google APIs
- **Machine Learning & Statistics:** Classification, Regression, Neural Networks, Inferential Statistics
- **MLOps & Monitoring:** Pandera, YAML validation, SHAP, Fairlearn, Evidently
- **Web & Cloud:** Flask, FastAPI, Gradio, HTML (basic), CSS (basic), JavaScript (basic), AWS (basic), Azure (basic)
- **Data Handling & Automation:** APIs, Data Cleaning, Data Pipelines, Python automation, Power Automate
- **Version Control & Collaboration:** Git, GitHub
- **Languages:** French (Fluent), English (Intermediate, actively improving)

---

## Education
- Applied Data Science – Collège La Cité (Ottawa), 2025 – Present
- BSc Mathematics – Faculty of Sciences (Bizerte), WES evaluated (4 years)

---

## Experience
- **Data Analyst – EoCube (2023):** Data cleaning, validation, reporting (FAO project)
- **Financial Analyst / Loan Portfolio Manager – Association for the Development of Menzel Jemil (2009–2024):** Financial reporting, KPI monitoring, portfolio analytics, process automation (Python)

---

## Projects

### 1. [Ontario 511 Road Data Pipeline](https://github.com/alouiyaz78/ontario511-road-data-pipeline)
Python | PostgreSQL & pgvector | dbt | Apache Airflow | Docker | Gradio | FastAPI | LangChain

End-to-end data platform built on Ontario's public 511 traffic API, from ingestion to an AI-assisted dashboard. Originally a SQL Server course project, rebuilt from the ground up with a modern data stack.

- Automated ingestion of six live traffic data sources (events, construction, cameras, road conditions, alerts) into a bronze/silver/gold medallion architecture with dbt
- Apache Airflow orchestration: full pipeline runs every two hours, with automated dbt tests and email alerts on failure
- Interactive Gradio dashboard: real-time KPIs, a per-roadway disruption index, an incident map, and an exportable alert table
- LangChain chatbot agent combining Text-to-SQL (validated, read-only queries) with semantic search (pgvector + Ollama embeddings) over incident descriptions; users bring their own LLM provider and API key (Claude, OpenAI, or Gemini)
- Fully containerized with Docker Compose; images published to Docker Hub

🔗 Docker images: https://hub.docker.com/u/alouiyaz

---

### 2. [Zero-Defect Credit Risk Pipeline](https://github.com/alouiyaz78/Zero-defect-credit-risk-pipeline)
Python | XGBoost | Pandera | YAML | SHAP | Fairlearn | Evidently | Streamlit

End-to-end credit risk scoring pipeline with a strong focus on data quality, reliability, and business impact.

- Data quality validation using Pandera and YAML contracts
- Feature engineering within a controlled pipeline
- Cost-sensitive threshold optimization (FN vs FP)
- Model explainability with SHAP
- Fairness analysis across demographic groups
- Data drift monitoring using Evidently
- Interactive Streamlit dashboard for decision simulation

🔗 Live app: https://zero-defect-credit-risk-pipeline-fxqrngtu5bmqpctnghwnqn.streamlit.app/

---

### 3. [Hadoop Mini Cluster + MapReduce KPI Dashboard](https://github.com/alouiyaz78/Hadoop_mini_cluster)
Docker | Hadoop | Spark | HDFS | Streaming MapReduce | Python | Streamlit | Plotly

Big Data processing pipeline with automated MapReduce jobs and an interactive KPI dashboard.

---

### 4. [NYC Taxi Data ETL Pipeline – Databricks & Delta Lake](https://github.com/alouiyaz78/Databricks_project_nyct)
Databricks | Delta Lake | PySpark | Spark SQL | GitHub | VS Code

End-to-end ETL pipeline using Medallion architecture (Landing → Bronze → Silver → Gold → Export) with incremental and historical processing.

---

### 5. [London Hotel Chatbot](https://github.com/alouiyaz78/Chatbot)
Python | Flask | OpenAI | LangChain | FAISS | Web Scraping

AI chatbot using Retrieval-Augmented Generation (RAG) to answer questions from documents and web content.

---

### 6. [Ontario Francophone Newcomers Survey](https://github.com/alouiyaz78/projet_enquette_sociaux)
Python | MongoDB Atlas | Power Automate | Dashboards

End-to-end survey data pipeline: collection → cleaning → storage → visualization.

---

## Dashboard Preview

### Credit Risk Project
![Dashboard 1](img/Dashborad_1_project_credit_score.png)
![Dashboard 2](img/Dashborad_2_project_credit_score.png)
![Dashboard 3](img/Dashborad_3_project_credit_score.png)
![Dashboard 4](img/Dashborad_4_project_credit_score.png)

---

### Survey Project
![Survey Dashboard](img/dashboard_preview.png)

## Certifications & Training
IBM Data Science (2022) | ML-Pro (2025) | SQL Bootcamp | Power BI | Python Advanced

---

## Contact
Open to Data Analyst / ML / Data Engineer / BI roles.
📧 alouiyaz78@gmail.com
