# Explore_Resturant_db_SQLite 
Explore a resturant database which include different tables 
1. EventsLocations 
2. Events 
3. 	CustomersEvents 
4. 	CustomersDishes 
5. 	Customers 
6. 	Dishes 
7.	OrdersDishes 
8. 	Reservations 
9. 	Orders

- Customers table include columns :  
CustomerID (Primary Key)	FirstName	LastName	Email	Address	City	State	Phone	Birthday	FavoriteDish (Foregion Key) 

- Orders table  include : OrderID(PK) CustomerID(FK)	OrderDate

I explores the database and add some  changes with SQLite in Python through sqlite3

## challenges

1. print menu according different conditions such as (order by price) , types 
2. add new customers to table 
3. Add new reservation to new customers 
4. change some information about customers such as new address
5. search for customers with just three charaters from their first name
6. change the favorite dish for some customers
7. determine the customers with highest number of orders 
