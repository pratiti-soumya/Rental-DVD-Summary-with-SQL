# Rental DVD Data Exploration – SQL Project

I explored a relational DVD rental database using advanced SQL queries. I extracted meaningful insights into customer behavior, rental trends, and category performance using structured query techniques.

---

## Project Objectives

- Analyze **rental durations** of family-friendly movies by category using quartiles
- Compare **monthly rental activity across stores**
- Identify the **top 10 paying customers** in 2007 and analyze their payment behavior
- Track **month-to-month payment differences** using window functions

---

## Key Insights

### 🔹 1. Rental Duration by Category Quartile
Grouped Animation, Children, Classics, Comedy, Family, and Music categories into **quartiles** using rental duration, revealing:
- Animation and Children films cluster in **short-duration quartiles**
- Classics and Family appear more in **longer-duration quartiles**

### 🔹 2. Monthly Rentals by Store
- July 2005 saw the **highest rental counts** at both stores
- Store 2 slightly outperformed Store 1 overall, especially mid-2005

### 🔹 3. Top Customers by 2007 Payment
- Analyzed **top 10 customers** by total payment in 2007
- Peak spending occurred in **March and April**, possibly due to promotions

### 🔹 4. Monthly Payment Differences
- Used `LAG()` to calculate **month-to-month changes** in customer payments
- Eleanor Hunt had the **largest monthly increase** (+$64.87)
- Marion Snyder had the **largest drop** (-$80.83)

---

## 🛠️ SQL Techniques Used

**Skills demonstrated:** SQL, Window Functions, CTEs, Aggregation, Subqueries, Filtering, Joins, Date Functions, Data Analysis, PostgreSQL Syntax

---

## 📂 Files Included

| File | Description |
|------|-------------|
| [📄 SQL Queries - Pratiti Soumya.txt](https://github.com/pratiti-soumya/Rental-DVD-Summary-with-SQL/blob/master/SQL%20Queries-%20Pratiti%20Soumya.txt) | Full SQL queries with comments |
| [📘 SQL Project - Rental DVD Data Exploration.pdf](https://github.com/pratiti-soumya/Rental-DVD-Summary-with-SQL/blob/master/SQL%20Project-%20Rental%20DVD%20Data%20Exploration.pdf) | Visual summary of insights with graphs |
| [📊 ERD - dvd-rental-erd-diagram.pdf](https://github.com/pratiti-soumya/Rental-DVD-Summary-with-SQL/blob/master/dvd-rental-erd-diagram.pdf) | Entity Relationship Diagram of the DVD Rental database |

---

## 🔗 Author

**Pratiti Soumya**  
[GitHub Profile](https://github.com/pratiti-soumya)  
[LinkedIn](https://www.linkedin.com/in/pratiti-soumya)

---

## 📌 Acknowledgments

This project was completed as part of the **Udacity Programming for Data Science with Python Nanodegree**.
