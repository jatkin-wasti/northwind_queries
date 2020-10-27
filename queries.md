# This file contains the entire SQL script used for the assignment
```
SELECT * FROM Employees;

SELECT Count(*) FROM Employees WHERE City = 'London'; 

SELECT FirstName, LastName FROM Employees WHERE TitleOfCourtesy = 'Dr.';

SELECT * FROM Products;

SELECT Count(*) FROM Products WHERE Discontinued = '1'; 

SELECT ProductName, ProductID FROM Products WHERE UnitPrice < 5.00;

SELECT CategoryName FROM Categories WHERE CategoryName LIKE 'B%' OR CategoryName LIKE 'S%';

SELECT Count(*) FROM Orders WHERE EmployeeID = 5 OR EmployeeID = 7;

SELECT EmployeeID, FirstName + ' ' + Lastname AS EmployeeName, Title, TitleOfCourtesy, BirthDate, HireDate, Address, City, Region, PostalCode, Country, HomePhone, Extension, Photo, Notes, ReportsTo, PhotoPath FROM Employees;

SELECT DISTINCT Country FROM Customers WHERE Region LIKE '%';
```
