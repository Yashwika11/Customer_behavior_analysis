# Customer_behavior_analysis
**Project Overview**
RetailIQ is a full-stack data analytics project that explores customer shopping patterns across demographics, product categories, payment methods, and subscription behaviors.
The pipeline covers everything from raw data ingestion and cleaning, through SQL-based business querying, to an interactive Power BI dashboard.

**project structure**
RetailIQ/
│
├── customer_shopping_behavior.csv   # Raw dataset (~3,900 records, 18 features)
├── pythoncode.ipynb                 # Data cleaning, EDA & MySQL ingestion notebook
├── sql_queries.sql                  # Business intelligence SQL queries
├── customer_behavior_dashboard.pbix # Power BI interactive dashboard
├── _eve.py                          # Script to generate the .env credentials file
└── .env                             # DB credentials (auto-generated, not committed)

**Tech Stack**
Layer           |    Tool
--------------------------------------------------------------
Data Cleaning &      EDA |Python (Pandas) ,Jupyter Notebook
Database            |    MySQL
ORM / Connector     | SQLAlchemy, PyMySQL
Secrets Management  | python-dotenv
Business Intelligence |SQL (MySQL Workbench)
Visualization       |  Power BI

**Dataset**
File: customer_shopping_behavior.csv
Records: ~3,900 customers

**Pipeline Walkthrough**
1.Environment Setup
Run _eve.py to auto-generate your .env credentials file:
    python _eve.py
Update the values in .env with your MySQL credentials before proceeding.
2. Data Cleaning & Feature Engineering (pythoncode.ipynb)
3. SQL Business Analysis (sql_queries.sql)
4. Power BI Dashboard (customer_behavior_dashboard.pbix)



**End-to-end data analytics project — from raw CSV to business dashboard.**
