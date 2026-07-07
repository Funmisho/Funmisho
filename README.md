# Hey, I'm Bukunmi 👋
I build data pipelines, design schemas, and model data for analytical systems.
Based in Lagos. Tilting hard toward **data engineering** — the infrastructure layer that makes analytics actually work.

---

## 🔧 What I've Shipped

**[Weather Data ETL/ELT Pipeline](https://github.com/Funmisho/weather-pipeline)**
Production-style pipeline pulling live forecast data (Lagos, Abuja, Kano) from the Open-Meteo API. Raw JSON staged to SQLite before transformation (ELT pattern). Star schema with fact and dimension tables, Apache Airflow orchestration on a daily schedule, structured logging, data validation, and per-city fault-tolerant error handling.

**[Movie Recommendation ETL Pipeline](https://github.com/Funmisho/movie-etl-pipeline)**
End-to-end ETL on MovieLens 100K. Extracts raw CSVs, applies recommendation logic, loads into PostgreSQL modelled as a star schema. Four dimension tables, one fact table, SQLAlchemy for the load layer, credentials managed via python-dotenv.

**[Hospital Relational Database — General Hospital Keffi](https://github.com/Funmisho/general-hospital-keffi-db)**
Replaced a fragmented Excel system with a 3NF relational database for a real Nigerian hospital. Six tables, WHO ICD-10 diagnosis codes, bridge table for many-to-many relationships. Analytical SQL queries for reporting. Azure SQL deployment path documented.

**[Cloud Kitchen Business Intelligence System](https://github.com/Funmisho/cloud-kitchen-analytics-system)**
Full BI workflow for a delivery-only restaurant — from database design to operational dashboards. Normalized MySQL database storing orders, inventory, and staff records. SQL views transform transactional data into three Tableau dashboards covering sales performance, inventory health, and staff efficiency. Key finding: evening hours drive peak demand, cheese is the primary cost driver despite flour being the most-used ingredient.

**[Google Fiber Repeat Call Analysis](https://github.com/Funmisho/google-fiber-bi-capstone)**
BigQuery pipeline consolidating three market datasets via UNION ALL into a single reporting table. Surfaced a 31.2% repeat call rate. Dashboard live on Tableau Public.

**[Sales Pipeline & Lead Conversion Analysis](https://github.com/Funmisho/sales-pipeline-analysis)**
Rebuilt a broken data model — replaced a single stage column with a relational stage history table (the structure Salesforce actually uses). SQL views as the single source of truth feeding Tableau.

---

## 🛠 Stack

```
SQL          PostgreSQL · MySQL · SQLite · BigQuery · CTEs · window functions · views
Modelling    Star schema · snowflake · normalisation · ERD design · OLTP vs OLAP
Pipelines    ETL/ELT · SQLAlchemy · pandas · Apache Airflow · fault-tolerant orchestration
Warehousing  Data warehouse design · staging layers · star schema implementation
Python       requests · logging · pytest · data validation
Viz          Tableau Public
Learning     Kafka · dbt · feature stores
```

---

## 📜 Certifications

- Microsoft Certified: Azure Data Fundamentals (DP-900) — **Microsoft** (2026)
- Associate Data Engineer in SQL — **DataCamp** (May 2026)
- Google Business Intelligence Professional Certificate — **Google / Coursera** (2026)
- Google Data Analytics Professional Certificate — **Google / Coursera** (2026)

---

## 📖 Currently

- Completed Data Engineering Track at **AI Community Africa** 
- Reading *Fundamentals of Data Engineering* — Joe Reis
- Writing about data engineering concepts on **[Medium](https://medium.com/@oluwabukunmi)**

---

## 📬 Let's talk

[Mail](mailto:akinmioluwabukunmi109@gmail.com) · [LinkedIn](https://linkedin.com/in/akinmi) · [Medium](https://medium.com/@oluwabukunmi) · Lagos, Nigeria
