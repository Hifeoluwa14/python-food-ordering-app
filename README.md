# python-food-ordering-app

### This is a python project to build a food ordering app for a small business.

Here are the functions I created took to achieve the goal

* display_menu: This function create list of products and prices
* user_choice: This function uses a while loop to accept user's input and only stops loop until a correct input has been inputted.
* get_quantity: This function uses a while loop to accept user's input for quantity of item the user would purchase
* get_item_name: This function uses the output from the user_choice to determine the item being purchased.
* get_item_price: This function uses the output from the user_choice function to determine the price of item being purchased
* calculate_total_price: This does the simple job of using the output from item price and quantity to determine the price of the purchase for that particular item.
* place_order: This function uses the output from display_menu, get_item_name, quantity and calculate_total_price to process the order by adding it to cart. It uses a while loop to keeping asking for order until user decides to check out.
* check_out: This function display receipts from purchase.
* food_ordering_app: This function runs the processing using the check out and place_order function
