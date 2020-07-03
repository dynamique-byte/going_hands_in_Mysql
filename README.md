# going_hands_in_Mysql
With Mysqlworkbench & Queries


# Database Management for Retail Application
### Project Description
### Problem Statement:
* A business organization (_retail) is not able to handle and maintain
the details of potential market.
* It is unable to manage various employees who belong to various
departments, information about the customers and sold products
their defects, quality and Voucher details etc.

### Scope of Project:
* This lab project aims to build a database for retail application for
an organization let say name Target where customers buy projects
online and offline.
* Retail application database is mainly used by the retail store
administrators to improve their sales by analyze the product sales,
customer and employees working in their organization.
* This project helps in designing unique database which holds the
information of the business model to properly store, analyze the data
that company is looking for.
* Products list with minimum defects and maximum quality can be
know which helps the organization to maintain good quality
products in their store and increase their sales.
* This project helps the organization to store and analyze customers,
employee, product sales details.
* This Database design helps in analyzing which product is highly
rated by customers.

### STEPS :-
* Designed a relational database schema & entity relationship model
with proper description of relationships,attributes,etc.
* Created multiple tables and managed the retail stores’ data in
MySQL.
* Applied database objects like triggers, stored procedures, views,
functions on the database.
* Generated reports of queries which helped the retail organization
to evaluate their sales, analyze sales for this season and forecast
sales for next season.

### Identification of Entities:
* Employee
* Address
* Bill
* Order
* Order Product
* Voucher
* Product Description
* Customer
* Zip Code
* Payment Mode
* Order Item
* Product
* Product Group
* Reviews

⇾ Employee -Any person who is employed as a part of company staff.
Attributes: EmployeeID, EmpFirst_Name, EmpLast_SSN,
EmpMail_Address, Designation, Department, Salary, Employee_Type.
⇾ Customer - A person who buys products with cash or card basis. He may
be internal or external customer.
Attributes: CustomerID, First_Name, Last_Name, Mail_Address,
Phone_Number, Category
⇾ Bill - Bill includes the total bill for the purchased products and amount that
customer paid .Attributes: Billing_ID, Amount_Paid
⇾ Address - Address to with a particular order must be delivered.
Attributes: AddressID, Address_line1, Address_line2
⇾ Zip Code - Zip details of customers address is included
Attributes: ZipCode, City, State
⇾ Payment- This table hold Date of customer visit number, payment and
payment type whether the customer bought directly from store or purchased
online. It also includes the customer card details.
Attributes: Payment_ID, Payment_Type, CreditCard_Number,Card_Type,
CVV_Number, ExpiryDate, CardHolder_Name
⇾ Orders – This table hold the status of the order whether the order is
delivered or not and the shipment option given by the customer.
Attributes: Order_ID,Shippment_Duration, Order_Date,Status.
⇾ Order Item- OrderItem contains the details like date and quantity of items
purchased.
Attributes: Date of Order, Quantity
⇾ Order Product- This contains the details of quantity of product that
customer ordered
Attributes: OrderProduct_ID, Quantity
⇾ Voucher- Voucher includes priority of customers so based on that
customers are given discount on their purchase.
Attributes: Voucher_Number, Description, Priority, Quantity_Item
⇾ Product - It is a form of good that is purchased by customer.
Attributes: ProductID, Product_Name, Available_Number
⇾ Product Details – Product details contains the description of particular
product.
Attributes: Weight, Width, Colour, Height⇾ Product Group – Product group tells to which category the product
belongs to (Ex. Electronics).
Attributes: Group_ID, Group_Name
⇾ Review- Reviews are the feedback given to the product by customers.
Attributes: Quality, Defect%, Review_ID, Review_Date

### CONCEPTS:-
1.Creating tables.
2.Filtering, sorting, and calculating data using:
WHERE, SELECT, FROM, IN, OR, AND, NOT, ORDER BY
3.Using wildcards to find specific strings
4.Math operations
5.Aggregate functions such as :
MAX, MIN, SUM, AVG, COUNT
6.Grouping data using :
GROUP BY
7.Subqueries
8.Different type of joins including :
INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER
JOIN, and self joins
9.Creating aliases
10.Using UNION queries
11.Working with string variables : Concatenations, Trimming,
Substring, Upper case and Lower case
12.Date and Time Strings: STRFTIME, Date(‘now’), computing
how many years have passed from a certain time period
13.Case Statements
14.Creating Views### ER Diagram for Retail Application
