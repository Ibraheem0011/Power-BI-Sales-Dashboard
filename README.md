# Sales Performance Dashboard (Power BI)

An interactive Power BI report analysing sales for **360 orders across 4 countries and 40 products (January – June 2024)**. It combines custom DAX measures, country, product and monthly views, and a country slicer in a one-page executive dashboard.

## Business Questions

- How much did the business sell, and how did sales move month by month?
- Which countries and products drive the most sales?
- How many customers are active, and how much does each one spend?
- What share of orders are high value, and how does performance compare across countries?

## Dataset

- **Records:** 360 orders from 115 active customers
- **Period:** January – June 2024
- **Coverage:** 4 countries, 40 products
- **Structure:** Sales table linked to customer and product tables (5 product categories: Electronics, Beauty, Sports, Home, Clothing)
- **Key fields:** OrderID, OrderDate, CustomerID, Country, Category, ProductName, Quantity, SalesAmount
- **Note:** Customer names and emails are placeholder values, so no real personal data is included
- **Source:** Kaggle
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
| Active Customers | Distinct count of customers who placed orders |
| Sales per Customer | Total Sales divided by Active Customers |
| High Value Orders % | Share of orders with a sales amount above 1,000 |
| Avg Units per Order | Units sold divided by number of orders |
| Average Order Value | Total Sales divided by number of orders |
| Sales Share % | Each country's share of total sales across all countries |
| Country Rank | Rank of each country by Total Sales |

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

*Total sales: 249,315 from 360 orders. Average order value: 692.54. Average of 3.0 units per order.*

1. **The UK wins on volume, while Canada and India win on order size.** The UK leads with 34.8% of sales (86,880) from 136 orders and 44 customers. Canada has only 70 orders yet ranks second with 23.2% of sales, because its average order value is the highest at 825 (UK: 639, US: 612).
2. **A quarter of orders produce over half of sales.** The 97 high-value orders (above 1,000) are 26.9% of all orders but 56.7% of total sales. Canada has the largest share of high-value orders (37.1%), followed by India (31.3%).
3. **Electronics is the top category in every country.** It brings in 29.8% of sales (74,267), well ahead of Beauty (20.0%). Sales are also concentrated in a few products: the top 10 of 40 products generate 51.3% of sales, with Product_24 alone at 7.8%.

Sales are strongest in March (52,092) and June (51,826) and weakest in May (33,712). The peaks come from more orders rather than bigger ones.

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
