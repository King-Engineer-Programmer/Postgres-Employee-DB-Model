# Postgres-Employee-DB-Model

For your first assignment, you’ll first design tables to hold data from CSV files, and you’ll then import the CSV files into a PostgreSQL database.

Background
It’s a beautiful spring day, and it’s been two weeks since you were hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remains of the database of employees from that period are six CSV files.
So for this assignment, you’ll first design tables to hold data from the CSV files, and you’ll then import the CSV files into a PostgreSQL database

Before You Begin


Create a new repository, named Employee_DB, for this homework assignment.
Important: Don’t add this assignment to an existing repository.


Clone the Employee_DB repository to your computer.



Instructions


Inspect the CSV files, and then sketch an ERD of the tables that you want. To do so, feel free to use a tool like QuickDBD.


Use the information from the ERD to create a table schema for each of the six CSV files. Remember to specify the data types, primary keys, foreign keys, and other constraints. For each primary key, remember to do the following:


Verify that the column is unique. If it isn’t, create a composite key, which takes two primary keys to uniquely identify a row.
Hint: You need to create a composite key for the titles table to avoid the "duplicate key value violates unique constraint" import error when importing the dept_emp.csv file.




Save an image of the ERD to your GitHub repository.


Save the database schema as a Postgres .sql file to your GitHub repository.


Create a new Postgres database, named Employee_DB.


Using the database schema, create the tables in the correct order to handle the foreign keys.


Verify that the tables have been created by using a SELECT statement for each table.


Import each CSV file into its corresponding SQL table.
Hint: To avoid errors, be sure to import the data in the same order that you created the tables. And, remember to account for the headers when importing.


Save the six CSV files to your GitHub repository.


Verify that each table contains the correct data by using a SELECT statement for each table.




Employee Database Analysis
For this assignment, you’ll perform a data analysis on the Employee_DB database that you created earlier.
