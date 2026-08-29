Walmart Sales Data Analysis | Python, SQL & Power BI
# 🛒 Walmart Sales Data Analysis

## End-to-End SQL + Python + Power BI Project

An end-to-end data analytics project that analyzes Walmart sales data to extract meaningful business insights.

The project demonstrates a complete analytics workflow using **Python for data processing**, **MySQL and PostgreSQL for data storage**, **SQL for business analysis**, and **Power BI for interactive data visualization**.

---

## 📌 Project Overview

The goal of this project is to transform raw Walmart sales data into meaningful business insights.

The complete workflow includes:

- Data loading and exploration using Python
- Data cleaning and preprocessing using Pandas
- Loading processed data into relational databases
- Performing SQL-based business analysis
- Creating an interactive Power BI dashboard
- Visualizing important KPIs and sales trends

---

# 🔄 Project Workflow

![Project Workflow](images/project_workflow.png)

### Workflow Summary

**Walmart Dataset → Python → Data Cleaning → MySQL/PostgreSQL → SQL Analysis → Power BI Dashboard**

```text
                ┌─────────────────────┐
                │   Walmart Dataset   │
                │       (CSV)         │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │       Python        │
                │       Pandas        │
                │ Data Cleaning &     │
                │   Preprocessing     │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   MySQL / PostgreSQL│
                │   Data Storage      │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    SQL Analysis     │
                │  Business Queries   │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │      Power BI       │
                │ Interactive Dashboard│
                └─────────────────────┘
Workflow Summary

Walmart Dataset → Python → Data Cleaning → MySQL/PostgreSQL → SQL Analysis → Power BI Dashboard

🛠️ Technologies Used
🐍 Python

Used for:

Loading the dataset
Data cleaning
Data preprocessing
Feature engineering
Database connectivity

Libraries used:

Pandas
NumPy
SQLAlchemy
PyMySQL
Psycopg2
🗄️ MySQL

Used for:

Storing processed Walmart sales data
Creating database tables
Performing SQL queries
Business analysis
🐘 PostgreSQL

Used for:

Database connectivity
Loading processed data
Running SQL queries
📊 Power BI

Used for:

Creating an interactive dashboard
KPI visualization
Sales analysis
Interactive filtering
📓 Jupyter Notebook

Used for:

Python development
Data processing
Database loading
📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of Walmart sales performance.

Key Performance Indicators

The dashboard displays:

⭐ Average Rating
📦 Total Quantity Sold
💰 Total Sales
🧾 Total Transactions
Business Analysis

The dashboard includes:

📊 Sales by Category
📈 Sales Trend Over Time
🏙️ Sales by City
💳 Sales by Payment Method
🏪 Sales by Branch
Interactive Filters

Users can filter the dashboard based on:

City
Payment Method
Product Category
🖼️ Dashboard Preview

❓ Business Questions Solved

The project uses SQL queries to answer important business questions such as:

What is the total sales and quantity sold?
Which product category generates the highest sales?
Which city contributes the most to total sales?
Which payment method is most preferred?
Which branch has the highest sales?
What are the top-selling product categories?
What is the average customer rating?
What are the peak sales periods?
How do sales change over time?
Which branch and category combinations are the most profitable?
📂 Project Structure
Walmart_SQL_Python/
│
├── Walmart.csv
├── project.ipynb
│
├── MySQL Queries.sql
├── PSQL Queries.sql
│
├── PowerBI/
│   ├── Walmart_Sales_Dashboard.pbix
│   └── dashboard.png
│
├── requirements.txt
│
└── README.md
⚙️ How to Run the Project
1. Clone the Repository
git clone <your-repository-url>
cd Walmart_SQL_Python
2. Install Required Libraries
pip install -r requirements.txt
3. Run the Jupyter Notebook

Open:

project.ipynb

Run the notebook to:

Load the Walmart dataset
Explore the data
Clean and preprocess the data
Perform feature engineering
Connect to the databases
Load the processed data into MySQL/PostgreSQL
4. Run MySQL Queries

Open:

MySQL Queries.sql

Run the queries in MySQL Workbench to perform business analysis.

5. Run PostgreSQL Queries

Open:

PSQL Queries.sql

Run the queries using PostgreSQL.

6. Open the Power BI Dashboard

Open:

PowerBI/Walmart_Sales_Dashboard.pbix

The dashboard can then be used to interactively explore Walmart sales data.

📈 Key Learnings

Through this project, I gained hands-on experience in:

Data cleaning using Python and Pandas
Working with real-world structured datasets
Data preprocessing and feature engineering
Connecting Python applications with databases
Loading data into MySQL and PostgreSQL
Writing SQL queries for business analysis
Performing aggregation and analytical queries
Using SQL concepts such as:
GROUP BY
Aggregate Functions
Window Functions
Date Functions
Creating interactive Power BI dashboards
Creating KPIs and data visualizations
Using interactive dashboard filters
Building an end-to-end data analytics workflow
🚀 Future Improvements

Possible future improvements include:

Automating the ETL pipeline
Connecting the dashboard to a live database
Adding real-time data updates
Creating advanced DAX measures in Power BI
Adding more business KPIs
Performing customer segmentation
Deploying the data pipeline to the cloud
👩‍💻 Author

Sakshi Patil

📄 License

This project is licensed under the MIT License.


---

## What you need to do now

### 1. Your folder structure should ideally look like this:

```text
F:\Walmart_SQL_Python
│
├── Walmart.csv
├── project.ipynb
├── MySQL Queries.sql
├── PSQL Queries.sql
├── requirements.txt
│
├── PowerBI
│   ├── Walmart_Sales_Dashboard.pbix
│   └── dashboard.png
│
└── README.md