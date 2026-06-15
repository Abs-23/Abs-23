# Hi 👋, I'm Abhishek Siriki

**Data Engineer · Analytics Engineer | M.S. in Data Science**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-siriki/)

---

## 🔎 About Me

I am a Data Engineer and Analytics Engineer with a Master's in Data Science, focused on building reliable data systems that support financial services operations and business decision making.

My work centers on building pipelines that operations and analytics teams can trust, catching data quality issues before they reach end users, and making sure the right information gets to the right people without manual intervention. I build across the full analytics stack, from raw ingestion and transformation all the way through to reporting layers and dashboards that answer real business questions for finance teams, operations teams, and leadership.

I focus on:
- Building end to end ELT pipelines that turn raw operational data into trusted, analytics ready tables for business use.
- Designing data models and dashboards that answer real business questions for finance, operations, and leadership teams.
- Strengthening data quality with validation checks, anomaly detection, and clear data contracts at every layer of the pipeline.
- Supporting warehouse and lakehouse architecture decisions for growing firms that are moving beyond spreadsheet and single system reporting.
- Supporting ML and AI use cases with clean feature tables, MLflow experiment tracking, and explainable models where the business problem calls for it.

Open to roles in financial services, wealth management, healthcare, and beyond.

---

## 💻 Tech Stack

