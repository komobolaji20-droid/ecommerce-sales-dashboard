# Retail E-commerce Sales Performance Analysis

![Dashboard Screenshot](Retail%20ecommerce%20project_202605082144_1.jpg)

## 📌 Project Overview
This project features an interactive **E-commerce Sales Performance Dashboard** designed to track key business metrics, analyze regional trends, and identify revenue drivers. The analysis focuses on a dataset of **$228K in total revenue**, evaluating performance against a **$214K target**.

## 📊 Key Performance Indicators (KPIs)
* **Total Revenue:** $228K (Exceeded target by 6.31%)
* **Total Orders:** 310
* **Average Order Value (AOV):** $735
* **Total Quantity Sold:** 968 units

## 🔍 Deep Dive Insights

### 1. Revenue Concentration (Pareto Principle)
Using a Pareto analysis, we identified that the **Books** category is the primary revenue driver, contributing **24% of total sales**. The top three categories (Books, Apparel, and Electronics) account for over 60% of total revenue.

### 2. Temporal Trends
* **Peak Performance:** Revenue reached its highest peak in **May**.
* **Seasonal Volatility:** Notable dips occurred in **February** and **April**, suggesting a need for mid-quarter promotional activities to stabilize cash flow.

### 3. Regional Distribution
Revenue is fairly balanced across territories, though the **North Region** leads with **$52K**, while the **Northeast** shows room for growth at **$40K**.

### 4. Correlation Analysis
The dashboard highlights a strong positive correlation (**$R^2 = 0.63$**) between order volume and total revenue. This indicates that growth is driven by healthy transaction volume rather than outlier high-ticket sales.

## 🛠️ Tech Stack
* **Data Visualization:** Power BI
* **Data Processing:** SQL (Data cleaning & Aggregation)
* **Analysis:** DAX (Calculated measures for AOV and Target Variance)
* **Statistics:** Correlation and Pareto distribution analysis

## 📂 Dataset Description
The analysis is based on a retail transactional dataset (`retail ecommerce dataset.csv`) containing the following attributes:
* **Order ID & Date:** Unique transaction identifiers used for time-series analysis.
* **Category:** Product groupings (Books, Apparel, Electronics, etc.).
* **Revenue & Target:** Financial metrics used to calculate variance and performance.
* **Region:** Geographic data for spatial distribution analysis.
* **Customer Type:** Segmentation between New and Returning customers.
* **Discount %:** Applied promotional rates used to analyze pricing elasticity.

## 💡 Recommendations
1. **Inventory Optimization:** Prioritize stock levels for **Books** and **Apparel** as they show the highest conversion and revenue contribution.
2. **Marketing Strategy:** Investigate the drivers behind the **May** revenue spike to replicate successful campaigns in lower-performing months.
3. **Regional Expansion:** Implement targeted marketing campaigns in the **Northeast** region to bridge the $12K gap compared to the North region.

---
*Developed by OMOBOLAJI KEHINDE ZACHARIAH*
