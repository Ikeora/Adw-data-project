
# Customer Sales Insights Dashboard

## Project Overview

This project addresses a critical business need: understanding customer demographics and purchasing behaviors to inform strategic decisions. Specifically, the project focuses on analyzing **sales by gender and product category**, providing stakeholders with actionable insights through a user-friendly KPI dashboard.

### Key Objectives

- **Demographic Analysis**: Break down sales data by gender to identify purchasing trends and gender distribution within the customer base.
- **Product Category Insights**: Analyze product category performance in terms of total products sold and total sales revenue.
- **Data Exploration**: Allow stakeholders to filter data dynamically by product category and gender, with a date-based query interface.
- **Automation**: Ensure data pipelines are updated automatically every day for real-time accuracy.

---

## Solution Highlights

### Data Pipeline

A robust pipeline was developed to:

1. **Extract** data from the on-premises SQL database.
2. **Transform** the extracted data to meet the requirements for analysis and visualization.
3. **Load** the transformed data into **Azure** for further processing and accessibility.

### Data Transformation

- Applied transformations to make the data more query-friendly.
- Aggregated sales metrics, including total products sold and total revenue, by gender and product category.

### Dashboard Features

- **KPI Visualizations**: Display key metrics such as total sales, gender splits, and category performance.
- **Dynamic Filters**: Users can filter data by date, product category, and gender.
- **User Interface**: Designed with simplicity and usability in mind to ensure seamless access for non-technical stakeholders.

### Automation

- The data pipeline is scheduled to run daily, guaranteeing stakeholders always have access to the latest and most accurate data.

---

## Tools and Technologies

- **Database**: SQL for querying on-premises data.
- **Cloud Platform**: Azure for data storage and processing.
- **Visualization**: Power BI
- **Scheduling**: Automated data pipeline ETL and scheduling using Azure Data Factory , Databricks and Synapse.

---

## Key Learnings

- Enhanced skills in data pipeline development, including ETL processes.
- Gained experience with cloud integration using Azure.
- Improved understanding of designing user-focused dashboards for business stakeholders.

---

## Future Improvements

- Incorporate additional demographic factors (e.g., age, location) for a more granular analysis.
- Expand the dashboard's scope to include predictive analytics and trend forecasting.
- Optimize the data pipeline for faster processing and scalability.

---

## Getting Started

### Prerequisites

- SQL Server or an equivalent database setup.
- An Azure account for data storage and processing.
- Visualization tool software (Power BI or Tableau)


## Demo

![Dashboard Preview](/docs/dashboard_screenshot.png)

---

## License


---
