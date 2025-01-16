# SQL Script to Discover Errors
Creating a SQL script to discover errors in table data, log them in a notepad document, and then clean the data automatically involves several steps.

We'll break this down into three phases:
  1.	Discovering Errors in Data: This can be achieved by creating a query that identifies potential issues like missing values, out-of-range values, incorrect data types, etc.
  2.	Logging Errors to a Notepad: To log errors, we can export the results to a file. In SQL, we can use various methods like OUTFILE for MySQL or use server-side scripting          for SQL Server (e.g., PowerShell or Python) to create a notepad file.
  3.	Cleaning the Data Automatically: After identifying errors, we'll write SQL code to clean the data based on the discovered issues.
