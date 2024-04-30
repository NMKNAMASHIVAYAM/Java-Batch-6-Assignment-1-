# Java-Batch-6-Assignment-1-
SQL Database Management 

You are working as a database administrator for a fictional company named "TechShop," which sells electronic gadgets. TechShop maintains data related to their products, customers, and orders. Your task is to design and implement a database for TechShop based on the following requirements:

Database Tables:

1. Customers:
  • CustomerID (Primary Key)
  • FirstName
  • LastName
  • Email
  • Phone
  • Address

2. Products:
  • ProductID (Primary Key)
  • ProductName
  • Description
  • Price

3. Orders:
  • OrderID (Primary Key)
  • CustomerID (Foreign Key referencing Customers)
  • OrderDate
  • TotalAmount

4. OrderDetails:
  • OrderDetailID (Primary Key)
  • OrderID (Foreign Key referencing Orders)
  • ProductID (Foreign Key referencing Products)
  • Quantity

5. Inventory
  • InventoryID (Primary Key)
  • ProductID (Foreign Key referencing Products)
  • QuantityInStock
  • LastStockUpdate

