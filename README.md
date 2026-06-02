# Brazilian E-Commerce Data Engineering Project
------------------------------------------------

## Project Overview
-------------------
Designed and developed an end-to-end Data Engineering and Business Intelligence solution using the Brazilian E-Commerce Public Dataset. The project transforms raw transactional data into a scalable analytical platform through ETL processing, dimensional data modeling, SQL analytics, interactive Power BI dashboards, and AWS cloud deployment architecture.

## Objectives
---------------
\* Build a scalable data pipeline

\* Design a Star Schema Data Warehouse

\* Perform business analytics using SQL

\* Create interactive Power BI dashboards

\* Deploy the solution on AWS


## Technology Stack
-------------------
### Programming
\* Python

\* SQL

### Data Processing
\* Pandas

\* NumPy 

\* VS Code

### Database
\* MySQL

### Business Intelligence
\* Power BI
\* DAX

### Cloud
\* AWS

##Development Tools
\*VS Code, Git, GitHub


-------------------------------------------------
| Category               | Technologies         |
| ---------------------- | -------------------- |
| Programming            | Python, SQL          |
| Data Processing        | Pandas, NumPy        |
| Database               | MySQL                |
| Data Warehousing       | Star Schema Modeling |
| Business Intelligence  | Power BI, DAX        |
| Workflow Orchestration | Apache Airflow       |
| Cloud Platform         | AWS (EC2, S3, RDS)   |
| Development Tools      | VS Code, Git, GitHub |
-------------------------------------------------



## Dashboard Screenshots
### Figure A.1 – KPI Analysis Dashboard
<img width="1356" height="800" alt="Screenshot 2026-06-01 165124" src="https://github.com/user-attachments/assets/04819497-704b-42f2-a311-71e6c965c361" />

### Figure A.2 – Sales Analysis Dashboard
<img width="1342" height="755" alt="Screenshot 2026-06-01 223141" src="https://github.com/user-attachments/assets/a62f9126-5763-4520-8075-3550afa32543" />

### Figure A.3 – Customer Analysis Dashboard
<img width="1387" height="806" alt="Screenshot 2026-06-01 164041" src="https://github.com/user-attachments/assets/d4a98bd0-887c-46c3-a5c1-caae99120532" />

### Figure A.4 – Product Analysis Dashboard
<img width="1387" height="806" alt="Screenshot 2026-06-01 164041" src="https://github.com/user-attachments/assets/27059a18-6897-498d-91e4-cbb427efa239" />
<img width="1395" height="787" alt="Screenshot 2026-06-01 165636" src="https://github.com/user-attachments/assets/fba0645f-c36a-4e6b-8533-cb2a6351c752" />

### Figure A.5 – Payment Analysis Dashboard
<img width="1392" height="777" alt="Screenshot 2026-06-01 165536" src="https://github.com/user-attachments/assets/ef25379c-fab9-410b-8303-afdd2dcd5f10" />

### Figure A.6 - Delivery Analysis Dashboard
<img width="1402" height="832" alt="Screenshot 2026-06-01 164131" src="https://github.com/user-attachments/assets/caaa8a28-5695-4059-be26-586243322dac" />

### Figure A.7 – Review Analysis  Dashboard
<img width="1327" height="726" alt="Screenshot 2026-06-01 222900" src="https://github.com/user-attachments/assets/aa91614f-4a9f-4abc-bfff-fde752532224" />

### Figure A.8 – Seller Analysis Dashboard
<img width="1367" height="797" alt="Screenshot 2026-06-01 163914" src="https://github.com/user-attachments/assets/6dfada05-7e11-4e1e-9c63-c99dffa3fe42" />

### Figure A.9 – Top Products Dashboard
<img width="1363" height="791" alt="Screenshot 2026-06-01 164645" src="https://github.com/user-attachments/assets/af9d21fb-9171-43cd-8d20-e762a1c286ee" />

### Figure A.10 – Geolocation Analysis Dashboard
<img width="1347" height="812" alt="Screenshot 2026-06-01 164436" src="https://github.com/user-attachments/assets/d6285522-e4f7-4f51-8c4e-a5be3143c958" />

### Figure A.11 – Data Model (Star Schema)
<img width="1676" height="735" alt="DATA MODELING " src="https://github.com/user-attachments/assets/36f82a0f-8d5f-4297-b131-db131129ce2d" />

## Project Architecture
------------------------

<img width="1024" height="1536" alt="Project Architecture" src="https://github.com/user-attachments/assets/b11d72c9-4588-4da0-8bf9-96b3caa191ff" />


## PROJECT WORK FLOW
--------------------

