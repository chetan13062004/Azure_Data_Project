# Azure End-to-End Data Engineering Project 🌟

![Architecture Diagram](images/architecture.png)

This project demonstrates an end-to-end **Azure Data Engineering pipeline** built using multiple Azure services to ingest, transform, analyze, and visualize an **e-commerce (Olist) dataset**.

The dataset contains multiple files related to customers, orders, payments, products, sellers, and geolocation data, simulating a real-world data engineering scenario.

---

## Dataset Overview 📊

The dataset includes:

- Customer details  
- Orders and order items  
- Payment transactions  
- Product and seller information  
- Reviews and geolocation data  

The data is sourced from:

- **SQL Database**
- **MongoDB**
- **HTTP (GitHub)**

![Dataset Relationships](images/datafilesconection.png)

---

## Azure Resources Used 💡

- **Azure Data Factory (ADF)** – Data ingestion & orchestration  
- **Azure Data Lake Storage Gen2 (ADLS)** – Bronze, Silver & Gold storage layers  
- **Azure Databricks** – Data cleaning, transformation & enrichment  
- **Azure Synapse Analytics** – SQL analytics & views  
- **MongoDB** – Semi-structured data source  
- **HTTP (GitHub)** – External data source  
- **Power BI / Tableau / Fabric** – Visualization  

---

## Project Architecture 🏗️

![Project Architecture](images/resource_1.png)

---

## Project Workflow 🔄

### 1️⃣ Data Ingestion – Bronze Layer

- Raw data ingested using **Azure Data Factory**
- Sources:
  - SQL tables
  - MongoDB collections
  - HTTP (GitHub CSV files)
- Used **Lookup + ForEach + Copy Activity**
- Stored raw data in **ADLS Gen2 (Bronze layer)**

![ADF Pipeline](images/resource_2.png)
![ADF Copy Activity](images/resource_3.png)

---

### 2️⃣ Data Transformation – Silver Layer

- Data processing performed in **Azure Databricks**
- Steps:
  - Removed duplicates
  - Standardized schemas
  - Converted timestamps
  - Joined multiple datasets
  - Enriched data using MongoDB tables
- Output stored in **Parquet format** in **Silver layer**

![Databricks Notebook](images/resource_4.png)

---

### 3️⃣ Data Analysis – Gold Layer

- Transformed data loaded into **Azure Synapse Analytics**
- SQL queries and views created
- Aggregated and analytical data stored in **Gold layer**

![Synapse Analytics](images/resource_5.png)

---

### 4️⃣ Visualization 📊

- Data visualized using:
  - **Power BI**
  - **Tableau**
  - **Microsoft Fabric**
- Dashboards provide insights like:
  - Order delays
  - Payment methods
  - Seller performance
  - Customer distribution

![Visualization](images/resource_6.png)

---

## Key Features ✨

- ✅ Dynamic ADF Pipelines  
- ✅ Multi-source data ingestion  
- ✅ Bronze–Silver–Gold architecture  
- ✅ Real-world joins & enrichment  
- ✅ Scalable Databricks transformations  
- ✅ SQL analytics using Synapse  

---

## Technologies Used 🛠️

| Technology | Purpose |
|---------|--------|
| Azure Data Factory | Data ingestion |
| ADLS Gen2 | Data storage |
| Azure Databricks | Data transformation |
| Azure Synapse | SQL analytics |
| MongoDB | Semi-structured data |
| GitHub (HTTP) | External data source |
| Power BI | Visualization |

---

## Future Enhancements 🚀

- 🔹 Real-time streaming using Event Hub  
- 🔹 Delta Lake implementation  
- 🔹 Advanced Power BI dashboards  
- 🔹 Data quality checks  
- 🔹 CI/CD for ADF pipelines  

---

## Contact 📧

For any queries or feedback, feel free to reach out:

**Chetan Bochare**  
📩 Email: **chetanbochare2004@gmail.com**

---

⭐ If you found this project useful, don’t forget to star the repository!
