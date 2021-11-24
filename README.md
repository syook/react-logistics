# react-logistics

Problem Statement

 - I own a logistics company that has vehicles to deliver orders. 
 - I want to create an automated logistics management system that allows me to add vehicles, items, orders, customers.
 - When the order is placed in my warehouse, I want to have the order issued to the customer with a price. 
 - The ordering process includes:
     - Checking the availability of the fleet of vehicles.
     - Documenting the order number.
     - Creating the customer record if they do not already exist in the system and allocating the vehicle to the said order using its registration number (number plate) before actually creating the order.
      - Creating the order with price and delivery location.

Forms required:

## Items

schema:
 - id
 - name
 - price

## Customers

schema:
 - id
 - name
 - city

## Delivery vehicles

schema:
 - id
 - registrationNumber: unique, alphanumeric
 - vehicleType: bike/truck
 - city (location serving)

## Order

schema:
 - orderNumber: id
 - itemId - item id (from item list)
 - price - price stored in item at the time of the creation (from item list)
 - customerId - customer id (from customer list)
 - deliveryVehicleId - delivery vehicle id (from delivery vehicle list)


Expectations:
  - Needs to have forms for the above mentioned including edit.
  - Needs to have table view pages for the above-mentioned.
  - Have basic validations for the forms inputs
  - Prefill the values in case of order forms (customerId, deliveryVehicleId)
  - Use only HTML, CSS, React JS. 
  - Design is up to you. Use any simple design which you think is best 	

Good to have 
 - Search the list on basis of title or content 
 - Object-oriented code 
 - Semantic code and mobile web compatible design
 - Web hosting of the application 

How will the assignment be graded? 
 - Functionality: Is the web-app functional? Code should work in multiple mobile browsers  (Chrome, Safari, UC browser, mobile browser) 
 - Code Quality: Code Readability, Reusability, and structuring. 
 - Use react JS, CSS, and HTML to complete your task.  
 - Git Commit practices: Manage your code in GitHub and make frequent commits.
