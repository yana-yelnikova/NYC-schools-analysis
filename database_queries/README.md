# SQL via Python: NYC School Data Exploration

### 🎯 Project Objective

This project uses **Python** and **SQL** together to explore real-world education data. The main goals were to connect to a PostgreSQL database, write SQL queries, analyze school-level insights, and present the work in a Jupyter Notebook.

---

### ✅ What Has Been Done

1.  **Database Connection:** A connection to the PostgreSQL database was successfully established using Python. The `pandas.read_sql()` method was used to query the database and display results.
2.  **SQL Queries and Analysis:** SQL queries were written to answer key questions about school distribution, language learners, and special education students.
3.  **Insights Generated:** The analysis provided key findings and insights, which are summarized below.

---

### 🧠 Conclusions

* **School Distribution by Borough**
    The number of schools varies greatly among the boroughs. Brooklyn (121) and the Bronx (118) have the most schools, while Staten Island has the fewest (10). This highlights the uneven distribution of educational institutions across New York City.

* **Average Percentage of English Language Learners (ELL)**
    Based on the provided information, the average percentage of ELL students in Manhattan is 7.57%, which is below the overall average of 12.7%. Information for other boroughs is missing, making a full comparison impossible.

* **Top 3 Schools with a High Percentage of Special Education Students**
    I was able to identify three schools in Manhattan with the highest percentage of special needs support. The leader, Manhattan East Side Community School, has a rate exceeding 28.8%. As with the ELL data, information for other boroughs is missing, which makes a full city-wide comparison impossible.
