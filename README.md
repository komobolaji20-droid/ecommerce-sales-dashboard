# Retail E-commerce Sales Performance Analysis

![Dashboard Screenshot](<Retail ecommerce project_202605082144_1.png>)

##  Project Overview
This project features an interactive **E-commerce Sales Performance Dashboard** designed to track key business metrics, analyze regional trends, and identify revenue drivers. The analysis focuses on a dataset of **$228K in total revenue**, evaluating performance against a **$214K target**.


## Key Performance Indicators (KPIs)
* **Total Revenue:** $228K (Exceeded target by 6.31%)
* **Total Orders:** 310
* **Average Order Value (AOV):** $735
* **Total Quantity Sold:** 968 units

## Business Problem
The executive team identified the need for a centralized reporting solution to monitor the overall performance of their global e-commerce operations. Prior to this dashboard, sales data was fragmented across multiple sources, making it difficult to efficiently answer critical business questions and support data-driven decision-making.

* **Key business concerns included:**
* **Target Monitoring**
Was the business on track to achieve its $214K quarterly revenue target?

* **Inventory & Category Performance**
Which product categories across the six primary product groups  were driving revenue growth, and which categories were underperforming?

* **Regional Variance**
Was revenue evenly distributed across geographic regions, or were certain territories underperforming and requiring localized marketing interventions?

* **Operational Efficiency**
How did discount rates influence overall revenue performance? Additionally, was there a sufficiently strong relationship between order volume and revenue generation to justify ongoing scaling efforts?


##  Deep Dive Insights

### 1. Revenue Concentration (Pareto Principle)
Using a Pareto analysis, I identified that the **Books** category is the primary revenue driver, contributing **24% of total sales**. The top three categories (Books, Apparel, and Electronics) account for over 60% of total revenue.
This suggests that a small number of product categories disproportionately influence business performance, making them strategic priorities for inventory planning and targeted marketing campaigns.

### 2. Temporal Trends
* **Peak Performance:** Revenue reached its highest peak in **May**.
* **Seasonal Volatility:** Notable dips occurred in **February** and **April**, suggesting a need for mid-quarter promotional activities to stabilize cash flow,This presents an opportunity for:
* **Mid-quarter promotional campaigns**
* **Discount strategies**
* **Customer retention initiatives**
* **Seasonal product bundling**
These actions could help stabilize monthly cash flow and reduce revenue fluctuations.

### 3. Regional Distribution
Revenue is fairly balanced across territories, though the **North Region** leads with **$52K**, while the **Northeast** shows room for growth at **$40K**,This indicates potential growth opportunities in underperforming regions through localized marketing, pricing optimization, or improved distribution strategies.

### 4. Correlation Analysis
The dashboard highlights a strong positive correlation (**$R^2 = 0.63$**) between order volume and total revenue. This indicates that growth is driven by healthy transaction volume rather than outlier high-ticket sales,From a business perspective, this indicates:
* **Stable customer purchasing behavior**
* **Healthy demand distribution**
* **Scalable revenue growth potential through customer acquisition strategies**

##  Tech Stack
* **Data Visualization:** Power BI
* **Data Processing:** SQL (Data cleaning & Aggregation)
* **Analysis:** DAX (Calculated measures for AOV and Target Variance)
* **Statistics:** Correlation and Pareto distribution analysis
* **Data Preparation** Power Query

##  Dataset Description
The analysis is based on a retail transactional dataset 
* **Dashboard:** [Retail E-commerce Dashboard](./Retail%20ecommerce%20project_202605082144_1.jpg)
* **Dataset:** [Download Raw Data (.csv)](./retail%20ecommerce%20dataset.csv)
* containing the following attributes:
* **Order ID & Date:** Unique transaction identifiers used for time-series analysis.
* **Category:** Product groupings (Books, Apparel, Electronics, etc.).
* **Revenue & Target:** Financial metrics used to calculate variance and performance.
* **Store Region:** Geographic data for spatial distribution analysis.
* **Customer Type:** Segmentation between New and Returning customers.
* **Discount %:** Applied promotional rates used to analyze pricing elasticity
* **Customer name** Used to calculate AOV 

##  Recommendations
1. **Inventory Optimization:** Prioritize stock levels for **Books** and **Apparel** as they show the highest conversion and revenue contribution.
2. **Marketing Strategy:** Investigate the drivers behind the **May** revenue spike to replicate successful campaigns in lower-performing months.
3. **Regional Expansion:** Implement targeted marketing campaigns in the **Northeast** region to bridge the $12K gap compared to the North region.

## Conclusions
The E-commerce Sales Performance Dashboard successfully transformed raw transactional data into a strategic asset. By achieving a $228K revenue result, the business proved its current model is robust and exceeding established targets by 6.31%.
* **Perfomance**: The organization is highly dependent on the Books and Apparel categories. While this provides a strong revenue floor, it highlights a need to diversify sales in lower-performing categories like Beauty and Home & Kitchen to mitigate risk.

* **Market Dynamics:** The strong correlation ($R^2 = 0.63$) between order volume and revenue suggests that the business scales efficiently; as volume increases, revenue follows predictably without significant profit erosion.

* **Opportunity:** The May peak and Northeast regional gap represent the two biggest levers for future growth. Replicating May's success across other quarters could lead to a significant year-over-year (YoY) revenue increase.

This project serves as a foundation for future predictive modeling, such as forecasting Q3 sales trends and implementing customer lifetime value (CLV) tracking.
---
*Developed by OMOBOLAJI KEHINDE ZACHARIAH*
