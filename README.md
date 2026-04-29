📊 E-commerce Profitability Analysis

📌 Overview

This project analyzes an e-commerce dataset to identify the key drivers of low profitability despite strong sales performance.

The analysis focuses on how discount strategies, shipping costs, and pricing decisions impact overall margins and lead to loss-making transactions.

🎯 Business Problem

The company generates high sales volume but operates at very low profit margins, with a significant share of transactions becoming unprofitable.

The goal was to identify:

Why profitable sales turn into losses
Which factors drive unprofitability
How to optimize pricing and discount strategies

🧹 Data Preparation

Data preparation was performed in MySQL, where raw transactional data was cleaned, structured, and enhanced with calculated fields (e.g., delivery time).
The processed dataset was then used in Power BI to build analytical models, KPIs, and interactive dashboards.


SalesOrdersProject/
│
├─ README.md ← Project description (this file)
├─ SalesOrdersOriginalSet.csv ← Original dataset
└─ schema.sql ← Table schema with data types (after data clining)
```

🧠 Key Insights

🔴 1. Discounts are the primary driver of losses
Profitability turns negative beyond ~20% discount
Over $10K in losses driven by excessive discounting
Discounts often exceed sustainable (break-even) levels

🚚 2. Shipping costs significantly reduce profitability
Reduce margins by 11 percentage points
Turn ~40% of orders unprofitable
Higher shipping costs strongly increase loss risk

⚠️ 3. Two distinct loss drivers identified
1. Excessive discounting
Discounts exceed break-even threshold
Directly turn profitable orders into losses
2. Structural pricing issues
~15% of products are unprofitable even at 0% discount
Indicates pricing or cost structure problems

🌍 4. Losses are concentrated
Specific countries and product categories contribute disproportionately to losses

💡 Solution & Recommendations

A differentiated strategy is required:

✅ Optimize discount policies
Reduce discounts above break-even levels
Introduce discount thresholds

⚠️ Adjust pricing for structurally unprofitable products
Increase prices where feasible
Reassess cost structure

📌 Align pricing with margins
Avoid applying high discounts to low-margin products

📊 Dashboard Overview

The project includes a multi-page Power BI dashboard:

1. Business Performance Overview
Sales, profit, margin, and loss ratios
Identifies overall profitability issues




📚 Sources

- Original dataset: [Kaggle](https://www.kaggle.com/datasets/thuandao/superstore-sales-analytics)
  
- Please refer to the Kaggle page for license and usage terms. Use responsibly.


