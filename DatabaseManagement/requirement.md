## Test for Database Management

### Objective:
Evaluate the ability to work with JSON data files, manage databases, create data pipelines, and ensure data synchronization between systems.

### Part 1: Data Loading and Database Setup
Data Files:

•	You have been provided with two JSON data files: company.json and address.json.

Task:

•	Clean and load the data from the provided JSON files into a MySQL database. Pay attention to relationship between the table, configure foreign key if needed.

•	Make a test on insert new rows to the company table. If the company is already in the table, update the existing row instead of creating the new record.

### Part 2: Data Pipeline Development

Task:

•	Develop a data pipeline that migrates data from the MySQL database to an Elasticsearch db. Ensure all necessary data types are correctly assigned in Elasticsearch (e.g., strings, integers, dates, json string).

### Part 3: Synchronize Changes
Task:

•	Implement a mechanism that ensures Elasticsearch stays synchronized with MySQL whenever new row is added or existing data is updated in the MySQL database.

