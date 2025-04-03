# Pandas Challenge: PyCitySchools

# Project Overview

As the new Chief Data Scientist for the city's school district, your responsibility is to provide insightful data analysis to help the school board and mayor make strategic decisions regarding school budgets and priorities. This project leverages Pandas and Jupyter Notebook to analyze district-wide standardized test results.

The goal is to aggregate and analyze data related to student performance, school size, budget allocation, and other metrics to uncover trends and insights.
 
# Key Objectives
* District Summary
  
Calculate and display key district metrics including:
Total number of unique schools
Total number of students
Total budget
Average math score
Average reading score
Percentage passing math
Percentage passing reading
Overall passing percentage

* School Summary
  
Summarize key metrics for each school, including:
School name and type
Total students and school budget
Per student budget
Average math and reading scores
Percentage passing math and reading
Overall passing percentage

* Performance Rankings

Identify and display:
Top Performing Schools (by % Overall Passing)
Lowest Performing Schools (by % Overall Passing)

* Scores by Grade

Analyze average math and reading scores for each grade level (9th to 12th) at each school.

* Scores by School Spending

Analyze school performance based on spending per student using the following bins:
<$585, $585-630, $630-645, $645-680

* Scores by School Size

Analyze performance based on school size using the following bins:
Small (<1000), Medium (1000-2000), Large (2000-5000)

* Scores by School Type

Compare school performance based on school type (e.g., Charter vs. District).

# Installation and Setup

-Python 3.x

-Jupyter Notebook

-Pandas library

# Key Insights

Charter schools outperform district schools in terms of average math and reading scores as well as overall passing percentages.
Smaller schools tend to have better performance metrics compared to larger schools.
Spending per student does not necessarily correlate with higher performance—schools with moderate spending tend to have the best outcomes.

# Challenges and Solutions

Challenge: Large Dataset Performance
Solution: Used groupby() and vectorized operations for efficient data aggregation.
Challenge: Data Cleaning and Integrity
Solution: Validated data consistency before performing analysis to avoid discrepancies.
