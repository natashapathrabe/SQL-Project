# 🍕 Pizza Sales SQL Analysis Project

## 📌 Project Overview

This SQL project is designed to manage and analyze data for a pizza store. The database consists of four main tables:

- order_details
- pizzas
- orders
- pizza_types

Each table stores different information about the pizza store, making it easier to analyze sales, customer preferences, inventory, and business performance.

---

## 📂 Database Schema

### 1. order_details

| Column | Description |
|---------|-------------|
| order_details_id | Unique ID for each order detail |
| order_id | Links to the orders table |
| pizza_id | Links to the pizzas table |
| quantity | Number of pizzas ordered |

### 2. pizzas

| Column | Description |
|---------|-------------|
| pizza_id | Unique ID for each pizza |
| pizza_type_id | Links to the pizza_types table |
| size | Pizza size (Small, Medium, Large) |
| price | Selling price |

### 3. orders

| Column | Description |
|---------|-------------|
| order_id | Unique order ID |
| date | Order date |
| time | Order time |

### 4. pizza_types

| Column | Description |
|---------|-------------|
| pizza_type_id | Unique pizza type ID |
| name | Pizza name |
| category | Pizza category |
| ingredients | Ingredients used |

---

# 📊 Business Use Cases

### Sales Analysis
- Identify best-selling pizzas
- Calculate revenue
- Compare pizza sizes
- Analyze sales trends

### Inventory Management
- Track ingredient demand
- Reduce food waste
- Improve stock planning

### Customer Preference Analysis
- Find popular pizzas
- Understand customer ordering patterns
- Support menu improvements

### Operational Efficiency
- Identify peak ordering hours
- Improve staff scheduling
- Reduce customer waiting time

### Marketing Insights
- Discover low-sales days
- Plan promotional offers
- Increase customer engagement

---

# 🛠 Tools Used

- SQL
- MySQL
- Joins
- Aggregate Functions
- GROUP BY
- ORDER BY
- Subqueries
- Common Table Expressions (CTEs)

---

# 📈 Key SQL Analysis Performed

- Total Orders
- Total Revenue
- Best Selling Pizza
- Most Ordered Pizza Category
- Revenue by Pizza Size
- Daily Order Trend
- Hourly Sales Analysis
- Top 5 Pizzas by Revenue
- Category-wise Sales
- Average Pizzas Ordered per Day

---

# 🎯 Conclusion

This SQL project demonstrates how relational databases can be used to solve real business problems. By analyzing sales, customer behavior, and operational data, store managers can make informed decisions that improve profitability and customer satisfaction.
