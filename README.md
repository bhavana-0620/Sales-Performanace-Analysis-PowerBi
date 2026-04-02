# 📊 Sales Performance Analysis – Power BI & Python Project

## 🔗 Live Dashboard

👉 https://app.powerbi.com/view?r=eyJrIjoiMjZkNjk5ZWUtZTNlOC00YmQxLTgwNmUtZDdhMzUwYWRiMGRmIiwidCI6Ijc4NTAyYzI3LTY4ZTktNDA2Ni1iNmVkLWI3NjdjOWE2NDY2OSJ9

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
* Are there any sharp drops or anomalies in specific periods?  

### 🟢 Product Analysis

* Which products generate the most revenue?  
* Which products are underperforming?  
* How do top and bottom products compare in contribution?  

### 🟢 Channel Analysis

* Which sales channel contributes the most?  
* How profitable are different channels?  
* Are there differences in monthly performance across channels?  

### 🟢 Geographic Analysis

* Which states or regions drive revenue?  
* Are there regional performance differences?  

---

# 🛠 Approach & Methodology

## 🔹 1. Data Cleaning & Preparation (Python)

* Converted date columns to proper datetime format  
* Handled missing values and inconsistencies  
* Created derived columns (Year, Month, Quarter)  
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
* Ensured correct date hierarchy for accurate time-based visuals  

---

## 🔹 4. Dashboard Development (Power BI)

### 📊 Page 1: Executive Overview

* KPIs: Revenue, Profit, Orders, Profit Margin  
* Revenue trend over time with proper **year and month hierarchy**  
* Identified noticeable revenue decline in **early 2017 (Q1)**  
* Interactive tooltip to analyze contributing factors (Revenue, Orders, Revenue per Order, Top Products)  
* Channel performance overview  
* Key business insight summary  

---

### 📊 Page 2: Product & Channel Analysis

* Interactive **Top 10 and Bottom 10 toggle using bookmarks**  
* Bottom 10 products correctly sorted (lowest → highest)  
* Revenue vs Profitability scatter analysis  
* Channel contribution to profit (Distributor, Export, Wholesale)  
* Monthly profit trends across channels  

---

### 📊 Page 3: Geographic Insights

* Revenue distribution by state (map visualization)  
* Top-performing states by revenue  
* Profit margin comparison across regions  
* Clear identification of high-revenue regions  

---

# 🧠 Key Insights

* Revenue shows **fluctuating trends over time**, with a **sharp drop observed in early 2017 (Q1)**  

* The revenue drop is **not driven by total orders**, indicating:
  * A change in **revenue per order** or **product mix**  

* A small group of products contributes a **large portion of total revenue**, showing dependency on top performers  

* Bottom-performing products generate significantly lower revenue, indicating:
  * Opportunities for optimization or removal  

* Wholesale channel contributes the **highest share of revenue**, while other channels lag behind  

* Some high-revenue products operate at **lower profit margins**, suggesting pricing or cost inefficiencies  

* Geographic analysis shows:
  * Certain states contribute significantly more revenue  
  * Profit margins remain relatively consistent across regions  

---

# 📊 Business Recommendations

* Investigate the **revenue decline in 2017 Q1**, focusing on:
  * Revenue per order  
  * Product performance changes  

* Optimize or discontinue **low-performing products**  

* Improve margins for **high-revenue but low-profit products**  

* Reduce dependency on **Wholesale channel** by strengthening other channels  

* Focus marketing and expansion strategies on **high-performing regions**  

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
