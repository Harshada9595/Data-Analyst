# Monthly Sales Performance Report — Excel Project

An interactive Excel sales analysis project that analyzes monthly revenue, product-category performance, and regional sales using PivotTables, PivotCharts, KPIs, and slicers.

This project demonstrates data cleaning, exploratory analysis, dashboard design, and technical documentation using Microsoft Excel.

---

## 📌 Business Problem

A retail business needs to understand:

- How revenue changes month by month
- Which product categories generate the highest revenue
- Which regions perform best
- Where sales are strong or weak
- How managers can filter results by year, region, and product category

The goal is to convert raw sales transactions into a clear, interactive report for business decision-making.

---

## 📊 Dataset

- **Source:** Kaggle retail sales dataset  
- **File:** `data/sales_data.csv`  
- **Data type:** Transaction-level sales data  
- **Key columns:**
  - Order ID
  - Order Date
  - Region
  - Category
  - Sub-Category
  - Sales
  - Profit
  - Quantity

> Note: `Sales` is treated as revenue in this project.

---

## 🛠️ Tools Used

- Microsoft Excel
- Excel Tables
- Data cleaning
- PivotTables
- PivotCharts
- Slicers
- KPI cards
- Conditional formatting
- PDF reporting

---

## 🧹 Data Cleaning Steps

The raw dataset was cleaned before analysis:

- Removed duplicate records
- Checked and removed blank or incomplete rows
- Corrected date formatting
- Standardized region, category, and sub-category names
- Verified numeric values in Sales, Profit, and Quantity
- Converted the dataset into an Excel Table named `SalesData`
- Created a separate `Raw_Data` sheet to preserve the original file

---

## 📈 Analysis Performed

### 1. Monthly Revenue Analysis
Created a PivotTable using:

- **Rows:** Order Date grouped by Month and Year  
- **Values:** Sum of Sales  

This shows revenue trends across months.

### 2. Revenue by Product Category
Created a PivotTable using:

- **Rows:** Category  
- **Values:** Sum of Sales  

This identifies the highest- and lowest-revenue product categories.

### 3. Revenue by Region
Created a PivotTable using:

- **Rows:** Region  
- **Values:** Sum of Sales  

This compares performance across regions.

### 4. Interactive Dashboard
Created a dashboard with:

- Total Revenue
- Total Orders
- Total Units Sold
- Total Profit
- Monthly revenue trend chart
- Revenue by category chart
- Revenue by region chart
- Slicers for Year, Region, and Product Category

---

## 📸 Dashboard Preview

![Excel Sales Dashboard](images/01_dashboard.png)

### Monthly Revenue Trend

![Monthly Revenue Trend](images/02_monthly_revenue_chart.png)

### Revenue by Product Category

![Revenue by Category](images/03_revenue_by_category.png)

### Revenue by Region

![Revenue by Region](images/04_revenue_by_region.png)

---

## 🔍 Key Insights

Replace these with your actual results:

- Total revenue for the reporting period was **[₹/$ value]**.
- **[Category Name]** generated the highest revenue, contributing **[percentage]%** of total sales.
- **[Region Name]** was the strongest-performing region.
- Sales peaked in **[Month, Year]**.
- **[Category or Region]** underperformed and may require further investigation.

---

## ✅ Recommendations

- Increase inventory or marketing focus for the top-performing product category.
- Investigate the reasons behind low performance in the weakest region.
- Repeat successful campaigns from the highest-revenue month.
- Monitor monthly revenue, profit, and average order value regularly.
- Use slicers to review performance by region, category, and year.

---

## 📂 How to Use This Report

1. Download or clone this repository.
2. Open `Monthly_Sales_Report.xlsx` in Microsoft Excel.
3. Go to the **Dashboard** sheet.
4. Use the slicers to filter by:
   - Year
   - Region
   - Product Category
5. Review the charts and KPI cards.
6. Open the **Summary** sheet for key findings and recommendations.
7. Open the **How_To_Use** sheet for instructions on updating the report.

---

## 🔄 How to Update With New Data

1. Open the `Clean_Data` sheet.
2. Add new sales records at the bottom of the Excel Table.
3. Go to **Data → Refresh All**.
4. All PivotTables, charts, and KPIs will update automatically.
5. Review the Summary sheet and update key insights if required.

---

## 📄 Project Files

| File | Description |
|---|---|
| `Monthly_Sales_Report.xlsx` | Complete Excel workbook with cleaned data, PivotTables, dashboard, and documentation |
| `Monthly_Sales_Report_Summary.pdf` | One-page executive summary and dashboard export |
| `data/sales_data.csv` | Source dataset used for analysis |
| `images/` | Dashboard and chart screenshots |

---

## 🎯 Skills Demonstrated

- Data cleaning and validation
- Excel Tables
- PivotTables and PivotCharts
- KPI reporting
- Dashboard design
- Slicer-based interactivity
- Data storytelling
- Technical documentation

---

## 👤 Author

👩🏻‍🎓 Harshada Tapase 
Aspiring Junior Data Analyst | Excel • SQL • Power BI | Technical Documentation  

- LinkedIn: [https://www.linkedin.com/in/harshada-tapase-124982267/] 
- GitHub: [https://github.com/Harshada9595]  
- Email: [harshadatapase2018@gmail.com]
