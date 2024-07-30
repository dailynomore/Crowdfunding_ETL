# Crowdfunding ETL Project

This project demonstrates the building of an ETL (Extract, Transform, Load) pipeline using Python, Pandas, and PostgreSQL. The pipeline processes crowdfunding data sourced from Excel files, transforming the data into a relational database format suitable for analytical purposes.

## Background

In the Crowdfunding ETL Project, I developed skills necessary to construct a robust ETL pipeline by processing real-world crowdfunding data. The project involves extracting data from structured Excel files, transforming this data through cleaning and normalization, and loading the results into a PostgreSQL database.

## Features

- **Extract and Transform Data**: Pull data from Excel files using Python and Pandas.
- **CSV File Creation**: Generate and export cleaned data into CSV files for Categories, Subcategories, Campaigns, and Contacts.
- **Database Schema Design**: Create an Entity Relationship Diagram (ERD) and corresponding table schemas.
- **Database Management**: Load CSV data into PostgreSQL database tables and perform queries to manage and verify the data integrity.

## Installation

To set up and run this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dailynomore/Crowdfunding_ETL
Install Required Packages

2. **Ensure you have Python installed, then run:**
   ```bash
   pip install pandas openpyxl psycopg2
   
3. **Database Setup**
-Install PostgreSQL and set up a local server.
-Create a new database named crowdfunding_db.

**Usage**
  1. **Run the Jupyter Notebook**
    -Navigate to the notebook directory and launch Jupyter Notebook.
    -Execute the notebook cells sequentially to extract and transform the data.
  2. **Database Schema Creation**
    -Use the crowdfunding_db_schema.sql file to create tables in your PostgreSQL database.
  3.****Data Loading**
    -Load the generated CSV files into the PostgreSQL database using the provided SQL commands or through a GUI like pgAdmin.
  4。 **Verify Data**
    -Run SQL queries within your PostgreSQL client to ensure the data has been loaded and is formatted correctly.
**Built With**
-Python - Programming language used for scripting and data manipulation.
-Pandas - Data analysis library used for handling data in Python.
-PostgreSQL - Open-source relational database.
-Jupyter Notebook - Interactive computing environment.
-Excel - Used for initial data storage and extraction.
