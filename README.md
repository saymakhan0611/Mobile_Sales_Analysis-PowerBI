# Mobile_Sales_Analysis
This project is an interactive Mobile Sales Analysis Dashboard developed using Microsoft Power BI. The dashboard provides a comprehensive view of mobile sales performance across different cities, mobile models, brands, payment methods, customer ratings, months, and days.
## Dateset Used
-<a href="https://github.com/saymakhan0611/Mobile_Sales_Analysis-/blob/main/Dataset.xlsx">Dataset</a>
## Key KPIs
- Total Sales-Represents the overall sales generated during the selected period.
- Total Quantity-Represents the total number of mobile units sold.
- Total Transactions-Represents the number of sales transactions.
- Average-Average metric displayed on the dashboard for the selected data.
- Dashboard interaction <a href="https://github.com/saymakhan0611/Mobile_Sales_Analysis-/blob/main/Screenshot.png">View Dashboard</a>
## Process Description
1) Data Cleaning & Transformation-The dataset was prepared using Power Query before creating the dashboard.
Typical data preparation activities included:
- Removing duplicate records 
- Handling missing values 
- Correcting data types 
- Standardizing categorical values 
- Formatting date fields 
- Creating calculated columns 
- Creating measures using DAX 
- Preparing data for visualization
2) Power BI / DAX Measures-Some useful measures for this project include:
- Total Sales =SUM(Sales[Total_Sales])
- Total Quantity =SUM(Sales[Quantity])
- Total Transactions =COUNT(Sales[Transaction_ID])
- Average Sales =AVERAGE(Sales[Total_Sales])
3) Visualizations
- KPI Cards
- Map
- Line Chart
- Funnel Chart
- Pie Chart
- Table
- Area/Line Chart
- Bar Chart
- Slicers

## Dashboard
<img width="1416" height="892" alt="Screenshot" src="https://github.com/user-attachments/assets/a27707a5-1a2a-4f72-9db7-357fad47d675" />

## Key Insights 
- Xiaomi is a strong-performing brand-Xiaomi records approximately 13.58M in sales, making it the highest-selling brand among the brands shown.
- Samsung has strong transaction performance-Samsung has 68 transactions, indicating strong customer demand.
- Higher customer ratings dominate-The highest number of customers have given a 5-star rating (128), which indicates strong customer satisfaction.
- Payment methods are diversified-Customers use multiple payment methods, including UPI, cards, and cash. This indicates the importance of supporting multiple payment options.
- Sales vary by day-The daily sales chart shows noticeable variation between days, suggesting that customer purchasing behavior changes throughout the week.
- Sales are geographically distributed-The map shows sales activity across multiple Indian cities, allowing management to identify regions with stronger sales potential.
## Project Conclusion
This project demonstrates how can convert raw sales data into an interactive business intelligence dashboard.
The dashboard enables users to quickly monitor:
Sales,Quantity,Transactions,Customers,Brands,Models,Cities,Payment Methods,Trends
It provides management with a centralized view of sales performance and helps support data-driven business decisions








