# NYC School SAT Scores Data Engineering

### 🎯 Project Objective

The objective of this project is to evaluate, clean, and integrate a real-world dataset into an existing PostgreSQL schema. This involves inspecting the data, identifying relational keys, correcting inconsistencies, and using a Python script to append the data.

---

### ✅ What Has Been Done

1.  **Dataset Exploration:** The `sat-results.csv` file was reviewed to understand its structure, identify useful columns, and detect inconsistencies.
2.  **Data Cleaning:** A Python script was used to perform a series of data cleaning tasks:
    * Handled duplicates and invalid SAT scores (out of the 200-800 range).
    * Cleaned inconsistent formatting, such as `85%`.
    * Normalized column headers and dropped irrelevant fields.
3.  **Schema Design:** The final columns for upload were chosen, and a schema for the table was designed to accommodate the cleaned data.
4.  **Data Appending Script:** A Python script was written to connect to the PostgreSQL database. The script used `psycopg2` or `sqlalchemy` to append the cleaned data to the designated table using parameterized queries to ensure data integrity and security.
