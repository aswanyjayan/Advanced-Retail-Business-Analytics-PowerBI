# Advanced-Retail-Business-Analytics-PowerBI
End-to-end retail business analytics project using Power BI

Project Overview

This project presents an end-to-end retail business analysis using Microsoft Power BI. The objective was to transform retail sales, customer, returns, and inventory data into an interactive, multi-page dashboard to examine business performance and identify useful patterns for decision-making.

The report contains six interconnected analytical pages: Executive Overview, Sales Analysis, Time Intelligence, Customer Analytics, Returns & Profitability, and Inventory & Operations. Each page focuses on a different business area, avoiding unnecessary repetition of visuals and providing a more detailed view of the business.

Project Objectives

* Evaluate overall revenue, profit, profit margin, order volume, return rate, and target achievement.

* Compare revenue performance across regions, sales representatives, product categories, and sales channels.

* Examine product-level revenue and profitability, customer contribution, discount patterns, and average order value.

* Analyse monthly and quarterly revenue patterns and compare performance across 2024 and 2025.

* Understand customer segments, purchasing behaviour, customer value, and purchase recency.

* Investigate product and salesperson return rates, return reasons, and the relationship between returns and profitability.

* Compare current inventory levels with reorder levels and examine inventory availability in relation to sales quantity.


## Dashboard Structure

The Power BI report consists of six interactive dashboard pages, each designed to examine a different aspect of retail business performance.

| Dashboard | Purpose and Analysis |
|---|---|
| **1. Executive Overview** | Provides a summary of overall business performance through total revenue, total profit, profit margin, total orders and return rate. It also presents regional revenue, sales representative performance against targets and gross profit margin by region. |
| **2. Sales Analysis** | Examines product revenue and profitability, top five customers by revenue, revenue contribution by sales channel, discount impact on sales and average order value across customer segments. |
| **3. Time Intelligence** | Analyses year-on-year revenue growth, monthly revenue trends, quarterly performance and the comparison of total net revenue with gross sales over time. |
| **4. Customer Analytics** | Examines customer purchase frequency, revenue contribution, customer segments, top ten customers by lifetime revenue and customer purchase recency. |
| **5. Returns & Profitability** | Analyses return rates by salesperson and product, product revenue against refund exposure, return reasons, monthly return-rate trends and profit before and after returns. |
| **6. Inventory & Operations** | Examines inventory availability, sales quantity, closing stock, reorder levels and product-level inventory requirements to identify potential replenishment priorities. |

## Key Observations from the Current Dashboards

The following observations are based on the values and visual patterns currently displayed in the dashboard screenshots.

### Overall Business Performance

The Executive Overview displays the following KPIs:

| KPI | Reported Value |
|---|---:|
| Total Revenue | ₹154.37M |
| Total Profit | ₹44.60M |
| Profit Margin | 28.89% |
| Total Orders | 1,797 |
| Return Rate | 9.50% |

The report covers the period from 1 January 2024 to 30 December 2025, with a channel filter available.

### Sales Analysis

- The product revenue versus profitability visual compares revenue generation with gross profit across products.
- The top five customers visual identifies the leading customers by revenue.
- Revenue contribution is compared across Online, Retail Store and Distributor channels.
- The discount-impact visual examines the relationship between average discount percentage and net revenue.
- Average order value is compared across Consumer, Corporate and Small Business segments.

### Time Intelligence

- Year-on-year revenue growth is presented for monthly periods.
- Monthly net revenue is compared across 2024 and 2025.
- A separate visual compares total net revenue and gross sales over time.

### Customer Analytics

The customer segment visual shows the following distribution:

| Customer Segment | Customers | Share |
|---|---:|---:|
| Consumer | 129 | 53.75% |
| Corporate | 71 | 29.58% |
| Small Business | 40 | 16.67% |
| **Total** | **240** | **100%** |

