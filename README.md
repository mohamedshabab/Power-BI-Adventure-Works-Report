# 📊 AdventureWorks Sales Report (Power-BI)

This project presents an interactive multi-page Power BI dashboard built using the **AdventureWorks Sales Analysis** dataset.  
The report provides insights into monthly sales performance, profit margin trends, regional breakdowns, and product category quantities.  

Designed for fast, executive-level decision-making, the dashboard combines line charts, bar charts, and slicers to clearly visualize business performance across regions and product categories.

---

## 📁 Dataset Overview

This project uses multiple CSV files from the AdventureWorks Sales dataset, including:

- **Sales** — transactions with dates, quantities, product, reseller, and salesperson keys  
- **Product** — product names, categories, and pricing  
- **Reseller** — reseller locations and business types  
- **Region** — country and regional group mapping  
- **Salesperson / SalespersonRegion** — salesperson assignments  
- **Targets** — monthly sales targets

These tables form a star-schema model used in the Power BI report.

---

## 🎯 Project Objectives

The goal of this project is to analyze AdventureWorks sales performance using an interactive Power BI dashboard.  
The report focuses on identifying trends in sales, product demand, regional performance, and salesperson contribution.

### **Key Objectives**
- Provide a clear overview of **monthly sales performance**
- Compare **sales amount vs. target achievements**
- Analyze **sales by product category and subcategory**
- Evaluate **regional performance** across countries and groups
- Identify **top-performing resellers and salespeople**
- Highlight sales **quantity trends** over time
- Build a clean, multi-page Power BI report for decision-makers

---

## 🛠️ Technical Skills Used

### 📌 Data Preparation & Modeling
- Imported multiple CSVs and built a clean star-schema model  
- Created relationships using product, reseller, salesperson, and region keys  

### 📌 DAX Measures
- Built measures for total sales, profit, margin, quantity, and target comparison  

### 📌 Visualizations
- Line charts, bar charts, KPIs, maps, and matrix tables  
- Added slicers for region, year, category, and salesperson  

### 📌 Dashboard Design
- Designed a consistent 3-page Power BI report for executive insights  

---

## 🔍 Analysis Highlights

The Power BI AdventureWorks Sales Report includes several key visuals that summarize performance across products, regions, months, and sales targets.  
Below are the recommended screenshots to include in your README, each corresponding to a specific page or visual in your report.
---

### 📈 1. Sales and Profit Margin by Month  
A combined bar + line chart showing **monthly sales** and **profit margin** across FY2019–FY2020.

<img width="1332" height="554" alt="Screenshot 2025-11-23 at 15 14 20" src="https://github.com/user-attachments/assets/bcdd12f0-d5c8-46ff-85a4-e9569a831436" />


### 🌍 2. Sales by Country and Category  
A stacked bar chart displaying **sales across countries** (US, Canada, France, Germany, etc.) and product categories.

<img width="604" height="387" alt="Screenshot 2025-11-23 at 15 14 51" src="https://github.com/user-attachments/assets/686d658e-6aa8-43cd-bd14-adf30fc6fbb0" />


### 🛒 3. Quantity by Category  
A horizontal bar chart ranking categories such as **Clothing**, **Bikes**, **Components**, and **Accessories** by quantity sold.

<img width="742" height="387" alt="Screenshot 2025-11-23 at 15 14 42" src="https://github.com/user-attachments/assets/262cdf24-2824-4ff8-b5d2-25fd914a7fec" />


### 💼 4. Profit Summary Table  
A table showing **Orders, Sales, Cost, Profit, and Profit Margin** broken down by year.

<img width="1119" height="573" alt="Screenshot 2025-11-23 at 17 34 41" src="https://github.com/user-attachments/assets/4aec483a-e0ee-4009-b450-4a6646341b2a" />


### 🎯 5. Sales vs Target Performance  
A comparison showing **Actual Sales vs Target**, plus KPIs for Sales, Target, Variance, and Variance Margin.

<img width="1650" height="929" alt="Screenshot 2025-11-23 at 17 35 43" src="https://github.com/user-attachments/assets/602af89e-f056-42a1-96db-194d3deb0c62" />


### 🖥️ Full Dashboard Overview  
A complete screenshot of the **AdventureWorks Sales Analysis Dashboard** (Overview Page).

<img width="1667" height="928" alt="Screenshot 2025-11-23 at 15 14 04" src="https://github.com/user-attachments/assets/587376f6-6a44-47b7-99e9-07741ccfe679" />


📌 *To capture each screenshot in Power BI:*  
**File → Export → Export to Image (.png)**  

---

## 🎓 Learning Outcomes

- Built a complete Power BI star-schema model from multiple CSV files  
- Created DAX measures for sales, profit, targets, and variance  
- Designed a clear 3-page executive dashboard  
- Analyzed trends across categories, regions, and time  
- Improved skills in DAX, modeling, and data storytelling  

----

## 📌 Conclusion

The AdventureWorks Sales Analysis Report provides a clear, structured, and interactive view of company performance across products, regions, salespeople, and time periods.  
By combining three focused report pages—**Overview**, **Profit**, and **My Performance**—the dashboard delivers insights that support strategic decision-making at both executive and operational levels.

- The **Overview page** highlights trends in sales, profit margin, country-level performance, and product category demand.  
- The **Profit page** provides a financial breakdown that helps assess profitability, cost behavior, and yearly performance.  
- The **My Performance page** compares actual sales to targets, offering a direct view of progress, gaps, and achievements.

Together, these visuals offer a comprehensive understanding of the business, from high-level KPIs down to product-level and region-level detail.

This project demonstrates strong skills in Power BI dashboard creation, data modeling, DAX calculations, and business data analysis—all applied to a real-world sales dataset.

---

## 🖥️ How to Use This Project

This repository includes:

- **AdventureWorks Sales Report (.pbix)**
- **CSV files:** Sales, Product, Region, Reseller, Salesperson, SalespersonRegion, Targets

To explore the report:

1. Open **Power BI Desktop**
2. Load the file: **08-Solution-Sales Analysis.pbix**
3. Use slicers (Year, Region, Category) to interact with the dashboard

You can also publish the PBIX file to Power BI Service to view it online.
