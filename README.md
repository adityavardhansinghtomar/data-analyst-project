Sales Performance Dashboard

📌 Project Overview

This project analyzes sales performance across different states, products, and sales channels using Python (Pandas) for data preprocessing and Power BI for interactive dashboard visualization.

The goal of this project is to extract meaningful business insights and support data-driven decision making.

🎯 Objectives

Analyze total sales and profit performance

Identify top-performing states and products

Compare sales across different sales channels

Calculate overall profit margin

Build an interactive Power BI dashboard

🛠 Tools & Technologies Used

Python

Pandas

Power BI

DAX (Data Analysis Expressions)

Data Cleaning & Transformation

Data Visualization

🐼 Role of Pandas in This Project
Pandas was used for:

Handling missing values

Removing duplicate records

Converting data types

Formatting date columns

Exploratory Data Analysis (EDA)

Basic statistical analysis

Example:
df.isnull().sum()
df.drop_duplicates()
df['Order Date'] = pd.to_datetime(df['Order Date'])


📂 Dataset Description
The dataset contains:

Order Date

Product Category

Shipping State

Sales Channel

Cost Price

Total Price

Quantity

📊 Dashboard Features

KPI Cards (Total Sales, Total Profit, Profit Margin %)

Top 10 States by Sales

Top 5 Products by Sales

Sales Trend Over Time

Sales by Channel

Profit by Channel

📈 Key Insights

Uttar Pradesh and Delhi are top-performing states.

Pulses and Jam are among the top-selling products.

Shopify generates higher sales compared to Amazon.

Overall profit margin is approximately 4.45%.

🧮 DAX Measures Used

Total Sales

Total Profit

Profit Margin %
