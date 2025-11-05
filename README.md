🛒 Customer Shopping Behavior Analytics
📄 Overview

This project explores customer shopping patterns for a retail business to uncover insights that drive sales and improve customer retention. It follows the complete data analytics lifecycle, integrating Python, PostgreSQL, and Power BI to clean, analyze, and visualize data efficiently.

📊 Dataset

Dataset Name: customer_shopping_behavior.csv
Description: Contains customer demographic details, purchase frequency, product categories, discounts, and review ratings.
Key Columns:

customer_id, gender, age, item_purchased, category, purchase_amount,

review_rating, discount_applied, frequency_of_purchases, payment_method

🧰 Tools & Technologies

Python (Pandas, NumPy) – Data cleaning, transformation, and feature engineering

PostgreSQL (SQL) – Advanced querying using CTEs and window functions

Power BI – Interactive dashboard for visualization and business insights

Jupyter Notebook – Exploratory data analysis and pipeline execution

GitHub – Version control and project showcase

⚙️ Project Steps
1. Data Understanding & Preparation

Loaded dataset into Python and handled missing values

Standardized column names to snake_case

Engineered new features such as age_group and purchase_frequency_days

2. Data Storage & SQL Analysis

Imported cleaned data into PostgreSQL using SQLAlchemy

Executed analytical SQL queries using CTEs, CASE statements, and window functions to answer business questions like:

Top 3 products by category

Revenue by gender and age group

Customer loyalty segmentation

3. Dashboard & Visualization

Built a Power BI dashboard connected to PostgreSQL

Visualized KPIs including:

Total Revenue

Average Review Rating

Revenue by Category

Sales by Age Group

Discount Rate by Product

📈 Dashboard Preview

Page 1: Customer Overview

Page 2: Product Performance

Page 3: Sales & Loyalty Insights

🚀 Results & Insights

Identified top-performing product categories by revenue and customer rating

Found that loyal customers contribute over 60% of total revenue

Discovered seasonal purchasing trends influencing marketing strategy

Provided actionable recommendations to improve discount targeting
