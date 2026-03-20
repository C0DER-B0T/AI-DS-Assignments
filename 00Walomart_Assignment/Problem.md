# Problem Statement 1: Walmart Sales Analysis

A retail store with multiple outlets across the country is facing issues managing inventory to match demand with respect to supply.

### Dataset Information:
The `walmart.csv` contains 6435 rows and 8 columns.

| Feature Name | Description |
| :--- | :--- |
| **Store** | Store number |
| **Date** | Week of Sales |
| **Weekly_Sales** | Sales for the given store in that week |
| **Holiday_Flag** | Boolean indicating if it is a holiday week |
| **Temperature** | Temperature on the day of the sale |
| **Fuel_Price** | Cost of fuel in the region |
| **CPI** | Consumer Price Index |
| **Unemployment** | Unemployment Rate |

### Tasks:

1.  **Statistical Analysis & EDA:**
    Use statistical analysis, Exploratory Data Analysis (EDA), outlier analysis, and handle missing values to provide insights on:
    a. Are weekly sales affected by the unemployment rate? If so, which stores are suffering the most?
    b. Do weekly sales show a seasonal trend? What are the potential reasons?
    c. How does temperature affect weekly sales?
    d. How is the Consumer Price Index (CPI) affecting the weekly sales of various stores?
    e. Identify the top-performing stores according to historical data.
    f. Identify the worst-performing store and determine the significance of the difference between the highest and lowest performing stores.

2.  **Predictive Modeling:**
    Use predictive modeling techniques to forecast sales for each store for the next 12 weeks.
