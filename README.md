# Excel-Online-Retail-Dataset
This project utilizes real world transactional ecommerce data. The goal was to clean the raw data, perform RFM analysis, cohort analysis and generate sales forecast to help with business decision making.

## Dataset
**Dataset**: UCI Online Retail Dataset

**Description**: Transaction-level data from a UK-based online retailer

**Period Covered**: December 2010 – December 2011

**Size**: around 540,000 transactions

**Fields Used**: InvoiceNo, InvoiceDate, CustomerID, StockCode, Description, Quantity, UnitPrice, Country, Unique CustomerID, FirstPurchaseDate, LastPurchaseDate, Recency, CohortMonth, and MonthSinceFirstPurchase.

## Tools Used In Excel
1. Power Query
2. PivotTables & PivotCharts
3. Forecast Sheet
4. Excel formulas

## Approach
### Data Loading and Preparation
- Imported the online retail dataset into Excel using the Power Query feature.
- Cleaned text fields using Trim and Clean.
- Coverted InvoiceDate to Date/Time format.
- Converted Quantity and UnitPrice to numeric values.
- Removed transactions with CustomerID.
- Created a calculated column TotalPrice = Quantity * UnitPrice.
- Flagged cancelled transactions by identifying Invoice numbers starting with “C”.
- Loaded the cleaned data into Excel for analysis.

### Sales Analysis
- Built a monthly revenue time series using PivotTables.
- Created a line chart to visualize revenue trends.
- Identified top-selling products by total revenue using a Top-10 filter.
- Identified top customers by revenue contribution using Pareto type chart.

### Customer Segmentation
- Calculated Recency (days since last purchase), Frequency (number of invoices), and Monetary value (total spend) for each customer.

### Cohort Analysis
- Identified each customer’s first purchase month.
- Created a Cohort Month field.
- Analyzed customer retention by tracking repeat purchases across months using PivotTables.
- Used cohort-based tables to observe retention patterns over time.

### Sales Forecasting
- Used Excel’s built-in Forecast Sheet on monthly revenue data.
- Generated a 6–12 month sales forecast with confidence intervals.

## Valuable Insights
- Revenue showed clear seasonality with higher sales usually during peak retail months.
- Customer retention declined over time, showing opportunities for re-engagement strategies.
- The sales forecast suggests bounce back of growth.
- A small percentage of customers contributed a large share of total revenue.
- RFM analysis revealed a strong group of high-value repeat customers.

## Conclusion
This project shows practical Excel skills needed for real world business analysis, such as; data cleaning, customer segmentation, trend analysis, and forecasting. Analysis like this provides actionable insights tat could support marketing, and revenue goal planning.















