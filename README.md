# phyton_db_example
For course DE

## Here is the given list of purchases:

```
purchases = [
    {"item": "apple", "category": "fruit", "price": 1.2, "quantity": 10},
    {"item": "banana", "category": "fruit", "price": 0.5, "quantity": 5},
    {"item": "milk", "category": "dairy", "price": 1.5, "quantity": 2},
    {"item": "bread", "category": "bakery", "price": 2.0, "quantity": 3},
]
```

* item — name of the product,
* category — product category,
* price — price per unit,
* quantity — number of units purchased at once.

## You need to implement several functions for data analysis:

* **total_revenue(purchases)**: Calculate and return the total revenue (price × quantity for all entries).
* **items_by_category(purchases)**: Return a dictionary where the key is the category, and the value is a list of unique items in that category.
* **expensive_purchases(purchases, min_price)**: Return all purchases where the price of the product is greater than or equal to min_price.
* **average_price_by_category(purchases)**: Calculate the average price of products for each category.
* **most_frequent_category(purchases)**: Find and return the category in which the largest number of units was purchased (consider the quantity field).

## Your script should output a report for each of the following points:

* Total revenue.
* List of items by category.
* List of purchases where the price exceeds a given value.
* Average price of products by category.
* The category with the highest number of purchased items.
* The output format should follow the template:

```
Total revenue: 21.0  
Items by category: {'fruit': ['apple', 'banana'], 'dairy': ['milk'], 'bakery': ['bread']}  
Purchases costing more than 1.0: [{'item': 'apple', 'category': 'fruit', 'price': 1.2, 'quantity': 10}, {'item': 'milk', 'category': 'dairy', 'price': 1.5, 'quantity': 2}, {'item': 'bread', 'category': 'bakery', 'price': 2.0, 'quantity': 3}]  
Average price by category: {'fruit': 0.85, 'dairy': 1.5, 'bakery': 2.0}  
Category with the highest number of purchased items: fruit 

```
