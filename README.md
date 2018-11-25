#This Project is maintained by:
 Abhishek Singh Rathore (161b010)
 Adarsh Kumar (161b011)
 Aditya Priyam (161b013)
By student of Jaypee University of Engineering and Technology,Guna.
# BudgetApp called "Budget Buddy"
For those who prefer to manage their budget locally and not use a retail app that stores data in the cloud(someone elses server).
A python web app using bottle and a sqlite db. 
Current functionality limited to setting a budget, adding purchases to a "receipt" list and, subtracting those receipts from the budget. 

Page structure: 
<pre>
Home(index)
--Budget
	--Update Budget
	--Expense List
	--Home
--Update Budget
	--Budget
	--Home
	--Cancel
--Expense List
	--New Expense 
	--Budget 
	--Home 
	--Import Expense List [shell, future functionality]
--Add Expense
	--Budget 
	--Expense list
	--Home 
	--Cancel
</pre>

Requirements: 
Works with python 3.6, bottle 12.13

How to run: 
1. Create the database with manage_receipt_tables.py
	python .\manage_receipt_tables.py 
	
	Builds two tables, "reciepts" and "budget"

2. Run, python .\app.py

	Defaults to localhost:5555, go to your browser and type that address in. 

3. Manage your receipts and budget 

