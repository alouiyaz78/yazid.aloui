Yazid Aloui – Data Analyst | Data Engineering & Machine Learning
Ottawa, Ontario alouiyaz78@gmail.com | 514-242-7895 LinkedIn | GitHub

About Me
Bilingual Data Analyst (FR/EN) with a strong background in mathematics and hands-on experience in Python, SQL, BI, and data automation. I focus on building reliable data pipelines and end-to-end data products, combining Data Engineering, Machine Learning, applied AI, and business-driven decision making.

Skills
Programming & Data Tools: Python (advanced), SQL (advanced), MongoDB, Power BI (data modeling, DAX, hands-on since 2020), Tableau, Excel (advanced), Java
Data Engineering & Orchestration: dbt, Apache Airflow, Docker & Docker Compose, Databricks, Delta Lake, Spark (PySpark), Hadoop (HDFS, Streaming MapReduce), ETL Pipelines, medallion architecture (bronze/silver/gold)
AI & LLM Applications: LangChain, Retrieval-Augmented Generation (RAG), pgvector, agentic tool-calling (Text-to-SQL), Ollama, OpenAI/Anthropic/Google APIs
Machine Learning & Statistics: Classification, Regression, Neural Networks, Inferential Statistics
MLOps & Monitoring: Pandera, YAML validation, SHAP, Fairlearn, Evidently
Web & Cloud: Flask, FastAPI, Gradio, HTML (basic), CSS (basic), JavaScript (basic), AWS (basic), Azure (basic)
Data Handling & Automation: APIs, Data Cleaning, Data Pipelines, Python automation, Power Automate
Version Control & Collaboration: Git, GitHub
Languages: French (Fluent), English (Professional)
Education
Applied Data Science – Collège La Cité (Ottawa), 2025 – Present
BSc Mathematics – Faculty of Sciences (Bizerte), WES evaluated (4 years)
Experience
Institution Director & Data Reporting – Association for the Development of Menzel Jemil (2011–2024): Financial reporting, KPI monitoring (Power BI, Excel), portfolio analytics, regulatory reporting, process automation (Python)
Data Analyst – EoCube (2023, 4-month contract): Data cleaning, validation, automated progress reporting (National Forest Inventory project for the FAO)
Projects
1. Ontario 511 Road Data Pipeline
Python | PostgreSQL & pgvector | dbt | Apache Airflow | Docker | Gradio | FastAPI | LangChain

End-to-end data platform built on Ontario’s public 511 traffic API, from ingestion to an AI-assisted dashboard. Originally a SQL Server course project, rebuilt from the ground up with a modern data stack.

Automated ingestion of six live traffic data sources (events, construction, cameras, road conditions, alerts) into a bronze/silver/gold medallion architecture with dbt
Apache Airflow orchestration: full pipeline runs every two hours, with automated dbt tests and email alerts on failure
Interactive Gradio dashboard: real-time KPIs, a per-roadway disruption index, an incident map, and an exportable alert table
LangChain chatbot agent combining Text-to-SQL (validated, read-only queries) with semantic search (pgvector + Ollama embeddings) over incident descriptions; users bring their own LLM provider and API key (Claude, OpenAI, or Gemini)
Fully containerized with Docker Compose; images published to Docker Hub
Docker images

2. AI Quiz Generator
Python | LLM APIs (OpenAI, Claude, Gemini) | Streamlit | Gradio | Hugging Face Spaces

Interactive quiz generation system built from course documents, with both a CLI and a Streamlit UI, deployed live on Hugging Face Spaces.

Generates quizzes automatically from uploaded documents (PDF, TXT, DOCX, PY, IPYNB), with chunk-based processing for large files
Prompt-engineered difficulty levels (facile, moyen, difficile) targeting basic understanding, applied reasoning, and comparison/interpretation
Question quality controls: autonomous questions only (no missing context), duplicate filtering via similarity checks, comparison-based questions, no open-ended questions
Weighted scoring system for multi-select questions (partial credit, bounded between 0 and max points, no penalty for missed correct answers)
Secure in-UI API key input, real-time interactive scoring, and export to Markdown, DOCX, and JSON
Deployed to production via Gradio on Hugging Face Spaces
Live demo

