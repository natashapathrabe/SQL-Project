# Project Overview:

This SQL project is designed to manage and analyze data for a pizza store. The database is made up of four main tables: **order_details**, **pizzas**, **orders**, and **pizza_types**. Each table stores a specific type of information related to the store's daily operations, such as customer orders, pizza details, and menu items. Together, these tables help organize the data and make it easier to perform different types of business analysis.

Below is a brief explanation of each table and its columns:

### 1. **order_details:**

* **order_details_id:** A unique ID assigned to each record in the order details table.
* **order_id:** Refers to the ID in the **orders** table and connects each record to a particular customer order.
* **pizza_id:** Refers to the ID in the **pizzas** table and identifies the pizza that was ordered.
* **quantity:** Shows how many pizzas of the selected type were ordered.

### 2. **pizzas:**

* **pizza_id:** A unique ID for every pizza available in the store.
* **pizza_type_id:** Links each pizza to the **pizza_types** table.
* **size:** Represents the size of the pizza, such as Small, Medium, or Large.
* **price:** The selling price of the pizza.

### 3. **orders:**

* **order_id:** A unique ID for every customer order.
* **date:** The date on which the order was placed.
* **time:** The time when the order was placed.

### 4. **pizza_types:**

* **pizza_type_id:** A unique ID for each pizza type.
* **name:** The name of the pizza, such as Margherita or Pepperoni.
* **category:** The category of the pizza, for example, Vegetarian or Non-Vegetarian.
* **ingredients:** A list of ingredients used to prepare the pizza.

# Relevance to a Pizza Sales Store Manager:

This SQL project helps a pizza sales store manager understand the store's performance by analyzing different types of business data. Using SQL queries, managers can gain useful insights that support better decision-making and improve the overall efficiency of the store.

* **Sales Analysis:** By analyzing data from the **order_details** and **pizzas** tables, managers can identify the best-selling pizzas, compare sales across different pizza sizes, and calculate the revenue generated from each product.

* **Inventory Management:** The **pizza_types** table provides details about pizza ingredients, helping managers plan inventory more effectively. This ensures that popular ingredients are always available while reducing unnecessary stock and waste.

* **Customer Preferences:** Information from the **orders** and **pizzas** tables allows managers to understand customer buying patterns. This helps in updating the menu, introducing new pizzas, or promoting customer favorites.

* **Operational Efficiency:** The **date** and **time** columns in the **orders** table help identify peak business hours. Managers can use this information to schedule employees efficiently and provide faster customer service during busy periods.

* **Marketing Insights:** The database can also support marketing decisions by identifying popular pizzas and low-sales days. Managers can create special offers, discounts, or promotional campaigns to increase sales and attract more customers.

# Conclusion:

This SQL project is more than just a database for storing information. It is a valuable business analysis tool that helps managers understand sales trends, customer preferences, inventory requirements, and daily operations. By using SQL queries to analyze the stored data, managers can make informed business decisions that improve customer satisfaction and increase profitability.

Overall, this project demonstrates how SQL can be used to solve real-world business problems. It serves as a practical example for students, aspiring data analysts, and business owners who want to learn how data can support smarter business decisions.
