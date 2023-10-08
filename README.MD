# Creating a Database and Table Using PostgreSQL
## STEP 0: Pre-requisites;
- PostgreSQL installed and configured in your PC
## STEP 1: Create a Database
- expand servers on your pgAdmin4
- expand postgreSQL, rightclick on database and open a query tool
- input ``` create database sport ``` and run it. This will create a database named sport.
![Alt text](<Images/Creating Database.png>)

## STEP 2: Create Table and Columns
- input ```create table nba (Name VARCHAR(100),Team VARCHAR(70),Position VARCHAR(50),Birthday VARCHAR(50),Salary VARCHAR(100));```
- This will create a table with columns Name, Team, Position, Birthday and Salary in your sport database.
![Alt text](<Images/creating the table.png>)
![Alt text](<Images/Table created.png>)

## STEP 3: Import .csv File
- Rightclick on the table
- click on import/export
- select import
- select the csv file from directory
- select UTF8 as the encoding, then click ok to import the file
![Alt text](<Images/Importing the csv files.png>)
![Alt text](<Images/File imported.png>)

## STEP 4: View the Imported File
- expand tables and rightclick on nba
- select 'view/edit data' and choose 'all rows' to view the imported file.
![Alt text](<Images/View the imported file.png>)