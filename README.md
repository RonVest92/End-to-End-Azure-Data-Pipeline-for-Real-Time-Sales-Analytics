
# 🌍 End-to-End Azure Data Engineering Capstone Project – Real-Time Sales Analytics


## 📘 Project Overview
This project showcases a complete, production-style data engineering pipeline built on Microsoft Azure. It automates the ingestion, transformation, and analysis of sales and customer data using Azure Data Factory, Databricks (PySpark), Delta Lake, and Synapse Analytics, with real-time insights visualized in Power BI.

The solution demonstrates key Azure data engineering skills including ETL/ELT pipeline orchestration, big data processing, data lake architecture, real-time streaming, and business intelligence integration. It serves as a full data-to-decision workflow—transforming raw data into actionable insights for data-driven decision-making.

🚀 Tech Stack: Azure Data Factory • Azure Databricks • PySpark • Delta Lake • Azure Data Lake Gen2 • Synapse Analytics • Event Hubs • Stream Analytics • Power BI

---

## 🧩 Architecture Overview

**Pipeline Flow:**
```

[Source Data: CSV/API/Streaming]
↓
Azure Data Factory (ETL Orchestration)
↓
Azure Databricks (PySpark Transformations)
↓
Delta Lake (Data Versioning)
↓
Azure Synapse / SQL DB (Data Warehouse)
↓
Power BI Dashboard (Visualization)

```

---

## 🛠️ Tech Stack

| Category | Tools / Services |
|-----------|------------------|
| Languages | Python, SQL, PySpark |
| Cloud | Microsoft Azure |
| ETL / Orchestration | Azure Data Factory |
| Processing | Azure Databricks, Delta Lake |
| Storage | Azure Blob Storage, Data Lake Gen2 |
| Warehouse | Azure Synapse Analytics |
| Streaming | Event Hubs, Stream Analytics |
| Visualization | Power BI |
| Version Control | Git, GitHub |

---

## ⚙️ Key Components

### 1. **Data Ingestion**
- Extracted CSV and API-based sales data using **Azure Data Factory** Copy Activity.
- Scheduled ingestion pipelines with triggers for daily batch and event-driven refreshes.

### 2. **Data Storage**
- Stored raw data in **Azure Data Lake Gen2** using a structured folder hierarchy:
```

/raw
/processed
/curated

```

### 3. **Data Transformation**
- Cleaned and transformed data with **PySpark in Databricks Notebooks**.
- Implemented Delta Lake for data reliability, schema evolution, and ACID compliance.

### 4. **Data Modeling & Warehouse**
- Created star schema models in **Synapse Analytics** for optimized analytical queries.
- Integrated curated data with Power BI datasets for reporting.

### 5. **Real-Time Streaming**
- Simulated sales streams through **Azure Event Hubs**.
- Processed incoming data in near real time using **Azure Stream Analytics**.

### 6. **Visualization**
- Built Power BI dashboard to display:
- Total and regional sales trends
- Top-selling products
- Real-time updates from Stream Analytics output

### 7. **Automation & Monitoring**
- Configured **ADF triggers** for end-to-end automation.
- Enabled monitoring through ADF pipeline runs and Databricks job dashboards.

---

## 📈 Results
- Reduced reporting lag from hours to minutes.
- Automated ETL workflows with full error handling and retry logic.
- Demonstrated scalability for enterprise data operations on Azure.
- Enhanced understanding of Azure Data Engineering best practices.

---

## 🧠 Learning Outcomes
- Hands-on mastery of Azure Data Factory, Databricks, Delta Lake, and Synapse Analytics.
- Understanding of cloud-based ETL/ELT orchestration.
- Practical experience with data lakehouse architecture.
- End-to-end deployment of a real-time analytical solution.

---

## 📊 Power BI Dashboard – Real-Time Sales Analytics

This dashboard visualizes the processed and curated data from Azure Synapse and Stream Analytics.  
It provides executives with real-time sales performance, customer insights, and operational KPIs.

![PowerBI_Dashboard_Screenshot](images/powerbi_dashboard_sample.png)

### Dashboard Highlights:
- **Total Sales & Growth KPIs**
- **Regional Sales Heatmap**
- **Top Products & CLV Insights**
- **Real-Time Data Feed Monitoring**
- **Automated Refresh & Pipeline Status**

Each visual connects directly to live Azure datasets, updating seamlessly through Power BI’s real-time streaming capabilities.

## 📎 Repository Structure
```

├── data/
│   ├── raw/
│   ├── processed/
│   ├── curated/
├── notebooks/
│   ├── data_cleaning_pyspark.ipynb
│   ├── delta_merge_notebook.ipynb
├── pipelines/
│   ├── adf_pipeline.json
│   ├── databricks_jobs.json
├── reports/
│   ├── PowerBI_dashboard.pbix
│   ├── Dashboard_Screenshot.png
├── docs/
│   ├── Architecture_Diagram.png
│   ├── Setup_Instructions.md
├── README.md


```

---

## 📬 Contact
**Author:** Ronald Ddibya  
📧 ronald.ddibya@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/ronaldddibya)  
```

---


