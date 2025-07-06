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

