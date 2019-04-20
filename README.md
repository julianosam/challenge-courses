# Vending machine

The goal of this project is to build a the system that controls a vending machine, just like the ones you find in public places selling snacks and drinks.

## Iteration #1

The machine system should contain

- A list of products available
- Each product should have
    - Code
    - Quantity available
- The user will request to see all products available for purchase
- After deciding, they will enter the code of the product they want to buy along with the desired quantity
- The machine should validate the input and either decide to deny the request or dropping the products on the tray.
- If the request was denied, machine should inform the user about the reason:
  - Product does not exist
  - Not enough products


### Tech requirements
For this phase, your project should contain the following classes:
- VendingMachine
- Product
- PurchaseRequest

## Iteration #2


Adding price to the products
Calculation total price of the purchase
Giving change
Adding error messages


## Iteration #3
Adding support for card payments
Validating card numbers and account balances
