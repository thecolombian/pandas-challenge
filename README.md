# PyCitySchools Analysis Report

## Summary of Analysis
This report analyzes school performance within a district, focusing on various school and student data metrics. It includes district and charter schools, comparing their performance in average scores, passing rates, and budget allocations. The aim is to identify critical trends and insights that can inform educational policy and resource distribution.

## Key Metrics Calculated
1. **District-Level Metrics**:
   - Total number of unique schools.
   - Total number of students.
   - Total budget for all schools.
   - Average math and reading scores across the district.
   - Percentage of students passing math, reading, and both subjects.

2. **School-Level Metrics**:
   - Total students and total budget for each school.
   - Budget per student.
   - Average math and reading scores for each school.
   - Percentage of students passing math, reading, and both subjects for each school.

3. **Summary Tables**:
   - Performance categorized by spending per student.
   - Performance categorized by school size.
   - Performance categorized by school type.

## Key Data
![Analysis Image](https://github.com/thecolombian/pandas-challenge/blob/main/IMAGES/2024-06-21_15-25-08.png)

## Conclusions and Comparisons

### Conclusion 1: Charter Schools Outperform District Schools
**Observation**: The analysis reveals that charter schools consistently outperform district schools in terms of average scores and passing rates. Charter schools have higher average math and reading scores and significantly higher percentages of students passing both subjects.

**Example Calculation**:
   - **Average Math Score**: Charter schools (83.46) vs. District schools (76.94)
   - **Overall Passing Rate**: Charter schools (90.29%) vs. District schools (53.72%)

This suggests that charter schools may employ more effective teaching methods or benefit from favorable student-to-teacher ratios.

### Conclusion 2: Per Student Budget and Performance
**Observation**: The analysis indicates a complex relationship between per-student budget and school performance. While charter schools generally have lower per-student budgets than district schools, they achieve higher performance metrics.

**Example Calculation**:
   - **Per Student Budget**: Charter schools (average $598.00) vs. District schools (average $642.14)
   - **Overall Passing Rate**: Despite lower budgets, charter schools (90.29%) outperform district schools (53.72%).

This suggests that factors other than funding, such as teaching quality, administrative efficiency, and school environment, play crucial roles in determining academic success.

## Final Thoughts
The PyCitySchools analysis provides valuable insights into how different types of schools and their funding impact student performance. Despite operating with lower per-student budgets, charter schools demonstrate higher academic achievement. This finding highlights the need for district schools to explore innovative teaching methods and efficient resource utilization to improve student outcomes. Policymakers should consider these insights when allocating resources and implementing educational reforms to ensure all students have the opportunity to succeed.







**Overview**

This script analyzes school and student data to generate various summary metrics and insights about school performance within a district. It uses Python and pandas for data processing and analysis.

**Files**
Resources/schools_complete.csv: Contains data on various schools within the district.
Resources/students_complete.csv: Contains data on students, including their math and reading scores.

**Steps Performed**
Data Loading:

Load school and student data from CSV files into pandas DataFrames.
Merge these DataFrames into a single dataset for comprehensive analysis.

**District-Level Metrics:**

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

**Usage******
To run the analysis, execute the script in a Jupyter Notebook environment. Ensure that the required CSV files are available in the specified paths. The script will generate various summary tables and metrics that can be used to assess school performance across different dimensions.

