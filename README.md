# 13-Crowdfunding_ETL

13-Crowdfunding_ETL is a project building an ETL pipeline using Python, Pandas, Python dictionary methods and regular expressions to extract and transform data.  This repository contains a SQLite file named Crowdfunding_db_schema, a Jupyter Notebook file called ETL_Mini_Project_Starter_Code, a PNG file with the image of an ERD created for our data, a README file, and a Resources folder containing two Excel files with the data used for the project, and five CSV files created from the Excel file data.

We created pandas DataFrames for Category and Subcategory from the Crowdfunding Excel files and exported them as CSV files. We also created a Campaign DataFrame and exported it to a CSV, renamed columns, converted datatypes, and joined it with the Category DataFrame and dropped unneeded columns. We then created two Contacts DataFrames using the Pandas dictionary method and using regex and exported them as CSV files.

We then created an ERD model for each of the four CSV files and used Postgres to create the four tables from the model and import the CSV files associated with each table.
