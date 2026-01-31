# -Walmart-Sales-Analysis-2010---2012-Power-BI-
This project provides a comprehensive analysis of sales performance across 45 Walmart locations over a 33-month period (February 2010 - October 2012). The goal was to transform raw retail data into strategic insights regarding seasonality and economic impacts.


🌟 Overview
This project provides a comprehensive analysis of sales performance across 45 Walmart locations over a 33-month period (February 2010 - October 2012). The goal was to transform raw retail data into strategic insights regarding seasonality and economic impacts.

🛠️ Tech Stack & Skills
Tool: Power BI Desktop.

Data Engineering: Power Query (ETL) & Data Modeling.

Analytics: Advanced DAX (Data Analysis Expressions).

Architecture: Star Schema Implementation.

🏗️ Data Architecture (The Model)
To ensure high performance and scalability, the project implements a Star Schema:

Fact Table: Sales_Data ($6.74bn in total sales volume).

Dimension Tables: Stores, Calendar (Engineered via DAX), and HolidayTypes.

Relationship: One-to-Many (1:*) with strictly defined filtering directions for interactive cross-filtering.

📈 Key Insights
Operational Stability: 92.5% of the total revenue was generated during Normal Business Weeks, while Holiday periods accounted for 7.5%.

Economic Resilience: Sales remained stable despite regional fluctuations in Unemployment rates and Fuel prices, demonstrating Walmart's strong market position.

AI-Driven Drill-Down: Utilized Decomposition Trees to isolate revenue drivers by Year and Month.

🚀 How to View
Download the .pbix file from the /Dashboard folder.

Open with Power BI Desktop.