| Category | Technologies |
|----------|-------------|
| **Core Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |
| **Data Engineering** | ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-fff000?style=flat&logo=duckdb&logoColor=000) ![Databricks](https://img.shields.io/badge/Databricks-EF3B2D?style=flat&logo=databricks&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white) |
| **Cloud Platforms** | ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white) ![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-0078D4?style=flat&logo=microsoft&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white) |
| **Wealth Platforms** | ![Tamarac](https://img.shields.io/badge/Tamarac-004B87?style=flat&logoColor=white) ![Addepar](https://img.shields.io/badge/Addepar-00A3E0?style=flat&logoColor=white) ![Orion](https://img.shields.io/badge/Orion-FF6600?style=flat&logoColor=white) |
| **CRM** | ![Salesforce FSC](https://img.shields.io/badge/Salesforce%20FSC-00A1E0?style=flat&logo=salesforce&logoColor=white) |
| **ML & Data Science** | ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-FF6B35?style=flat&logoColor=white) ![SHAP](https://img.shields.io/badge/SHAP-Explainability-blue?style=flat) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white) |
| **Visualization & BI** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white) |
| **AI & Agents** | ![Generative AI](https://img.shields.io/badge/Generative%20AI-purple?style=flat) ![LLMs](https://img.shields.io/badge/LLMs-blueviolet?style=flat) ![Agentic AI](https://img.shields.io/badge/Agentic%20AI-Google%205--Day%20Course-4285F4?style=flat) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) |
| **Tools & Platforms** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37726?style=flat&logo=jupyter&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

## 🚀 Featured Data Engineering & Analytics Projects

### 💳 CDP Analytics Platform – Snowflake, dbt, Python, Hightouch
A production grade Customer Data Platform pipeline built on Snowflake, simulating how a real business collects, unifies, segments, and activates customer data across 3.3 million records.

- Built a full medallion architecture across Bronze, Silver, and Gold layers on Snowflake using SQL, with strict separation of concerns at each layer and audit columns on every table to support data lineage and compliance traceability.
- Implemented identity resolution to link 1.1 million anonymous visitor events to known customers through session based matching, producing a unified 360 degree customer profile with purchase KPIs across 76,000 customer records.
- Built four business rule driven customer segments including High Value, Churn Risk, Win Back, and One Time Buyer, and integrated dbt for model lineage tracking, automated testing, and documentation across the full pipeline.
- Designed the activation layer using Hightouch Reverse ETL to push live segments downstream, and integrated the Google Gemini API for natural language querying of the Gold layer.

---

### 💰 SaaS Finance Analytics – dbt, DuckDB, Python, Power BI
End to end analytics stack for subscription revenue operations.

- Modeled subscriptions, MRR, and churn using dbt on DuckDB to create a clean semantic layer that finance and operations teams can query without needing raw SQL access.
- Built a Python ELT pipeline from raw CSV files through DuckDB to Power BI, replacing manual refresh workflows with a repeatable automated process.
- Designed an executive dashboard so leadership can explore MRR trends, churn rates, and plan performance without touching SQL or waiting for analyst support.

---

### 🚕 NYC Taxi Fleet Analytics – Microsoft Fabric, PySpark, KQL, Power BI
A batch and streaming analytics pipeline built on Microsoft Fabric for operational fleet decision making.

- Built dual batch and streaming pipelines that merge into a unified Gold layer using medallion architecture on Microsoft Fabric Lakehouse, processing 4.8 million historical trip records alongside live Eventstream data.
- Implemented custom incremental watermarking logic in scheduled PySpark notebooks to process only new streaming data on each run, preventing duplicate records and reducing compute cost across hourly executions.
- Built a KQL validation layer in Eventhouse to test all streaming transformations before they reach production Gold tables, catching data quality issues upstream before they corrupt reporting.
- Designed five Power BI dashboard pages covering revenue analysis, demand patterns, trip duration, weather impact, and live streaming status, with row level security restricting regional managers to their own zones and Direct Lake mode for low latency refreshes.

---

### 🚗 Traffic & Toll Revenue Forecasting – Databricks, PySpark, SQL, MLflow, Power BI
Lakehouse and forecasting pipeline for transportation revenue planning.

- Built a medallion architecture in Databricks to process six years of traffic and weather data using PySpark, producing clean Gold layer tables ready for revenue analysis and forecasting.
- Engineered features and trained forecasting models with MLflow experiment tracking, improving forecast accuracy over the baseline model.
- Exposed results in Power BI so planning teams can compare toll scenarios and visualize revenue impact under different policy conditions.

---

### 🛡️ Insurance Claims Lakehouse – Databricks, SQL, Python, AWS Kinesis, S3
Streaming and batch lakehouse for insurance claims operations and risk modeling.

- Ingested streaming telematics from AWS Kinesis alongside batch claims and policy data into a unified Delta Lake, normalizing and deduplicating entities across both ingestion paths.
- Built reusable ML ready feature tables for claim severity and risk modeling and integrated model predictions back into the pipeline for automated triage and anomaly detection.

---

## 📚 More Projects (Healthcare & ML)

### 🏥 Healthcare Readmission Risk – Python, Scikit-Learn, Power BI
ML model and operational reporting for hospital readmission prediction.

- Trained a classification model to estimate readmission probability and used SHAP explainability tools to surface key clinical drivers for operations and clinical teams.
- Built visuals in Power BI so clinical and operations teams can understand high risk cohorts and trends without needing to interpret raw model outputs.

### ❤️ Heart Disease Risk Predictor – Scikit-Learn, SHAP, Streamlit
- Developed a classification model to estimate heart disease risk and used SHAP for explainability so clinicians can understand which factors drive each prediction.
- Deployed an interactive Streamlit app so clinical stakeholders can explore predictions without needing a data science background.

### 🧠 EMG Neuromotor Interface – PyTorch, Signal Processing
- Built a staged classification pipeline for EMG biosignals and explored multi-stage model design for neuromotor applications.

### 🩺 Other Healthcare Analytics Work
- Exploratory analysis and predictive modeling on clinical and claims style datasets, with a focus on interpretable models and stakeholder friendly reporting.

---

## 🎓 Education

### Master's in Data Science
**University of Massachusetts Dartmouth** | 2023 – 2025 | GPA: 3.6

- **Focus**: Applied ML for Healthcare, Time Series and Streaming Analytics.
- **Coursework**: Advanced ML, AI, HPC, Advanced Data Mining, Advanced Statistics, Small World Networks.
- **Activities**: Badminton Club (Tournament Champion), Valorant Esports Roster.

### Bachelor of Technology in Computer Science and Engineering
**Jawaharlal Nehru Technological University, Kakinada** | 2017 – 2021

---

## 🔗 Connect

- 🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-siriki/)
- 💻 GitHub: [@Abs-23](https://github.com/Abs-23)
- 📧 abhishek.siriki23@gmail.com
- Open to collaborations in financial services data engineering, wealth management analytics, and healthcare ML.
