# Superstore Sales Analysis — Power BI

A four-page interactive Power BI report on the Sample Superstore retail dataset, covering sales, profitability, customers and shipping, with year-over-year comparisons and slicers for Year, Region and Segment.

<img width="2075" height="1200" alt="Superstore_page-0001" src="https://github.com/user-attachments/assets/f5bba5a8-82b6-45cf-a2e8-608caee54a6a" />


## Key findings (2017)

| Metric | Value | vs prior year |
|---|---|---|
| Sales | $733K | ▲ 20.4% |
| Profit | $93K | ▲ 14.2% |
| Profit margin | 12.7% | ▼ 0.7 pts |
| Orders | 1,687 | ▲ 28.3% |
| Avg order value | $435 | ▼ 6.2% |

- **Discounting is destroying margin.** Undiscounted lines earn a 29.9% margin and 1–20% discounts still earn 13.3%, but 21–40% discounts fall to -17.6% and discounts over 40% to -92.5%.
- **Furniture barely breaks even.** It brings in $215K of sales at a 1.4% margin. Tables lose $8,141 (-13.4%) and Bookcases lose $584.
- **Office Supplies is the growth engine.** Sales rose 33.8% to $246K at a 16.1% margin, with Appliances up 64.8%.
- **Growth came from volume, not basket size.** Orders grew faster than sales, so average order value dropped 6.2%.
- **The customer base is almost entirely repeat.** 682 of 693 customers were returning and only 11 were new.
- **18.7% of order lines lose money**, which ties back to the discount bands above.

## Report pages

### 1. Overview
Headline KPIs with prior-year deltas, monthly sales vs prior year, sales by category, state and segment, and profit by sub-category.

<img width="2075" height="1200" alt="Superstore_page-0001" src="https://github.com/user-attachments/assets/278e6ba4-89cb-4608-af4c-70ebe7de6646" />


### 2. Products
Sales vs margin scatter by sub-category, profit margin by discount band, a category and sub-category matrix with YoY growth, and the top 10 products by sales.

<img width="2075" height="1200" alt="Superstore_page-0002" src="https://github.com/user-attachments/assets/a13dc50d-03fe-4459-8aa5-b963bd6763ec" />


### 3. Customers
Customer count, sales and orders per customer, new vs returning customers by quarter, sales and profit by region, top 10 customers and a state league table.

<img width="1312" height="732" alt="Superstore_page-0003" src="https://github.com/user-attachments/assets/a052a16f-c80b-42f3-b1a8-54a097b5db9d" />


### 4. Shipping
Orders by weekday and ship mode, average days to ship by mode (3.9 days overall, from 0.1 for Same Day to 5.0 for Standard Class), ship mode mix by segment, and monthly orders vs prior year.

<img width="2075" height="1200" alt="Superstore_page-0004" src="https://github.com/user-attachments/assets/906e23b0-a06c-479a-8e93-ecb7b56df00f" />


## Features

- Page navigation buttons across all four pages
- Slicers for Year, Region and Segment synced across pages
- Time-intelligence measures for prior-year sales, orders and YoY change
- Conditional colouring for loss-making products and discount bands
- Bubble maps for sales and customers by state



## How to open it


No Power BI? Open `Superstore.pdf` for a static view of every page.

## Data

Sample Superstore: order-line data for a fictional US retailer, with order and ship dates, customer, segment, region and state, product category and sub-category, sales, quantity, discount and profit.

## Tools

Power BI Desktop · Power Query · DAX

