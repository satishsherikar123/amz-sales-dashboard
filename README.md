# amz-sales-dashboard
Amazon Sales Analysis Dashboard (Power BI)

An interactive Power BI dashboard that analyzes ~10K sales orders across product categories, regions, customer segments and years, to show where revenue comes from and where profit is being lost.

Tagline: More Sales. More Smiles.

Dashboard Preview

Objective

Give business users a single view of sales performance so they can:

Track overall health through headline KPIs
Compare category, region and segment performance
Spot growth trends over time
Identify profitable and loss-making sub-categories
Key Metrics (KPIs)
Metric	Value
Total Orders	9,994
Total Sales	2.30M
Total Shipment Cost	87.03K
Total Customers	793
Total Profit	286.40K
Overall Profit Margin	~12.5%
Dashboard Components
Visual	Purpose
KPI cards	Orders, sales, shipment cost, customers, profit at a glance
Sum of Sales by Category (column chart)	Compare Technology, Furniture and Office Supplies
Sum of Sales by Year (line chart)	Yearly sales trend, 2014 to 2017
Category / Segment table	Sales and profit split by Consumer, Corporate and Home Office
Total Sales by Region (pie chart)	Regional contribution: West, East, Central, South
Sum of Profit by Sub-Category (column chart)	Rank sub-categories by profit, including losses
Category slicer	Filter the whole dashboard by category
Key Insights
Sales are growing. Sales dipped slightly from 484K (2014) to 471K (2015), then rose to 609K (2016) and 733K (2017). That is roughly +56% from 2015 to 2017.
Technology leads revenue. Technology (0.84M) is ahead of Furniture (0.74M) and Office Supplies (0.72M), but the three categories are close.
Furniture has very low profitability. It generates ~0.74M in sales but only ~18K in profit (about 2.5% margin), versus roughly 17% for both Technology and Office Supplies.
West is the strongest region with 725K (31.6%) of sales, followed by East (29.6%), Central (21.8%) and South (17.1%). South is the weakest.
Top profit drivers: Copiers (58K), Phones (45K) and Accessories (42K).
Loss-making sub-categories: Tables (-18K), Bookcases (-3K) and Supplies (-1K). Tables are the biggest drain and worth a pricing or discount review.
Consumer is the largest segment in every category, followed by Corporate and Home Office.
Tools and Skills Used
Power BI Desktop for data modeling, DAX measures and visuals
Data cleaning and transformation with Power Query
Visual design: KPI cards, slicers, tables and custom-themed charts
Dataset
Sales order records covering 2014 to 2017 (9,994 orders, 793 customers)
Fields include: Order details, Category, Sub-Category, Segment, Region, Sales, Profit, Shipment Cost
Source: add dataset name / link here
How to Use
Clone or download this repository.
Open the .pbix file in Power BI Desktop.
If prompted, refresh the data or point it to the dataset file.
Use the Category slicer (left panel) to filter all visuals.
Hover over charts for tooltips and exact values.
