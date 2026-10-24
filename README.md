# Logistics Operations & Fleet Performance Analytics

## Project Overview

This project focuses on analyzing logistics operations data to evaluate business performance, delivery outcomes, customer distribution, fleet status, and maintenance-related costs. Using a synthetic logistics operations dataset covering 2022–2024, the project explores operational data across 14 interconnected tables to identify relevant performance indicators and transform raw records into structured, analysis-ready information.

Google BigQuery was used as the primary data analysis environment, where SQL queries were applied to explore table structures, validate data quality, examine relationships between datasets, and perform multi-table joins and aggregations. A delivery performance data mart was also developed by integrating load, trip, and delivery event data, providing a consolidated dataset for analyzing shipment and delivery performance.

The analytical outputs were presented through an interactive two-page dashboard built in Looker Studio. The Executive Overview page provides insights into freight revenue, shipment volume, delivery performance, customer accounts, destination coverage, and revenue trends. The Fleet Operations & Maintenance Analytics page focuses on fleet status, key operational metrics, and maintenance performance through cost breakdowns by truck brand and maintenance type, monthly maintenance cost trends, and maintenance record counts.

By combining SQL-based data preparation, data validation, analytical data modeling, and interactive visualization, this project demonstrates a practical workflow for converting relational logistics data into structured business reporting. It highlights the application of data analytics and business intelligence techniques to monitor operational indicators, evaluate performance patterns, and support data-driven decision-making.
## Tools & Technologies

- **Google BigQuery** — Data exploration, SQL querying, data validation, joins, aggregations, and data mart development
- **SQL** — Data quality checks, relationship validation, and analytical transformations
- **Looker Studio** — Interactive dashboard development and data visualization

## Dashboard

### Page 1: Executive Overview

Provides a high-level overview of logistics performance, covering shipment volume, on-time delivery performance, freight revenue, customer coverage, and destination reach.

Key metrics and visualizations include:
- Total Loads
- On-Time Delivery Rate
- Total Freight Revenue
- Total Customers and Destination Cities
- Revenue by Load Type
- Revenue by Top 5 Destination States
- Monthly Revenue Trend
- Revenue by Top 5 Customers
- Customer Account Status Distribution

### Page 2: Fleet Operations & Maintenance Analytics

Focuses on fleet performance indicators, fleet status, and maintenance cost analysis.

Key metrics and visualizations include:
- Total Trips Completed
- Total Fuel Cost
- Total Maintenance Cost
- Total Downtime Hours
- Total Trucks
- Maintenance Cost by Truck Brand
- Monthly Maintenance Cost Trend
- Maintenance Record Count by Type
- Truck Fleet Status Distribution
- Maintenance Cost by Maintenance Type

## Key Findings

- **Freight Revenue:** Total freight revenue reached approximately **$262.53 million** across 85,410 loads.
- **Delivery Performance:** The recorded on-time delivery rate was **44.61%**, based on the dataset's delivery performance indicator.
- **Revenue Composition:** Refrigerated loads contributed approximately 50.27% of total freight revenue, while Dry Van loads contributed 49.73%.
- **Customer Coverage:** The dataset included 200 customers and 19 destination cities.
- **Fleet Status:** The fleet consisted of 120 trucks across Active, Maintenance, and Inactive statuses.
- **Maintenance Analysis:** Maintenance costs were examined by truck brand and maintenance type, alongside monthly cost trends and maintenance record counts.

## Data Processing & SQL Workflow

1. **Data Exploration** — Examined table structures, record counts, and relationships across 14 interconnected tables.
2. **Data Quality Assessment** — Performed checks on data completeness, key relationships, and consistency.
3. **SQL Transformations** — Used joins and aggregations to combine relevant operational data for analysis.
4. **Data Mart Development** — Built a delivery performance data mart integrating load, trip, and delivery event data.
5. **Dashboard Development** — Connected the analytical outputs to Looker Studio for interactive reporting and visualization.

## Dataset

The project uses a synthetic logistics operations dataset covering 2022–2024, sourced from Kaggle.

The dataset contains interconnected tables covering logistics operations, including loads, trips, customers, drivers, trucks, delivery events, fuel purchases, and maintenance records.

**Note:** The dataset represents simulated operational data and does not describe the actual performance of a real logistics company.

## Project Objectives

- Apply SQL to explore, validate, and transform relational operational data.
- Consolidate relevant logistics data for analytical reporting.
- Evaluate freight revenue, delivery performance, customer distribution, fleet status, and maintenance costs.
- Develop interactive dashboards to communicate operational metrics and support data-driven decision-making.
