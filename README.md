# zepto-pricing-inventory-analysis

📌 Project Overview

This project analyzes Zepto’s e-commerce product catalog to understand pricing behavior, discount effectiveness, and inventory risk. Using SQL, the project identifies where money is locked in inventory, which products consume the most discount budget, and which SKUs should be prioritized for price optimization to maximize revenue.

The goal is to move beyond basic reporting and provide business-driven insights that support pricing, marketing, and inventory decisions.

📂 Dataset
The dataset contains 3,700+ products with the following attributes:
Product Name
Category
MRP
Discounted Selling Price
Discount Percentage
Available Quantity
Weight

This represents a realistic snapshot of Zepto’s grocery and FMCG catalog.

🧰 Tools Used
SQL – Core analysis, business metrics, and aggregations
Excel – Data validation and price normalization
Power BI – Dashboard design for executive reporting

📊 Key Business Metrics
Metric	Value
Total Products	          3,731
Total Stock Units	  14,959
Total Inventory Value	 ₹2,243,080
Highest MRP	         ₹2,600
Maximum Discount Given	₹1,201 on a single product
Inventory Concentration (Top 10 Products)	6.1%


Analysis Performed :

1. Inventory Valuation
Calculated inventory value for each product:
         Inventory Value = Discounted Selling Price × Available Quantity

This revealed how much cash is tied up across Zepto’s catalog.

2. Discount Cost Analysis
Computed the real cost of discounts:
         Discount Cost = (MRP − Selling Price) × Available Quantity

This showed which products are consuming the largest share of Zepto’s promotional budget.

3. Revenue Concentration Risk
Measured what percentage of inventory value is held by the top 10 products.
Result: Only 6.1%, indicating low dependency on a few SKUs and a diversified product mix.

4. Strategic Pricing Prioritization
Created a pricing priority score:
        Priority Score = Selling Price × Stock × (100 − Discount %)

This metric identifies which products would produce the highest revenue increase if discounted.
The top candidates were primarily:

        Cooking oils
        Ghee
        Baby food and breakfast cereals

These are high-value, high-volume, and low-discount products — ideal targets for promotional pricing.

📈 Key Insights
Cooking oils and ghee dominate both inventory value and discount spend
A small set of premium staples controls a large portion of revenue impact
Zepto’s inventory is well diversified with no dangerous product dependency
Strategic discounting on high-value staples can significantly boost revenue

📌 Business Recommendations
Prioritize discounts on high-value staples like oils and ghee
Monitor discount spending to avoid excessive revenue leakage
Use inventory value instead of unit count for stock decisions
Avoid deep discounts on low-impact SKUs
