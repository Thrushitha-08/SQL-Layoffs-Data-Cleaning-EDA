SQL Layoffs Data Cleaning & Exploratory Data Analysis (EDA)

Project Overview

This project demonstrates the complete data cleaning and exploratory data analysis (EDA) process using SQL on a real-world layoffs dataset. The project focuses on transforming raw data into a clean and consistent dataset before performing analysis to identify business trends and insights.

Project Objectives

? Clean and preprocess raw layoffs data.

? Remove duplicate records.

? Handle missing and NULL values.

? Standardize inconsistent data.

? Convert text dates into DATE format.

? Perform SQL-based exploratory data analysis.

? Generate meaningful business insights.


Tools & Technologies

• MySQL

• SQL

• MySQL Workbench

• Git

• GitHub


SQL Concepts Used

• Data Cleaning

• Exploratory Data Analysis (EDA)

• Window Functions

• ROW_NUMBER()

• Common Table Expressions (CTEs)

• Aggregate Functions

• GROUP BY

• ORDER BY

• JOIN

• UPDATE

• DELETE

• ALTER TABLE

• TRIM()

• STR_TO_DATE()

• NULL Handling


Project Structure

SQL-Layoffs-Data-Cleaning-EDA/

??? datasets/
?   ??? layoffs.csv
?
??? sql/
?   ??? 01_Data_Cleaning.sql
?   ??? 02_Exploratory_Data_Analysis.sql
?
??? screenshots/
?
??? README.md
??? LICENSE
??? .gitignore

Data Cleaning Process

The following data cleaning steps were performed:

• Created a staging table.

• Removed duplicate records using ROW_NUMBER().

• Standardized industry names.

• Standardized country values.

• Converted blank values into NULL.

• Filled missing industries using self joins.

• Converted text dates into DATE format.

• Removed rows with insufficient information.

• Created the final cleaned dataset.


Exploratory Data Analysis

The following business questions were answered using SQL:

• Which companies laid off the most employees?

• Which countries experienced the highest layoffs?

• Which industries were most affected?

• Which locations had the highest layoffs?

• Which funding stages experienced the most layoffs?

• Which companies laid off 100% of their workforce?

• How did layoffs change over different years?

Business Insights

• Identified companies with the highest cumulative layoffs.

• Compared layoffs across industries.

• Compared layoffs across countries.

• Analyzed yearly layoff trends.

• Identified companies with complete workforce layoffs.

• Evaluated layoffs across different funding stages.

Project Screenshots

The screenshots folder contains important SQL query outputs, including:

• Top Companies by Layoffs

• Top Industries by Layoffs

• Top Countries by Layoffs

• Layoffs by Year

• Companies with 100% Layoffs

Future Improvements

? Create an interactive Power BI dashboard.

? Build Tableau visualizations.

? Perform predictive analysis using Python.

? Develop an end-to-end analytics dashboard.




Author

Thrushitha Reddy

GitHub:
https://github.com/Thrushitha-08

If you found this project useful, feel free to ? the repository.
