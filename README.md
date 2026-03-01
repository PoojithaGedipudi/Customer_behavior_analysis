# Customer_behavior_analysis
Analyzing customer behavior using python, SQL and powerBI to identify trends, segmentation, and insights.

# 📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases. The goal is to understand spending patterns, customer segments, product preferences, and subscription behavior to support better business decisions.

# 📊 Dataset Information

Total Records: 3,900
Total Columns: 18
Includes:
* Customer details (Age, Gender, Location, Subscription Status)
+ Purchase details (Item, Category, Amount, Season, Size, Color)
* Shopping behavior (Discount, Promo Code, Purchase Frequency, Review Rating, Shipping Type)

# 🛠 Tools Used

- Python (Pandas, NumPy)
- MYSQL (SQL Analysis)
- Power BI (Dashboard Visualization)

# 🔎 Analysis Performed

## Data Cleaning (Python)
  - Handled missing values
  - Renamed columns for consistency
  - Created new features like age groups
  - Loaded cleaned data into MYSQL
    
## Business Analysis (SQL)
   - Revenue by gender
   - High-spending discount users
   - Top-rated products
   - Shipping type comparison
   - Subscribers vs non-subscribers
   - Customer segmentation (New, Returning, Loyal)
   - Revenue by age group

## PowerBI Dashboard
  An interactive Power BI dashboard was built to visualize:
   - Total customers
   - Average purchase amount
   - Average review rating
   - Revenue by category
   - Revenue by age group
   - Subscription status
   - Sales by category
   - Sales by age group
   - Shipping Type
   - Gender distribution
   - Shipping Type

## 📈 Key Insights

### Results & Insights

   - Revenue is heavily driven by male customers, who generate nearly twice the total revenue compared to female customers.
   - Although only 27% of customers are subscribed, their spending is comparable to non-subscribers, indicating strong potential to increase revenue through subscription conversion.
   - The customer base shows high loyalty (≈80% Loyal customers), suggesting strong retention but an opportunity to grow new customer acquisition.
   - Express shipping users and high-spending discount customers demonstrate higher transaction values, highlighting opportunities for targeted promotions and premium service offerings.
   - Customer segmentation reveals that converting New customers into Returning and Loyal customers can substantially increase long-term revenue and retention.

# 💡 Business Recommendations

  - Strengthen subscription benefits to increase enrollment.
  - Create loyalty programs to retain repeat buyers.
  - Optimize discount strategy for margin protection.
  - Promote high-rated and best-selling products.
  - Target high-revenue age groups with personalized marketing.

# 🛠️ How to Use This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/PoojithaGedipudi/Customer_behavior_analysis.git
   cd Customer_behavior_analysis
   ```
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **Customer_shopping_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
6. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI

# 📜 License

MIT — feel free to fork, star, and use in your portfolio.