<img width="1122" height="1402" alt="PROJECT STUCTURE" src="https://github.com/user-attachments/assets/250c2eea-0274-4e84-9ce9-7d5bc1a8ffc0" />


### Data Warehouse Schema
--------------------------
Dimension Tables
----------------
dim\_customers

dim\_products

dim\_sellers

dim\_dates

dim\_geolocation

dim\_payment\_types


 Fact Tables
-------------
fact\_orders

fact\_order\_items

fact\_payments

fact\_reviews


### ETL Pipeline Features
--------------------------
Raw Data Validation

Data Cleaning & Standardization

Missing Value Handling

Duplicate Removal

Data Transformation

Fact & Dimension Table Creation

Automated Data Loading

Data Quality Checks



### SQL Analytics
-------------------
Developed 30+ analytical SQL queries covering:

Revenue Analytics

Customer Analytics

Product Analytics

Seller Analytics

Payment Analytics

Delivery Analytics

Review Analytics

Geographical Analytics

Window Functions

Advanced Business Intelligence Queries


## Power BI Dashboards
------------------------
Executive Dashboard
-------------------
Revenue KPIs
Order KPIs
Customer KPIs
Business Performance Metrics

Sales Dashboard
----------------
Revenue Trends
Category Performance
Top Products
Growth Analysis

Customer Dashboard
-------------------
Customer Segmentation
Customer Distribution
Purchase Behavior

Seller Dashboard
-----------------
Seller Performance
Revenue Contribution
Order Fulfillment Metrics

Delivery Dashboard
-------------------
Delivery Performance
Shipping Analysis
Order Completion Trends

Payment Dashboard
------------------
Payment Method Analysis
Payment Distribution
Revenue Contribution


## Key Achievements
---------------------
Processed 9 Raw Datasets

Built 6 Dimension Tables

Created 4 Fact Tables

Developed 30+ SQL Analytics Queries

Designed 7 Business Intelligence Views

Implemented 35+ DAX Measures

Built Multiple Interactive Power BI Dashboards

Designed AWS Cloud Deployment Architecture


## AWS Deployment Architecture
----------------------------------
The solution is designed for cloud deployment using AWS services:
Amazon EC2 – Application Hosting
Amazon RDS – Managed MySQL Database
Amazon S3 – Data Storage
AWS IAM – Security & Access Control
Amazon CloudWatch – Monitoring & Logging


## Skills Demonstrated
------------------------
Data Engineering

ETL Pipeline Development

Data Warehousing

Dimensional Modeling

SQL Analytics

Business Intelligence

Power BI Development

DAX

Cloud Architecture

AWS Services

Data Visualization




# How to Run the Project
------------------------

## Prerequisites

- Python 3.10+
- MySQL Server 8.0+
- Power BI Desktop
- Git

## Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Brazilian_Ecommerce_Analytics.git
cd Brazilian_Ecommerce_Analytics
```

## Step 2: Install Required Packages

```bash
pip install -r requirements.txt
```

## Step 3: Create MySQL Database

```sql
CREATE DATABASE brazilian_ecommerce_dw;
```

## Step 4: Run ETL Pipeline

Execute the ETL scripts to clean, transform, and load data into the data warehouse.

```bash
python etl/customer_etl.py
python etl/product_etl.py
python etl/seller_etl.py
python etl/order_etl.py
```

## Step 5: Create Data Warehouse Objects

Run SQL scripts to create dimension tables, fact tables, and business views.

```sql
SOURCE sql/create_dimension_tables.sql;
SOURCE sql/create_fact_tables.sql;
SOURCE sql/create_business_views.sql;
```

## Step 6: Open Power BI Dashboard

1. Open the `Brazilian E-Commerce Data Engineering & Business Intelligence Project.pbix` file in Power BI Desktop.
2. Connect to the MySQL Data Warehouse.
3. Refresh the dataset.
4. Explore the dashboards.

## Available Dashboards

- KPI Analysis
- Sales Analysis
- Customer Analysis
- Product Analysis
- Seller Analysis
- Delivery Analysis
- Payment Analysis
- Review Analysis
- Geolocation Analysis


## Documentation
Project Documentation
Brazilian_Ecommerce_Data_Engineering_Project_Documentation.pdf

Project Report
Brazilian_Ecommerce_Data_Engineering_Project_Report.pdf

Project Presentation
Brazilian_Ecommerce_Data_Engineering_Project_Presentation.pdf

Architecture Document
Brazilian_Ecommerce_Data_Engineering_Architecture.pdf



## Author
------------

Sunil Badimela

Email:badimelasunil92@gmail.com

Data Engineer | Business Intelligence Developer



