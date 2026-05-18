# Sales Insights Dashboard — Power BI

---

## Project Overview

This project is an interactive Power BI dashboard built to provide automated 
sales insights for AtliQ Hardware — a company that sells electrical goods 
across multiple cities in India.

The dashboard has 3 pages:
- **Revenue Analysis** — Revenue trend, top 5 customers, top 5 products, revenue by city
- **Profit Analysis** — Profit by market, profit contribution %, detailed customer table
- **Performance Insights** — City wise profit, zone wise breakdown, customer type analysis

### Tools Used
- Power BI
- Power Query
- DAX
- SQL
- Excel

### Data Model
Used **Star Schema** with 5 tables:

| Table | Type | Details |
|-------|------|---------|
| Transactions | Fact Table | product_code, customer_code, market_code, order_date, sales_qty, sales_amount |
| Customers | Dimension | customer_code, customer_name |
| Products | Dimension | product_code, product_type |
| Markets | Dimension | market_code, market_name, zone |
| Date | Dimension | date, year, month_name |

---

## Key Insights

- **Bhubaneshwar** has the highest profit contribution despite not being the 
  highest revenue city — showing strong operational efficiency
- **Lucknow** shows negative profit — meaning the company is spending more 
  than it is earning there — needs immediate business attention
- **Top customer (Electricalsara Stores)** contributes nearly half of total 
  revenue — this is a high dependency risk for the business
- **Central zone** contributes the highest profit compared to North and South zones
- **Brick and Mortar** customers contribute more profit than E-Commerce customers
- Revenue showed a declining trend from March to June 2020 — likely due to 
  COVID-19 lockdown impact

---

## Business Impact

- Dashboard provides real-time sales insights so the sales team can make 
  faster and better decisions
- Helped identify weak markets like Lucknow and Surat where cost saving 
  actions can be taken — targeting **10% cost reduction**
- Eliminated manual data gathering process — saving the sales team 
  **20% of their working time** which can now be used for actual analysis
- Enabled the Sales Director to get answers to key business questions 
  instantly without depending on the data team every time

---

## Screenshots

### Revenue Analysis
![Image_Alt](https://github.com/Suriyapriya-S/Sales-Insights-Dashboard/blob/main/revenue_analysis.png)

### Profit Analysis
![Image_Alt](https://github.com/Suriyapriya-S/Sales-Insights-Dashboard/blob/main/profit_analysis.png)

### Performance Insights
![Image_Alt](<img width="1379" height="732" alt="Screenshot 2026-05-18 143408" src="https://github.com/user-attachments/assets/04ee5208-be2a-4da0-b31d-d16d859be6dc" />)


---


