# Challenge

Task is to develop a simple app that handles order placement. It should be implemented as a headless web api that exposes following endpoints:
* Place an order for a DNA testing kit providing desired amount of kits, customer id and expected delivery date
* List all customer orders

Discount rules:
* DNA testing kit base price is 98.99 EUR
* Starting from 10 item order there is 5% discount
* From 50 item order there is 15% discount

Reject order placement when:
* Delivery date is not in future
* Desired amount is not positive round number
* Desired amount is greater than 999

You can skip authentication and authorization. 

## Technical requirements
* Use c# programming language
* Use any testing framework for tests
* You can choose whatever tools and libraries you prefer

## What gets evaluated
* Accordance to business requirements described above
* Code quality (we value design guided by tests)
* Checkout-and-run convenience

## Have fun! 
