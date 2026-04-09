Grocery Store Management System (SQL Project)

Overview :

This project simulates a **real-world grocery store business** using SQL by designing a structured relational database and performing data analysis to extract meaningful insights.

It helps in understanding:

* Customer behavior
* Product performance
* Sales trends
* Supplier contribution
* Employee performance

The project demonstrates how SQL can be used for **data-driven decision making in retail businesses**. 

---

Objectives

* Design a relational database for grocery store operations
* Manage data for customers, products, orders, suppliers, and employees
* Perform SQL-based analysis to extract business insights
* Identify patterns in sales, customers, and inventory
* Simulate real-world business scenarios using SQL

---

Database Schema & Relationships

### Entity Relationships:

* One-to-Many → Supplier → Products
* One-to-Many → Category → Products
* One-to-Many → Product → Order Details
* One-to-Many → Order → Order Details
* One-to-Many → Customer → Orders
* One-to-Many → Employee → Orders

---

Tables Used

* Customers
* Products
* Categories
* Suppliers
* Orders
* Order_Details
* Employees

---

SQL Concepts Covered

* Joins (INNER, LEFT, RIGHT)
* Aggregations (SUM, AVG, COUNT)
* GROUP BY & HAVING
* Subqueries
* Data Cleaning (`STR_TO_DATE`)
* Complex Queries for business insights

---

Analysis & Insights

---

 Customer Insights

Key Findings:

* Total unique customers: **156**
* Strong customer base → good engagement
* Few customers place more orders (loyal customers exist)
* Example: One customer placed **7 orders (highest)**
* Revenue is concentrated among top customers

Recommendations:

* Introduce **loyalty programs**
* Provide **personalized offers**
* Target low-frequency customers

---

Product Performance

Key Findings:

* Uneven product distribution across categories
* Clear **premium vs budget categories**
* Some products are **fast-moving (high demand)**
* High revenue ≠ always high quantity
* Supplier dependency exists

Recommendations:

* Maintain stock for high-demand products
* Balance product distribution
* Focus on high-margin products
* Diversify suppliers

---

Sales & Order Trends

Key Findings:

* Total orders: **300** → stable business
* Avg order value: **~2153**
* Seasonal trends observed
* Peak demand on specific dates/months
* Weekdays (210 orders) > Weekends (90 orders)

Recommendations:

* Run promotions during low-sales periods
* Improve weekend engagement
* Use seasonal trends for planning
* Introduce combo offers

---

Supplier Contribution

Key Findings:

* Total suppliers: **5 (limited)**
* One supplier dominates inventory
* Revenue heavily depends on few suppliers
* Pricing varies across suppliers

Recommendations:

* Add more suppliers
* Reduce dependency risk
* Negotiate better pricing
* Strengthen supplier relationships

---

 Employee Performance

Key Findings:

* Total employees: **10 (all active)**
* Some employees handle more orders
* Sales contribution varies
* Some employees manage high-value orders

 Recommendations:

* Reward top performers
* Train low performers
* Balance workload

---

## 🧾 Order Details Analysis

 Key Findings:

* Higher quantity → higher total price
* Some products bought in bulk
* Price variation exists (offers/discounts)

 Recommendations:

* Promote bulk purchase discounts
* Identify fast-moving items
* Maintain pricing consistency

---

Business Recommendations

* Focus on high-value customers
* Maintain stock for fast-moving products
* Reduce supplier dependency
* Improve weekend sales
* Train employees
* Apply smart pricing strategies

---

Key Outcome

* Identified top customers, products, and suppliers
* Discovered seasonal sales patterns
* Extracted actionable business insights
* Demonstrated strong SQL + analytical skills

---

 Challenges Faced

* Data cleaning (date format issues using `STR_TO_DATE`)
* SQL safe update mode
* Designing schema relationships
* Writing complex joins
* Aggregation and grouping
* Converting raw data into insights

---

 Project Structure

```bash
Grocery-SQL-Project/
│── schema.sql
│── data.sql
│── queries.sql
│── README.md
```

---

Conclusion

This project successfully demonstrates how SQL can be used to **analyze business performance, understand customer behavior, and support decision-making** in a retail environment.
