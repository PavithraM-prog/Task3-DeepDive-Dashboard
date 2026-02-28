# Task3-DeepDive-Dashboard
Project Overview

This project focuses on performing a deep-dive analysis on the Superstore sales dataset and building an interactive Power BI dashboard to uncover key business insights.

The objective was to identify major revenue drivers, analyze regional and segment performance, and provide actionable business recommendations.

Objective

To analyze regional and customer segment performance using key performance indicators (KPIs) and develop an interactive dashboard that supports data-driven decision-making.

📌 Core KPIs Defined
1.Total Revenue
Formula: SUM(Sales)
Measures overall business performance.
2.Total Orders
Formula: DISTINCTCOUNT(Order ID)
Measures total number of transactions.
3.Average Order Value (AOV)
Formula: Total Revenue / Total Orders
Measures average spending per transaction.
4.Sales per Customer
Formula: Total Revenue / Unique Customers
Measures average revenue generated per customer.
5.Region Contribution %
Formula:
DIVIDE([Total Revenue], CALCULATE([Total Revenue], ALL(Region)))
Measures percentage contribution of each region to total revenue.

Dashboard Components
*KPI Summary Cards (Revenue, Orders, AOV, Sales per Customer)
*Monthly Revenue Trend (Line Chart)
*Sales by Region (Column Chart)
*Sales by Segment (Bar Chart)
*Interactive Slicers (Region, Category, Year)
*Region Contribution Table

Key Insights
*The West region contributes approximately 31% of total revenue, making it the top-performing region.
*The East region follows closely at around 30%, showing revenue concentration in two major regions
*The Consumer segment generates the highest revenue (~$1.15M), accounting for nearly one-third of total sales.
*Revenue demonstrates noticeable seasonal peaks during Q4, indicating strong year-end demand.
*Revenue is not evenly distributed geographically, with South contributing the lowest share.

💡 Business Recommendations
*Strengthen marketing and customer retention strategies in West and East regions to sustain revenue dominance.
*Develop loyalty programs targeting the Consumer segment to increase lifetime value.
*Improve performance in underperforming regions (e.g., South) through targeted promotions.
*Prepare inventory and campaigns ahead of Q4 to maximize seasonal sales opportunities.

Tools & Technologies Used
*Power BI
*DAX (Data Analysis Expressions)
*Data Modeling
*Interactive Dashboard Design

Repository Contents
*Superstore_Task3_Dashboard.pbix
*Deep_Dive_Report.pdf
*Dashboard screenshots
*README documentation

Outcome
This project demonstrates the ability to:
*Define and calculate business KPIs
*Perform segmentation and contribution analysis
*Build interactive dashboards
*Translate data into actionable business insights

















