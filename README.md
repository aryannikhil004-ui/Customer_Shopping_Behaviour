## Customer_shopping_behaviour
Data analyst project showing Customer_shopping_behaviour analysis using tools like Python,SQL, and Power BI

📌 Project Overview

This project analyzes customer shopping behavior using a complete Data Analytics lifecycle approach.

It demonstrates:

📂 Data loading using Python

🔎 Exploratory Data Analysis (EDA)

🧹 Data cleaning & preprocessing

🗄️ SQL-based business analysis (SQL Server)

📊 Interactive dashboard creation in Power BI

📑 Business insights reporting

The goal is to extract meaningful insights about customer spending patterns, discounts, subscriptions, and product performance to support data-driven decision-making.

📁 Dataset Information

File: customer_shopping_behavior.csv

The dataset includes customer-level transactional data such as:

Customer ID

Gender

Age

Product Category

Purchase Amount

Discount Applied

Review Rating

Shipping Type (Standard / Express)

Subscription Status

Purchase Date

This dataset is used to analyze revenue trends, customer segments, and purchasing behavior.

🛠️ Tools & Technologies
Category	Tools Used
Programming	Python
Libraries	Pandas, Matplotlib, Seaborn
Database	SQL Server
Visualization	Power BI
Environment	Jupyter Notebook
🔄 Project Workflow
1️⃣ Data Loading (Python)

Imported CSV using Pandas

Checked structure and data types

Reviewed missing values

import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
df.info()
df.head()
2️⃣ Data Cleaning

Removed duplicate records

Handled missing/null values

Converted data types (e.g., date columns)

Standardized categorical fields

Verified numerical ranges

3️⃣ Exploratory Data Analysis (EDA)

Performed statistical and visual analysis including:

Revenue distribution

Gender-wise revenue comparison

Discount vs Non-discount spending

Shipping type comparison

Subscriber vs Non-subscriber analysis

Top 5 highest-rated products

Average purchase amount trends

Visualizations Created:

Bar Charts

Line Charts

Histograms

Pie Charts

Box Plots

Scatter Plots

4️⃣ SQL Server Analysis

The cleaned dataset was imported into SQL Server for structured query analysis.

Key Business Queries:

Total revenue by gender

Customers who used discount but spent above average

Top 5 products by average rating

Average purchase by shipping type

Subscriber vs non-subscriber revenue comparison

Example:

SELECT gender, SUM(purchase_amount) AS total_revenue
FROM customer
GROUP BY gender;
5️⃣ Power BI Dashboard

An interactive dashboard was built including:

KPI Cards (Total Revenue, Avg Purchase, Total Customers)

Revenue by Gender

Revenue by Product Category

Shipping Type Comparison

Subscription Spending Analysis

Top Rated Products

Interactive Filters (Slicers)

📊 Dashboard Preview (Add Screenshot Here)
/images/dashboard_screenshot.png

(Replace this section with actual dashboard screenshots in your repository.)

📈 Key Business Insights

Subscribers spend more on average compared to non-subscribers

Express shipping customers show higher purchase values

Discounts positively influence overall revenue

Certain product categories generate significantly higher revenue

Highly rated products correlate with higher sales

▶ How to Run This Project
🔹 Run Python Analysis

Clone the repository:

git clone https://github.com/your-username/customer-shopping-analysis.git

Install dependencies:

pip install pandas matplotlib seaborn pyodbc

Run the Jupyter Notebook or Python script.

🔹 Run SQL Analysis

Import CSV into SQL Server

Create database and table

Execute provided SQL queries

🔹 Open Power BI Dashboard

Open Power BI Desktop

Connect to SQL Server or CSV

Load dataset

Open .pbix file (if included)

📂 Repository Structure
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── analysis.ipynb
├── sql/
│   └── queries.sql
├── powerbi/
│   └── dashboard.pbix
├── images/
│   └── dashboard_screenshot.png
└── README.md
💼 Why This Project Stands Out

✔ Demonstrates complete Data Analytics lifecycle
✔ Combines Python + SQL + Power BI
✔ Includes business-focused SQL queries
✔ Provides actionable insights
✔ Recruiter-friendly structure
✔ Real-world problem-solving approach

👨‍💻 Author

Nikhil
Aspiring Data Analyst

Skills:
Python | SQL | Power BI | Data Cleaning | EDA | Data Visualization



