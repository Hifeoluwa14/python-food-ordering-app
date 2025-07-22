# Python Food Ordering App  

A *simple command-line food ordering application* designed for small businesses, built with Python. This project demonstrates core functionalities like menu display, order processing, cart management, and payment simulation.

## Features  

- *Interactive Menu Display*: Browse available food items with prices.  
- *Order Management*: Add items to cart, specify quantities, and calculate totals.  
- *Payment Simulation*: Integrates with mock payment processing (e.g., PayPal) and handles success/failure scenarios.  
- *Receipt Generation*: Prints order summaries upon successful payment.  

### Key Functions  

| Function | Description |  
|----------|-------------|  
| display_menu() | Shows the menu, prices, and options (checkout/cancel). |  
| user_choice() | Validates user input for menu selections. |  
| get_quantity() | Prompts for item quantity and validates input. |  
| get_item_name() | Maps user selection to the item name. |  
| get_item_price() | Retrieves the price of the selected item. |  
| calculate_total_price() | Computes the subtotal for an item (price × quantity). |  
| place_order() | Manages the order loop, adds items to cart, and processes checkout. |  
| payment() | Displays the total cost and initiates payment. |  
| payment_check() | Simulates payment verification (success/failure). |  
| payment_retry() | Handles retries for failed payments. |  
| check_out() | Generates a receipt or cancels the order based on payment status. |  
| food_ordering_app() | Main function to run the app workflow. |  

## Usage  

1. *Run the Jupyter Notebook*:  
   bash  
   jupyter notebook python-food-ordering-app.ipynb  
     
2. Follow the prompts to select items, quantities, and proceed to checkout.  

## Scenarios Covered  

- ✅ *Successful Payment*: Order confirmed, receipt generated.  
- ❌ *Declined Payment*: Option to retry or cancel.  

## Code  

The project is implemented in a Jupyter Notebook:  
[food-ordering-app.ipynb](food-ordering-app.ipynb)  
