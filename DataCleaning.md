Sales Orders Dataset

A refined transactional dataset containing detailed order, customer, product, and shipping information. Prepared in MySQL Workbench, ready for analytics, visualization, and business intelligence workflows.

Dataset Overview
Orders & Customers: Track order dates, shipping dates, shipping modes, customer names, segments, and geographic data.
Products & Sales: Includes product categories, sub-categories, quantities, sales, discounts, profits, and shipping costs.
Performance Metrics: Calculated delivery_days for shipping efficiency; region converted to text for categorical analysis.
Prioritization: Order priority levels (High, Medium, Low, Critical) included.

Schema Snapshot
Column	Type	Description
order_id	TEXT	Unique order identifier
order_date	DATETIME	Date order was placed
ship_date	DATETIME	Date order was shipped
ship_mode	TEXT	Shipping method
customer_name	TEXT	Customer name
segment	TEXT	Customer segment
state	TEXT	Customer state
country	TEXT	Customer country
market	TEXT	Market region
region	TEXT	Regional classification
product_id	TEXT	Unique product identifier
category	TEXT	Product category
sub_category	TEXT	Product sub-category
product_name	TEXT	Full product name
sales	DECIMAL(10,2)	Sales amount
quantity	INT	Number of items ordered
discount	DECIMAL(5,2)	Discount applied
profit	DECIMAL(10,2)	Profit earned
shipping_cost	DECIMAL(10,2)	Shipping cost
order_priority	TEXT	Order priority
year	INT	Order year
delivery_days	INT	Days between order and ship dates

Key Features
Refined Data Types: Financial fields (sales, profit, discount, shipping_cost) are stored as DECIMAL to maintain precision.
Calculated Fields: delivery_days allows easy analysis of shipping performance and logistics efficiency.
Categorical Consistency: region has been converted to text for easier grouping, filtering, and visualization.
Business Insights Ready: Suitable for analyzing sales trends, customer segmentation, product performance, and shipping efficiency.