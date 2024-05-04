# Restaurant Data Analysis MySQL

## Overview

This project is a comprehensive analysis of restaurant data using MySQL. It involves transforming a provided dataset into a relational database and executing various SQL queries to extract meaningful insights. The tasks cover a wide range of SQL functionalities, including basic SELECT queries, filtering, sorting, aggregate functions, joins, subqueries, date and time functions, data modification, window functions, common table expressions (CTE), and advanced joins.

## Completed Tasks

Below are the tasks completed in this project:

1. **Convert Dataset to SQL Database**:
   - Defined and populated tables for `menu_details` and `order_details` using the provided dataset.

2. **Basic SELECT Queries**:
   - Retrieved all columns from the `menu_items` table.
   - Displayed the first 5 rows from the `order_details` table.

3. **Filtering and Sorting**:
   - Selected the `item_name` and `price` columns for items in the 'Main Course' category, sorted the result by price in descending order.

4. **Aggregate Functions**:
   - Calculated the average price of menu items.
   - Found the total number of orders placed.

5. **Joins**:
   - Retrieved `item_name`, `order_date`, and `order_time` for all items in the `order_details` table, including their respective menu item details.

6. **Subqueries**:
   - Listed the menu items (`item_name`) with a price greater than the average price of all menu items.

7. **Date and Time Functions**:
   - Extracted the month from the `order_date` and counted the number of orders placed in each month.

8. **Group By and Having**:
   - Showed the categories with the average price greater than $15, including the count of items in each category.

9. **Conditional Statements**:
   - Displayed `item_name` and `price`, indicating if the item is priced above $20 with a new column named 'Expensive'.

10. **Data Modification - Update**:
    - Updated the price of the menu item with `item_id = 101` to $25.

11. **Data Modification - Insert**:
    - Inserted a new record into the `menu_items` table for a dessert item.

12. **Data Modification - Delete**:
    - Deleted all records from the `order_details` table where the `order_id` is less than 100.

13. **Window Functions - Rank**:
    - Ranked menu items based on their prices, displaying the `item_name` and its rank.

14. **Window Functions - Lag and Lead**:
    - Displayed the `item_name` and the price difference from the previous and next menu item.

15. **Common Table Expressions (CTE)**:
    - Created a CTE that lists menu items with prices above $15, used the CTE to retrieve the count of such items.

16. **Advanced Joins**:
    - Retrieved the `order_id`, `item_name`, and `price` for all orders with their respective menu item details, including rows even if there is no matching menu item.
