# End-to-End Medallion Pipeline in Microsoft Fabric

<img src="lineage.png" width="600">

## 🚀 Project Overview
I built a rapid-deployment data pipeline in Microsoft Fabric to transform raw CSV sales data into a business-ready "Gold" layer. This project demonstrates the Medallion Architecture using PySpark and OneLake.

## 🏗️ Architecture
- **Bronze:** Raw CSV ingestion into OneLake.
- **Silver:** Data cleansing, schema enforcement, and standardization via Spark Notebooks (Delta format).
- **Gold:** Aggregated regional sales performance for executive reporting.

## 🛠️ Tech Stack
- **Platform:** Microsoft Fabric
- **Engine:** Apache Spark (PySpark)
- **Storage:** OneLake / Delta Lake
- **Visualization:** Power BI (DirectLake mode)

## 📈 Key Achievements
- Implemented **Schema Enforcement** to ensure data quality.
- Utilized **Delta Lake** tables to support ACID transactions.
- Developed a **DirectLake** connection to Power BI, eliminating the need for data refreshes.
