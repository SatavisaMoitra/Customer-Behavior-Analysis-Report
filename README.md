# 📊 Customer Behaviour Analysis Project
# 📌 Project Overview

This project focuses on analyzing customer purchasing behavior using an end-to-end data analytics pipeline. It integrates Excel, Jupyter Notebook, PostgreSQL, and Power BI to clean data, extract insights, and visualize key business metrics through an interactive dashboard.

The objective is to understand customer trends, spending patterns, subscription behavior, and product performance to support data-driven decision-making.

#🛠️ Tools & Technologies Used

Excel – Initial data inspection and formatting

Jupyter Notebook (Python) – Data cleaning, handling null values, and preprocessing

PostgreSQL – Data storage, querying, and analytical SQL insights

Power BI – Interactive dashboard creation and visualization

# 🔄 Project Workflow
1️⃣ Data Collection

Raw customer data was initially explored using Excel.

Basic checks were performed for missing values, incorrect data types, and inconsistencies.

2️⃣ Data Cleaning & Preprocessing (Jupyter Notebook)

Null and missing values were handled appropriately.

Data types were standardized (numerical, categorical, and date fields).

Cleaned and structured data was prepared for database ingestion.

3️⃣ Data Storage & Analysis (PostgreSQL)

The cleaned dataset was loaded into PostgreSQL.

SQL queries were executed to generate insights such as:

Revenue by gender and age group

Subscription vs non-subscription spending behavior

Discount impact on purchases

Product performance and customer segmentation

4️⃣ Data Visualization (Power BI)

PostgreSQL was connected to Power BI.

An interactive Customer Behaviour Dashboard was created to visualize:

Total customers, average purchase amount, and review ratings

Revenue and sales by product category

Age group and customer segment analysis

Subscription and discount trends

# 📈 Key Insights Generated

Subscribed customers tend to have higher average spending

Young adults contribute the highest revenue among age groups

Clothing and accessories are top-performing categories

Discounts significantly influence purchase decisions

Loyal customers generate consistent revenue

# Customer-Behaviour-Analysis
│
├── notebooks/
│   └── customer_behavior.ipynb
│
├── sql/
│   └── customer_behaviour_analysis.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
└── README.md


# 🚀 How to Run This Project

Clean and preprocess the dataset using the Jupyter Notebook.

Load the cleaned data into PostgreSQL.

Run the SQL queries provided in the .sql file.

Connect Power BI to PostgreSQL and refresh the dashboard visuals.

# 📊 Dashboard Preview

The Power BI dashboard provides a comprehensive view of customer behavior and helps identify key business insights efficiently.

# ⭐ Feedback

If you find this project useful, feel free to ⭐ the repository and share your feedback.
