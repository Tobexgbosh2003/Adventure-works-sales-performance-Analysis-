🚴‍♂️ Adventure Works Sales Performance Dashboard
📊 Project Overview

As a Business Intelligence Analyst, I developed an interactive Power BI dashboard for a hypothetical global cycling equipment company, Adventure Works. The goal was to support data-driven decision-making by analyzing key performance indicators such as revenue, profit, return rates, product performance, regional trends, and customer behavior.

🎯 Objective

The objective of this project was to:

Track and visualize business performance metrics (Revenue, Profit, Returns).

Identify top-performing products, regions, and customers.

Detect potential improvement areas through data insights.

Provide actionable recommendations to boost business growth.

⚙️ Approach & Tools

🧹 Data Preparation:

Performed automated ETL processes using Power Query.

Applied transformations, merges, and pivot/unpivot operations.

🧱 Data Modeling

The project follows a Star Schema design to optimize performance and ensure efficient data relationships for analysis.

🧩 Model Overview

The model consists of Fact and Dimension tables connected through one-to-many relationships.

Fact Tables:

Sales Data: Contains transactional sales details (CustomerKey, OrderDate, ProductKey, TerritoryKey).

Returns Data: Tracks returned products with quantity and return dates.

Dimension Tables:

Customer Lookup – Customer details and demographic attributes.

Product Lookup – Product information with keys linked to subcategories and categories.

Product Subcategory Lookup – Groups products into meaningful subcategories.

Product Category Lookup – Groups subcategories under major product categories.

Territory Lookup – Geographic sales regions and markets.

Calendar Lookup – Date table supporting time intelligence calculations.

🧮 Additional Tables:

Measure Table: Contains DAX measures for KPIs and calculations.

Metric Selection Tables: Allow for dynamic metric switching (e.g., Customer Metric Selection, Product Metric Selection).

Price Adjustment (%): Stores price adjustment percentages used for scenario analysis.

⚙️ Approach & Tools

🧹 Data Preparation:

Performed automated ETL processes using Power Query.

Applied transformations, merges, and pivot/unpivot operations.

🗂️ Data Modeling:

Built a relational star schema connecting all fact and dimension tables.

Defined one-to-many relationships and established referential integrity.

Ensured proper filter direction and relationship cardinality for accurate DAX calculations.

🧠 DAX Development:

Authored advanced DAX measures and time intelligence calculations using functions like CALCULATE, FILTER, DATESYTD, and SUMX.

Created dynamic KPIs for revenue, profit, and return rates.

📊 Data Visualization & Reporting:

Designed an interactive Power BI dashboard featuring:

Custom visuals and KPIs.

Drill-through pages, bookmarks, and dynamic slicers.

Role-based access control for secure data exploration.

🔍 Key Insights

📈 Revenue Growth: Revenue increased steadily over the past two years, showing a 3.31% month-over-month growth.

🌎 Regional Performance: The United States recorded the highest number of orders (8,700).

💎 Top-Value Customer: Mr. Maurice Shan generated the highest revenue at $12.4K.

🏆 Best-Selling Product: The Water Bottle – 30 Oz achieved the highest order volume (3,983 units).

⚠️ Highest Return Rate Product: The Road-650 Red 52 had a return rate of 11.76%, indicating potential quality or expectation issues.

💡 Recommendations

Expand Market Reach: Increase promotional efforts in international regions to boost sales.

Reduce Returns: Investigate product quality or expectation gaps for high-return items such as “Road-650 Red 52”.

Retain High-Value Customers: Launch loyalty programs or personalized discounts for top customers.

📈 Key Metrics Tracked

Total Revenue

Profit Margin

Return Rate

Regional Sales Performance

Product Category Sales

Customer Value Segmentation

🏁 Conclusion

This dashboard empowers decision-makers at Adventure Works with actionable insights into sales performance, product profitability, and customer behavior, enabling better strategic and operational decisions.

📧 Contact

Author: Bamgbose Okikiola (Tobex Gbosh)
📩 Email: [gboshtobex@gmail.com
]
🔗 LinkedIn: [Bamgbose Tobiloba]






