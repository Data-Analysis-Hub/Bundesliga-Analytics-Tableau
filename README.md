# Bundesliga Performance Analytics (Tableau Edition)

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)](https://spark.apache.org/docs/latest/api/python/index.html)
[![Tableau](https://img.shields.io/badge/Tableau-E97628?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/)

> **Project Note:** This repository contains the **Tableau-driven Business Intelligence layer** for my comprehensive Bundesliga data engineering pipeline. It is the visual companion and reporting extension of the core PySpark & Power BI repository found here: [pyspark-football](https://github.com/Data-Analysis-Hub/pyspark-football).

---

## 📌 Project Overview
This project analyzes **16 seasons of historical German Bundesliga data (18 teams)** to uncover deep historical trends, seasonal team dynamics, and core performance metrics. 

By leveraging **PySpark** for scalable data processing and optimization, the raw dataset was transformed into an enterprise-ready dimensional model. This specific repository focuses on delivering interactive, high-impact executive dashboards built in **Tableau** to translate complex statistical results into actionable stakeholder insights.

---

## 🏗️ Architecture & Data Workflow

1. **Data Ingestion & Processing:** Raw data is processed using **PySpark** to handle historical volume efficiently.
2. **Storage Optimization:** Data structures are optimized and saved using high-performance **Parquet** formatting.
3. **Data Modeling:** Transformed data is structured into a clean **Star Schema** optimized for BI tool performance and complex relational query speeds.
4. **Analytics & Visualization:** **Tableau** dashboards are deployed to deliver comprehensive performance breakdowns, including custom "Team DNA" quadrant analyses.

---

## 📊 Dashboard Key Features
* **Executive Performance Tracking:** High-level overview of team standings, win/loss ratios, and historical trajectories across 16 seasons.
* **Team DNA (Quadrant Analysis):** Advanced scatter plots tracking offensive efficiency vs. defensive resilience to classify team playing styles.
* **Seasonal Trend Drills:** Dynamic time-series filtering allowing stakeholders to isolate specific eras, seasonal peaks, or relegated team statistics.

---

## 🚀 Status
🔧 **In Progress:** The PySpark data pipeline and Parquet files are complete. The final Tableau workbook (`.twbx`) and high-resolution dashboard screenshots are currently being published and uploaded. 

---
*Developed as part of an advanced data analytics portfolio focusing on scalable BI architectures.*
