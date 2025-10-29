# Final Project: Chicago Data Analysis with SQL and Python

![ibm-l-min](https://github.com/user-attachments/assets/2d621411-aeb6-41fa-9ca1-50a90d53fd11)

*Disclaimer: This repository contains the Final Assignment notebook for the "Databases and SQL for Data Science with Python" course, part of the IBM Data Science Professional Certificate on Coursera. (Link course: https://www.coursera.org/learn/sql-data-science?specialization=ibm-data-science
)*

This project focuses on demonstrating proficiency in database management and analytical SQL querying using real-world public data from the City of Chicago. The included Jupyter Notebook uses Python to effectively load data into a SQLite database and then execute complex SQL commands to derive specific data insights.

## 📚 Datasets Used
To complete the analysis in this notebook, the project utilizes three public datasets sourced from the City of Chicago's Data Portal:
1. Socioeconomic Indicators in Chicago
2. Chicago Public Schools
3. Chicago Crime Data

## 💻 Python Notebook Structure
The Jupyter Notebook (.ipynb) is logically structured to showcase the following key steps:
1. **Understand Three Chicago Datasets:** Initial exploration and structure review of the three datasets.
2. **Load Datasets into SQLite Database:** Using Python functionality to create three separate tables and load the corresponding Chicago data into a local SQLite database instance.
3. **Execute SQL Queries to Answer Assignment Questions:** Running a series of targeted SQL commands designed for data analysis, extraction, and cross-table querying.

## 📋 10 SQL Analytical Commands Executed
The notebook successfully executes SQL queries to address the following major analytical instructions:
1. Find the total number of crimes recorded in the CRIME table.
2. List community area names and numbers with per capita income less than $11,000.
3. List all case numbers for crimes involving minors? (Note: Children are not considered minors for the purposes of this crime analysis.)
4. List all kidnapping crimes involving a child?
5. List the kind of crimes that were recorded at schools (No repetitions).
6. List the type of schools along with the average safety score for each type.
7. List 5 community areas with the highest percentage of households below the poverty line.
8. Which community area is most crime prone? Display the community area number only.
9. Use a sub-query to find the name of the community area with the highest hardship index.
10. Use a sub-query to determine the Community Area Name with the most number of crimes.
