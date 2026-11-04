# RetailPulse – Retail Analytics Dashboard

## Project Overview

RetailPulse is an end-to-end retail analytics project developed using **Microsoft Power BI**. The project analyzes retail sales, customer behavior, product performance, sales trends, forecasting, and inventory health to help identify business insights and support data-driven decision-making.

The dashboard brings multiple aspects of retail operations into one interactive report, allowing users to explore business performance through KPIs, charts, trends, and filters.

## Dashboard Pages

The Power BI report contains seven pages:

| Page | Description |
|---|---|
| 1. Executive Summary | Provides an overview of key business KPIs and overall retail performance. |
| 2. Sales Performance & Trends | Analyzes revenue, order performance, and sales trends over time. |
| 3. Customer Analytics & Retention | Examines customer behavior, purchasing patterns, and retention. |
| 4. Customer Churn & At-Risk Customers | Highlights customers who may be at risk of disengagement. |
| 5. Product & Category Performance | Evaluates product and category-level sales performance. |
| 6. Sales Forecasting | Explores historical sales trends and projected future performance. |
| 7. Inventory & Stock Health | Monitors stock levels, inventory value, low-stock items, and stock shortages. |

## Tools & Technologies

- **Microsoft Power BI** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** – Measures, calculated columns, and business metrics.
- **CSV** – Source data storage and input files.

## Dataset Structure

The project uses five interconnected datasets:

| Dataset | Description |
|---|---|
| `transactions.csv` | Retail transaction and sales information. |
| `customers.csv` | Customer demographic and segmentation information. |
| `products.csv` | Product details, categories, brands, and costs. |
| `stores.csv` | Store and sales channel information. |
| `inventory.csv` | Inventory snapshots, stock quantities, and reorder levels. |

These datasets are connected through relevant identifiers to support analysis across sales, customers, products, stores, and inventory.

## Key Analytical Areas

- Revenue and order performance analysis.
- Sales trends and forecasting.
- Customer segmentation and retention analysis.
- Identification of at-risk customers.
- Product and category performance.
- Inventory monitoring and stock health analysis.
- Low-stock and out-of-stock identification.
- Estimated inventory valuation.

## Repository Contents

The repository is intended to contain:

- `RetailPulse.pbix` – Interactive Power BI report.
- `RetailPulse_Dashboard.pdf` – Exported dashboard containing all seven pages.
- `data/` – Source CSV datasets.
- `README.md` – Project documentation.

## How to View the Project

1. Clone or download this repository.
2. Open `RetailPulse.pbix` using Microsoft Power BI Desktop to explore the interactive report.
3. Alternatively, open `RetailPulse_Dashboard.pdf` to view the exported dashboard without Power BI Desktop.

**Note:** Power BI Desktop is required to interact with the `.pbix` report. The PDF is provided as a static version of the dashboard.

## Project Outcome

RetailPulse demonstrates the application of data analytics and business intelligence techniques to retail operations. It transforms structured retail data into an interactive dashboard that helps users understand business performance, identify trends, monitor customer activity, evaluate products, and assess inventory health.

---

**Project:** RetailPulse – Retail Analytics Dashboard  
**Technology:** Microsoft Power BI  
**Developed as part of:** Zidio Development Project
