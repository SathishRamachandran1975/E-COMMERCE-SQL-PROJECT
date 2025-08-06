# E-COMMERCE-SQL-PROJECT
"E-commerce Sales Performance &amp; Customer Analytics using SQL" is a hands-on project simulating a retail business. It analyzes customer behavior, product sales, 
and revenue trends using SQL. Key techniques include customer segmentation, lifetime value, and RFM analysis to drive strategic insights.

## 📌Project Objective
To perform a comprehensive analysis of an e-commerce business using SQL by exploring sales trends, customer behavior, order history, and product performance. 
The goal is to derive actionable insights to enhance customer engagement, optimize sales strategies, and increase revenue.

## 📋Tasks Performed
- Database Design & Schema Creation
   * Created tables: customers, categories, products, orders, order_items.
- Data Insertion
   * Inserted sample data across all tables to simulate real-world transactions.
- Customer Analytics
   * Analyzed customer lifetime value, frequency, average order value.
- Sales Trend Analysis
   * Month-wise revenue and order volume tracking.
- Customer Segmentation
   * Segmented users into Platinum, Gold, Silver, and Bronze using views.
- RFM Analysis
   * Implemented Recency, Frequency, and Monetary analysis for strategic targeting.
- Views & Reports
   * Used SQL Views for modular and repeatable analytics (segmentation & RFM).

## 📊Key Insights
- High-Spending Customers (Platinum) drive a large portion of revenue.
- Top Categories: Electronics and Clothing were the most sold.
- Repeat Customers showed significantly higher LTV than one-time buyers.
- Seasonal Peaks in revenue observed in Jan, Mar, and Jul.
- Dormant Customers identified through RFM can be reactivated via campaigns.

## 📈Key Performance Indicators (KPIs)

| KPI                              | Description                                      |
|----------------------------------|--------------------------------------------------|
| 🧾 Total Revenue                 | Sum of `total_amount` from completed orders     |
| 🧍 Customer Lifetime Value       | Sum of spend per customer                       |
| 📦 Most Sold Products            | Count of quantities per product                 |
| 📅 Monthly Sales Trends          | Revenue & order count by month                  |
| 💰 Average Order Value (AOV)     | Total Revenue / Total Orders                    |
| 🔁 RFM Scores                    | Recency, Frequency, Monetary Segmentation       |
| 🛍️ Segment Classification        | Bronze to Platinum based on spend               |


## 🗃️SQL File Structure
-<a href="https://github.com/SathishRamachandran1975/E-COMMERCE-SQL-PROJECT/blob/main/E-commerce%20SQL-Project.sql"> SQL FILE</a>
1. Create Database & Tables
2. Insert Sample Data
3. Customer Purchase & LTV Queries
4. Monthly Sales & Product Performance
5. Views:
   - customer_segmentation_view
   - customer_rfm_view
6. Final Result Queries from Views

