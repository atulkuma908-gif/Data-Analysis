# Data-Analysis
Interactive Power BI dashboard analyzing Blinkit sales, outlet performance, product categories, and key business KPIs.
# 📊 Blinkit Sales Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![Excel](https://img.shields.io/badge/Excel-Dataset-green)
![DAX](https://img.shields.io/badge/DAX-KPI%20Analysis-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Cleaning-orange)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Project-purple)

---

## 📌 Project Overview

This project presents an interactive **Blinkit Sales Analysis Dashboard** developed using **Microsoft Power BI**.

The objective of this project is to analyze sales performance, product characteristics, outlet performance, and customer ratings using an interactive business intelligence dashboard.

The project converts raw grocery sales data into meaningful **KPIs, visualizations, and business insights** that can support data-driven decision-making.

The dashboard includes interactive filters and visualizations for analyzing sales based on **item type, fat content, outlet size, outlet location, outlet type, and outlet establishment year**.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall sales performance.
* Identify top-performing product categories.
* Analyze sales based on product fat content.
* Compare sales performance across different outlet sizes.
* Analyze sales by outlet location tier.
* Understand the relationship between outlet establishment and sales.
* Compare different outlet types.
* Monitor customer ratings.
* Create an interactive dashboard for business analysis.
* Convert raw data into actionable business insights.

---

## 🗂️ Dataset

The project uses a grocery sales dataset containing information about products, sales, outlets, locations, and customer ratings.

### Important Dataset Fields

| Column                    | Description                        |
| ------------------------- | ---------------------------------- |
| Item Identifier           | Unique identifier of the product   |
| Item Type                 | Category/type of product           |
| Item Fat Content          | Fat classification of the product  |
| Item Visibility           | Visibility of the product          |
| Item Weight               | Weight of the product              |
| Item MRP                  | Maximum retail price               |
| Outlet Identifier         | Unique outlet identifier           |
| Outlet Establishment Year | Year the outlet was established    |
| Outlet Size               | Size of the outlet                 |
| Outlet Location Type      | Location tier of the outlet        |
| Outlet Type               | Type of outlet                     |
| Sales                     | Revenue generated from the product |
| Rating                    | Customer rating                    |

---

# 🛠️ Tools & Technologies

The following tools were used in this project:

* **Microsoft Power BI** – Dashboard development and visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – KPI and calculated measure creation
* **Microsoft Excel** – Dataset/source data
* **Data Visualization** – Business insight presentation

---

# 🔄 Project Workflow

The project follows an end-to-end data analytics workflow:

```text
Raw Dataset
     ↓
Data Import
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

# 🧹 Data Cleaning & Transformation

The raw dataset was prepared using **Power Query** before building the dashboard.

### Major Data Preparation Tasks

* Checked the dataset for missing values.
* Identified and handled inconsistent values.
* Standardized categorical values.
* Corrected data types.
* Reviewed duplicate records.
* Transformed columns where required.
* Created appropriate fields for analysis.
* Prepared the dataset for Power BI visualization.

---

# 📐 DAX & KPI Analysis

Several measures were created using **DAX** to calculate important business metrics.

### Key KPIs

#### 1. Total Sales

Calculates the overall revenue generated from the products.

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
```

#### 2. Average Sales

Calculates the average sales value.

```DAX
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
```

#### 3. Number of Items

Counts the number of items/records in the dataset.

```DAX
Number of Items = COUNTROWS('BlinkIT Grocery Data')
```

#### 4. Average Rating

Calculates the average customer rating.

```DAX
Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
```

> **Note:** Update the table/column names in the DAX formulas if your dataset uses different names.

---

# 📊 Dashboard KPIs

The dashboard focuses on four primary KPIs:

### 💰 Total Sales

Shows the overall revenue generated from the products.

### 📈 Average Sales

Shows the average revenue generated per transaction/item.

### 📦 Number of Items

Shows the total number of items available in the dataset.

### ⭐ Average Rating

Shows the average customer rating.

These KPIs provide a quick overview of overall business performance.

---

# 📈 Dashboard Analysis

## 1. Sales by Fat Content

This analysis compares sales performance between different product fat-content categories.

### Purpose

* Understand customer preferences.
* Compare sales of Low Fat and Regular products.
* Analyze product demand based on fat content.

---

## 2. Sales by Item Type

This visualization analyzes sales across different product categories.

### Key Categories Include

* Fruits & Vegetables
* Snack Foods
* Household
* Frozen Foods
* Dairy
* Baking Goods
* Health & Hygiene
* Canned Foods
* Soft Drinks
* Meat
* Breakfast
* Others

### Purpose

This helps identify which product categories contribute the most to overall sales.

---

## 3. Outlet Establishment Analysis

A time-based visualization is used to analyze sales according to the outlet establishment year.

### Purpose

* Understand sales trends over outlet age.
* Compare newer and older outlets.
* Identify years associated with stronger sales performance.

---

## 4. Sales by Outlet Size

The dashboard compares sales across different outlet sizes.

### Outlet Size Categories

* Small
* Medium
* High

### Purpose

This analysis helps understand whether outlet size has an impact on sales performance.

---

## 5. Sales by Outlet Location

Sales are analyzed across different location tiers.

### Location Categories

* Tier 1
* Tier 2
* Tier 3

### Purpose

This helps identify which location tiers contribute most to overall sales.

---

## 6. Sales by Outlet Type

Different outlet types are compared based on their performance.

The dashboard can be used to compare:

* Total Sales
* Average Sales
* Number of Items
* Average Rating
* Product visibility

This provides a broader understanding of outlet-level performance.

---

# 🎛️ Interactive Dashboard Features

The Power BI dashboard contains interactive features such as:

* Slicers
* Filters
* KPI cards
* Bar charts
* Line charts
* Donut charts
* Funnel charts
* Matrix/table visualizations
* Dynamic visual interaction

Users can select different filters to dynamically analyze the data.

---

# 💡 Key Insights

The analysis provides several useful business insights.

### Product Insights

* Fruits & Vegetables and Snack Foods are among the important product categories.
* Product sales can be compared based on fat-content classification.
* Item-level analysis helps identify high-performing categories.

### Outlet Insights

* Outlet size can be compared to understand its relationship with sales.
* Location tier provides useful information about geographical sales performance.
* Outlet establishment year helps analyze sales trends over time.

### Business Insights

The dashboard can help management:

* Identify high-performing product categories.
* Understand outlet performance.
* Evaluate location-wise sales.
* Analyze customer ratings.
* Improve product and inventory decisions.
* Make data-driven business decisions.

---

# 📷 Dashboard Preview

Add your Power BI dashboard screenshot here.

```markdown
![Blinkit Dashboard](images/blinkit-dashboard.png)
```

Example folder structure:

```text
Blinkit-Sales-Analysis/
│
├── Dataset/
│   └── BlinkIT Grocery Data.xlsx
│
├── Dashboard/
│   └── Blinkit Sales Analysis.pbix
│
├── Images/
│   └── blinkit-dashboard.png
│
└── README.md
```

---

# 📁 Project Structure

```text
📦 Blinkit-Sales-Analysis
│
├── 📂 Dataset
│   └── BlinkIT Grocery Data.xlsx
│
├── 📂 Dashboard
│   └── Blinkit Sales Analysis.pbix
│
├── 📂 Images
│   └── blinkit-dashboard.png
│
└── 📄 README.md
```

---

# 🧠 Skills Demonstrated

Through this project, I demonstrated practical skills in:

* Data Cleaning
* Data Transformation
* Power Query
* DAX
* Data Modeling
* KPI Development
* Data Visualization
* Business Intelligence
* Dashboard Development
* Exploratory Data Analysis
* Business Insights
* Interactive Reporting

---

# 🚀 Learning Outcomes

This project helped me gain practical experience in:

1. Working with real-world business datasets.
2. Cleaning and transforming data using Power Query.
3. Creating calculated measures using DAX.
4. Designing interactive Power BI dashboards.
5. Selecting appropriate visualizations for business questions.
6. Analyzing sales and outlet performance.
7. Converting raw data into meaningful insights.
8. Presenting analytical findings in a business-friendly format.

---

# 📌 Business Questions Answered

The dashboard helps answer questions such as:

* What is the total sales revenue?
* What is the average sales value?
* How many items are present in the dataset?
* What is the average customer rating?
* Which product categories generate the highest sales?
* How does fat content affect sales?
* Which outlet size performs better?
* Which location tier generates higher sales?
* How have sales changed according to outlet establishment year?
* Which outlet types perform better?
* Which products/categories should receive more attention?

---

# 🔮 Future Improvements

The project can be further enhanced by adding:

* Sales forecasting
* Monthly/Yearly trend analysis
* Customer segmentation
* Profit analysis
* Inventory analysis
* Advanced DAX measures
* Drill-through pages
* Row-level security
* Automated data refresh
* Additional business KPIs

---

# 👨‍💻 Author

**Atul Kumar**

🎓 B.Tech Computer Science Student
📊 Aspiring Data Analyst

### Skills

`SQL` `Python` `Excel` `Power BI` `DAX` `Power Query` `Data Analytics`

---

# ⭐ Conclusion

The **Blinkit Sales Analysis Dashboard** demonstrates how Power BI can be used to transform raw sales data into an interactive business intelligence solution.

By combining **Power Query, DAX, data modeling, and visualization**, the project provides a structured way to analyze product sales, outlet performance, customer ratings, and location-based trends.

This project demonstrates practical **Data Analytics and Business Intelligence skills** and can be used as a portfolio project to showcase Power BI capabilities.

---

