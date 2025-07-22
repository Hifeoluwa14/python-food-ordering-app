# python-food-ordering-app

### This is a python project to build a food ordering app for a small business.

Here are the functions I created took to achieve the goal

* display_menu: This function create list options of products, prices, check-out and cancel order.
* from IPython.display import clear_output
* user_choice: This function uses a while loop to accept user's input and only stops loop until a correct input has been inputted.
* get_quantity: This function uses a while loop to accept user's input for quantity of item the user would purchase
* get_item_name: This function uses the output from the user_choice to determine the item being purchased.
* get_item_price: This function uses the output from the user_choice function to determine the price of item being purchased
* calculate_total_price: This does the simple job of using the output from item price and quantity to determine the price of the purchase for that particular item.
* place_order: This function uses the output from display_menu, get_item_name, quantity and calculate_total_price to process the order by adding it to cart. It uses a while loop to keeping asking for order until user decides to check out.
* payment: This function display total cost of order and ask if a user would like to make payment or not
* payment_check: This communicate with payment partner like paypal to know if the payment was successful or not.
* payment_retry: This ask customer if they will like to retry making payment or not if the payment was unsuccessful
* check_out: This function runs other functions to determine if order was successful after payment was made or customer di=ecided to cancel. It display receipts from purchase if payment was successful. However in this case we set payment as successful to permit our code to run without error
* food_ordering_app: This function runs the processing using the check out and place_order function
* check_out_declined: This is an alternate function that say payment was unsuccessful.
* food_ordering_declined: In this case we wanted to understand the run of event when payment was unsuccessful.

The code file is attached to this repository in a form of jupyter notebook.
