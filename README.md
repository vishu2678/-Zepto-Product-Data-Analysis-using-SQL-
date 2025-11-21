# -Zepto-Product-Data-Analysis-using-SQL-
This project focuses on cleaning, exploring, and analyzing product inventory data from Zepto using SQL. 

Dataset Source

The dataset used in this project is the Zepto product dataset from Kaggle. It includes information such as category, name, MRP, discount percentage, discounted selling price, available quantity, weight in grams, and stock availability.

Tools and Environment:

PostgreSQL
pgAdmin4
Kaggle dataset

Project Workflow

1. Data Extraction
The product dataset from Kaggle was imported into PostgreSQL using pgAdmin4.

2. Data Exploration

The following exploratory checks were performed:

Total number of rows
Sample preview of data
Detection of null values
Listing of distinct product categories
Stock status comparison (in stock vs out of stock)
Identification of duplicate product names

3. Data Cleaning

The cleaning process included:
Finding and removing products with price equal to zero
Converting pricing units from paise to rupees
Validating the dataset after updates

Business Questions Answered

1.Top 10 best-value products based on highest discount percentage.

2.Products with high MRP but currently out of stock.

3.Estimated revenue per category calculated from discounted selling price and available quantity.

4.Products with MRP greater than 500 and discount less than 10 percent.

5.Top five categories offering the highest average discount percentage.

6.Products above 100 grams sorted by best price per gram.

7.Categorization of products into Low, Medium, and Bulk based on weight.

8.Total inventory weight calculated per category.

Highlights:

Complete SQL workflow including extraction, exploration, cleaning, and analysis.
Focus on real-world retail and e-commerce insights.
Emphasis on revenue estimation, discount evaluation, and inventory management.
Strengthens skills in data preprocessing and analytical SQL queries.
