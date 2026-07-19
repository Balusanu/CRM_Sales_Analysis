# 📊 CRM Sales Opportunities Analysis | Power BI Dashboard

An end-to-end **Power BI Sales Analytics Dashboard** that transforms raw CRM sales data into actionable business insights through data modeling, advanced DAX calculations, and interactive visualizations.

---

## 📌 Project Overview

The objective of this project is to analyze CRM sales opportunities, monitor sales performance, evaluate the effectiveness of sales teams, and identify key revenue drivers using Power BI.

The dashboard enables stakeholders to track KPIs, compare sales performance across regions and products, and drill down into detailed sales metrics for informed decision-making.

---

## 🎯 Project Objectives

- Analyze the overall sales pipeline performance.
- Track revenue and sales opportunity trends.
- Measure sales team performance.
- Identify top-performing products and customer segments.
- Analyze deal conversion rates and sales cycle efficiency.
- Enable interactive business reporting through dynamic dashboards.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling (Star Schema)

---

## 📂 Dataset

The dataset consists of CRM sales data containing information about:

- Sales Opportunities
- Accounts
- Products
- Sales Team
- Regional Offices
- Opportunity Status
- Revenue
- Dates

---

# 🔄 Data Preparation (Power Query)

The following ETL steps were performed:

- Imported multiple data files directly from a folder.
- Disabled loading for the Data Dictionary table.
- Verified and corrected data types.
- Renamed columns for consistency.
- Created **Account Type** based on company revenue.
- Cleaned and transformed the data before loading into Power BI.

---

# 🏗️ Data Modeling

A **Star Schema** was implemented to improve model performance and simplify analysis.

### Fact Table

- Sales_Facts

### Dimension Tables

- Date_Table
- Products_Dim
- Accounts_Dim
- Sales_Team_Dim

### Date Table

A custom Date table was created containing:

- Date
- Day
- Month
- Quarter
- Year

The Date table was connected to the **Close Date** in the Sales Fact table.

---

# 📈 DAX Analysis

### Company Analysis

- Company Age
- Company Age Groups
  - Startup
  - Growing
  - Established
  - Legacy

### Discount Analysis

Calculated:

- Average Discount
- Maximum Discount
- Minimum Discount

using **Sales Price** and **Deal Revenue**.

### Deal Performance

Calculated:

- Average Deal Time
- Fastest Deal
- Slowest Deal

using **Engage Date** and **Close Date**.

### Revenue KPIs

- Total Revenue
- Average Deal Value
- Median Deal Value
- Highest Deal Value
- Lowest Deal Value

### Sales Pipeline KPIs

- Won Deals
- Lost Deals
- Open Deals
- Win Rate
- Loss Rate
- Open Deal %

### Time Intelligence

- MTD
- QTD
- YTD
- Month-over-Month Growth
- Year-over-Year Growth

---

# 📊 Dashboard Pages

The report consists of **three interactive dashboard pages**.

---

## 🏠 1. Overview Dashboard

### KPI Cards

- Total Revenue
- Total Opportunities
- Win Rate
- Average Deal Value
- Median Deal Value
- Average Deal Time

### Visualizations

- Dynamic Pie Chart using **Field Parameters**
- Revenue by Regional Office
- Opportunities by Regional Office
- Revenue by Product Series
- Opportunities by Product Series

---

## 🏢 2. Account-wise Analysis

### Field Parameters

Dynamic KPI switching for:

- Revenue
- Opportunities
- Win Rate
- Average Deal Value
- Median Deal Value
- Average Deal Time

Additional dimensions:

- Account Sector
- Company Age Group
- Revenue Group

### Visualizations

- Dynamic Bar Chart
- Map Visualization displaying KPIs across company headquarters

---

## 👥 3. Sales Team Performance

### Decomposition Tree

Analyze KPIs through the hierarchy:

Regional Office → Sales Manager → Sales Agent

Supported KPIs:

- Revenue
- Opportunities
- Win Rate
- Average Deal Value
- Median Deal Value
- Average Deal Time

### Line Chart

Track KPI trends over time.

---

# 🚀 Advanced Power BI Features

- ⭐ Star Schema Data Model
- ⭐ Field Parameters
- ⭐ Page Navigation
- ⭐ Drill-through Analysis
- ⭐ Custom Tooltips
- ⭐ Decomposition Tree
- ⭐ Time Intelligence
- ⭐ Interactive Maps
- ⭐ Dynamic KPI Switching

---

# 🔍 Drill-through Analysis

A dedicated drill-through page was created for **Product Series** analysis.

It displays:

- Product-wise KPIs
- Manager-wise KPIs
- Won Deals
- Lost Deals
- Open Deals
- Fastest Deal
- Slowest Deal
- Highest Deal Value

---

# 💬 Custom Tooltip

A customized tooltip was created for the Decomposition Tree to display:

- Won Deals
- Lost Deals
- Open Deals

using an interactive Pie Chart.

---

# 📌 Key Business Insights

- 📈 Generated **9K sales opportunities** resulting in **$10M** in total revenue.
- 🎯 Achieved an overall **69% Win Rate**.
- 💰 Average Deal Value: **$2.36K**
- 💵 Median Deal Value: **$1.12K**
- ⏳ Average Deal Closure Time: **52 Days**
- 🚀 The **GTX Series** contributes **73% of total revenue** and **65% of all opportunities**.
- 🌍 The **Central Regional Office** leads in both revenue and opportunity count.
- 🏢 **Retail, Technology, and Medical** sectors generate the highest revenue.
- 🏆 **Melvin Marxen** is the top-performing Sales Manager.
- ⭐ **Darcel Schlecht** is the highest-performing Sales Agent.
- 📅 The highest daily revenue (**$82.28K**) was recorded on **29 June 2017**.
- 📦 **GTX Basic** recorded the highest sales volume.
- 💎 **GTX Pro** generated the highest revenue.

---

# 📷 Dashboard Preview

### Overview Dashboard

![Overview Dashboard](images/overview.png)

### Account-wise Analysis

![Account Analysis](images/account_analysis.png)

### Sales Team Performance

![Sales Team Dashboard](images/sales_team.png)

---

# 📁 Repository Structure

```
CRM-Sales-Analysis/
│
├── Dataset/
├── Power BI Dashboard.pbix
├── Images/
├── README.md
└── LICENSE
```

---

# 🎯 Business Value

This dashboard helps business leaders:

- Monitor sales pipeline performance.
- Improve sales conversion rates.
- Evaluate regional and sales team performance.
- Identify high-value customers.
- Optimize product strategies.
- Make data-driven business decisions.

---

# 👨‍💻 Author

**Balasubramanya C K**

**Connect with me**

- LinkedIn: https://www.linkedin.com/in/bck98/
- Portfolio: https://balusanu.github.io/My-Portfolio/
- GitHub: https://github.com/Balusanu

---

## ⭐ If you found this project useful, don't forget to give it a Star!
