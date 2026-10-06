# 📊 Sales Performance Analysis Dashboard

> **Interactive Power BI dashboard for analyzing sales, profit, quantity, discounts, payment methods, and category-level performance.**

---

## 📌 Project Overview

The **Sales Performance Analysis Dashboard** is an interactive **Power BI business intelligence project** designed to analyze sales performance across different product categories and business dimensions.

The dashboard transforms raw sales data into meaningful **KPIs, trends, comparisons, and business insights** that can help stakeholders understand overall performance and identify areas requiring attention.

The analysis covers three major product categories:

* 👕 Clothing
* 💻 Electronics
* 🛋️ Furniture

The project demonstrates the complete BI workflow — from understanding and preparing data to creating an interactive dashboard and generating actionable insights.

---

## 🎯 Business Objective

The main objective of this project is to provide a centralized dashboard that helps answer important business questions such as:

* What is the overall sales performance?
* How many orders and products were sold?
* How much profit was generated?
* Which product categories perform best?
* How does sales performance change over time?
* What payment methods are most commonly used?
* How do discounts affect overall performance?
* Which areas contribute most to revenue and profit?

---

# 📈 Key Performance Indicators

The dashboard tracks the following major KPIs:

| KPI                    |      Value |
| ---------------------- | ---------: |
| 🧾 Total Orders        |  **5,000** |
| 📦 Total Quantity Sold |    **15K** |
| 💰 Total Sales         |   **202M** |
| 📈 Total Profit        | **20.24M** |
| 🏷️ Average Discount   |   **0.09** |

These KPIs provide a quick overview of the organization's overall sales performance.

---

# 📊 Dashboard Analysis

## 1. 💰 Sales & Profit Analysis

The dashboard provides an overview of:

* Total sales
* Total profit
* Order volume
* Quantity sold
* Average discount
* Category-level performance

This allows users to quickly evaluate whether sales growth is translating into profitable business performance.

---

## 2. 🛍️ Category Analysis

Sales performance is analyzed across:

* **Clothing**
* **Electronics**
* **Furniture**

Category-level analysis helps identify high-performing and low-performing product segments and supports better inventory and business planning.

---

## 3. 💳 Payment Method Analysis

The dashboard also analyzes customer payment preferences.

| Payment Method |      Share |
| -------------- | ---------: |
| UPI            | **34.25%** |
| Cash           | **33.29%** |
| Card           | **32.45%** |

UPI represents the largest share, followed closely by cash and card payments.

The relatively balanced distribution indicates that customers use multiple payment methods rather than relying on a single payment channel.

---

## 4. 📅 Sales Trend Analysis

Time-based analysis is used to identify changes in sales performance across different periods.

The dashboard can help stakeholders identify:

* Increasing or decreasing sales trends
* High-performing periods
* Seasonal patterns
* Changes in order volume
* Profitability trends

---

## 5. 🏷️ Discount Analysis

Discount performance is included to understand the relationship between discounts and sales.

The dashboard tracks **Average Discount** as a KPI and allows business users to evaluate whether discounting strategies are supporting sales performance without unnecessarily reducing profitability.

---

# 🧹 Data Preparation

Before creating the dashboard, the sales data needs to be prepared for analysis.

Typical data preparation activities include:

* Removing duplicate records
* Handling missing values
* Checking data types
* Standardizing categorical values
* Validating sales and profit fields
* Creating calculated columns/measures
* Preparing date fields for time-based analysis

The cleaned data is then used to build the Power BI data model and dashboard.

---

# 🧮 Power BI & DAX

The dashboard uses **Power BI** for data modeling, visualization, KPI reporting, and interactive analysis.

DAX measures can be used to calculate important business metrics such as:

```DAX
Total Sales = SUM(Sales[Sales])
```

```DAX
Total Profit = SUM(Sales[Profit])
```

```DAX
Total Quantity = SUM(Sales[Quantity])
```

```DAX
Total Orders = DISTINCTCOUNT(Sales[Order ID])
```

These measures allow the dashboard to dynamically respond to filters and slicers.

---

# 🎛️ Dashboard Features

The Power BI dashboard includes interactive analytical capabilities such as:

### KPI Cards

* Total Orders
* Total Quantity
* Total Sales
* Total Profit
* Average Discount

### Visual Analysis

* Sales trends
* Profit analysis
* Category comparison
* Payment method distribution
* Quantity analysis
* Discount analysis

### Interactive Filtering

Users can filter the dashboard to perform more detailed analysis based on available dimensions such as:

