📊 Data Warehouse Analytics using SQL
5
🔍 Project Overview

This project demonstrates end-to-end SQL-based analytical reporting using a data warehouse schema. Fact and dimension tables are used to analyze sales, customers, and products, transforming raw transactional data into meaningful business insights suitable for decision-making and BI reporting.

🏗️ Data Model

gold.fact_sales – Sales transactions

gold.dim_customers – Customer demographics

gold.dim_products – Product and category details

The model follows a star schema, enabling efficient aggregations and analytical queries.

📈 Key Analyses Performed
1️⃣ Trends Over Time Analysis

Yearly and monthly sales trends

Total sales, customers, and quantities over time

📸 Code Snapshot

![Trends Over Time SQL](screenshots/trends_over_time.sql.png)

2️⃣ Cumulative & Moving Average Analysis

Running total of sales

Monthly moving average calculations using window functions

📸 Code Snapshot

![Cumulative Analysis SQL](screenshots/cumulative_analysis.sql.png)

3️⃣ Performance Analysis

Product-wise yearly sales comparison

Comparison against historical averages

Year-over-Year (YoY) growth and decline analysis

📸 Code Snapshot

![Performance Analysis SQL](screenshots/performance_analysis.sql.png)

4️⃣ Part-to-Whole Analysis

Category contribution to overall revenue

Percentage contribution using window functions

📸 Code Snapshot

![Part to Whole Analysis SQL](screenshots/part_to_whole.sql.png)

5️⃣ Data Segmentation

Product segmentation based on cost ranges

Customer segmentation into VIP, Regular, and New based on spending and lifespan

📸 Code Snapshot

![Data Segmentation SQL](screenshots/data_segmentation.sql.png)

👥 Customer Reporting View

A reusable SQL view (gold.report_customers) is created to centralize customer KPIs:

Total orders, sales, quantity, and products

Customer lifespan and recency

Average order value

Average monthly spend

Age and customer segment classification

📸 Code Snapshot

![Customer Report View SQL](screenshots/customer_report_view.sql.png)

🧠 SQL Concepts Used

Common Table Expressions (CTEs)

Window Functions (SUM, AVG, LAG)

CASE statements

Date functions

Aggregations

View creation

🛠️ Tools & Technologies

SQL Server

SQL Server Management Studio (SSMS)

🎯 Outcome

This project showcases strong data warehousing fundamentals, advanced SQL analytics, and the ability to design business-ready reporting logic, making it well-suited for Data Analyst and BI roles.

📌 How to add screenshots (important)

Create a folder named screenshots in your GitHub repo

Take screenshots of your SQL code from SSMS

Name them clearly (example: performance_analysis.sql.png)

Upload them into the screenshots folder

GitHub will automatically render them in this README
