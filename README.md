# Nordic Retail Masters — Interactive Sales & Profitability Dashboard

An interactive Power BI dashboard analyzing product performance across a multi-brand retail dataset. Built as an individual assignment during the Data Science program (YH, EC Utbildning).

![Dashboard preview](screenshot.png)

## What it does

The report tracks sales, profit, and profit margin across product categories and brands, helping identify which products and brands drive the most value.

**Key metrics covered:**
- Total sales: 151,141,385 kr
- Total profit: 53,366,614 kr
- Units sold: 161,509
- Blended profit margin: 35.31%

**Views included:**
- Category-level breakdown (Sports, Home, Electronics, Apparel) with sales, profit, quantity, and margin per category
- Top 10 brands by sales and profit (Solaria, Contoso, Fabrikam, UrbanPeak, Northwind)
- Top 10 best-selling products
- Quantity distribution by category (donut chart)
- Interactive filters for year and category, with a reset-filters control

## Tools & techniques

- **Power BI Desktop** — data modeling, DAX measures, interactive visuals
- **Power Query** — data transformation and cleaning
- Category-level KPI cards, ranked bar charts, and a donut chart for distribution
- Slicers and bookmarks for interactive filtering

## How to explore it

1. Download `FinalAssignment.pbix` from this repo.
2. Open it in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free).
3. Use the Year and Category filters on the left panel to explore different slices of the data.

## About this project

Built to practice end-to-end BI development: data modeling, DAX calculations, and dashboard design for a retail business scenario, with a focus on making profitability and product performance easy to compare at a glance.
