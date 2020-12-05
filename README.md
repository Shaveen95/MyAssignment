# MyAssignment
This assignment completed using spring boot.(Question 01 Rest API Design)
I created database which include 3 tables.(Customers, Items, Orders).
Database Structure :
  Customer details will save in Customers table with Primary key of "ID".
  Available food items to buy are store in Items table. 
  Order details are save in Order table with primary key orderId & 2 refferece keies of "customers" an "items" tables.
To create database I used wamp server.
Sample Request to Test API Flow : 
  Customers:
    http://localhost:9090/showCustomers (GET method)
    http://localhost:9090/addCustomer (POST method)
    http://localhost:9090/updateCustomer/1 (PUT method)
    http://localhost:9090/deleteCustomer/300 (DELETE method)
    http://localhost:9090/showCustomers/1 (GET method, retrive one specific customer details)
    
  Items : 
    http://localhost:9090/showItems (GET method)
    http://localhost:9090/addItem (POST method)
    http://localhost:9090/updateItem/1 (PUT method)
    http://localhost:9090/deleteItem/300 (DELETE method)
    http://localhost:9090/showItem/1 (GET method, retrive one specific item details)
    
  Orders:
    http://localhost:9090/showOrders (GET method)
    http://localhost:9090/addOrder (POST method)
    http://localhost:9090/updateOrder/ord001 (PUT method)
    http://localhost:9090/deleteOrder/ord001 (DELETE method)
    http://localhost:9090/showOrders/ord001 (GET method, retrive one specific order details)
