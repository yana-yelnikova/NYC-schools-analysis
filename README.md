# Project Overview: NYC School Data Analysis

## 📌 Motivation
This project is a comprehensive study of NYC school data. Its main goal is to demonstrate a full data analysis workflow: from initial exploration and cleaning to analysis, visualization, and integration into a database. The project showcases the use of various tools like Google Sheets, Python (with pandas and matplotlib), and SQL (with PostgreSQL) to gain valuable insights from real-world data.

---

## 💾 Data Sources
The project used four primary datasets related to NYC schools:
* **`school_safety_report`**: Data on school incidents.
* **`high_school_directory`**: A directory of high schools.
* **`school_demographics`**: Demographic data for schools.
* **`sat_results`**: SAT exam results.

---

## 🛠️ Methodology
* **Initial Data Exploration:** The first stage involved **basic data cleaning** and analysis using Google Sheets, including normalizing column names and identifying the most frequent incident types.
* **Python-based Analysis:** A **Jupyter Notebook** was used with **pandas** to load the data, perform filtering and grouping, and create visualizations to understand the distribution of schools and students.
* **SQL-driven Insights:** Data stored in a **PostgreSQL** database was queried using **SQL** via Python. This step answered key questions about school distribution and demographic trends.
* **Data Engineering:** The final stage focused on **data pipeline development**. It involved inspecting and cleaning a new dataset (SAT scores), designing a database schema, and writing a Python script to reliably append the cleaned data into the database.

---

## 📊 Results and Key Findings
* **Uneven Distribution:** The number of schools varies significantly among boroughs, with Brooklyn and the Bronx having the most, and Staten Island the fewest.
* **School Efficiency:** Schools in Staten Island and Queens are, on average, much larger and more densely populated than those in Brooklyn and the Bronx, indicating a different educational infrastructure model.
* **Incident Analysis:** The most frequent type of incident was found to be "non-criminal."
* **Student Support:** The analysis identified schools with a significantly high percentage of students requiring special needs support.
* **Data Integration:** A cleaned and prepared dataset of SAT scores was successfully integrated into the database, ready for further analysis.

---

## ⏭️ Next Steps
* **Data Merging:** Conduct a deeper analysis by joining all four datasets into a single data model.
* **Correlation Analysis:** Investigate relationships, such as the correlation between incident rates and school demographics, or between school size and SAT scores.
* **Dashboard Creation:** Develop an interactive dashboard to visualize key metrics and insights.
* **Advanced Analytics:** Use machine learning methods to predict SAT results based on other school characteristics.
