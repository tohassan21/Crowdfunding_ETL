# Crowdfunding_ETL
Project Title: 
Project 2 Crowdfunding_ETL

Group Members: 
Zach, Makenna, Alice, Ethan, Jacob, and Duvoe

Overview/Use: 
This project is to practice using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform data, then creating CSV files and using CSV data to create an ERD and table schema, then uploading the CSV file into a Postgres database.

Setup:
The jupyter notebook file contains all of the starter code that creates all of the CSVs needed for the schema file.
All of the csv files created by the jupyter notebook file can be found in the Resources folder.
The schema file was created using an ERD that was completed by myseld and my group members.
This file uses the CSVs created in the starter jupyter notebook file to create a database. 
The end of the schema file checks for imports.
I have also included a screenshot of my ERD that was used to create the schema file.

How to Run the Program:
First you must run the whole jupyter notebook titled ETL_Mini_Project_Starter_Code.ipynb
By doing so, all of the CSVs created will be exported into the Resources folder.
Next, go into Postgres and run the crowdfunding_db_schema.sql file.
This will create tables with matching names to the four CSVs created using the jupyter notebook file.
Import the CSVs into each table in this order:
- contacts.csv
- category.csv
- subcategory.csv
- campaign.csv
Once they are all successfuly imported, run each of the SELECT statements to check that the tables were imported correctly.
