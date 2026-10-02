# Yazid Aloui – Data Analyst | Data Engineering & Machine Learning

Ottawa, Ontario  
alouiyaz78@gmail.com | 514-242-7895  
[LinkedIn Profile](https://www.linkedin.com/in/yazidaloui/) | [GitHub Profile](https://github.com/alouiyaz78)

---

## About Me

Bilingual Data Analyst (FR/EN) with a strong background in mathematics and hands-on experience in Python, SQL, BI, and data automation. I focus on building reliable data pipelines and end-to-end data products, combining Data Engineering, Machine Learning, applied Agentic AI, and business-driven decision making.

---

## Technical Skills

- **Programming & Data Tools:** Python (advanced), SQL (advanced), PostgreSQL, MongoDB, Power BI (data modeling, DAX, hands-on since 2020), Tableau, Excel (advanced), Java
- **Data Engineering & Orchestration:** dbt, Apache Airflow, Docker & Docker Compose, Databricks, Delta Lake, Spark (PySpark), Hadoop (HDFS, Streaming MapReduce), ETL Pipelines, Medallion architecture (bronze/silver/gold)
- **AI & Multi-Agent Systems:** CrewAI, LangChain, Retrieval-Augmented Generation (RAG), pgvector (Neon PostgreSQL), FastEmbed, LiteLLM, Agentic Tool Calling (Text-to-SQL), Multimodal Vision, Hugging Face Spaces
- **Machine Learning & Statistics:** Classification, Regression, Neural Networks, Transfer Learning, Inferential Statistics
- **MLOps & Telemetry:** Pandera, YAML validation, SHAP, Fairlearn, Evidently, SQL-based app telemetry & user feedback tracking
- **Web & Cloud:** Gradio, Streamlit, FastAPI, Flask, HTML/CSS/JS (basic), AWS (basic), Azure (basic)
- **Data Handling & Automation:** APIs, Data Cleaning, Data Pipelines, Python automation, Power Automate
- **Version Control & Collaboration:** Git, GitHub
- **Languages:** French (Fluent), English (Professional)

---

## Education

- **Applied Data Science** – Collège La Cité (Ottawa), 2025 – Present
- **BSc Mathematics** – Faculty of Sciences (Bizerte), WES evaluated (4 years)

---

## Professional Experience

- **Executive Director & Data Reporting – Association for the Development of Menzel Jemil (2011–2024):** 
  Financial reporting, KPI monitoring (Power BI, Excel), portfolio analytics, regulatory reporting, 
  process automation (Python).

  **Annual Board Report – Power BI Dashboard (2005–2021):** Built for the organization's annual 
  board meetings, presenting portfolio performance, recovery rates, and financial activity through 
  star-schema data modeling and DAX measures, segmented by sector, region, education level, and gender.

  🔗 [View Interactive Dashboard (Power BI)](https://app.powerbi.com/links/KSbe3px7BI?ctid=b93e7a34-ce42-4e06-b127-447bf8f5c1bd&pbi_source=linkShare&bookmarkGuid=b3cf586c-c038-4007-bfb7-6b5a6b87a788)

- **Data Analyst – EoCube (2023, 4-month contract):** Data cleaning, validation, automated progress reporting (National Forest Inventory project for the FAO).

---

## Key Projects

### 1. [CarthageKitchen-AI – Autonomous Multi-Agent Culinary Studio](https://github.com/alouiyaz78/CarthageKitchen-AI)
**Tech Stack:** Python | CrewAI | LiteLLM | Neon PostgreSQL (pgvector) | FastEmbed | Gradio | Hugging Face Spaces

Full-stack agentic platform orchestrating collaborative AI agents to preserve, adapt, and source authentic heritage recipes, built with clinical safety guardrails and real-world Canadian grocery sourcing.

- **Multi-Agent Orchestration:** Deployed specialized autonomous agents via CrewAI handling multimodal vision parsing (fridge/pantry photos), dietary/clinical filtering, and chef-level culinary composition.
- **Cultural Grounding via RAG:** Built a domain-specific vector retrieval pipeline with Neon PostgreSQL, `pgvector`, and FastEmbed, anchoring recipes in authentic culinary literature to prevent hallucinations.
- **Deterministic Nutrition Engine:** Engineered a pure Python calculation module (`src/nutrition.py`) computing calories and macronutrients strictly from verified food composition weights, eliminating LLM arithmetic errors.
- **Localized Sourcing Tool:** Mapped verified Mediterranean specialty grocers across Ottawa/Gatineau, Montreal, Quebec City, and Toronto alongside mainstream supermarket alternatives.
- **Production Telemetry & Observability:** Implemented an asynchronous logging and human-in-the-loop feedback pipeline in Neon PostgreSQL (`app_analytics`) to monitor agent latency, track model failovers, and flag domain hallucinations.

🔗 **Links:** [Live Demo on Hugging Face](https://huggingface.co/spaces/alouiyaz/CarthageKitchen-AI) | [GitHub Repository](https://github.com/alouiyaz78/CarthageKitchen-AI)

---

### 2. [Ontario 511 Road Data Pipeline](https://github.com/alouiyaz78/ontario511-road-data-pipeline)
**Tech Stack:** Python | PostgreSQL & pgvector | dbt | Apache Airflow | Docker | Gradio | FastAPI | LangChain

End-to-end data platform built on Ontario's public 511 traffic API, from ingestion to an AI-assisted dashboard. Rebuilt from the ground up with a modern data stack.

- Automated ingestion of six live traffic data sources (events, construction, cameras, road conditions, alerts) into a bronze/silver/gold medallion architecture with dbt.
- Apache Airflow orchestration: full pipeline runs every two hours, with automated dbt tests and email alerts on failure.
- Interactive Gradio dashboard: real-time KPIs, a per-roadway disruption index, an incident map, and an exportable alert table.
- LangChain chatbot agent combining Text-to-SQL (validated, read-only queries) with semantic search (pgvector + Ollama embeddings).
- Fully containerized with Docker Compose; images published to Docker Hub.

🔗 **Links:** [GitHub Repository](https://github.com/alouiyaz78/ontario511-road-data-pipeline) | [Docker Hub Images](https://hub.docker.com/u/alouiyaz)

---

### 3. [AI Quiz Generator](https://github.com/alouiyaz78/Robot_questionnaire)
**Tech Stack:** Python | LLM APIs (OpenAI, Claude, Gemini) | Streamlit | Gradio | Hugging Face Spaces

Interactive quiz generation system built from course documents, with both a CLI and a Streamlit UI, deployed live on Hugging Face Spaces.

- Generates quizzes automatically from uploaded documents (PDF, TXT, DOCX, PY, IPYNB), with chunk-based processing for large files.
- Prompt-engineered difficulty levels targeting basic understanding, applied reasoning, and comparison/interpretation.
- Question quality controls: autonomous questions only, duplicate filtering via similarity checks, comparison-based questions.
- Weighted scoring system for multi-select questions with partial credit.
- Secure in-UI API key input, real-time interactive scoring, and export to Markdown, DOCX, and JSON.

🔗 **Links:** [Live Demo](https://huggingface.co/spaces/alouiyaz78/robot_questionnaire) | [GitHub Repository](https://github.com/alouiyaz78/Robot_questionnaire)

---

### 4. [Brain Tumor Detection — MRI Classification with Deep Learning](https://github.com/alouiyaz78/Brain_tumor_MRI_classification)
**Tech Stack:** Python | PyTorch | EfficientNet-B0 | Grad-CAM | Albumentations | Gradio | Hugging Face Spaces

Classifying brain MRI scans as healthy or tumor-affected, deployed as a public web application.

- Iterated from a baseline CNN (94% accuracy) to transfer learning with EfficientNet-B0 (4.0M parameters), reaching 100% precision, 90.3% recall, and a 94.9% F1-score on 394 test images.
- Addressed a 73%/27% class imbalance with a weighted loss function (6.27x penalty on minority-class errors).
- Applied Test-Time Augmentation (5 augmented views) and threshold tuning.
- Grad-CAM interpretability comparing attention maps between the baseline CNN and EfficientNet-B0.

🔗 **Links:** [Live Demo](https://huggingface.co/spaces/alouiyaz/MRI_segmentation) | [GitHub Repository](https://github.com/alouiyaz78/Brain_tumor_MRI_classification)

---

### 5. [Zero-Defect Credit Risk Pipeline](https://github.com/alouiyaz78/Zero-defect-credit-risk-pipeline)
**Tech Stack:** Python | XGBoost | Pandera | YAML | SHAP | Fairlearn | Evidently | Streamlit

End-to-end credit risk scoring pipeline with a strong focus on data quality, reliability, and business impact.

- Data quality validation using Pandera and YAML contracts.
- Feature engineering within a controlled pipeline and cost-sensitive threshold optimization (FN vs FP).
- Model explainability with SHAP and fairness analysis across demographic groups.
- Data drift monitoring using Evidently.
- Interactive Streamlit dashboard for decision simulation.

🔗 **Links:** [Live App](https://zero-defect-credit-risk-pipeline-fxqrngtu5bmqpctnghwnqn.streamlit.app/) | [GitHub Repository](https://github.com/alouiyaz78/Zero-defect-credit-risk-pipeline)

#### Project Dashboards Preview
![Credit Risk Dashboard 1](img/Dashborad_1_project_credit_score.png)
![Credit Risk Dashboard 2](img/Dashborad_2_project_credit_score.png)
![Credit Risk Dashboard 3](img/Dashborad_3_project_credit_score.png)
![Credit Risk Dashboard 4](img/Dashborad_4_project_credit_score.png)

---

### 6. [Ontario Francophone Newcomers Survey](https://github.com/alouiyaz78/projet_enquette_sociaux)
**Tech Stack:** Python | MongoDB Atlas | Power Automate | Power BI Dashboards

End-to-end survey data pipeline: automated collection, schema validation, persistent cloud storage, and executive KPI reporting.

🔗 **Links:** [GitHub Repository](https://github.com/alouiyaz78/projet_enquette_sociaux)

#### Survey Dashboard Preview
![Survey Dashboard Preview](img/dashboard_preview.png)

---

### 7. [Hadoop Mini Cluster + MapReduce KPI Dashboard](https://github.com/alouiyaz78/Hadoop_mini_cluster)
**Tech Stack:** Docker | Hadoop | Spark | HDFS | Streaming MapReduce | Python | Streamlit | Plotly

Big Data processing pipeline with automated MapReduce jobs and an interactive KPI dashboard.

🔗 **Links:** [GitHub Repository](https://github.com/alouiyaz78/Hadoop_mini_cluster)

---

### 8. [NYC Taxi Data ETL Pipeline – Databricks & Delta Lake](https://github.com/alouiyaz78/Databricks_project_nyct)
**Tech Stack:** Databricks | Delta Lake | PySpark | Spark SQL | GitHub | VS Code

End-to-end ETL pipeline using Medallion architecture (Landing -> Bronze -> Silver -> Gold -> Export) with incremental and historical processing.

🔗 **Links:** [GitHub Repository](https://github.com/alouiyaz78/Databricks_project_nyct)

---

### 9. [London Hotel Chatbot](https://github.com/alouiyaz78/Chatbot)
**Tech Stack:** Python | Flask | OpenAI | LangChain | FAISS | Web Scraping

AI chatbot using Retrieval-Augmented Generation (RAG) to answer questions from unstructured documents and web content.

🔗 **Links:** [GitHub Repository](https://github.com/alouiyaz78/Chatbot)

---

## Certifications & Training

- IBM Data Science Professional Certificate (2022)
- Machine Learning Specialization (2025)
- Advanced SQL & Database Design Bootcamp
- Power BI Data Modeling & DAX Masterclass

---

## Contact

Open to Data Analyst, Machine Learning Engineer, and Data Engineer roles.  
Email: [alouiyaz78@gmail.com](mailto:alouiyaz78@gmail.com)
