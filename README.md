🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases to uncover insights into customer spending patterns, product preferences, subscription behavior, and revenue drivers.

The analysis combines Python for data cleaning and EDA, PostgreSQL for business queries, and Power BI for dashboard visualization, followed by business recommendations to support strategic decision-making.

This project demonstrates a complete end-to-end data analytics workflow, including data preparation, database analysis, visualization, and reporting.

📂 Dataset Summary

Dataset Characteristics:

Total Records: 3,900

Total Columns: 18

Data Type: Structured transactional dataset

Key Features:

Customer Information

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

Data Quality Handling

Missing values found in Review Rating column

Missing ratings were imputed using median values per category

🛠️ Tools and Technologies Used

Programming & Analysis

Python

Pandas

NumPy

Jupyter Notebook

Database

PostgreSQL

SQL (Aggregation, Joins, Filtering, Segmentation)

Visualization

Power BI

Reporting & Presentation

Microsoft PowerPoint

Gamma AI

⚙️ Project Workflow
1️⃣ Data Loading and Cleaning (Python)

Loaded dataset using Pandas

Checked data structure using:

.info()

.describe()

Handled missing values in Review Rating column

Renamed columns to snake_case format

Removed redundant columns

Ensured consistency and data quality

2️⃣ Feature Engineering

Created new analytical features:

age_group → Categorized customers into age ranges

purchase_frequency_days → Derived customer purchase behavior metric

These features improved segmentation and analysis.

3️⃣ Database Integration (PostgreSQL)

Connected Python to PostgreSQL database

Loaded cleaned dataset into database

Performed SQL analysis to answer business questions

4️⃣ Business Analysis using SQL

Key business queries performed:

Revenue comparison by gender

Identified high-spending customers using discounts

Top-rated products analysis

Shipping type spending comparison

Subscriber vs non-subscriber revenue comparison

Discount-dependent product analysis

Customer segmentation:

New Customers

Returning Customers

Loyal Customers

Top products per category

Repeat purchase and subscription relationship

Revenue contribution by age group

📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize insights.

Dashboard Features:

Revenue analysis visuals

Customer segmentation charts

Product performance analysis

Subscription impact analysis

Purchase trends visualization

Interactive filters and slicers

This dashboard enables easy and clear business insight exploration.

📈 Key Insights and Results

Key findings from the analysis:

Loyal customers contribute significantly to total revenue

Subscribers show higher spending behavior

Certain products rely heavily on discounts

High-rated products correlate with better sales performance

Specific age groups generate higher revenue

Express shipping users tend to spend more

💡 Business Recommendations

Based on analysis findings:

Promote subscription programs to increase revenue

Implement customer loyalty programs

Optimize discount strategies to protect profit margins

Focus marketing on high-performing products

Target high-value customer segments
