# 👋 Hi, I'm Dilip Chikatla

**Data Engineer | Lakehouse Architecture | Cloud-Native Pipelines**

Passionate about building scalable, production-grade data platforms that drive business intelligence and fraud detection. About 4 years of experience designing and deploying ETL/ELT solutions on AWS, Databricks, and Snowflake. I specialize in implementing modern data architectures (Medallion, Lakehouse) with emphasis on data governance, real-time streaming, and ML-driven analytics.

---

## 🎯 Featured Projects

### 🚗 **Insurance Claims Lakehouse Pipeline on Databricks** ⭐ FEATURED
**Production-grade Medallion Architecture with ML fraud detection**

- **Problem:** Manual insurance claims processing is slow, error-prone, and expensive
- **Solution:** End-to-end automated pipeline processing 37K+ records with production-grade data quality

**Key Achievements:**
- ✅ **Medallion Architecture:** Bronze-Silver-Gold layers processing 37,289 raw records
- ✅ **Data Quality:** 84.5% pass rate (31,504 valid records) with 17.4% invalid data detection
- ✅ **ML Fraud Detection:** Logistic Regression model with **AUC-ROC 1.0** (100% accuracy) on 10,733 claims
- ✅ **Pipeline Automation:** 4-task Databricks Workflow orchestration (5-6 min end-to-end)
- ✅ **Infrastructure as Code:** Terraform for Databricks workspace, AWS S3, IAM roles
- ✅ **Analytics Dashboard:** 5 SQL queries + 6 Gold layer tables for business insights

**Tech Stack:**
- Databricks (Auto Loader, Delta Lake, Unity Catalog, Workflows)
- PySpark, SparkSQL for transformations
- Logistic Regression (PySpark ML) for fraud scoring
- Terraform for infrastructure provisioning
- AWS S3 for data storage

