🛍️ Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover actionable insights into spending patterns, customer segmentation, product preferences, and subscription behavior to guide data-driven business decisions.

📊 Project Overview

Objective: Understand customer shopping patterns to support marketing, pricing, and retention strategies.

Dataset: 3,900 rows × 18 columns

Key Attributes:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Product Category, Amount, Season, Size, Color

Shopping Behavior: Discounts, Promo Codes, Purchase Frequency, Ratings, Shipping Type

🧹 Data Preparation & Cleaning (Python)

Performed using Pandas and NumPy:

Imported dataset and explored basic statistics

Handled missing values in review_rating using median imputation per product category

Standardized column names for consistency

Engineered new features:

age_group (based on age bins)

purchase_frequency_days (derived from purchase history)

Removed redundant columns (e.g., promo_code_used)

Loaded cleaned data into PostgreSQL for advanced analysis

🧮 Data Analysis (PostgreSQL)

Key SQL-based insights:

Revenue by Gender — Compared total spending by male vs female customers

High-Spending Discount Users — Identified discount users who still spent above average

Top 5 Products by Rating — Found products with highest average review ratings

Shipping Type Comparison — Compared average purchase amounts between Standard and Express

Subscribers vs Non-Subscribers — Analyzed revenue and spending by subscription status

Discount-Dependent Products — Identified products most reliant on discounts

Customer Segmentation — Classified customers as New, Returning, or Loyal

Top 3 Products per Category — Listed best-selling products by category

Repeat Buyers & Subscription — Checked if frequent buyers were more likely to subscribe

Revenue by Age Group — Calculated contribution of each age group to total revenue

📈 Dashboard (Power BI)

An interactive Power BI dashboard was built to visualize:

Total and average revenue trends

Customer segmentation

Top products and categories

Discount and subscription patterns

Demographic-based insights

(Add screenshot or link to dashboard here once available)

💡 Business Recommendations

Boost Subscriptions: Offer exclusive perks to encourage sign-ups

Reward Loyalty: Create incentives for returning customers

Optimize Discounts: Review discount policies to maintain profit margins

Highlight Best Sellers: Promote top-rated and best-selling products

Targeted Marketing: Focus campaigns on high-revenue age groups and express-shipping users

🛠️ Tech Stack

Languages: Python (Pandas, NumPy, Matplotlib, Seaborn), SQL

Database: PostgreSQL

Visualization: Power BI

Environment: Jupyter Notebook / VS Code

📁 Project Structure
├── data/
│   ├── customer_shopping_data.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── sql_analysis_queries.sql
├── reports/
│   ├── Customer_Shopping_Behavior_Analysis_Report.pdf
├── dashboard/
│   ├── PowerBI_Dashboard.pbix
├── README.md

🚀 Future Improvements

Implement machine learning for customer churn prediction

Add time-series sales forecasting

Automate report generation and alerts

👨‍💻 Author
Mo Saleem
📧 mosaleem0213@gmail.com
🔗 www.linkedin.com/in/sal013
