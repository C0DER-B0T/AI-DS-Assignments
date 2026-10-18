# Capstone Project: Online Retail Analytics and Customer Segmentation

## Problem Statement

An online retail store with operations across multiple countries is trying to understand customer purchasing behaviors and patterns to improve customer retention, marketing campaign efficiency, and overall revenue.

### Dataset Information: `OnlineRetail.csv`
The dataset contains transactional data of an online retail company with 8 key attributes:

| Feature Name | Description |
| :--- | :--- |
| **Invoice** | Unique 6-digit number assigned to each transaction. If this code starts with 'C', it indicates a cancellation. |
| **StockCode** | Unique 5-digit number assigned to each distinct product. |
| **Description** | Product (item) name. |
| **Quantity** | The quantities of each product (item) per transaction. |
| **InvoiceDate** | The day and time when each transaction was generated. |
| **Price** | Product price per unit in sterling. |
| **CustomerID** | 5-digit integral number uniquely assigned to each customer. |
| **Country** | Name of the country where each customer resides. |

---

### Objectives and Tasks:

1. **Exploratory Data Analysis & Purchasing Insights:**
   - Handle missing values (e.g., transactions with missing CustomerID) and cancelled transactions (Quantity < 0).
   - Compute total sales value (`Quantity * Price`).
   - Identify top-selling products by quantity and revenue.
   - Analyze regional purchase distribution and sales across top countries.
   - Analyze monthly revenue trends and seasonal buying patterns.

2. **Customer Segmentation via RFM Analysis & Clustering:**
   - Engineer **RFM (Recency, Frequency, Monetary)** features for each unique customer.
   - Address distribution skewness using log transformation and standard feature scaling.
   - Determine optimal cluster numbers using the **Elbow Method** and **Silhouette Scores**.
   - Build a **K-Means Clustering** model to segment customers into distinct behavioral cohorts (e.g., Champions, Loyal Customers, Potential Loyalists, At Risk / Churned).
   - Provide strategic, actionable business recommendations for each customer segment.
