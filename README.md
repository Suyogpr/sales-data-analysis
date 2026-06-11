# Sales Data Analysis (SQL + Pandas)

## 📊 Project Overview

This project analyzes retail sales data from a superstore dataset using **Python (Pandas)** and **SQL-style aggregations**. The goal is to uncover key business insights related to sales performance, profitability, customer segments, regional trends, and product-level performance.

---

## 🎯 Objectives

* Analyze overall business performance (Sales, Profit, Orders)
* Identify top-performing categories and sub-categories
* Understand regional sales and profitability distribution
* Detect loss-making products and inefficiencies
* Evaluate the impact of discounts on profitability
* Analyze monthly sales trends and seasonality

---

## 🧰 Tools & Technologies

* Python
* Pandas
* Matplotlib
* SQL-style groupby analysis
* Jupyter Notebook

---

## 📁 Dataset

* Sample Superstore Dataset (Kaggle)
* 9,994 transaction records
* 21 columns including Sales, Profit, Discount, Category, Region, etc.

---

## 🔍 Key Analyses Performed

### 1. Overall Business Performance

* Total Sales: **2.29M**
* Total Profit: **286K**
* Total Orders: **5009**

---

### 2. Category Performance

| Category        | Sales | Profit |
| --------------- | ----: | -----: |
| Technology      |  836K |   145K |
| Furniture       |  742K |    18K |
| Office Supplies |  719K |   122K |

📌 Insight: Furniture has high sales but extremely low profit margin.

---

### 3. Regional Performance

* West: Highest sales & profit
* East: Strong performer
* Central: Low profitability despite decent sales
* South: Lowest sales but relatively efficient

---

### 4. Sub-Category Analysis

* Highest profit: Copiers, Phones, Accessories
* Loss-making: Tables (-17K), Bookcases (-3K), Supplies (-1K)

📌 Insight: Some high-sales products are actually unprofitable.

---

### 5. Discount Impact Analysis

* Correlation between Discount and Profit: **-0.219**
* Higher discounts tend to reduce profitability

📌 Insight: Heavy discounting negatively impacts profit margins.

---

### 6. Seasonality Analysis

* Time period: 2014–2017
* Sales fluctuate throughout the year
* Peak sales observed in **November 2017**
* Strong Q4 seasonality trend

---

## 📈 Key Business Insights

* Technology is the most profitable category overall
* Furniture category is inefficient in terms of profit generation
* Certain sub-categories consistently generate losses due to high discounting
* Discounts negatively impact profitability
* Sales show strong seasonal trends, peaking in Q4

---

## 🚀 Conclusion

This analysis demonstrates how raw sales data can be transformed into actionable business insights using Python and SQL-style analysis. It highlights key areas for improvement such as pricing strategy, discount optimization, and product portfolio management.

---

## 📌 Future Improvements

* Build predictive sales forecasting model
* Add interactive dashboard (Power BI / Tableau)
* Perform customer segmentation analysis
