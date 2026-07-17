# Superstore-sales-Dashboard
This project presents an interactive Sales Analysis Dashboard built in Power BI using the Sample Superstore dataset. The dashboard helps analyze sales performance, profitability, customer behavior, and regional trends through interactive visualizations and KPIs.

Analyze overall sales and profit performance.
Identify top-performing products and customer segments.
Compare sales and profitability across regions and states.
Track monthly sales trends.

--📊 Key DAX Measures
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Orders = DISTINCTCOUNT(Orders[Order ID])

Total Customers = DISTINCTCOUNT(Orders[Customer ID])

Total Quantity = SUM(Orders[Quantity])

Profit Margin =
DIVIDE([Total Profit],[Total Sales])

📚 Skills Demonstrated
Data Cleaning using Power Query
Data Modeling
DAX Calculations
KPI Development
Data Visualization
Dashboard Design
Business Analysis
Interactive Reporting
Data Storytelling
