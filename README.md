# Customer_behavior_analysis
Analyzing customer behavior using python, SQL and powerBI to identify trends, segmentation, and insights.
Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective is to uncover insights into:

Customer spending patterns

Product preferences

Discount impact

Subscription behavior

Customer segmentation

The project combines Python (EDA & cleaning), SQL (business analysis), Power BI (dashboarding), and presentation storytelling to deliver end-to-end analytics insights.

Dataset

Rows: 3,900
Columns: 18

Key Features

Customer Information

Customer ID

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount (USD)

Season

Size

Color

Behavioral Data

Discount Applied

Promo Code Used

Previous Purchases

Frequency of Purchases

Review Rating

Shipping Type

Data Quality

37 missing values in review_rating

Standardized column names to snake_case

Removed redundant column (promo_code_used)

Tools Used

Python (Pandas, NumPy, Matplotlib/Seaborn) – Data cleaning & EDA

MYSQL – Business query analysis

Power BI – Interactive dashboard

PowerPoint / Gamma – Presentation storytelling

Steps Performed
1️⃣ Data Cleaning & EDA (Python)

Loaded dataset using pandas

Performed structural checks using:

df.info()

df.describe()

Handled missing values (median imputation by category for review ratings)

Renamed columns to snake_case

Feature Engineering:

Created age_group

Created purchase_frequency_days

Removed redundant columns

Exported cleaned dataset to PostgreSQL

2️⃣ SQL Business Analysis

Key analytical queries:

Revenue by gender

High-spending discount users

Top 5 products by rating

Shipping type comparison

Subscribers vs non-subscribers analysis

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Repeat buyers vs subscriptions

Revenue by age group

Dashboard

An interactive Power BI dashboard was built to visualize:

Total customers

Average purchase amount

Average review rating

Revenue by category

Revenue by age group

Subscription distribution

Sales by category

Sales by age group

The dashboard enables filtering by:

Gender

Category

Shipping Type

Subscription Status

Results & Insights

Male customers generated higher total revenue than female customers.

Loyal customers form the majority of the customer base.

Express shipping users show slightly higher average spending.

Some products are highly discount-driven (e.g., hats, sneakers).

Subscription does not significantly increase average spend but increases customer retention.

Young adults contribute the highest revenue among age groups.

Business Recommendations

Strengthen subscription benefits to increase enrollment.

Create loyalty programs to retain repeat buyers.

Optimize discount strategy for margin protection.

Promote high-rated and best-selling products.

Target high-revenue age groups with personalized marketing.

How to Run the Project
1. Clone Repository
git clone <repository-url>
cd customer-shopping-analysis
2. Install Dependencies
pip install -r requirements.txt
3. Run Python Script
python data_cleaning_analysis.py

This will:

Clean the dataset

Generate EDA outputs

Load cleaned data into PostgreSQL

4. Run SQL Queries

Execute the SQL scripts inside:

/sql_queries/

Using:

MySQL

SQL Server (if applicable)

5. Open Power BI Dashboard

Open:

Customer_Behavior_Dashboard.pbix

Refresh data if required.

Project Structure
customer-shopping-analysis/
│
├── data/
│   └── raw_dataset.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── scripts/
│   └── data_cleaning_analysis.py
│
├── sql_queries/
│   └── business_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
└── README.md
Why This Project Matters

This project demonstrates:

End-to-end analytics workflow

Data cleaning & feature engineering

SQL-based business problem solving

Dashboard storytelling

Actionable business recommendations

It reflects real-world data analyst responsibilities from raw data to executive insights.
