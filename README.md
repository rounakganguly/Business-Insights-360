# Atliq Hardware: Business Insights 360 🖥️📊

## Brief One Line Summary
A comprehensive Power BI solution providing 360-degree visibility into Finance, Sales, Marketing, and Supply Chain performance to drive data-driven decision-making.

---

## Overview
This project focuses on building an executive-level analytics platform for Atliq Hardware, a global electronics manufacturer. The solution replaces manual Excel-based tracking with an automated, integrated dashboard system that connects data across multiple departments to provide a "single source of truth."

## Problem Statement
Atliq Hardware faced significant challenges due to:
* **Data Silos:** Information was trapped in disparate Excel files and SQL databases.
* **Lack of Visibility:** No real-time tracking of Net Sales, Gross Margin, or Net Profit across different regions.
* **Inventory Issues:** Inaccurate supply chain forecasting led to frequent "Stock Outs" and "Excess Inventory" costs.
* **Gut-Feeling Decisions:** Strategic moves were made without concrete data support, leading to a loss in market share.

## Dataset
The project utilizes a robust relational database with over **1 million+ records**:
* **Dimension Tables:** `dim_customer` (27 markets), `dim_market`, `dim_product` (75+ products).
* **Fact Tables:** `fact_sales_monthly`, `fact_forecast_monthly`, `fact_actual_estimates`.
* **Global Reach:** Covers data from APAC, EU, NA, and LATAM regions.

## Tools and Technologies
* **Database:** MySQL / SQL Server
* **BI Tool:** Power BI Desktop
* **Data Transformation:** Power Query (M Language)
* **Modeling:** Star Schema Methodology
* **Calculations:** Advanced DAX (Data Analysis Expressions)
* **Presentation:** Power BI Service & Canva (for UI elements)

## Methods
1.  **Data Cleaning (ETL):** Handled currency normalization, created a centralized Date Table, and managed null values in Power Query.
2.  **Data Modeling:** Implemented a **Star Schema** to ensure high performance and scalability.
3.  **Finance Engineering:** Developed a dynamic P&L statement to track performance from Gross Sales to Net Profit.
4.  **Supply Chain Analytics:** Calculated **Forecast Accuracy** and **Net Error** to optimize inventory levels.
5.  **UI/UX Design:** Built an intuitive navigation system with synchronized slicers and bookmarks for a seamless user experience.

## Key Insights
* **Financial Health:** Identified that certain high-revenue markets were underperforming in Net Profit due to aggressive promotional discounts.
* **Customer Loyalty:** Segmented customers into a "Performance Matrix" to identify those with high growth potential.
* **Operational Efficiency:** Discovered that a **5% increase in Forecast Accuracy** could potentially save millions in warehousing and logistics costs.
* **Unit Economics:** Visualized the breakdown of COGS and operational expenses to protect gross margins.

## Dashboard / Model Output
The report consists of 5 specialized views:
1.  **Home Page:** Central hub for navigation.
2.  **Finance View:** Detailed P&L statement with YoY growth metrics.
3.  **Sales View:** Customer performance and unit economics breakdown.
4.  **Marketing View:** Product-level performance and market share analysis.
5.  **Supply Chain View:** Inventory risk assessment and forecast reliability.

## How to Run This Project?
1.  **Prerequisites:** Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2.  **Database Setup:** Import the provided `.sql` dump into your local MySQL/SQL Server instance.
3.  **Clone Repository:** `git clone https://github.com/your-username/atliq-insights-360.git`
4.  **Connect Data:** Open the `.pbix` file, go to **Transform Data > Data Source Settings**, and update the credentials to match your local server.
5.  **Refresh:** Hit the **Refresh** button to populate the visuals with your data.

## Results & Conclusion
The **Business Insights 360** project successfully transitioned Atliq Hardware from reactive to proactive management. By consolidating Finance, Sales, and Supply Chain data, the company can now identify underperforming regions instantly and optimize inventory levels, directly impacting the bottom line and recovering lost market share.

---
*Created by Rounak Ganguly