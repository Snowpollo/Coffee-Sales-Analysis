# ☕ Coffee Sales Performance Analysis

## 📌 Project Overview

This project analyzes coffee sales data using Microsoft Excel to identify sales performance trends, customer purchasing patterns, product performance, and geographic sales distribution.

The project demonstrates how Excel can be used to transform raw sales data into meaningful business insights through data preparation, lookup functions, calculated fields, PivotTables, and visualizations.

The analysis covers **1,000 orders**, generating approximately **$45,134.26 in total sales** from **3,551 units sold**.

---

## 🎯 Business Objective

The objective of this analysis is to understand coffee sales performance and identify patterns that could help a business make better decisions around:

* Product performance
* Sales trends over time
* Geographic sales performance
* Product size preferences
* Customer purchasing behavior
* Customer loyalty
* Revenue growth opportunities

---

## 📊 Dataset

The workbook contains several interconnected datasets.

### Orders

The Orders dataset contains transaction-level sales information, including:

* Order ID
* Order Date
* Customer ID
* Product ID
* Quantity
* Customer Name
* Email
* Country
* Coffee Type
* Roast Type
* Size
* Unit Price
* Sales
* Loyalty Card status

### Customers

The Customers dataset contains:

* Customer ID
* Customer Name
* Email
* Phone Number
* Address
* City
* Country
* Postcode
* Loyalty Card status

### Products

The Products dataset contains:

* Product ID
* Coffee Type
* Roast Type
* Product Size
* Unit Price
* Price per 100g
* Profit

---

## 🛠️ Tools & Techniques Used

**Microsoft Excel**

The following techniques were used throughout the project:

* Data cleaning and preparation
* XLOOKUP
* IF functions
* Calculated columns
* Sales calculations
* PivotTables
* PivotCharts
* Data aggregation
* KPI analysis
* Dashboard development
* Data visualization

A calculated **Sales** field was created using:

`Quantity × Unit Price`

XLOOKUP was also used to connect relevant information between the Orders, Customers, and Products datasets.

---

## 📈 Key Performance Indicators

| KPI                     |          Result |
| ----------------------- | --------------: |
| Total Sales             |  **$45,134.26** |
| Total Orders            |       **1,000** |
| Total Quantity Sold     | **3,551 units** |
| Average Sales per Order |      **$45.13** |

---

## 🔎 Key Findings

### 1. Sales Performance Over Time

Sales were analyzed from **2019 to 2022**.

| Year |          Sales |
| ---- | -------------: |
| 2019 |     $12,187.17 |
| 2020 |     $12,117.55 |
| 2021 | **$13,766.11** |
| 2022 |      $7,063.44 |

**2021 recorded the highest annual sales**, contributing approximately $13,766 to total revenue.

The decline in 2022 is an important area for further investigation and could indicate changes in sales volume, customer demand, product performance, or the period covered by the dataset.

---

### 2. Sales by Country

The analysis compared sales across the countries represented in the dataset.

| Country        |          Sales |
| -------------- | -------------: |
| United States  | **$35,909.68** |
| Ireland        |      $6,563.07 |
| United Kingdom |      $2,661.50 |

The United States accounted for approximately **80% of total sales**, making it the dominant market in this dataset.

---

### 3. Sales by Coffee Type

The analysis compared four coffee types:

* Arabica
* Exelsa
* Liberica
* Robusta

| Coffee Type |          Sales |
| ----------- | -------------: |
| Exelsa      | **$12,306.44** |
| Liberica    |     $12,054.07 |
| Arabica     |     $11,768.49 |
| Robusta     |      $9,005.25 |

**Exelsa generated the highest sales**, while Robusta generated the lowest sales among the four coffee types.

The relatively close performance of Arabica, Exelsa, and Liberica suggests that demand is distributed across multiple coffee types rather than being concentrated in one product category.

---

### 4. Sales by Product Size

The analysis compared sales across different product sizes.

| Size   |          Sales |
| ------ | -------------: |
| 0.2 kg |      $3,307.95 |
| 0.5 kg |      $7,029.99 |
| 1 kg   |     $11,010.75 |
| 2.5 kg | **$23,785.56** |

The **2.5 kg size generated the highest sales**, contributing more than half of total sales.

This could indicate that customers purchasing larger quantities represent an important revenue segment.

---

## 📊 Dashboard

The Excel dashboard provides a visual summary of the analysis using charts covering

* Sales by year
* Sales by country
* Sales by coffee type
* Sales by product size
* Customer-level sales performance

The dashboard makes it easier to identify important sales trends and patterns without having to examine the raw transaction data directly.

---

## 💡 Business Insights & Recommendations

### Focus on the strongest market

The United States is the largest market in the dataset and represents a significant portion of total revenue.

**Recommendation:**
Prioritize customer retention, targeted marketing campaigns, and product promotions in the U.S. market while exploring opportunities to grow the Ireland and United Kingdom markets.

### Promote high-performing products

Exelsa generated the highest sales among the coffee types analyzed.

**Recommendation:**
Consider using high-performing coffee types in promotional campaigns, bundles, and cross-selling strategies.

### Leverage larger product sizes

The 2.5 kg size generated the highest sales.

**Recommendation:**
Consider maintaining attractive pricing, bundles, or volume-based promotions for larger sizes to encourage higher-value purchases.

### Investigate the 2022 decline

Sales dropped considerably in 2022 compared with 2021.

**Recommendation:**
Further investigate the decline by examining monthly sales, order volume, customer retention, product-level performance, and other operational factors.

---

## 📚 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Microsoft Excel
* Data Cleaning
* Data Transformation
* XLOOKUP
* Excel Formulas
* PivotTables
* PivotCharts
* KPI Development
* Sales Analysis
* Customer Analysis
* Business Intelligence
* Data Visualization
* Dashboard Development
* Business Insight Generation

---

## 📁 Project Files

The repository contains:

* **Coffee Sales Dashboard.xlsx** — Excel workbook containing the raw data, analysis, PivotTables, and dashboard.
* **Coffee-Sales-Dashboard.jpg** — Dashboard preview.

---

## 👤 About

This project was created as part of my data analytics portfolio to demonstrate my ability to transform raw business data into actionable insights using Microsoft Excel.

**Focus:** Data Analysis | Sales Analytics | Business Intelligence | Excel

