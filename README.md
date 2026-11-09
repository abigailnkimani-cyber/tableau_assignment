# Olist E-Commerce Sales Dashboard

An interactive Tableau dashboard analysing sales on the Olist Brazilian e-commerce dataset, covering revenue trends, product categories, payment methods and customer ordering behaviour.


## Dashboard preview

![Sales Overview](screenshots/sales-overview.png)

## Dataset

Brazilian E-Commerce Public Dataset by Olist (orders, order items, payments, products, customers and category translations), joined in Tableau. Prices and payment values are in Brazilian reais (R$).

## What's in the workbook

| Sheet | Chart type | What it shows |
|---|---|---|
| Top 10 categories | Bar | Highest-revenue product categories |
| Revenue by Month Trend | Line | Monthly revenue, with a Black Friday 2017 annotation |
| Orders by Customer State | Map | Order volume by Brazilian state |
| Revenue vs Order by month | Dual axis | Revenue and order count together |
| Price vs Freight | Scatter | Relationship between item price and freight cost |
| Freight cost as a share of price | Bar (calculated field) | Freight burden by category |
| % Payment value by payment type | Pie | Share of payment value by method |
| Revenue by payment type | Stacked area | Payment method mix over time |
| Order by weekday and hour | Heatmap | When customers place orders |
| Month on Month Revenue growth | Table calculation | Percent change in revenue versus the previous month |

The **Sales Overview** dashboard combines the main sheets into one view.

## Key findings

- Revenue peaked in November 2017 (Black Friday), then settled into a plateau through 2018.
- Credit card is the dominant payment method, followed by boleto.
- Orders are highest on weekday afternoons and evenings and fall off late on weekends.
- [Add one or two findings of your own, for example from the category or state charts.]

## Notes

Payment value totals are higher than the revenue line chart because payment value includes freight and instalment charges, while the revenue chart sums item prices only.

## Files

- `olist-dashboard.twbx`: Tableau packaged workbook

## Tools

Tableau Desktop / Tableau Public
