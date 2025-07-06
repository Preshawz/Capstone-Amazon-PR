# Capstone-Amazon-PR
One of my Data Analysis training project, supervised by Incubator Hub

## Project Overview
This project aims to ananlyse the products and customer review data by Amazon company, to generate insights that can guide product improvement, marketing strategies, and customers engagement

### Data Source
The data is an Excel file from Amazon product page

### Data Tools
Excel (Analysis and Visualisation)

### Data Preparation
This stage inlvolved;

1. Data Importing from Access
2. Making a duplicate of data
3. Data Cleaning'
   - Removal of unwanted cloumns
   - Removal of duplicates data by product_id
   - Delimit category column
   - create calculated column

### Exploratory Data Analysis
EDA involved exploring data to answer questions like;

1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category? etc.

### Analysis
This involved inserting a Pivot table
1. Average Discount Percentage by Product Category
•	Rows: main_category
•	Values: Average of discount_pct_clean

2. Number of Products per Category
•	Rows: main_category
•	Values: Count of product_id 

3. Total Reviews per Category
•	Rows: main_category
•	Values: Sum of rating_count_clean

4. Products with Highest Average Ratings
•	Sort the rating column in descending order
•	highlight top values.

6. Average Actual vs Discounted Price by Category
•	Rows: main_category
•	Values: Average of actual_price_clean, discounted_price_clean

7. Products with Highest Number of Reviews
•	Sort rating_count_clean in descending order
•	Manually identify top products

8. Distribution of Product Ratings
•	Rows: rating
•	Values: Count of product_id

9. Total Potential Revenue by Category
•	Rows: main_category
•	Values: Sum of potential_revenue

11. Unique Products per Price Bucket
•	Rows: price_bucket
•	Values: Count of product_id

12. Products with Fewer than 1,000 Reviews
=COUNTIF(rating_count_clean, "<1000") to get the total.

14. Categories with Highest Discounts
o	Rows: category
o	Values: Average of discount_percentage_clean
