### 📊 Customer & Marketing Analytics Dashboard

Interactive Power BI dashboard analyzing customer behavior, purchasing patterns, product spending, customer segmentation, and marketing campaign performance. The project demonstrates data cleaning, DAX measures, KPI development, and interactive business reporting.

**Tools:** Power BI | DAX | Excel

🔗 [View Project](https://github.com/DanielJeremiahEnumaje/Customer-Marketing-Analytics-Dashboard)
## Project Overview

This project analyzes customer and marketing data to identify patterns in customer spending, purchasing behavior, campaign response, and customer value.

The dashboard was designed to provide an easy-to-understand view of customer performance and marketing activity, helping businesses understand their customers and make data-informed decisions.

## Dashboard Pages

### 1. Customer & Marketing Overview

This page provides a high-level overview of:

- Total customers
- Total revenue
- Average customer spend
- Campaign response rate
- Customer segmentation
- Revenue by education
- Revenue by age group
- Purchases by channel
- Campaign acceptance performance
- Spending by product category

![Customer & Marketing Overview](screenshots/Customer%20%26%20Marketing%20Overview.png)

### 2. Customer & Campaign Insights

This page provides deeper analysis of:

- Total campaign acceptances
- Average campaign acceptance
- Total complaints
- Average customer recency
- Purchases by customer segment
- Revenue by customer segment
- Purchases by age group
- Purchases by education
- Average recency by customer segment
- Complaints by customer segment

![Customer & Campaign Insights](screenshots/Customer%20%26%20Campaign%20Insights.png)

## Data Cleaning

The dataset was initially cleaned and prepared in Excel before being imported into Power BI.

The cleaning process included:

- Checking and handling missing values
- Identifying and removing invalid income values
- Checking and removing duplicate records
- Handling invalid birth years
- Standardizing education categories
- Standardizing marital status categories
- Removing unnecessary constant columns
- Checking numeric fields for invalid negative values
- Converting the cleaned data into an Excel table

## Tools Used

- Microsoft Excel — Data cleaning and validation
- Microsoft Power BI — Data modeling, DAX, analysis, and visualization
- DAX — Calculated columns and measures
- AI — Used as a supporting tool during the project development process

## Key Metrics

The dashboard includes metrics such as:

- Total Customers
- Total Revenue
- Average Customer Spend
- Campaign Response Rate
- Total Campaign Acceptances
- Average Campaign Acceptance
- Total Purchases
- Average Recency
- Total Complaints

## Business Questions

This project explores questions such as:

- Which customer segments generate the most revenue?
- Which customer groups make the most purchases?
- Which product categories generate the most spending?
- Which purchasing channels are most frequently used?
- How do campaign acceptance levels vary?
- How does customer recency differ across customer segments?
- Which customer segments have more complaints?

## Project Structure

```text
Customer-Marketing-Analytics-Dashboard
│
├── Customer_Marketing_Analytics_Dashboard.pbix
├── README.md
│
├── data
│   └── Customer_Marketing_Cleaned.xlsx
│
└── screenshots
    ├── Customer-Marketing-Overview.png
    └── Customer-Campaign-Insights.png
