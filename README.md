# E-Commerce Data Pipeline using Databricks, PySpark & Medallion Architecture

## Project Overview
This project demonstrates an end-to-end **E-commerce data engineering pipeline** built using **Databricks, PySpark, and SparkSQL**.  
The pipeline processes raw e-commerce data using the **Medallion Architecture** (Bronze → Silver → Gold layers) to transform raw data into analytics-ready datasets.

The goal of this project is to simulate how modern data engineering pipelines work in real-world data platforms.

---

## Technologies Used

- Databricks
- PySpark
- SparkSQL
- Delta Lake
- Python
- Data Lakehouse Architecture

---

## Architecture Used

This project follows the **Medallion Architecture** used in modern data platforms.

### Bronze Layer
- Raw data ingestion
- Data stored as-is from source
- Minimal transformation

### Silver Layer
- Data cleaning
- Handling missing values
- Data standardization
- Removing duplicates

### Gold Layer
- Business-level aggregations
- Analytical datasets
- Data ready for dashboards and reporting

---

## Project Structure

```
ecommerce-medallion-architecture
│
├── 1_setup
│   └── data_ingestion_setup
│
├── 2_medallion_processing_dim
│   └── dimension_table_processing
│
├── 3_medallion_processing_fact
│   └── fact_table_processing
│
├─
│
└── README.md
```

---

## Data Pipeline Workflow

1. Raw e-commerce datasets are ingested into the Bronze layer.
2. Data is cleaned and transformed in the Silver layer.
3. Analytical tables are created in the Gold layer.
4. Business insights are generated through dashboards.

---

## Key Features

- End-to-end Data Engineering pipeline
- Implementation of Medallion Architecture
- Data transformation using PySpark
- Analytical queries using SparkSQL
- Dashboard for business insights

---

## Dashboard Insights

The dashboard provides insights such as:

- Sales performance
- Product category performance
- Revenue trends
- Customer purchasing behavior

Dashboard screenshots are included in the **dashboard** folder.

---

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Building scalable data pipelines
- Using PySpark for large-scale data processing
- Implementing Medallion Architecture
- Creating analytics-ready datasets
- Working with Databricks Lakehouse platform

---

## Author

**Sumran Harchirkar**

Artificial Intelligence & Data Science Student  
Passionate about Data Engineering, Data Science, and AI.

---

## Future Improvements

- Add streaming data pipeline
- Automate workflows using scheduled jobs
- Integrate BI tools such as Power BI or Tableau
