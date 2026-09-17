# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🎯 Objective

Develop a modern data warehouse using **PostgreSQL** to consolidate sales data, enabling analytical reporting and informed decision-making.

### Specifications

- **Data Sources:** Import data from source systems (e.g. ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** (Bronze, Silver, Gold layers):

- **Bronze Layer** — Stores raw data as-is from the source systems. Data is ingested from CSV files into the PostgreSQL database with no transformations.
- **Silver Layer** — Includes data cleansing, standardisation, and normalisation processes to prepare data for analysis.
- **Gold Layer** — Houses business-ready data modeled into a star schema, required for reporting and analytics.


---

## 📖 Project Overview

This project involves:

1. **Data Architecture** — Designing a modern data warehouse using the Medallion Architecture (Bronze, Silver, Gold layers).
2. **ETL Pipelines** — Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling** — Developing fact and dimension tables optimised for analytical queries.
4. **Analytics & Reporting** — Creating SQL-based reports and dashboards for actionable insights.

This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

## 🛠️ Important Links & Tools

- **Datasets:** Access the project dataset(s) in the [`datasets`](datasets/) folder.
- **PostgreSQL:** Database engine used to host the data warehouse.
- **DBeaver / pgAdmin:** GUI clients for managing and interacting with the database.
- **Draw.io:** Used to design data architecture, models, flows, and diagrams.
- **Git & GitHub:** Version control and collaboration.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**
Develop a modern data warehouse using PostgreSQL to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**
- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

### BI: Analytics & Reporting (Data Analysis)

**Objective**
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behaviour**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

📄 For specific requirements, check [`docs/requirements.md`](docs/requirements.md).

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                          # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                              # Project documentation and architecture details
│   ├── etl.drawio                     # Draw.io file for ETL techniques and methods
│   ├── data_architecture.drawio       # Draw.io file for data architecture
│   ├── data_catalog.md                # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio               # Draw.io file for data flow diagram
│   ├── data_models.drawio             # Draw.io file for data models (star schema)
│   ├── naming-conventions.md          # Naming conventions for tables, columns, and files
│
├── scripts/                           # SQL scripts for ETL and transformations
│   ├── bronze/                        # Scripts for extracting and loading raw data
│   ├── silver/                        # Scripts for cleaning and transforming data
│   ├── gold/                          # Scripts for creating analytical models
│
├── tests/                             # Test scripts and quality checks
│
├── README.md                          # Project overview and instructions
├── LICENSE                            # License information for the repository
└── .gitignore                         # Files and directories to be ignored by Git
```

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Reggie**, a Senior People Data Analyst working at the intersection of HR analytics, data reporting, and automation — with hands-on experience across Power BI, SQL, Python, and Power Automate.
