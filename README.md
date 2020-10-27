# This document contains answers for the assignment
### How many Employees have a home city of London? 
- 4
### Which Employee is a Doctor? 
- Andrew Fuller
### How many products are discontinued? 
- 8
### What are the names and product ID’s of the products with a unit price below 5.00? 
- Guaraná Fantástica (24)
- Geitost (33)
### Which categories have a category name with initials beginning with B or S? 
- Beverages
- Seafood
### How many orders are there for EmployeeIDs 5 and 7 (total for both)? 
- 114
### Write a SELECT using the Employees table and concatenate First name and Last name together. Use a column alias to rename the column to Employee Name 
```
SELECT EmployeeID, FirstName + ' ' + Lastname AS EmployeeName, Title, TitleOfCourtesy, BirthDate, HireDate, Address, City, Region, PostalCode, Country, HomePhone, Extension, Photo, Notes, ReportsTo, PhotoPath FROM Employees; 
```
### Write a SELECT statement to list the 6 countries that have region codes in the customer table 
- Brazil, Canada, Ireland, UK, USA, Venezuela
