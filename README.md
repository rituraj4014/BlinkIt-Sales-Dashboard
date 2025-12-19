# BlinkIt-Sales-Dashboard
Blinkit Sales Analysis Dashboard built in Power BI to track total sales, item performance, outlet size and location insights using cleaned data, DAX measures, and interactive visualizations for business decisions.
🛒 Blinkit Sales Analysis Dashboard (Power BI)
📌 Project Overview

This project is an end-to-end Sales Analysis Dashboard built using Microsoft Power BI, based on Blinkit (India’s Last Minute App) data.
The dashboard provides actionable business insights related to sales performance, outlet distribution, product categories, customer ratings, and inventory metrics.

It helps stakeholders:

Track total and average sales

Analyze item-level performance

Compare outlet sizes, locations, and tiers

Identify high-performing product categories

Monitor customer ratings and visibility

🎯 Objectives

Build an interactive business intelligence dashboard

Perform data cleaning & transformation

Apply DAX calculations

Visualize KPIs for decision-making

Follow real-world retail analytics use cases

🧰 Tools & Technologies Used

Microsoft Power BI

Power Query

DAX (Data Analysis Expressions)

Excel / CSV Dataset

Data Modeling

📊 Key KPIs Displayed
Metric	Description
💰 Total Sales	$1.2M
📦 Number of Items	8,523
📈 Average Sales	$141
⭐ Average Rating	3.9
📈 Dashboard Features
🔹 Filters Panel

Outlet Location Type

Outlet Size

Item Type

🔹 Visualizations

Sales Trend (Outlet Establishment)

Sales by Fat Content

Sales by Item Type

Sales by Outlet Size

Sales by Outlet Location (Tier 1, 2, 3)

Outlet Type Performance Table

🖼 Dashboard Preview

(Replace dashboard.png with your uploaded image name in GitHub)

📂 Project Structure
Blinkit-Sales-Analysis/
│
├── Blinkit_Dashboard.pbix
├── Dataset/
│   └── blinkit_sales_data.csv
├── Images/
│   └── dashboard.png
├── README.md

🔗 How to Open & Connect the Project
✅ Prerequisites

Install Microsoft Power BI Desktop
👉 https://powerbi.microsoft.com/desktop/

🟢 Step 1: Clone the Repository
git clone https://github.com/your-username/Blinkit-Sales-Analysis.git

🟢 Step 2: Open Power BI File

Open Power BI Desktop

Click File → Open

Select Blinkit_Dashboard.pbix

🟢 Step 3: Connect Dataset (If Required)

If data source is broken:

Go to Transform Data → Data Source Settings

Click Change Source

Select dataset file from:

Dataset/blinkit_sales_data.csv


Click Close & Apply

🔄 Data Cleaning & Transformation

Performed using Power Query:

Removed null values

Corrected data types

Standardized category names

Created calculated columns

Renamed fields for clarity

🧠 DAX Measures Used
Total Sales = SUM(Sales[Sales Amount])

Average Sales = AVERAGE(Sales[Sales Amount])

No of Items = COUNT(Sales[Item Identifier])

Average Rating = AVERAGE(Sales[Rating])

📌 Business Insights

Tier 3 outlets generate highest sales

Medium-sized outlets outperform others

Low Fat items contribute significant revenue

Fruits & Snacks are top-selling categories

Supermarket Type 1 dominates overall sales

🚀 Future Enhancements

Add time intelligence (YoY / MoM growth)

Integrate SQL database

Add forecasting using Power BI AI

Create mobile-optimized dashboard

Publish to Power BI Service

👤 Author

Ritu Raj
📊 Aspiring Data Analyst
💡 Skills: Power BI | SQL | Excel | Python

📧 Email:-rituraj4014@gmail.com
