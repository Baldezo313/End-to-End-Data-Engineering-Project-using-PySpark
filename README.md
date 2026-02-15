# End-to-End-Data-Engineering-Project-using-PySpark
End-to-End Retail Analytics Data Engineering Project using PySpark

***  
I build a complete, production-style retail analytics data engineering pipeline using PySpark on a distributed Spark cluster running in Docker.

We generate 1 million+ retail transactions with intentional data quality issues, process them using Medallion Architecture (Bronze → Silver → Gold), and deliver business-ready Parquet datasets optimized for Power BI dashboards.

This project is designed to demonstrate how Spark is actually used in real-world data engineering — not just DataFrame syntax, but distributed execution, schema enforcement, parallel transformations, and analytics modeling.
If you're preparing for Data Engineering, Analytics Engineering, or PySpark-focused roles, this is a serious portfolio project.

## 🚀 What You’ll Learn

In this hands-on project, you’ll learn how to:

• Generate large-scale raw datasets (1M records) with controlled data impurities  
• Run a distributed Spark cluster using Docker & Docker Compose  
• Enforce explicit schemas (no inferSchema shortcuts)  
• Implement Medallion Architecture properly:  

*Bronze*: raw CSV ingestion with schema enforcement  
*Silver*: data cleaning, deduplication, and business rule validation  
*Gold*: analytics-ready aggregations optimized for BI tools  

• Handle distributed transformations and wide shuffles  
• Optimize data storage using Parquet  
• Control partitions and observe Spark UI execution  
• Prepare curated datasets for Power BI dashboards  
• Think like a production data engineer, not a notebook coder  

## 🧠 Project Use Case

This project simulates how a retail analytics team processes large-scale transaction data to:

• Track daily revenue trends  
• Measure category-level product performance  
• Analyze city-level revenue distribution  
• Identify operational and data quality issues  
• Deliver clean, trusted datasets for business stakeholders  

The goal is not just cleaning data — it’s building a scalable, distributed analytics pipeline.

## 🧰 Tech Stack Used

* Apache Spark (3.5.x)  
* PySpark  
* Docker & Docker Compose: https://www.docker.com/products/docke...    
* Power BI: https://apps.microsoft.com/detail/9NT...   
* Python  
* VS Code: https://code.visualstudio.com/  

## 📊 Project Highlights

• 1,000,000 generated records  
• Distributed Spark cluster (Master + Workers)  
• Explicit schema enforcement  
• Data quality rules and standardization  
• Parallelized transformations  
• Business-level aggregations  
• BI-ready Gold datasets  
• Clean, modular, portfolio-ready project structure  