3. Brain Tumor Detection — MRI Classification with Deep Learning
Python | PyTorch | EfficientNet-B0 | Grad-CAM | Albumentations | Gradio | Hugging Face Spaces

Team project (6 members, Agile Scrum via Jira) classifying brain MRI scans as healthy or tumor-affected, deployed as a public web app.

Iterated from a from-scratch CNN (94% accuracy) to transfer learning with EfficientNet-B0 (4.0M parameters, roughly 6x fewer than the baseline CNN), reaching 100% precision, 90.3% recall, and a 94.9% F1-score on 394 held-out test images
Addressed a 73%/27% class imbalance with a weighted loss function (6.27x penalty on minority-class errors) rather than accepting a misleadingly high naive accuracy
Test-Time Augmentation (5 augmented views averaged per prediction) and threshold tuning to improve recall without sacrificing precision
Grad-CAM interpretability comparing attention maps between the baseline CNN and EfficientNet-B0, showing markedly more precise tumor localization with transfer learning
Deployed on Hugging Face Spaces with three modes: detailed single-image analysis, multi-slice batch comparison, and a transparency view of the model’s own performance metrics
Live demo

4. Zero-Defect Credit Risk Pipeline
Python | XGBoost | Pandera | YAML | SHAP | Fairlearn | Evidently | Streamlit

End-to-end credit risk scoring pipeline with a strong focus on data quality, reliability, and business impact.

Data quality validation using Pandera and YAML contracts
Feature engineering within a controlled pipeline
Cost-sensitive threshold optimization (FN vs FP)
Model explainability with SHAP
Fairness analysis across demographic groups
Data drift monitoring using Evidently
Interactive Streamlit dashboard for decision simulation
Live app

5. Hadoop Mini Cluster + MapReduce KPI Dashboard
Docker | Hadoop | Spark | HDFS | Streaming MapReduce | Python | Streamlit | Plotly

Big Data processing pipeline with automated MapReduce jobs and an interactive KPI dashboard.

6. NYC Taxi Data ETL Pipeline – Databricks & Delta Lake
Databricks | Delta Lake | PySpark | Spark SQL | GitHub | VS Code

End-to-end ETL pipeline using Medallion architecture (Landing → Bronze → Silver → Gold → Export) with incremental and historical processing.

7. London Hotel Chatbot
Python | Flask | OpenAI | LangChain | FAISS | Web Scraping

AI chatbot using Retrieval-Augmented Generation (RAG) to answer questions from documents and web content.

8. Ontario Francophone Newcomers Survey
Python | MongoDB Atlas | Power Automate | Dashboards

End-to-end survey data pipeline: collection → cleaning → storage → visualization.

9. CarthageKitchen-AI
Autonomous Multi-Agent Culinary and Nutrition Studio

Hugging Face Spaces Python CrewAI Database Gradio

CarthageKitchen-AI is an end-to-end multi-agent AI system designed to preserve, adapt, and source authentic Tunisian culinary heritage across Canada.

Originally inspired by the NourishBot hands-on lab in the IBM AI Agents Specialization on Coursera, the application was re-engineered into an autonomous, production-grade agentic pipeline featuring multimodal vision parsing, domain-grounded RAG, deterministic nutrition computation, localized Canadian grocery mapping, and live SQL telemetry.

Live Demo
Test the live application on Hugging Face Spaces:
https://huggingface.co/spaces/alouiyaz/CarthageKitchen-AI

System Architecture and Multi-Agent Workflow
Rather than relying on a single generic LLM prompt, the platform orchestrates collaborative autonomous agents using CrewAI:

Dashboard Preview
Credit Risk Project
Dashboard 1