* Product category
* Payment method
* Time period
* Other relevant business attributes

---

# 💡 Key Business Insights

The analysis provides several useful observations:

### 1. Strong Overall Sales Volume

The business generated **202M in total sales** from **5,000 orders**, indicating substantial transaction activity.

### 2. Profitability Tracking

Total profit of **20.24M** provides an important measure of overall business profitability and allows sales performance to be evaluated beyond revenue alone.

### 3. Balanced Payment Preferences

UPI, cash, and card payments each contribute a significant share of transactions, with UPI slightly leading at **34.25%**.

### 4. Category-Level Opportunities

Analyzing Clothing, Electronics, and Furniture separately helps identify which categories are driving sales and where performance improvements may be required.

### 5. Discount Monitoring

Tracking average discount alongside sales and profit helps management evaluate whether promotional strategies are creating sustainable business value.

---

# 🧠 Business Recommendations

Based on the dashboard analysis, businesses can:

* Focus inventory planning on high-performing categories.
* Monitor product-level profitability rather than sales alone.
* Evaluate discount strategies based on their impact on profit.
* Continue supporting multiple payment methods.
* Analyze sales trends to improve demand planning.
* Use category-level performance to optimize marketing strategies.
* Monitor KPIs regularly through an interactive BI dashboard.

---

# 🛠️ Tools & Technologies

| Tool                   | Purpose                               |
| ---------------------- | ------------------------------------- |
| **Microsoft Power BI** | Dashboard development & visualization |
| **DAX**                | KPI and calculated measure creation   |
| **Power Query**        | Data cleaning & transformation        |
| **Excel / Dataset**    | Source data preparation               |
| **GitHub**             | Project version control & portfolio   |

---

# 📂 Repository Structure

```text
sales-performance-analysis/
│
├── SALES PERFORMANCE DASH.pbix
│
└── README.md
```

### `SALES PERFORMANCE DASH.pbix`

The main Power BI report containing the interactive sales analysis dashboard.

### `README.md`

Project documentation covering the objective, methodology, KPIs, insights, and business recommendations.

---

# 🚀 How to Use the Dashboard

### Step 1 — Clone the repository

```bash
git clone https://github.com/anantlohade789-a11y/sales-performance-analysis.git
```

### Step 2 — Open the project

Open:

```text
SALES PERFORMANCE DASH.pbix
```

using **Microsoft Power BI Desktop**.

### Step 3 — Explore the dashboard

Use the available visual filters and slicers to analyze:

* Sales
* Profit
* Orders
* Quantity
* Categories
* Payment methods
* Discounts
* Trends

---

# 📸 Dashboard Preview

Add a screenshot of your Power BI dashboard here:

```markdown
![Sales Performance Dashboard](dashboard.png)
```

> **Recommended:** Upload a clean screenshot of the dashboard to the repository and name it `dashboard.png`.

This makes the GitHub repository much more attractive to recruiters because they can see the project before downloading the `.pbix` file.

---

# 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* Data Visualization
* Business Intelligence
* Data Cleaning
* Data Transformation
* Power Query
* DAX
* KPI Development
* Sales Analysis
* Profit Analysis
* Trend Analysis
* Business Analytics
* Dashboard Design
* Data Storytelling
* Business Insight Generation

---

# 💼 Resume Description

**Sales Performance Analysis Dashboard | Power BI**

> Developed an interactive Power BI dashboard to analyze 5,000 orders, 15K units sold, 202M in sales, and 20.24M in profit across Clothing, Electronics, and Furniture categories; implemented KPI reporting, category analysis, payment-method analysis, discount tracking, and interactive visualizations to generate actionable business insights.

---

# 📚 Learning Outcomes

Through this project, I strengthened my ability to:

* Transform raw data into business-ready information.
* Build interactive Power BI dashboards.
* Create meaningful KPIs using DAX.
* Analyze sales and profitability.
* Perform category-level performance analysis.
* Identify trends and business opportunities.
* Present analytical findings through data visualization.
* Convert business requirements into BI reports.

---

# 👨‍💻 Author

## Anant Lohade

**Data Analyst | Python | SQL | Power BI | Excel**

🔗 **GitHub:** [@anantlohade789-a11y](https://github.com/anantlohade789-a11y)

🔗 **LinkedIn:** [@anantlohade](https://www.linkedin.com/in/anantlohade/)

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐.

**Repository:**
https://github.com/anantlohade789-a11y/sales-performance-analysis

---

## 📄 License

This project is created for **educational and portfolio purposes**.
