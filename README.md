# E-commerce-Sales-Dashboard-Power-BI-
📘 Project Overview

This project presents an interactive Power BI dashboard built using the Madhav E-commerce Sales Dataset.
The dashboard provides a comprehensive analysis of sales, profit, quantity, and payment trends, allowing businesses to monitor performance, identify profitable segments, and make data-driven decisions.

🧾 Data Sources

The analysis is based on two CSV files derived from the Madhav E-commerce Sales Data:

Orders.csv – Contains order-level information including Order ID, Customer Name, Order Date, Ship Date, Sales, Profit, Quantity, and Region.

Details.csv – Contains product and transaction-level details such as Product Category, Sub-Category, Product Name, and Payment Mode.

These datasets were imported and transformed in Power Query Editor to ensure data consistency and proper relationships for accurate reporting.

⚙️ Project Workflow
1. Data Cleaning & Preparation

Imported both datasets (Orders.csv and Details.csv) into Power BI.

Fixed data types, handled null values, standardized category names, and merged tables.

Created a relationship model to link Orders and Details tables using a common key.

2. Data Modeling

Established a Star Schema for optimized data analysis.

Created calculated columns and DAX measures for KPIs like:

Total Sales

Total Profit

Total Quantity

Average Quantity Value (AVQ)

3. Visualization & Dashboard Design

Built an interactive dashboard to visualize key business insights:

Total Amount, Total Profit, Total Quantity, and Average Quantity (AVQ)

Quantity by Category (e.g., Clothing, Electronics, Furniture)

Profit by Month to track monthly sales performance

Category by Payment Mode (COD, UPI, Debit Card, Credit Card, EMI)

Profit by Sub-Category (Printers, Bookcases, Saree, Accessories, Tables)

Added filters and slicers for dynamic, user-driven exploration.

📊 Dashboard Preview


Interactive E-commerce Sales Dashboard built in Power BI using Madhav Sales Data.

💡 Key Insights

Clothing accounts for the highest sales quantity (~62%).

Printers and Bookcases yield the highest profit margins.

Cash on Delivery (COD) remains the most used payment method (~46%).

Sales and profits show strong performance during January–March and September–November.

🧠 Tools & Technologies Used

Power BI Desktop – for data visualization and KPI reporting

Power Query Editor – for data cleaning and transformation

DAX (Data Analysis Expressions) – for advanced measures and calculations

Madhav E-commerce Sales Dataset (Orders.csv, Details.csv) – as the data source

🏁 Outcome

This dashboard provides a comprehensive overview of e-commerce performance, helping business stakeholders:

Monitor sales trends and profit fluctuations

Identify high-performing product categories

Optimize payment channel strategies

Support strategic decision-making through clear, visual insights

📦 E-Commerce-Sales-Dashboard
 ┣ 📜 README.md
 ┣ 📊 E-Commerce-Sales-Dashboard.pbix
 ┣ 📁 Data
 ┃ ┣ 📄 Orders.csv
 ┃ ┗ 📄 Details.csv
 ┗ 📸 Dashboard Power BI.png


🚀 How to Use

Download or clone the repository.

Open the .pbix file in Power BI Desktop.

Load both Orders.csv and Details.csv files from the /Data folder.

Click Refresh to visualize and interact with the dashboard.
