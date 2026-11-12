# PhonePe Transaction Analytics Dashboard

## Project Overview

The PhonePe Transaction Analytics Dashboard is an interactive Business Intelligence project developed using Microsoft Power BI. It focuses on analyzing digital payment transactions, identifying transaction trends, evaluating payment performance, and generating meaningful business insights.

The dashboard transforms raw transaction data into interactive visualizations that help users understand transaction behavior across different time periods, payment modes, locations, and transaction statuses.

## Project Objectives

- Analyze overall digital payment transaction performance.
- Track total transaction volume and transaction value.
- Monitor successful, failed, and pending transactions.
- Identify monthly, quarterly, and yearly transaction trends.
- Analyze payment methods and transaction categories.
- Compare transaction performance across different cities and states.
- Present business insights through interactive visualizations.

## Key Features

- **KPI Cards:** Display total transactions, total transaction amount, average transaction value, and success rate.
- **Transaction Analysis:** Analyze transaction volume and payment value.
- **Time Intelligence:** Track monthly, quarterly, and yearly transaction trends.
- **Payment Mode Analysis:** Compare different digital payment methods.
- **Transaction Status Analysis:** Monitor successful, failed, and pending transactions.
- **Geographical Analysis:** Evaluate state-wise and city-wise transaction performance.
- **Interactive Filters:** Use slicers to filter data by date, location, payment mode, and transaction status.
- **Dynamic Visualizations:** Explore transaction patterns using interactive charts and graphs.

## Data Modelling

Data modelling was performed in Power BI to organize the dataset and establish relationships between relevant tables.

The data model focuses on:

- Fact table containing transaction-level information.
- Dimension tables for date, location, payment mode, and transaction categories.
- Establishing appropriate relationships between fact and dimension tables.
- Maintaining a structured data model for efficient reporting.
- Using a Star Schema approach where applicable.

## Data Cleaning and Transformation

Power Query was used for data preparation and transformation.

Key activities included:

- Removing duplicate records.
- Handling missing and null values.
- Correcting data types.
- Formatting date and numerical columns.
- Standardizing categorical values.
- Creating calculated columns where required.
- Preparing data for analysis and visualization.

## DAX Measures and Calculations

DAX was used to create calculated measures and business KPIs.

Key calculations include:

- Total Transactions
- Total Transaction Amount
- Average Transaction Value
- Successful Transactions
- Failed Transactions
- Pending Transactions
- Transaction Success Rate
- Month-over-Month Growth
- Year-over-Year Growth

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculations |
| Data Modelling | Relationships and schema design |
| Microsoft Excel | Dataset preparation |

## Dashboard Insights

The dashboard helps identify:

- Overall digital payment transaction performance.
- Changes in transaction volume over time.
- Payment method preferences.
- Transaction success and failure patterns.
- Geographical differences in transaction activity.
- High-performing transaction categories and locations.

## Project Structure

```text
PhonePe-Transaction-Analytics-Dashboard/
│
├── Dashboard/
│   └── PhonePe_Dashboard.pbix
│
├── Dataset/
│   └── PhonePe_Transactions.xlsx
│
├── Screenshots/
│   └── Dashboard.png
│
└── README.md
```

## How to Use This Project

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` file.
4. If required, update the dataset source path.
5. Refresh the data.
6. Explore the dashboard using interactive filters and visualizations.

## Skills Demonstrated

- Data Cleaning and Transformation
- Power Query
- Data Modelling
- DAX Measures
- KPI Development
- Data Visualization
- Business Intelligence
- Analytical Thinking
- Dashboard Design

## Project Information

**Project Name:** PhonePe Transaction Analytics Dashboard

**Domain:** Digital Payments and FinTech Analytics

**Tool:** Microsoft Power BI

**Project Type:** Data Analytics and Business Intelligence

## Author

**Dhanendra Yadav**

MCA Student | Aspiring Data Analyst

Raipur, Chhattisgarh, India
/)

LinkedIn: www.linkedin.com/in/dhanendrayadav

---

If you find this project useful, consider giving this repository a star.

