# Retail Sales Performance Analysis Dashboard

## Overview
This project presents an interactive Power BI dashboard developed to analyze retail and warehouse sales performance. It was built to help business stakeholders track sales trends, monitor supplier performance, and understand product-level and category-level sales behavior across time. The underlying dataset was first cleaned and explored using Python before being modeled and visualized in Power BI.

## Project Files
- **Retail_Project.pbix** — The Power BI project file containing the full interactive dashboard, data model, and DAX measures.
- **retail_project.ipynb** — A Jupyter Notebook used for data loading, cleaning, exploration, and preprocessing with Python (pandas, numpy, matplotlib, seaborn).
- **Retail_and_wherehouse_Sale.xlsx** — The original raw dataset containing retail and warehouse sales records.
- **cleaned_retail_data.xlsx** — The cleaned and processed version of the dataset, ready for use in Power BI.
- **Dashboard.png** — A static screenshot preview of the final dashboard.

## Dataset Description
The dataset contains approximately 30,000 records with the following key fields:

| Column | Description |
|---|---|
| YEAR | Year of the sales record |
| MONTH | Month of the sales record |
| SUPPLIER | Name of the supplier |
| ITEM CODE | Unique identifier for the item |
| ITEM DESCRIPTION | Detailed description of the item |
| ITEM TYPE | Product category (e.g., Beer, Wine, Liquor, Non-Alcohol, Kegs, Dunnage, Ref, STR Supplies) |
| RETAIL SALES | Sales volume through retail channels |
| RETAIL TRANSFERS | Volume of retail transfers |
| WAREHOUSE SALES | Sales volume through warehouse channels |

## Key Metrics Displayed
The dashboard highlights the following core KPIs at a glance:
- **Total Retail Sales** — 204.22K
- **Total Warehouse Sales** — 824.28K
- **Total Suppliers** — 290
- **Total Products** — 16K
- **Total Retail Transfers** — 197.70K

## Dashboard Features
The report is organized into multiple visual sections to support detailed analysis:

1. **Total Retail Sales by Item Type** — A pie chart breaking down retail sales share across categories such as Liquor, Wine, Beer, and Non-Alcohol.
2. **Total Retail Sales by Supplier Group** — A horizontal bar chart ranking top suppliers (e.g., Diageo North America, E&J Gallo Winery, Anheuser Busch) by retail sales contribution.
3. **Total Retail Sales by Month Name** — A line chart tracking how retail sales fluctuate across January, March, July, and September.
4. **Total Retail Sales by Item Description** — A bar chart identifying the best-selling individual products.
5. **Total Retail Transfers by Item Type** — A bar chart comparing transfer volumes across product categories, with Liquor and Wine leading.
6. **Total Suppliers by Is Return** — A donut chart showing the proportion of suppliers associated with returned goods versus non-returned goods.

## Filters
Users can slice the data dynamically using the following filter panel options:
- Item Type
- Month Name
- Is Return

## Tools & Technologies Used
- **Python (Jupyter Notebook)** — for data loading, cleaning, and exploratory analysis using pandas, numpy, matplotlib, and seaborn.
- **Excel (.xlsx)** — for storing raw and cleaned datasets.
- **Power BI Desktop** — for data modeling, DAX calculations, and dashboard design.

## Purpose
The dashboard was created to demonstrate an end-to-end analytics workflow — from raw data cleaning in Python to a fully interactive business intelligence dashboard in Power BI — enabling stakeholders to quickly identify top-performing suppliers, high-demand product categories, and seasonal sales trends.

## How to Use
1. Review **retail_project.ipynb** to see the data cleaning and preprocessing steps applied to the raw dataset.
2. Download **Retail_Project.pbix** and open it in Power BI Desktop to explore the interactive dashboard.
3. Use the filter panel on the left to explore sales patterns by item type, month, or return status.
4. Hover over visuals for detailed tooltips and drill-down insights.

## Author
This project was developed as part of a Data Analytics portfolio to showcase skills in Python-based data cleaning and Power BI dashboarding for retail sales analysis.
