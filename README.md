# Mobile_Sales_Analysis-
This project is an interactive Motorola Mobile Sales Analysis Dashboard developed using Microsoft Power BI. The dashboard provides a comprehensive view of mobile sales performance across different cities, mobile models, brands, payment methods, customer ratings, months, and days.
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
## Dashboard
<img width="1416" height="892" alt="Screenshot" src="https://github.com/user-attachments/assets/a27707a5-1a2a-4f72-9db7-357fad47d675" />








