# 🔥 Azure Databricks End-to-End Data Engineering Project

## 📚 Overview

This project demonstrates a complete real-time data engineering pipeline using **Azure Databricks**, **Delta Lake**, and **PySpark**. It covers end-to-end data transformation scenarios including **Slowly Changing Dimensions (SCD)**, **Star Schema Modeling**, and **real-time streaming** — ideal for both learning and showcasing production-grade pipelines in the cloud.

---

## 🧰 Tech Stack

- ✅ Azure Databricks
- ✅ Delta Lake Gen2
- ✅ Delta Live Tables (DLT)
- ✅ PySpark
- ✅ Azure Data Lake Storage (ADLS)
- ✅ Power BI
- ✅ Role-Based Security and Access Control

---

## 🧱 Architecture

![Azure Project](https://github.com/user-attachments/assets/58d6a722-c7e1-4cbd-a661-267ba9bbe7b9)

---

## 🔄 Pipeline Stages

1. **🔐 Data Ingestion**  
   - Source: Azure / GitHub  
   - Access: Secured via role-based access control (RBAC)

2. **⚙️ ETL & Transformation**  
   - Tool: Databricks with Delta Lake Gen2  
   - Code: PySpark notebooks  
   - Real-time and batch pipelines using Delta Live Tables

3. **📊 Data Modeling**  
   - Star schema with fact and dimension tables  
   - SCD Type 1 & Type 2 logic

4. **🏦 Data Load & Storage**  
   - Cleaned and modeled data stored in a curated (silver/gold) zone  
   - Delta Lake ensures ACID transactions and schema evolution

5. **📈 Reporting Layer**  
   - Power BI dashboard built over final curated tables  
   - Real-time insights using DirectQuery or import mode

---

## 🚀 Features Implemented

- ✅ Real-time data streaming with Spark
- ✅ Dimensional modeling (Star Schema)
- ✅ SCD Type 1 and Type 2 implementation
- ✅ Delta Lake transactions & time travel
- ✅ Power BI integration
- ✅ CI/CD with GitHub version control

---

## 🔍 Sample Pipeline View

![Databricks Pipeline](https://github.com/user-attachments/assets/e65105ac-6ee9-4a9a-b130-cf519b7d3312)

---

## 🖥️ Power BI Dashboard

> *(Include a screenshot or link to Power BI dashboard once published)*

---

## 🧪 How to Run

1. Clone the repository and open it in Azure Databricks.
2. Configure access to your Azure Data Lake and set required secrets.
3. Run notebooks in the provided order or trigger the DLT pipeline.
4. Load final tables into Power BI for dashboarding.

---


---

## 📬 Feedback

Have suggestions or found a bug? Open an issue or create a pull request — all contributions are welcome!

---

## 📄 License

This project is licensed under the MIT License.


