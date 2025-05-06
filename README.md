# E-commerce-Sales-Profit-Analysis-Dashboard-Using-Power-BI

🧩 Overview:
Designed and developed a comprehensive Power BI dashboard to analyze and monitor key performance indicators (KPIs) for a fictional e-commerce platform. The dashboard provides detailed insights into sales, profitability, customer behavior, product categories, and geographical performance.

🔨 Tools & Technologies:
Power BI Desktop – Data modeling, DAX, visual design

Microsoft Excel – Initial data preprocessing

Power Query – Data transformation and cleanup

DAX (Data Analysis Expressions) – Custom calculations and KPIs

📂 Project Data:
Base file: Orders.csv

Enriched into: Enriched_Ecommerce_Orders.xlsx

Records: ~200+ orders across various states, cities, and customers

Fields added:

Category & Sub-Category

Quantity Sold

Amount

Profit

Payment Mode

Quarter (derived from Order Date)

🔍 Key Features & Work Done:
🧹 Data Preprocessing:
Cleaned raw CSV data and handled missing fields using Power Query.

Enriched dataset with synthetic but realistic values for business context.

Derived new fields such as:

Quarter from Order Date

Profit as a % of sales

Average Order Value

📐 Data Modeling & DAX Measures:
Created custom DAX measures for:

Total Sales = SUM(Orders[Amount])

Total Profit = SUM(Orders[Profit])

Total Quantity Sold = SUM(Orders[Quantity Sold])

Average Order Value = [Total Sales] / DISTINCTCOUNT(Orders[Order ID])

Also created derived columns like:

Month = FORMAT(Order Date, "MMM")

📈 Interactive Visuals Built:
KPI Cards for total sales, profit, quantity sold, and AOV.

Slicer for Quarter to allow time-based filtering.

Donut Charts for:

Quantity by Product Category

Sales by Payment Mode

Bar Charts for:

Sales by State (Horizontal)

Profit by Month (Vertical)

Profit by Sub-category (Horizontal)

Stacked Column Chart for Customer-wise sales distribution.

🎨 Design & UX:
Applied a soft blue background and custom color palette for brand consistency.

Used a grid layout for optimal readability.

Enabled drill-down for multi-level analysis (e.g., Category → Sub-category).

Added slicers for Quarter and Date Range (10 March to 10 June 2025) to make the report time-dynamic.

🎯 Business Insights Provided:
Identified top-performing states and cities in terms of revenue.

Analyzed which categories and sub-categories drive most profit.

Measured customer-level contribution to overall sales.

Compared payment modes used by customers.

Visualized performance trends over quarters and months.

📁 Outcome:
Delivered a fully interactive dashboard ready for stakeholder presentation.

Optimized for decision-making related to marketing, logistics, and sales strategy.

Demonstrated ability to use Power BI for professional-grade business analytics.
