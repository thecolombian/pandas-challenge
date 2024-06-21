PyCitySchools Analysis

Overview

This script analyzes school and student data to generate various summary metrics and insights about school performance within a district. It uses Python and pandas for data processing and analysis.

Files
Resources/schools_complete.csv: Contains data on various schools within the district.
Resources/students_complete.csv: Contains data on students, including their math and reading scores.

Steps Performed
Data Loading:

Load school and student data from CSV files into pandas DataFrames.
Merge these DataFrames into a single dataset for comprehensive analysis.

District-Level Metrics:

Calculate the total number of unique schools.
Calculate the total number of students.
Calculate the total budget for all schools.
Compute average math and reading scores across the district.
Calculate the percentage of students passing math, reading, and both subjects.
School-Level Analysis:

Generate summary statistics for each school, including total students, total budget, budget per student, average math and reading scores, and percentage of students passing math, reading, and both subjects.
Summarize data by spending ranges per student, school size, and school type.
Data Grouping and Visualization:

Categorize and summarize school performance based on spending per student, school size, and school type.
Display results in well-structured DataFrames for easy interpretation and visualization.

Usage
To run the analysis, execute the script in a Jupyter Notebook environment. Ensure that the required CSV files are available in the specified paths. The script will generate various summary tables and metrics that can be used to assess school performance across different dimensions.

