# Inventory-Management-System
Project summation 

This application has 2 users 
1. Shop owner
2. Customers

The product has the following  5 attributes -
1. Name: Name of the product
2. Price: the price of each product
3. current Stock: Number of Products available 
4. min stock: Minimum product required at the store (if product stock reaches min stock number we should refill the product)
5. catagory: different category of product (e.g soap, cold drinks, snacks, etc)

Shop owner's role and access: 
1. Can check stock of a product 
2. Can check min stock of a product
3. if current stock is less than min stock shop owner can refill the product this can be done in 2 ways : 
   i: shop owner can refill the products by the default number of products set (e.g if the soap has default refill number 100 then the order placed is of 100 new soaps)
  ii: shop owner can set quantity of products to be refilled (this case will be used if have any dependency on a budget or other.)
4. Shop owner can add a new product in-store by providing all characteristics of products 

Customers role : 
1. A customer can add products to the cart
2. A customer can place an order 

when an order has been placed the list of products will be saved in sales_fn.json


