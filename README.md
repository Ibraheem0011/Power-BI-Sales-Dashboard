# Sales Performance Dashboard (Power BI)

An interactive Power BI report analysing sales for **360 orders across 4 countries and 40 products (January – June 2024)**. It combines custom DAX measures, country, product and monthly views, and a country slicer in a one-page executive dashboard.

## Business Questions

- How much did the business sell, and how did sales move month by month?
- Which countries and products drive the most sales?
- How many customers are active, and how much does each one spend?
- What share of orders are high value, and how does performance compare across countries?

## Dataset

- **Records:** 360 orders
- **Period:** January – June 2024
- **Coverage:** 4 countries, 40 products
- **Key fields:** OrderID, OrderDate, Country, Category, ProductName, SalesAmount, and customer information
- **Source:** [add where the data came from, e.g. dataset provided for the TWDP data analysis training assignment]

## Tools and Skills Used

- Power BI Desktop
- DAX measures and calculated metrics
- Date hierarchy (monthly trend analysis)
- Interactive visuals: slicer, bar and column charts, line chart, matrix and table
- Dashboard layout and KPI card design

## Report Structure

| Page | Purpose |
| --- | --- |
| **KPIs** | Headline metrics: Total Sales, Active Customers, Sales per Customer, High Value Orders % and Avg Units per Order |
| **Charts** | Working page with the detailed charts: sales trend, country comparison, product ranking and country-by-category matrix |
| **Dashboard** | Final one-page executive view that brings the KPIs and charts together, with a country slicer |

## DAX Measures

| Measure | What it shows |
| --- | --- |
| Total Sales | Sum of SalesAmount |
| Active Customers | Number of customers who placed orders |
| Sales per Customer | Total Sales divided by Active Customers |
| High Value Orders % | Share of orders above [add your threshold] |
| Avg Units per Order | Average quantity of units per order |
| Average Order Value | Total Sales divided by number of orders |
| Sales Share % | Each country's share of total sales |
| Country Rank | Ranking of countries by sales |

## Dashboard Visuals

- KPI cards: Total Sales, Active Customers, Sales per Customer, High Value Orders %
- Total Sales by Country
- Average of Sales by Country
- Total Sales by Product
- Total Sales by Month (trend)
- Sales Performance by Country and category (matrix)
- Sales Breakdown table: average order value, country rank and sales share
- Country slicer to filter the whole page

## Key Insights

- [Add insight 1, e.g. which country leads on sales and its share]
- [Add insight 2, e.g. the top product and how concentrated sales are]
- [Add insight 3, e.g. the strongest and weakest month and what the trend suggests]


## Repository Structure

```
├── analysis/        # Power BI report (.pbix)
├── presentation/ 
├── images/          # Dashboard screenshots
└── README.md
```

*This project was completed as an assignment in the TWDP Data Analysis Training.*

## Author

**Ibraheem Tunde Lawal**
Microbiology graduate and data analyst, Kwara State University
