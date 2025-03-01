# Data Warehouse & Analytics Project 🚀

Welcome to the **Data Warehouse and Analytics Project**! This project shows how to build a complete data warehouse and generate useful insights. It's designed as a portfolio project to demonstrate industry best practices in **data engineering and analytics**.

## 🏗️ Data Architecture
This project follows the **Medallion Architecture**, which consists of three layers:

- **Bronze Layer**: Stores raw data from source files (CSV files) in an SQL Server database.
- **Silver Layer**: Cleans, standardizes, and organizes the data for better processing.
- **Gold Layer**: Contains business-ready, structured data in a **star schema** for reporting and analytics.

## 📖 Project Overview
This project covers the following steps:

1. **Data Architecture** – Designing a modern data warehouse using Medallion Architecture.
2. **ETL Pipelines** – Extracting, transforming, and loading data from CSV files into SQL Server.
3. **Data Modeling** – Creating fact and dimension tables for better analytical queries.
4. **Analytics & Reporting** – Writing SQL queries and creating dashboards for insights.

## 🎯 Who is this project for?
This project is a great fit for anyone looking to gain hands-on experience in:
- **SQL Development**
- **Data Architecture**
- **Data Engineering**
- **ETL Pipelines**
- **Data Modeling**
- **Data Analytics**

## 🛠️ Tools & Resources
Everything used in this project is **free**! Here are the tools you will need:

- **Datasets**: CSV files containing ERP and CRM data.
- **SQL Server Express**: A lightweight version of SQL Server for managing databases.
- **SQL Server Management Studio (SSMS)**: A GUI tool for working with databases.
- **GitHub**: To manage and track code changes.
- **Draw.io**: To design data flow diagrams and models.
- **Notion**: A tool for managing project tasks and documentation.

## 🚀 Project Requirements
### **1. Building the Data Warehouse (Data Engineering)**
#### **Objective:**
Create a **modern data warehouse** using **SQL Server** to store and analyze sales data.

#### **Tasks:**
- Import data from **two sources** (ERP and CRM) as CSV files.
- Clean and fix data quality issues before analysis.
- Combine data into a **single, well-structured model** for analysis.
- Focus only on the latest dataset (no historical data is required).
- Provide **clear documentation** for business and analytics teams.

### **2. Analytics & Reporting (Data Analysis)**
#### **Objective:**
Use **SQL-based analysis** to extract insights on:
- **Customer behavior**
- **Product performance**
- **Sales trends**

These insights help businesses make **data-driven decisions**.

## 📂 Project Folder Structure
Here's how the project files are organized:
```
data-warehouse-project/
│
├── datasets/            # Raw ERP and CRM data (CSV files)
│
├── docs/               # Documentation and architecture details
│   ├── etl.drawio      # ETL process diagram
│   ├── data_architecture.drawio  # Data warehouse architecture
│   ├── data_catalog.md  # Dataset descriptions and metadata
│   ├── data_flow.drawio  # Data flow diagram
│   ├── data_models.drawio  # Data model (star schema)
│   ├── naming-conventions.md  # Naming guidelines for tables and columns
│
├── scripts/            # SQL scripts for ETL processes
│   ├── bronze/         # Extract and load raw data
│   ├── silver/         # Clean and transform data
│   ├── gold/           # Create analytical models
│
├── tests/              # Test scripts for data quality
│
├── README.md           # Project introduction and instructions
├── LICENSE             # Project license (MIT License)
├── .gitignore          # Files to be ignored by Git
└── requirements.txt     # List of dependencies
```

## 🛡️ License
This project is open-source under the **MIT License**, meaning you are free to use, modify, and share it with proper credit.

Let's connect! Feel free to reach out to me on social media. 😊

