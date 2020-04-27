# PyCitySchools-analysis

## Project Overview
Maria, the chief data scientist for a city district has given me the following tasks to analyze data on students funding and student's standardized test scores for assisting the school broad and superitendent in making decisions regarding th school budgets and priorities.

1. Make school and district summaries.
2. Get complete lists of the high- and low- performing schools based on the overall passing rate.
3. Calculate the average math and reading scores, as well as the passing rates. 
4. Determine the school performance based on the budget per student, school size, and type of school. 

## Resources
- Data Sources: students_complete.csv and schools_complete.csv
- Software: Pandas Library, Jupyter Notebook

## Summary
Since the grade of the ninth gradeer at Thomas High School have been changed:
- The new district summary shows that the average math and reading scores, math, reading, and overall passing rates are lower than the numbers before changed data. 

- Before the data being replaced, the top five schools ranked by the overall passing rate are 
  - Carbrera High School, Thomas High school, Griffin High School, Wilson High School, and Pena High School
- After the data changed, the top five schools have become to 
  - Carbrera High School, Griffin High School, Wilson High School, Pena High School, and Wright High School.

- The bottom five schools ranked by the overall passing rate are same before and after the data of Thomas High School being replaces, they are
  - Rodriguez High School, Figueroa High School, Huang High School, Hernandez High School, and Johnson High School.

- Replacing the ninth-grade score of Thomas High School only affect the math and reading scores in ninth-grade.It does not affect the scores in other grades

- However, it does affect the scores by school spending, school size, and school type:
  - It lower the overall passing rate for spending range $630-644 per student from 63% to 56%
  - It lower the overall passing rate for medium size school (1000-2000 students) from 91% to 68%
  - It lower the overall passing rate for charter school from 90% to 87%

- The both results of the analysis show that schools have relative high overall passing rate sharing the following charatceristics: 
  - Low spending per student (less than $584 per student)
  - Small school size (less than 1000 students)
  - Charter school type
  
## Challenge Overview

## Challenge Summary


