# Amazon-Analysis-Review-
This project is a detailed Excel dashboard analysis of an e-commerce product dataset. It explores product ratings, discounts, pricing patterns, and customer reviews across various product categories.

## Data Source
- Digital Skill Africa (The Incubator Hub)
- Dataset provided during a data analysis training program.
- File analyzed: Amazon Case Study(Excel Format)

## Data Cleaning Actions

- Standardized Product Names
Applied =TRIM(LEFT(B2,FIND(" ",B2,FIND(" ",B2,FIND(" ",B2)+1)+1))) to shorten long product names for pivot charts.

- Proper Case Formatting
Used =PROPER(C2) to format all text fields consistently (e.g., product names, categories).

- Column Hiding
Only Original product name and the column with the Trim function are hidden.

- Category Simplification with Delimiters
Used Excel delimiter tools to split and clean category names for easier grouping and pivoting.

- Converted Currency Text to Numbers
Replaced 13,9,900 to 139,900 using Replace values.

- Discount Calculations
Calculated discount percentage and applied logic: =IF(Discount>=0.5, 1, 0)


## Analysis Tasks
These business questions were answered using PivotTables, charts, helper columns, and calculated fields:

1.  What is the average discount percentage by product category?
2.  How many products are listed under each category?
3.  What is the total number of reviews per category?
4.  Which products have the highest average ratings?
5.  What is the average actual price vs. the discounted price by category?
6.  Which products have the highest number of reviews?
7.  How many products have a discount of 50% or more?
8.  What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?
9.  What is the total potential revenue (Actual Price × Rating Count) by category?
10. How many unique products fall into each price range bucket?
11. How does rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.



KPI Summary (from Excel Dashboard)

Metric	 Value	Insight
Total    Products	1350	Unique products analyzed
Number of Product name and Products ID	1350	Suggests product name and product id duplication; cleaned during processing
Total Potential Revenue	₹ 14B+	Based on price × review count
Average Rating Overall	4.09	Indicates high customer satisfaction
Total Reviews	2,380,431	High engagement from users
Average Discount	47%	Aggressive discounting across most products
Products with ≥50% Discount	602	Nearly half of all products are heavily discounted

