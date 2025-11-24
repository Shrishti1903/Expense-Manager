# project-for-software-engineering


Software Requirements Specification (SRS)

Users should be able to add and manage expenses

System should store expense details in memory (or file, if implemented)

Application should calculate total expenses dynamically

Interface must be intuitive and easy to use



Features:

Add new expenses with name, category, amount, date, and notes

Import expenses from CSV file

View all expenses in a structured table format

Automatic calculation of total expenses

Category-based expense summary (optional if implemented)

Editable and user-friendly Java Swing interface

Input validation & error handling



Design

Model–View–Controller (MVC) style architecture

Model: Expense.java

View: ExpenseManagerGUI.java

Controller: ExpenseManager.java & TableModel

Test Cases:
Test Case	                 Input	                    Expected Output
Add valid expense         Enter data & save	          Appears in table
Add empty fields        	Blank input	Show            validation alert
Calculate total	            Table filled	            Correct sum shown

Author

Shrishti Pathak
2301010052
K.R Mangalam University
