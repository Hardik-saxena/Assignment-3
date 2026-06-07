# Superstore Advanced SQL Analysis

## Objective

Analyze Superstore sales data using SQL Subqueries, Common Table Expressions (CTEs), Window Functions, and JOIN operations to generate customer sales insights.

## Dataset

Superstore Dataset from Kaggle

## Tasks Performed

### Data Setup

* Imported dataset into `superstore_raw`
* Created normalized tables:

  * customers
  * orders
  * products
* Inserted data using `SELECT DISTINCT`

### SQL Analysis

* Subqueries

  * Orders with sales above average
  * Highest sales order per customer

* CTEs

  * Total sales per customer
  * Customers with above-average sales

* Window Functions

  * Customer ranking
  * Row numbers within customer orders
  * Top 3 customers by sales

### Final Query

* JOIN + CTE + Window Function
* Customer Name
* Total Sales
* Customer Rank

### Business Insights

* Top 5 customers
* Bottom 5 customers
* Single-order customers
* Above-average sales customers
* Highest order value per customer

## Technologies Used

* Python
* Pandas
* SQLite
* SQL
* Kaggle Notebook

## Output

* SQL Queries
* Query Results
* Customer Sales Insights
* Advanced SQL Analysis

