# Sales Analytics Dashboard

![overview_sales-dashboard](https://raw.githubusercontent.com/nindykaro/sales-analytics-dashboard/refs/heads/main/Overview_sales-dashboard.png)

## Overview
This project involves the analysis of a comprehensive retail sales dataset. The goal is to derive actionable insights regarding sales performance, profit margins, and customer trends. The analysis identifies key areas of growth and profitability across different regions, segments, and product categories.

## Dataset Structure
The project utilizes a raw dataset (`Order Data.csv`) containing transaction-level details. 

**Key Columns:**
- **Order Details:** `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
- **Customer Info:** `Customer ID`, `Customer Name`, `Segment`
- **Location:** `Country`, `City`, `State`, `Postal Code`, `Region`
- **Product Info:** `Product ID`, `Category`, `Sub-Category`, `Product Name`
- **Financial Metrics:** `Sales`, `Quantity`, `Discount`, `Profit`
- **Time Dimensions:** `Month`, `Year`

## Analysis Goals
The project is structured to answer specific business questions and generate key performance indicators (KPIs), as outlined in the `Practice Helper Sheet`:

1.  **KPI Calculation:**
    - Total Sales
    - Total Quantity Sold
    - Total Profit
    - Profit Margin (%)

2.  **Segmentation Analysis:**
    - Performance breakdown by Customer Segment (Consumer, Corporate, Home Office)
    - Category and Sub-Category performance

3.  **Trend Analysis:**
    - Monthly sales and profit trends to identify seasonality and growth patterns.

4.  **Top Performers:**
    - Identification of "Top 10" products or customers by Sales volume.

## Tools Used
- **Microsoft Excel / Spreadsheet Software:** Used for data cleaning, pivot tables, and dashboard creation.
- **CSV:** Data storage format for interoperability.

## How to Use
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/nindykaro/sales-analytics-dashboard.git](https://github.com/nindykaro/sales-analytics-dashboard.git)
    ```
2.  **Open the Data:**
    - Load `Sales Analytics Dashboard.xlsx - Order Data.csv` into your preferred analysis tool (Excel, Python/Pandas, Tableau, PowerBI).
3.  **Reproduce the Analysis:**
    - Follow the guidelines in `Practice Helper Sheet.csv` to recreate the metrics and charts.

## Key Insights
- **Technology** products often drive the highest sales volume but may have variable profit margins due to discounts.
- **Consumer** segment typically accounts for the largest share of orders.
- Seasonal spikes are often observed in **November and December**..
