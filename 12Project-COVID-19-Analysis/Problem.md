# Project: Analyzing the Trends of COVID-19 with Python

## Problem Statement

Given demographic and epidemiological data about COVID-19 cases, write python code to visualize the impact, analyze the trends of infection, mortality, and recovery, and make predictive forecasts about the expected number of cases in the near future.

### Dataset Information: `covid_19_clean_complete.csv`
Contains daily case tracking data across countries and regions with the following attributes:

| Feature Name | Description |
| :--- | :--- |
| **Province/State** | Province or state level breakdown where available |
| **Country/Region** | Country or sovereign region name |
| **Lat** | Geographic Latitude coordinate |
| **Long** | Geographic Longitude coordinate |
| **Date** | Observation date (YYYY-MM-DD) |
| **Confirmed** | Cumulative confirmed COVID-19 cases |
| **Deaths** | Cumulative recorded deaths |
| **Recovered** | Cumulative recovered cases |
| **Active** | Currently active cases (`Confirmed - Deaths - Recovered`) |
| **WHO Region** | World Health Organization regional categorization |

---

### Project Guidelines & Objectives:

1. **Data Aggregation & Manipulation:**
   - Use `pandas` to process and aggregate daily global and regional infection data.
   - Calculate metrics such as active cases, daily new infections, recovery rates, and mortality rates.

2. **Interactive Visualizations:**
   - Use `plotly` to build interactive visualizations of cumulative cases, daily infection spikes, and country-level comparisons.
   - Deep-dive into specific high-impact nations, notably India and global epicenters.

3. **Time Series Forecasting with Prophet:**
   - Format time-series data for Facebook Prophet (`ds` and `y` columns).
   - Fit predictive models on cumulative confirmed cases globally and for India.
   - Forecast expected cases for a week ahead (7 days) with 95% confidence intervals.
   - Visualize and evaluate trend projections.
