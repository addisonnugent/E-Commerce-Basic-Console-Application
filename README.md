# E-Commerce-Basic-Console-Application
E-commerce platform in C# with a basic console application implementing CRUD operations with an inventory and a shopping cart. 

Each Product contained the elements:
1) Name - the name of the product
2) Description - the description of the product
3) Price - the unit price of the product
4) Quantity - the number of units being purchased
5) TotalPrice - the total price of the product being purchased (i.e., Price * Quantity)


Inventory - this is a list of products available at the store
Features include:
- Create a product to the inventory or add additional units to an exisiting product
- Remove a products from inventory or delete units from quantity
- Update the name/price of a product
- Displays current inventory with prices and quantity of a product that is available


Shopping Cart - this is a list of products being purchased by the user. 
Features include:
- Add items to their cart (which then takes the product away from the inventory)
- Delete items from their cart (which then adds those products back to the inventory)
- List items in the current inventory & items in cart 
- Shoppers are unable to modify items in the inventory 
- Search inventory & cart for an item by name or description


Checkout:
- Displays subtotal (without taxes)
- Tax amount (at 7%)
- Grand Total


Saves users shopping cart when exiting application and picks up where they left off when returning. 