**Repo:** [databricks-insurance-claims-project](https://github.com/dilip-ch-dev/databricks-insurance-claims-project)

**Notebooks:** 12 production notebooks (Bronze → Silver → Gold → ML → Orchestration)

---

### 📊 **SEC Filings Analysis Pipeline for Market Intelligence**
**Modern Data Stack with AWS, dbt, and Snowflake**

- **Problem:** Extracting financial intelligence from 100+ SEC filings manually is time-consuming
- **Solution:** Automated ELT pipeline with cost-efficient API usage and dbt transformation

**Key Achievements:**
- ✅ Ingested 5,000+ unique SEC 10-K/10-Q filings (10GB+ financial data) into S3 data lake
- ✅ **99% API cost reduction** - Python (BeautifulSoup) extraction targeting only key sections
- ✅ Built 10+ dbt models for transforming unstructured text into queryable Gold tables
- ✅ Structured complex financial data (risks, sentiment, summaries) in seconds

**Tech Stack:**
- Python (BeautifulSoup, Pandas) for extraction
- Google Gemini API for LLM-based extraction
- AWS S3 for data lake
- dbt Core for transformation modeling
- Snowflake for data warehouse

**Key Metrics:**
- Data ingestion: Automated, event-driven
- Query time: Reduced from hours to seconds
- API efficiency: 99% cost optimization

---

### 🤖 **PAIKA: Personal AI Knowledge Assistant**
**Local-first RAG system with LangChain and Llama3**

- **Problem:** Secure document querying without sending data to external APIs
- **Solution:** Local RAG-based AI tool achieving 92% accuracy

**Key Achievements:**
- ✅ **92% accuracy** in relevant information retrieval
- ✅ **80% performance improvement** - query response from 8s to 1.4s
- ✅ Optimized vector embedding and chunking strategy
- ✅ Local-first architecture for data privacy

**Tech Stack:**
- LangChain for RAG orchestration
- Llama3 (open-source LLM)
- Vector embeddings for semantic search
- Python for implementation

---

### 💼 **Work Experience Highlights**

#### **Citi (Remote) | Jan 2025 – Nov 2025**
*Data Engineer*

- Engineered serverless ETL/ELT pipeline on AWS: **Oracle → Snowflake** (40% faster processing)
- Infrastructure as Code with Terraform: Setup time **7 days → 4 hours**
- Real-time fraud detection pipeline: Data latency **days → <5 minutes**
- Snowflake performance tuning: Query performance improved by **50%+**
- Data quality framework with Great Expectations: **99.9% accuracy**

**Tech:** AWS (Kinesis, Lambda, S3, Glue), Snowflake, Terraform, Python, Great Expectations

---

#### **Kloudvisio Inc. (Remote) | Aug 2024 – Dec 2024**
*Data Engineer*

- Automated REST API ingestion (Harvest) + flat files into S3 data lake (bronze zone)
- Orchestrated daily ETL pipeline using Apache Airflow with Git-based SDLC
- Transformed JSON/CSV to Parquet format, built queryable schema with AWS Glue Catalog
- Enabled self-service analytics via AWS Athena backend for Tableau dashboards

**Tech:** Apache Airflow, AWS (S3, Glue, Athena), Python (Pandas, Boto3), Git, Jira

---

#### **EPAM Systems | Jan 2021 – Dec 2022**
*Data Engineer (Hyderabad, India)*

- Modernized monolithic ETL system → Python serverless AWS Glue: **30% faster, fewer failures**
- Established team-wide Infrastructure as Code (IaC) practice with Terraform
- Built core ingestion pipeline: **1.2M+ monthly ePoS transactions** via Kinesis + Lambda
- Architected first analytical data warehouse in Amazon Redshift ("source of truth")

**Tech:** AWS (Glue, Kinesis, Lambda, Redshift), Python, Terraform, SQL

---

#### **Cyberagis IT Solutions | June 2020 – Dec 2020**
*Data Scientist (Hyderabad, India)*

- Built Prophet-based forecasting pipeline for daily claims volume prediction
- Developed scikit-learn classification model: **~85% test accuracy** for claim approval assessment
- Engineered data pipeline (Pandas) → MongoDB with Flask-based real-time dashboard

**Tech:** Prophet, scikit-learn, Pandas, MongoDB, Flask

---

## 🛠️ Technical Skills

### **Cloud Platforms**
- **AWS:** S3, Glue, Lambda, Kinesis, Redshift, VPC, Athena, EC2, RDS, API Gateway, CloudWatch
- **Databricks:** Delta Lake, Auto Loader, Unity Catalog, Workflows, Lakehouse, MLflow
- **Snowflake:** Data warehousing, performance tuning, dimensional modeling
- **Azure:** Familiarity with cloud services

### **Data Processing & Transformation**
- **Apache Spark** - PySpark, SparkSQL for distributed processing
- **Python** - Pandas, NumPy, BeautifulSoup, Boto3
- **Delta Lake** - ACID transactions, schema evolution, time travel
- **dbt Core** - Data transformation, testing, documentation
- **Medallion Architecture** - Bronze-Silver-Gold layering pattern

### **Orchestration & DevOps**
- **Orchestration:** Databricks Workflows, Apache Airflow
- **Infrastructure as Code:** Terraform for AWS + Databricks
- **CI/CD:** GitHub Actions, Git-based SDLC
- **Containerization:** Docker
- **Project Management:** Jira, Agile/Scrum methodologies

### **Data Warehousing & Analytics**
- Dimensional Modeling, Star Schema design
- Data Lake Architecture, Lakehouse Architecture
- Query optimization, performance tuning
- Business intelligence (Tableau integration)

### **Data Quality & Advanced Topics**
- Great Expectations for data validation
- Fraud detection analytics
- ML model training & evaluation (scikit-learn, PySpark ML)
- Vector databases, semantic search
- LangChain, Llama3, RAG systems
- LLM-based data extraction (Google Gemini API)

### **Networking & Systems**
- TCP/IP, DNS, VPC architecture
- Cloud security, IAM policies

---

## 📚 Education

**M.S. in Computer Science and Artificial Intelligence**
- University of Central Missouri | Missouri, USA
- GPA: 3.7/4.0
- Coursework: Advanced Database Systems, Cloud Security, Data Mining, Computer Vision, Operating Systems

**B.E. in Electronics and Communication Engineering**
- Rajiv Gandhi University of Knowledge and Technologies (IIIT Basar) | Hyderabad, India
- Coursework: Python for Full Stack, Statistical Foundations of Data Science, Deep Learning, Networking

---

## 📈 Key Metrics & Achievements

| Project | Metric | Impact |
|---------|--------|--------|
| **Databricks Claims Pipeline** | Data Quality | 84.5% pass rate (31,504 valid records) |
| **Databricks Claims Pipeline** | ML Model Accuracy | AUC-ROC 1.0 (100% on test set) |
| **Databricks Claims Pipeline** | Pipeline Execution | 5-6 minutes end-to-end |
| **Hartford Insurance ETL** | Processing Speed | 40% faster (Oracle → Snowflake) |
| **Hartford Insurance IaC** | Setup Time | 7 days → 4 hours |
| **Hartford Insurance Fraud Pipeline** | Data Latency | Days → <5 minutes |
| **Hartford Insurance Query Performance** | Dashboard Optimization | 50%+ improvement |
| **Hartford Insurance Data Quality** | Accuracy | 99.9% (Great Expectations) |
| **CGG Health Bulletins** | Processing Speed | 30% faster, fewer failures |
| **CGG Redshift Warehouse** | Data Volume | 1.2M+ monthly transactions |
| **PAIKA RAG System** | Accuracy | 92% relevant retrieval |
| **PAIKA RAG System** | Query Performance | 80% faster (8s → 1.4s) |
| **SEC Filings Pipeline** | API Cost Optimization | 99% reduction |
| **Cyberagis ML Model** | Classification Accuracy | 85% test accuracy |

---

## 🎯 What I'm Passionate About

✅ **Medallion Architecture** - Implementing scalable Bronze-Silver-Gold patterns  
✅ **Data Governance** - Ensuring quality, lineage, and compliance  
✅ **Real-time Streaming** - AWS Kinesis, Apache Kafka pipelines  
✅ **Fraud Detection** - Building ML models for anomaly detection  
✅ **Infrastructure as Code** - Automating cloud deployment with Terraform  
✅ **Modern Data Stack** - dbt, Dagster, Databricks workflows  
✅ **Cloud Economics** - Optimizing costs while maintaining performance  
✅ **AI/LLM Integration** - RAG systems, vector databases, semantic search  

---

## 🔗 Connect With Me

- **LinkedIn:** [linkedin.com/in/dilipchikatla](https://www.linkedin.com/in/dilipchikatla/)
- **Email:** dilip77950@gmail.com
- **Location:** Overland Park, Kansas, USA

---

## 🚀 Current Focus

- Deep dive into **Databricks Lakehouse Architecture** - Production patterns & best practices
- Exploring **Advanced ML Ops** - Model versioning, serving, and monitoring
- Building with **Modern Data Stack** - dbt, LLMs, vector databases
- Mentoring others in **Data Engineering best practices**

---

## 📊 GitHub Statistics

Most of my work is in **private repositories** for current/past employers, but I actively maintain:

- 🔓 **Public Projects:** Databricks Insurance Claims, SEC Filings Analysis, PAIKA
- 📚 **Learning:** Data engineering patterns, cloud architecture, ML ops
- 🤝 **Open to:** Collaboration, contributions, and knowledge sharing

---

## 💡 Let's Connect!

I'm always interested in discussing:
- Data architecture and lakehouse design
- Cloud-native data pipelines
- Fraud detection and data quality frameworks
- Career growth in data engineering
- Open-source data projects

Feel free to reach out via LinkedIn or email! 🚀
