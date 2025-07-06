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


## Key Insights from the Dashboard

- High Discount Prevalence: Nearly half of all products (over 600) have discounts of 50% or more, suggesting aggressive price-cutting as a competitive strategy.
- Customer Engagement: The dataset shows over 2.3 million reviews across all products, with an average rating above 4.0, indicating strong user activity and overall product satisfaction.
- Top Performing Products: Products that rank highest in both rating and number of reviews tend to be in electronics and smartphone categories.
- Category Revenue Trends: Categories like Mobiles and Laptops generate significantly more potential revenue based on actual price × review count.

These insights enable stakeholders to make better marketing, pricing, and inventory decisions based on customer feedback, price sensitivity, and product popularity.

## Dashboard Screenshots
## Full Dashboard Overview


![Amazon CS analysis](https://github.com/user-attachments/assets/ef425cd2-5960-4a0c-b004-3f90b1a200a0)

![Amazon CS analysis 2](https://github.com/user-attachments/assets/c0cdce57-942b-4b5b-94d5-1dfb6d5fe5c5)


![Amazon CS analysis 3](https://github.com/user-attachments/assets/7cc44632-3003-4370-9c89-b5f38247e6eb)


![AMZ report 1](https://github.com/user-attachments/assets/54476800-0891-4598-b84c-3305c9d91f93)


![amz 1](https://github.com/user-attachments/assets/83d17b15-e63b-4934-9dad-c3a7125df9f2)


![AMZ 3](https://github.com/user-attachments/assets/d7acbc00-c4ca-4220-b354-3792b6922b47)


![AMZ 4](https://github.com/user-attachments/assets/b7463edd-247f-4f84-a125-0da7b363a2e6)



![Amz 5](https://github.com/user-attachments/assets/7d9b8cc5-bd1d-4cb8-b8ad-1b3d4d95fd62)


## Tools Used
- Pivot Tables
- Bar chart
- column chart
- Helper Columns & Logical Formulas








