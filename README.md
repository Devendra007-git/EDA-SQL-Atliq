Atliq Hardware Sales Analysis with SQL & Python
Project Overview
This project explores sales data for Atliq Hardware from a MySQL database using SQL queries and Python (Pandas, Matplotlib, Seaborn) to perform EDA and answer key business questions. The goal is to draw business insights from structured data and create visual representations for better decision-making.

🛠️ Tools & Tech Used
SQL (MySQL)

Python (Pandas, NumPy, Matplotlib, Seaborn)

MySQL Workbench / Server

Jupyter Notebook / Google Colab

GitHub

🧠 Business Questions Solved
1️⃣ Total Sold Quantity per Fiscal Year
Queried sales data by fiscal year

Visualized growth trend in bar chart

Insight: Steady growth observed till 2021; slight dip in 2022 due to incomplete data

2️⃣ Which Quarter in 2021 Had Highest Sales?
Used CASE-WHEN to derive quarters from the date

Grouped data by quarter

Insight: Q1 had the highest sales — festive demand and events boost

3️⃣ Top 5 Products per Division in 2021
Used a stored procedure: get_top_n_products_per_division_by_qty_sold(2021, 5)

Exported data to CSV

Insight: Useful for inventory and production planning

4️⃣ Which Channel Drove Highest Gross Sales in 2021?
Used gross_sales and dim_customer to calculate contribution

Visualized using a pie chart

Insight: Retailers brought in 73% of sales — potential for loyalty programs


Added meaningful visualizations for business heads.

Focused on real-world use cases — quarterly trends, channel strategy, and top product identification.

Outcomes
Improved SQL querying skills using GROUP BY, JOIN, CTE, WINDOW FUNCTIONS.

Gained practice writing Python code to clean, analyze, and visualize SQL output.

Created a reusable analysis notebook to support sales and strategy teams.

Acknowledgments
Special thanks to the Codebasics Bootcamp and mentors for this real-world project experience. This is part of my journey towards becoming a proficient Data Analyst.
