# sql-challenge

## Overview
This project analyzes employee data from Pewlett Hackard during the 1980s and 1990s. Using six CSV files, the analysis aims to uncover insights into the workforce and their roles by performing data modeling, data engineering, and data analysis with **SQL**.

## Features

### Data Modeling
- Inspects six CSV files containing employee data.
- An **Entity Relationship Diagram (ERD)** shows table relationships.
- Establishes primary and foreign keys to ensure data integrity.

### Data Engineering
- Creates SQL table schemas for all datasets with:
  - Defined data types.
  - Primary and foreign key relationships.
  - Constraints such as `NOT NULL`.

### Data Analysis
Performs a series of SQL queries to address specific research questions:
1. Lists each employee's ID, last name, first name, sex, and salary.
2. Identifies employees hired in 1986 with their first name, last name, and hire date.
3. Retrieves managers' details, including department name and number.
4. Lists employees' department information, including their department name.
5. Finds employees named "Hercules" with last names starting with "B".
6. Lists employees in the Sales department.
7. Lists employees in the Sales and Development departments, including department names.
8. Counts the frequency of last names among employees, sorted in descending order.

## Deliverables
- **Entity Relationship Diagram (ERD):** Represents table relationships.
- **Table Schemas:** SQL file defining the structure of all tables.
- **SQL Queries:** File containing SQL queries to answer data analysis questions.

## Setup and Dependencies

- Install **PostgreSQL** or another SQL database management system

## Running the Analysis
1. Clone the repository and navigate to the project directory.

2. Set up the database:
- Create a new database in the preferred SQL client.
- Run the table schema file `schema.sql` to create the tables.
- Import the CSV data into the respective tables.

3. Run SQL queries:
- Open the SQL query file `queries.sql` in the SQL client.
- Execute the queries to perform the analysis.

