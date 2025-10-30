
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

This interactive **Power BI Dashboard** provides real-time insights into company-wide sales performance, customer behavior, and operational efficiency.  
It connects directly to **Azure Synapse Analytics** and **Stream Analytics**, ensuring near real-time data updates for decision-makers.  

---

### 🖼️ Dashboard Preview

![Real-Time Sales Analytics Dashboard](https://github.com/RonVest92/End-to-End-Azure-Data-Pipeline-for-Real-Time-Sales-Analytics/blob/dfea65c627a60ada2b691150e66b54803853b5c3/images/Real-Time%20Sales%20Dashboard%20Overview.png)
---

### 🧮 Key Insights & Features

| Category | KPI / Visualization | Description |
|-----------|--------------------|-------------|
| **Performance Metrics** | 💰 **Total Sales, YoY Growth, AOV** | Track key financial indicators in real-time |
| **Trends Analysis** | 📈 **Monthly Revenue Line Chart** | Visualize revenue fluctuations and growth patterns |
| **Product Analysis** | 🏷️ **Top Products by Revenue** | Identify high-performing SKUs and categories |
| **Geographic Insights** | 🗺️ **Regional Sales Heatmap** | Monitor sales by region for strategic planning |
| **System Health** | ⚙️ **Refresh & Latency Monitor** | Display live pipeline refresh times and job status |

---

### ⚙️ Technical Integration
- **Data Sources:** Azure Synapse Analytics (batch), Azure Stream Analytics (real-time)  
- **Data Gateway:** Azure On-Premise Gateway for secure refreshes  
- **Auto-Refresh:** 5-minute intervals for streaming data  
- **Built With:** Power BI Desktop → Deployed via Power BI Service  

---

### 🚀 Value Delivered
This dashboard bridges the gap between **data engineering and business intelligence** by providing a complete data-to-decision flow.  
It demonstrates:
- Real-time analytical capability  
- Scalable Azure-based data pipelines  
- Clear, actionable insights for business users  
- Strong visualization design aligned with enterprise reporting standards  

---

📎 **Project Reference:**  
[🔗 View full Azure Data Engineering project repository](#) *(replace with your GitHub repo link)*  


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


