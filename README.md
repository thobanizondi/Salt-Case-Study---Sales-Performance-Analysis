# Salt Case Study – Sales Performance Analysis

## Project Overview

This project analyses historical sales data from a retail wine store to identify business trends, evaluate sales performance, and generate insights into revenue, profitability, customer spending, and product performance.

Using Power BI, the project transforms raw sales data into interactive dashboards that help users explore transaction-level results, compare product categories, monitor customer value, and understand changes in sales over time.

The project includes two dashboards: **Sales Performance Overview** and **Wine Stock Management**.

## Business Objectives

- Analyse sales and revenue trends over time.
- Evaluate product category performance and profitability.
- Understand customer spending patterns and customer lifetime value.
- Compare salesperson performance.
- Explore transaction-level sales results using interactive date filters.
- Present findings through dashboards that support data-driven business decisions.

## Tools and Technologies

- **Microsoft Power BI:** Dashboard development, interactive visualisations, and reporting.
- **Microsoft Excel:** Source dataset and data preparation.
- **GitHub:** Source control and project documentation.

## Project Structure

```text
Salt_Case_Study/
├── data/
│   └── SaltCaseStudy_Dataset.xlsx
├── dashboards/
│   └── SaltAnalytics-DataAnalytics.pbix
└── documentation/
    └── README.md
```

File names and folders may vary depending on the current repository structure.

## Dashboard 1: Sales Performance Overview

This dashboard provides an interactive view of sales performance, revenue, costs, and profitability.

### Key Metrics

- **Total Sales:** Revenue generated from sales transactions.
- **Total Cost:** Costs associated with the analysed sales.
- **Profit Made:** Profit calculated from sales and cost data.
- **Average Sales per Transaction:** Average sales value across transactions.

### Visualisations

- **Product Category Bar Chart:** Compares sales across product categories.
- **Sales, Cost and Profit Breakdown:** Provides a visual comparison of key financial measures.
- **Revenue and Profit Trend Line Chart:** Shows performance trends over time.
- **Transaction Date Slicer:** Filters dashboard visuals to the selected date.

### Interactivity

Users can select a transaction date, such as 14 October 2022, to filter the dashboard. The KPIs and charts update to show the results for the selected date, making it easier to investigate daily performance without manually filtering the raw dataset.

## Dashboard 2: Wine Stock Management

This dashboard focuses on customer-level sales performance and wine sales insights.

### Key Metrics

- **Total Spent per Customer:** Measures customer spending within the selected reporting period.
- **Customer Lifetime Value (CLV):** Represents customer value over time, according to the project's calculation.
- **Total Wine Sales:** Displays the wine sales measure defined in the dashboard.

### Visualisations

- **Customer Sales Table:** Displays customer ID, salesperson, and total spending.
- **Wine Sales and Profit Breakdown:** Compares financial measures for the selected reporting period.
- **Date-Based Filtering:** Allows users to investigate customer and sales performance for a specific date.

### Business Value

The dashboard helps users identify high-spending customers, compare sales contributions, and explore sales performance. These insights can inform customer engagement, sales planning, and inventory-related decisions when combined with suitable stock-level data.

## Screenshots

### Sales Performance Overview

![Sales Performance Overview Dashboard](https://private-user-images.githubusercontent.com/86374769/452997435-39fb184a-b1aa-4831-a9a3-b61013a306ae.png)

### Wine Stock Management Dashboard

![Wine Stock Management Dashboard](https://private-user-images.githubusercontent.com/86374769/452998553-d82eecdd-f4ae-4e11-9bb9-2716a8e81bac.png)

If these image links expire, upload the screenshots to the repository and update the README to use relative image paths.

## How to Explore the Project

1. Clone or download the repository.
2. Open `SaltAnalytics-DataAnalytics.pbix` in Microsoft Power BI Desktop.
3. If prompted, configure the source dataset path.
4. Refresh the data if required.
5. Use the date slicer to explore the selected reporting period.
6. Interact with the charts and tables to examine sales, profitability, customer spending, and product performance.

Microsoft Power BI Desktop is required to interact with the `.pbix` report. The Excel dataset is included as the expected source file if it is available in the repository.

## Key Analytical Questions

This project explores questions such as:

- How do sales revenue and profit change over time?
- Which product categories contribute most to sales?
- How do costs compare with revenue?
- Which customers generate the highest spending?
- How do sales contributions vary by salesperson?
- How does daily performance differ across selected dates?

## Potential Future Enhancements

- Add a dedicated inventory dashboard showing stock quantities and reorder levels.
- Include monthly and seasonal sales comparisons.
- Add profit margin and year-over-year growth measures.
- Introduce customer segmentation based on purchasing behaviour.
- Improve data validation and document data-cleaning steps.
- Publish the dashboard to Power BI Service for controlled sharing.

## Author

**Thobani Zondi**

Data Analytics | Power BI | SQL | Data Quality and Reporting

GitHub: [thobanizondi](https://github.com/thobanizondi)
