# Day 2 – Python Data Exploration

### 🎯 Project Objective

This project involved exploring a real-world dataset on NYC High School Directories using **Python** and **Jupyter Notebook**. The main goals were to clean the data, perform basic analysis, create visualizations, and share key insights based on the findings.

---

### ✅ What Has Been Done

1.  **Dataset loaded and cleaned:** The NYC High School Directory dataset was successfully loaded into a pandas DataFrame. Column names were cleaned by converting them to lowercase, replacing spaces with underscores (`_`), and removing special characters.
2.  **Filtering and analysis performed:** The dataset was filtered to focus on schools in Brooklyn. Key questions regarding the number of unique schools and Grade 9 entry were answered using appropriate methods.
3.  **Data grouped and summarized:** The data was grouped by borough to count the number of schools and calculate the average number of students. A summary of the `grade_span_max` was also generated for each borough.
4.  **Visualizations created:** Two bar charts were created:
    * [Number of Schools per Borough](school_directory_exploration/visuals/Number_of_Schools_per_Borough.png) 
    * [Number of Students per Borough](school_directory_exploration/visuals/Number_of_Students_per_Borough.png) 
5.  **Key insights shared:** Three key insights were derived from the analysis and are detailed below.

---

### 🧠 Analysis Insights

* **Insight 1: Difference Between Number of Schools and Population**
    Based on the charts, we can conclude that the number of schools directly correlates with the total student population in a borough. However, this isn't the most interesting finding. It is far more valuable to focus on the average number of students per school.

* **Insight 2: School Efficiency and Size**
    **Staten Island** and **Queens** have the highest average number of students per school, whereas the **Bronx**, **Brooklyn**, and **Manhattan** and have significantly lower average values. This insight shows that schools in boroughs like Staten Island and Queens are, on average, much larger and more densely populated than those in other boroughs. This may be due to:
    * **Type of schools:** There may be a prevalence of large schools over specialized or smaller ones.
    * **Resource Distribution:** Larger schools may have more resources but also face challenges related to managing a larger student body.
    * **Demographic Density:** The population in these boroughs may be more concentrated, requiring larger educational facilities to meet the needs of residents.

* **Insight 3: Comparative Borough Analysis**
    **Brooklyn** has the largest number of schools and students. **Queens** has fewer schools (80) than the **Bronx** (118) but nearly twice the average number of students per school. This shows that despite similar sizes, boroughs can have completely different educational infrastructures. While **Brooklyn** and the **Bronx** prefer a model with a large number of small and medium-sized schools, **Queens** is betting on a smaller number of larger schools. This observation can be useful for planning future educational policy, for example, when deciding whether to build new large schools or several smaller ones to meet the needs of the population.
