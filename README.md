# 🍕 Pizza Sales Analysis Using SQL

##  Project Overview

This project analyzes pizza sales data using **SQL** to uncover actionable business insights from transactional sales records. By querying and analyzing sales data, the project identifies revenue trends, customer purchasing behavior, product performance, and operational opportunities that support data-driven decision-making.

The analysis demonstrates practical SQL skills, including **JOINs, aggregate functions, Common Table Expressions (CTEs), subqueries, window functions, and business-oriented reporting** to solve real-world analytical problems.

---

## Project Objectives

* Analyze overall sales performance and revenue generation.
* Calculate key business performance indicators (KPIs).
* Identify top-performing and low-performing pizzas.
* Evaluate sales by pizza category and size.
* Discover customer ordering patterns.
* Analyze daily, weekly, monthly, and hourly sales trends.
* Generate actionable recommendations to improve profitability and operational efficiency.

---

## Technologies Used

* SQL
* MySQL
* MySQL Workbench
* CSV Datasets
* Aggregate Functions
* JOIN Operations
* GROUP BY & HAVING
* CASE Statements
* Common Table Expressions (CTEs)
* Window Functions
* Subqueries

---

## Dataset Information

The project uses four relational datasets that represent pizza sales transactions.

### Tables

| Table             | Description                                       |
| ----------------- | ------------------------------------------------- |
| **orders**        | Stores customer order date and time               |
| **order_details** | Stores quantity of pizzas ordered in each order   |
| **pizzas**        | Contains pizza sizes and prices                   |
| **pizza_types**   | Contains pizza names, categories, and ingredients |

The datasets were imported into MySQL and connected using **primary and foreign key relationships**, enabling efficient querying and analysis.

---

## Business Questions Answered

This analysis answers several business-focused questions, including:

* What is the total revenue generated?
* How many orders were placed?
* What is the average order value?
* Which pizzas generate the highest revenue?
* Which pizzas have the lowest sales?
* Which pizza sizes contribute the most revenue?
* Which pizza categories are most popular?
* What are the busiest days and peak ordering hours?
* What are the monthly sales trends?
* Which pizzas are frequently ordered together?
* What percentage of total revenue comes from each category?
* How can inventory management be optimized?

---

##  Key Insights

* Identified the highest-performing pizzas based on revenue and quantity sold.
* Determined low-performing pizzas that may require pricing or menu optimization.
* Found that larger pizza sizes contributed a significant share of total revenue.
* Identified peak ordering days and hours to support staffing and operational planning.
* Analyzed category-wise performance to understand customer preferences.
* Calculated revenue contribution by pizza category, size, and product.
* Generated business recommendations for improving sales and profitability.

---
<img width="1392" height="787" alt="image" src="https://github.com/user-attachments/assets/a83f3e5b-3464-46ba-98bf-afe9813228ba" />

## Repository Structure

```text
sql-pizza-sales-analysis/
│
├── README.md
├── pizza_sales_queries.sql
├── Pizza_Sales_Report.pdf
├── Presentation.pdf
│
├── Dataset/
│   ├── orders.csv
│   ├── order_details.csv
│   ├── pizzas.csv
│   └── pizza_types.csv
│
├── Images/
│   ├── er_diagram.png
│   ├── revenue_analysis.png
│   ├── top_pizzas.png
│   └── sales_trend.png
│
└── Results/
    └── query_outputs.pdf
```

---

##  Query Results & Visualizations


### Revenue Analysis

```markdown
<img width="1360" height="762" alt="image" src="https://github.com/user-attachments/assets/84eb06ab-9953-4bd0-9690-840ae80eb6e0" />

```

### Top Selling Pizzas

```markdown
<img width="1363" height="775" alt="image" src="https://github.com/user-attachments/assets/16a9f6da-d2ef-4ffe-8151-02beeb124297" />

```

### Sales Trend

```markdown
<img width="1361" height="763" alt="image" src="https://github.com/user-attachments/assets/c51ab7ea-e66a-4473-8ab4-85332d007d46" />

```

---

##  Future Enhancements

* Develop an interactive **Power BI dashboard** connected to the SQL database.
* Automate report generation using scheduled SQL procedures.
* Perform sales forecasting using machine learning models.
* Implement customer segmentation and RFM analysis.
* Optimize SQL queries for improved performance on larger datasets.

---

##  Skills Demonstrated

* SQL
* MySQL
* Relational Database Design
* Data Cleaning
* Data Analysis
* Business Intelligence
* Data Aggregation
* Window Functions
* Common Table Expressions (CTEs)
* Query Optimization
* Analytical Problem Solving

---

##  Author

**Sukhada Kulkarni**

**Aspiring Data Analyst | SQL | Excel | Power BI | Python**

 **GitHub:** https://github.com/your-username

 **LinkedIn:** https://linkedin.com/in/sukhada-kulkarni-81016433a/

---

## Support

If you found this project useful or informative, consider giving it a **⭐ Star** on GitHub. Your support is greatly appreciated!
