# Stamp and Flen Coffee Shop Sales Analysis (2019–2022)
## Transforming Coffee Shop Transaction Data into Actionable Business Intelligence

This repository presents a comprehensive sales performance analysis of Stamp and Flen Coffee Shop using historical transaction data spanning 2019–2022. Built entirely in Microsoft Excel with Power Query, the project follows an end-to-end business intelligence workflow, from data preparation and modeling to interactive dashboard development and strategic business recommendations.

The analysis integrates 1,000 customer transactions, 48 unique products, and 1,000 customer profiles to evaluate sales performance, profitability, customer loyalty, product mix, and regional revenue trends. The findings provide actionable recommendations to improve profitability, strengthen customer retention, and support sustainable business growth.

##Key Insights
- Generated $45,134.26 in total sales revenue and $4,520.18 in profit across 3,551 products sold to 913 unique customers.
- Liberica generated the highest gross profit margin (13%), while Robusta recorded the weakest profitability (6%), highlighting opportunities for product portfolio optimization.
- 2.5 kg coffee bags contributed over half of total revenue, making large-package sales the primary revenue driver.
- The United States consistently generated the highest sales throughout the analysis period, while Ireland demonstrated steady growth and the United Kingdom maintained stable demand.
- Sales performance remained relatively consistent between 2019 and 2021, before declining in 2022 due to incomplete Year-to-Date (Q1–Q3) transaction data.
- Customer loyalty analysis identified opportunities to strengthen retention strategies and increase repeat purchases among high-value customer segments.

##Tools Used
- Microsoft Excel – Data analysis, Pivot Tables, Pivot Charts, KPI reporting, dashboard development, and business reporting.
- Power Query – Data cleaning, transformation, merging tables, calculated columns, and ETL processes.

##Methodology
###Data Preparation
- Preserved the original dataset by working from a duplicate workbook.
- Imported all datasets into Power Query for transformation.
- Cleaned and standardized data types across all tables.
- Removed duplicate transaction records.
- Replaced missing values in non-critical fields such as Email and Phone Number with standardized placeholders.
- Created calculated columns for Total Sales and Total Profit at the transaction level.
###Data Modeling
- Designed a Star Schema by connecting the Orders fact table with the Customers, Products, and Calendar dimension tables.
- Built a dedicated Calendar Table to support year, quarter, and monthly time-intelligence analysis.
- Established relationships between fact and dimension tables to improve analytical consistency and reporting accuracy.
- Defined and validated key performance indicators (KPIs) used throughout the dashboard.
###Reporting and Visualization
- Developed Pivot Tables to summarize sales, profitability, customer activity, product performance, and regional trends.
- Built an interactive Excel dashboard featuring KPI cards, line charts, bar charts, and donut charts.
- Connected slicers for Year, Coffee Type, and Roast Type to enable dynamic filtering across all visualizations.
- Presented findings through business-focused insights and actionable strategic recommendations.

##Repository Structure
- Project Management: Project brief outlining the business problem, objectives, and key business questions.
- Data and Analysis (Excel Workbook):
-- Dataset
-- Methodology
-- Pivot Tables and KPI Analysis
-- Interactive Excel Dashboard
-- Business Insights and Strategic Recommendations
- Visualization: Interactive Excel Dashboard
Business Reporting
Strategic Decision Support
