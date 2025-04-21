# cmsc408-sp2025-hw8

Homework 8 - World Bank Indicator Analysis

Project Overview
This assignment involves analyzing the World Development Indicator (WDI) dataset from the World Bank. The goal is to practice SQL skills by querying and transforming large datasets to extract meaningful insights. You'll work with the world_bank_data schema, using various SQL queries to explore and manipulate the data, including aggregation, filtering, and creating new tables.

The assignment provides hands-on experience with:
1.SQL query writing and data manipulation.
2.Understanding how to transform raw data into useful information.
3.Working with real-world datasets (such as the WDI database) to analyze global development indicators.


Data Source
World Bank - World Development Indicators (WDI): A comprehensive database containing global data on various development indicators, such as GDP, population, and income categories, from countries worldwide.

File Structure
report.qmd: The main file for documenting your work, including SQL queries and their explanations.

helpers.py: Python script with functions to connect to the database, run SQL queries, and return the results.

my-ddl.sql: SQL script with the Data Definition Language (DDL) to set up and manage your database schema.

report.html: The rendered HTML report containing all queries, results, and reflections.

GitHub Repository: Contains your final code and files for submission to Gradescope.


## Setup & Installation  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/cmsc-vcu/cmsc408-sp2025-hw7-Braeden1Ferguson.git
   cd cmsc408-sp2025-hw7-Braeden1Ferguson

2. Install Python dependencies
If you’re using Poetry:
poetry install
poetry shell

3. Create and populate your .env file
In the repo root, add a file named .env containing:
CMSC408_HW8_USER=your_db_username
CMSC408_HW8_PASSWORD=your_db_password
CMSC408_HW8_HOST=your_db_host_or_ip
CMSC408_HW8_DB_NAME=your_database_name


# Generating the Report
1. Render the Quarto report
From the project root (or inside reports/ if that’s where report.qmd lives):
quarto render report.qmd

2. View your HTML output
open report.html





