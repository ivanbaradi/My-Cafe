# My Cafe

This project involves data analysis of customer orders and cafe items. Customers make request to employees such as purchasing and refunding items.

**Tools:** Python, Jupyter, JSON, Pandas, Matplotlib, VS Code

## Purpose

Employees keep track with inventory to see what items are available to let customers know. Generating revenue is also essential to restock goods, pay employees and rent, etc. 

## Data Analysis

**DataFrames** and **graphs** are utilized to track orders and items from the cafe. 

Order numbers are distinctive values to keep track of customers and they may want to propose a request. For instance, when customers wanted a refund from all or certain items, we can refer to their order numbers.

## Instructions

### Important

- Keep track of cafe items and order numbers to prevent errors.

- Keep track of bar graphs. Change `increment` values for appropriate amount of y-ticks *(not too less and too much)*.

### Adding Cafe Items

1. Go to **item.json** file.

2. Go to the bottom of the array.

3. Add a new object that includes the item's name, type, price, and availability count.

### Purchasing Cafe Items

1. Go to **main.ipynb** file.

2. From that file, go to **Transactions > Purchases**.

3. Set `customer_name` with customer's name.

4. Set `items` with objects including Item IDs, and quantities for purchases.

5. Parameterize them in `cafe_df.purchase()`.

6. Select **Run All** to run all cells and see changes.

### Refunding Cafe Items

1. Go to **main.ipynb** file.


#### For Each Item

2. From that file, go to **Transactions > Refunds > Each Item**.

3. Set `order_num` with customer's order number.

4. Set `items` with objects including Item IDs, and quantities for refunds.

5. Parameterize them in `cafe_df.refund()`.

6. Select **Run All** to run all cells and see changes.

#### For All Items

2. From that file, go to **Transactions > Refunds > All Items**.

3. Set `order_num` with customer's order number.

4. Parameterize it in `cafe_df.refund_all()`.

5. Select **Run All** to run all cells and see changes.