The dashboard also highlights the top ten customers by lifetime revenue, customer purchase frequency and revenue, and customer last-purchase information.

### Returns & Profitability

- Return rates are compared across sales representatives and products.
- Product revenue is examined alongside refund exposure.
- Return reasons are compared in a separate visual.
- Monthly return-rate trends are displayed for 2024 and 2025.
- Profit before returns and profit after returns are compared across product categories.

### Inventory & Operations

- Closing stock is compared with reorder levels at product level.
- Inventory availability is examined alongside sales quantity.
- Product-level stock and reorder requirements are presented in a table.
- These visuals can help identify products that may require replenishment.

**Validation note:** The regional revenue table currently displays identical revenue values for all four regions, despite the regional bar chart showing different values. The gross profit margin by region visual and the return-reason visual also need their measure names, values and axis labels checked. These should be corrected before making definitive regional or return-reason conclusions.

## Tools and Techniques

The project uses the following tools and analytical concepts:

- **Microsoft Excel:** Source workbook containing multiple related business datasets.
- **Microsoft Power BI:** Data modelling, DAX calculations, interactive visualisation and dashboard development.
- **Data modelling:** Working with customer, product, salesperson, order, return, target and inventory information.
- **Data quality analysis:** Identifying duplicates, missing values, inconsistent formats, invalid values and suspicious business records.
- **DAX:** Creating measures for revenue, profit, profit margin, order count, return rate and other business KPIs.
- **Business analysis:** Comparing performance across products, regions, sales channels, customer segments and time periods.
- **Data visualisation:** Using KPI cards, bar charts, column charts, scatter plots, line charts, donut charts, tables and slicers.

## Scope and Limitations

- The dataset is synthetic and was created for learning and portfolio development. It does not represent the actual financial or operational records of a real company.
- The workbook contains 2,998 order-line records, 240 customers, 260 return records and nine worksheets.
- The source data includes deliberately introduced data-quality issues, such as duplicate records, missing identifiers, inconsistent dates and regions, invalid quantities, unusual discounts and inventory anomalies.
- The analysis depends on the accuracy of the data-cleaning rules, relationships and DAX measures applied during development.
- Customer lifetime revenue is based on the historical transactions available in the dataset. It should not be interpreted as a predictive estimate of future customer value.
- The inventory analysis is based on the available closing-stock and reorder-level information. It does not, by itself, establish historical stockouts, inventory ageing or stock movements.
- The dataset covers a limited two-year period, so longer-term seasonal patterns cannot be established confidently.
- Some dashboard measures and visual labels require further validation before their results can be used for definitive management decisions.

## Conclusion

This project demonstrates an end-to-end retail business analytics workflow using a synthetic, multi-table dataset. It brings together sales, customer, product, returns, target and inventory information in a six-page Power BI report.

The dashboards provide different perspectives on business performance, including revenue and profitability, customer behaviour, sales trends, product returns and inventory requirements.


## Dashboard Screenshots

### 1. Executive Overview
![Executive Overview](Dashboard_Screenshots/Executive%20Overview.png)

### 2. Sales Analysis
![Sales Analysis](Dashboard_Screenshots/Sales%20Analysis.png)

### 3. Time Intelligence
![Time Intelligence](Dashboard_Screenshots/Time%20Intelligence.png)

### 4. Customer Analytics
![Customer Analytics](Dashboard_Screenshots/Customer%20Analytics.png)

### 5. Returns & Profitability
![Returns & Profitability](Dashboard_Screenshots/Returns%20%26%20Profitability.png)

### 6. Inventory & Operations
![Inventory & Operations](Dashboard_Screenshots/Inventory%20%26%20Operations.png)


The project also provides practical experience in working with imperfect data, developing business measures, analysing relationships between multiple datasets and presenting results through interactive dashboards.

The overall objective is to demonstrate the ability to transform raw business data into structured analysis and meaningful information that can support business decision-making.

