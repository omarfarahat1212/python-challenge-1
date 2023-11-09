# README.md

## **Overview**

This Python script implements a simple food truck menu and order taking system. It allows customers to browse and order items from a variety of categories, including snacks, meals, drinks, and desserts. The script also calculates the total cost of the order and prints it out to the console.

## **Usage**

To use the script, simply run it in a terminal or command prompt. The script will prompt the customer to select a menu category, then select an item from the category. The customer can then specify the quantity of the item they would like to order. The script will then add the item to the customer's order list and ask if they would like to order anything else. Once the customer is finished ordering, the script will calculate the total cost of the order and print it out to the console.

## **Example**

```python
$ python menu.py

Welcome to the variety food truck.
From which menu would you like to order?

1: Snacks
2: Meals
3: Drinks
4: Dessert

Type menu number: 2

You selected Meals

What Meals item would you like to order?

Item   | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49

Please type menu number: 1

How many of Burrito would you like to order? 2

Would you like to keep ordering? (Y)es or (N)o y

What Meals item would you like to order? 4

How many of Pad Thai would you like to order? 1

Would you like to keep ordering? (Y)es or (N)o n

Thank you for your order!

This is what we are preparing for you.

Item name         | Price  | Quantity
------------------|--------|----------
Burrito           | $4.49  | 2
Pad Thai          | $6.99  | 1

Total cost: $15.96

```

## **Code Structure**

The script is divided into the following main sections:

1. **Menu dictionary:** This section defines a dictionary that contains the food truck's menu items. The dictionary is organized by category, with each category containing a list of menu items.
2. **Order list:** This section creates a list to store the customer's order.
3. **Order taking loop:** This loop prompts the customer to select menu items and add them to their order list. The loop continues until the customer is finished ordering.
4. **Order printing loop:** This loop prints out the customer's order and calculates the total cost.

## **Recomendation**

- Add error handling: The code does not currently handle any errors, such as invalid quantities. Adding error handling would make the code more robust and user-friendly.
- Use a database: The code currently stores the menu items in a dictionary. However, using a database would be more efficient and scalable for a larger food truck menu.
- Add support for discounts and promotions. You could allow customers to apply coupons and discounts to their orders. You could also offer special promotions, such as buy-one-get-one-free deals or happy hour specials.


## **Conclusion**

This Python script provides a simple but effective way to implement a food truck menu and order taking system. It can be easily customized to meet the specific needs of your food truck.

