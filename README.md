# 📊 Sales Performance Analysis – Power BI & Python Project

## 🔗 Live Dashboard

👉 https://app.powerbi.com/view?r=eyJrIjoiMjZkNjk5ZWUtZTNlOC00YmQxLTgwNmUtZDdhMzUwYWRiMGRmIiwidCI6Ijc4NTAyYzI3LTY4ZTktNDA2Ni1iNmVkLWI3NjdjOWE2NDY2OSJ9&pageName=611c2cf82ee90b7c19a8

---

# 📌 Business Scenario

A retail company is experiencing fluctuations in revenue and profitability across different products, sales channels, and geographic regions.

The business leadership wants to understand:

* What is driving revenue and profit?
* Which products and channels are performing well or underperforming?
* How sales are distributed geographically
* Where improvements and optimizations can be made

This project aims to provide a **data-driven solution** to support strategic decision-making.

---

# 🎯 Business Objectives

* Analyze overall business performance
* Identify top and bottom-performing products
* Evaluate channel contribution to revenue and profit
* Understand geographic sales distribution
* Provide actionable business insights

---

# ❓ Key Business Questions

### 🟢 Overall Performance

* How are revenue and profit performing overall?
* What is the profit margin?

### 🟢 Time Analysis

* How is revenue trending over time?
* Are there seasonal patterns or declines?

### 🟢 Product Analysis

* Which products generate the most revenue?
* Which products are underperforming?

### 🟢 Channel Analysis

* Which sales channel contributes the most?
* How profitable are different channels?

### 🟢 Geographic Analysis

* Which states or regions drive revenue?
* Are there regional performance differences?

---

# 🛠 Approach & Methodology

## 🔹 1. Data Cleaning & Preparation (Python)

* Converted date columns to proper datetime format
* Handled missing values and inconsistencies
* Created derived columns (Year, Month, etc.)
* Structured data for analysis

---

## 🔹 2. Exploratory Data Analysis (EDA)

Performed detailed analysis using Python:

* Revenue trends over time
* Product performance (Top & Bottom products)
* Channel-wise revenue distribution
* Order value distribution
* Identification of patterns and anomalies

---

## 🔹 3. Data Modeling (Power BI)

* Implemented **Star Schema**
* Created:

  * Fact table (sales data)
  * Dimension tables (Date, Product, Channel, Location)
* Established relationships for efficient analysis

---

## 🔹 4. Dashboard Development (Power BI)

### 📊 Page 1: Executive Overview

* KPIs: Revenue, Profit, Orders, Profit Margin
* Revenue trend over time
* Channel performance
* Key business insight summary

---

### 📊 Page 2: Product & Channel Analysis

* Top 10 and Bottom 10 products
* Revenue vs Profitability scatter analysis
* Channel contribution to profit

---

### 📊 Page 3: Geographic Insights

* Revenue distribution by state
* Top-performing regions
* Profit margin by region

---

# 🧠 Key Insights

* Revenue shows seasonal patterns with noticeable fluctuations
* A small group of products contributes significantly to total revenue
* Some high-revenue products operate at lower margins
* Wholesale channel dominates revenue contribution
* Certain states drive a major share of total sales

---

# 📊 Business Recommendations

* Improve or discontinue low-performing products
* Optimize pricing for high-revenue low-margin products
* Diversify channel strategy beyond wholesale
* Focus marketing efforts on high-performing regions

---

# 🛠 Tools & Technologies

* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* DAX
* Data Modeling (Star Schema)

---

# 📂 Project Structure

* `data/` → Sales_Analysis_Dataset
* `notebook/` → EDA and data preparation
* `dashboard/` → Power BI (.pbix) file
* `images/` → Dashboard screenshots

---

# 🚀 How to Use

1. Open the live dashboard using the link above
2. Download `.pbix` file for detailed exploration
3. Review notebook for full analysis process

---

# 👤 Author

Bhavana
