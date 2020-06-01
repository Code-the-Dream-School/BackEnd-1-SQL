# Backend-1-SQL
SQL asssignment for BackEnd-1

A practice SQL environment is at https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_join_inner

Note: It is not possible to do the following exercises in Firefox.  Use Chrome, or if you have a different browser, try it to see if it works.

You can click on each table in the right hand column to familiarize yourself with the schema of the database.  As you solve each of the SQL tasks below, copy the SQL statement and paste it into sql.txt of your git repository using your editor.  When you are done with a week's lesson, push the result to github.

For Backend 1 Week 1, do the following:

SELECT practice: 

(1) Using the Customer Table, select the CustomerName, ContactName, and Country.  Use ORDER BY to order by Country.  Use LIMIT and OFFSET to get entries 11 through 20.

(2) Select all columns from the Customer table where the ContactName starts with A.

(3) Select all columns from the OrderDetails table where the ProductID is 51 and the quantity is greater than 10.

INSERT practice:

INSERT 3 rows into the Products table.  Note that you will have to specify a valid SupplierID and CategoryID, corresponding to rows from the Supplier and Category tables.

UPDATE the two top rows of the Products Table to increase the price by 1.50. (Just specify the new value; do not try to get SQL to do the addition for you.)

DELETE practice: Delete all rows of the Products Table where the price is less than 7.00.

For Backend 1 Week 2

SELECT with JOIN practice:

Join the OrderDetails and Products tables, to show a report where the columns are OrderID, ProductName, and Quantity

Join the Orders, OrderDetails, and Employees tables to return a report with with the EmployeeName, ProductID, and Quantity.
