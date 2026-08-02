# upi_transcaction_analysis
# 🏦 UPI Transaction Analysis Capstone Project

## 📘 Overview
This project analyzes Unified Payments Interface (UPI) transaction data to uncover insights on fraud risk, transaction performance, and customer/merchant behavior.  
It is developed as part of the **Data Analytics with GenAI Capstone** under **Career247 (AddaEducation)**.

The project demonstrates end-to-end data analytics — from data validation and SQL schema design to Python-based analysis and Power BI dashboarding — executed by a single contributor.

---

## 🎯 Objectives
- Detect and analyze fraudulent transaction patterns.
- Identify operational bottlenecks and failure causes.
- Develop KPIs for transaction performance and risk monitoring.
- Deliver actionable insights for business improvement.

---

## 🧩 Project Deliverables
| Phase | Deliverable | Tool |
|-------|--------------|------|
| 1. Business Understanding | KPI Framework, Hypotheses | PowerPoint / Google Slides |
| 2. Data Validation | Data Quality Log | Excel |
| 3. Database Design | SQL DDL Scripts, ER Diagram | MySQL / PostgreSQL |
| 4. Data Ingestion | Cleaned Tables | SQL / Python |
| 5. Data Cleaning & EDA | Jupyter Notebook | Python (Pandas, Seaborn) |
| 6. Statistical Analysis | Hypothesis Testing Results | Python (SciPy, Statsmodels) |
| 7. Dashboard | Power BI Report (.pbix) | Power BI |
| 8. Insights | Executive Summary Report | PowerPoint / Word |

---

## 📊 Key Performance Indicators (KPIs)
- **Transaction Volume**
- **Transaction Failure Rate**
- **Fraud Detection Rate**
- **Merchant Risk Ratio**
- **Device Fraud Ratio**
- **Customer Retention Rate**

---

## 🧠 Data Sources
- `customer_master`
- `device_info`
- `upi_account_details`
- `merchant_info`
- `upi_transaction_history`
- `customer_feedback_surveys`
- `fraud_alert_history`

---

## 🛠️ Tools & Technologies
- **Excel** – Data validation and quality checks  
- **SQL** – Database design, ingestion, and querying  
- **Python** – Data cleaning, EDA, and statistical analysis  
- **Power BI** – Dashboard visualization and executive reporting  

---
# 
upi-transaction-analysis-capstone/
│
├── README.md                # Project overview and setup guide
│
├── data/
│   ├── raw/                 # Original CSV/Excel files
│   ├── cleaned/             # Cleaned datasets
│
├── sql/
│   ├── ddl_scripts.sql      # Table creation scripts
│   ├── ingestion_queries.sql
│
├── notebooks/
│   ├── 01_data_validation.ipynb
│   ├── 02_data_cleaning_eda.ipynb
│   ├── 03_statistical_analysis.ipynb
│
├── reports/
│   ├── executive_summary.pdf
│   ├── dashboard.pbix
│
├── visuals/
│   ├── charts/              # PNGs from Python or Power BI
│
├── docs/
│   ├── BRD.md               # Business Requirements Document
│   ├── KPI_Framework.md
│
└── requirements.txt         # Python dependencies
