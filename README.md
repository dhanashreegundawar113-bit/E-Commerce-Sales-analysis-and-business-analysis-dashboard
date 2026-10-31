#E-Commerce Sales Analysis & Business Intelligence Dashboard

An interactive BI dashboard that analyzes e-commerce sales performance, profitability, regional trends and customer behavior to support data-driven business decisions.

Live Dashboard:https://dhanashreegundawar113-bit.github.io/E-Commerce-Sales-analysis-and-business-analysis-dashboard/

![Dashboard Screenshot](screenshots/dashboard.png)

## Business Problem

An online retailer wants to understand:
1. What drives revenue and profit?
2. Which categories and regions perform best or worst?
3. When does demand peak, and how should inventory be planned?
4. Which customers are most valuable, and which are at risk of leaving?

## Dataset

- 7,000 orders from Jan 2024 to Dec 2025
- 6 product categories, 5 regions, ~1,800 customers
- Fields: order date, category, region, customer ID, revenue, profit

## Tools & Technologies

| Area | Tools |
|---|---|
| Data analysis | SQL, Python (Pandas, NumPy) |
| Visualization | Power BI / Tableau, Chart.js |
| Dashboard hosting | HTML, CSS, JavaScript, GitHub Pages |
| Techniques | KPI design, trend analysis, RFM segmentation |

## Dashboard Features

- 6 KPIs:Revenue, Profit, Profit Margin, Orders, Average Order Value, Customers
- Filters:by year and region
- Charts: monthly revenue and profit trend, category performance, regional revenue share
- RFM customer segmentation:Champions, Loyal, Promising, At Risk, Lost
- Auto-generated insights that update with the filters

## 🔍 Key Findings

*(Update these with your own results.)*
- Electronics generates the most revenue but has one of the lowest margins.
- Revenue peaks in November and December, driven by holiday demand.
- The top 10% of customers contribute a large share of total revenue.
- Many customers are At Risk or Lost, creating a win-back opportunity.

## 💡 Recommendations

1. Review discounting and sourcing costs for low-margin categories.
2. Increase inventory and marketing spend ahead of Q4.
3. Launch a loyalty program for Champions and Loyal customers.
4. Run win-back email campaigns for At Risk customers.

## 📁 Project Structure

```
E-Commerce-Sales-analysis-and-business-analysis-dashboard/
├── index.html        # Interactive dashboard
├── data/             # Raw and cleaned datasets
├── sql/              # SQL queries for KPIs
├── notebooks/        # Python analysis (EDA, RFM)
├── screenshots/      # Dashboard images
└── README.md
```

## 🚀 How to Run

1. Clone the repository: `git clone https://github.com/dhanashreegundawar113-bit/E-Commerce-Sales-analysis-and-business-analysis-dashboard.git`
2. Open `index.html` in any browser.
