# TATA E-Commerce Sales Dashboard

An interactive Power BI dashboard that analyzes e-commerce sales across states, categories, payment modes, and time to understand revenue, profit, and customer buying behavior.



![Dashboard Overview](images/dashboard-overview.png)



## Problem Statement
Understand which states, product categories, and payment modes drive sales and profit, and find the months and sub-categories where profit is weak.

## Dataset
- Source: [Kaggle / other]
- Size: [X rows]
- Fields: Order date, state, city, category, sub-category, customer name, payment mode, amount, profit, quantity

## Tools Used
- Power BI Desktop
- DAX (measures)
- Power Query (data cleaning)
- Data modeling and visualization

## Key Metrics
| Metric | Value |
|---|---|
| Total Sales | 438K |
| Total Profit | 37K |
| Profit Margin | ~8.4% |
| Total Quantity Sold | 5,615 |

## Dashboard Features
- KPI cards for sales, profit, quantity, and AOV
- Sales by state
- Quantity share by category (donut chart)
- Quantity share by payment mode (donut chart)
- Monthly profit trend
- Profit by sub-category
- Top customers by amount
- Quarter slicer and city filter

## Key Insights
- Maharashtra is the top state by sales, followed by Madhya Pradesh and Uttar Pradesh
- Cash on Delivery is the most used payment mode (44%), followed by UPI (21%), Debit Card (13%), Credit Card (12%), and EMI (10%)
- Printers and Bookcases are the most profitable sub-categories
- [Category name] accounts for 63% of total quantity sold
- Profit is negative or near zero in [months], which needs a closer look

## Business Recommendations
- Focus marketing and inventory on top states like Maharashtra
- Promote UPI to reduce COD dependency and return risk
- Invest more in high-profit sub-categories like Printers and Bookcases
- Review pricing and discounts in months with low or negative profit

## Repository Structure
```
├── TATA_ECOMMERCE_SALES_DASHBOARD.pbix
├── images/
│   └── dashboard-overview.png
└── README.md
```

## How to Use
1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Use the quarter and city filters to explore the data

## Author
**Reyaz Ansari**
[GitHub](https://github.com/Reyaz99578) | [LinkedIn](your-linkedin-link)