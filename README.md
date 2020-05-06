# School_District_Analysis

## Project Overview
Analyzing the PyCity School District data to get a high-level snapshot of the district's key metrics and the metrics for each school.

Included metrics:
- Top 5 and bottom 5 performing schools, based on overall passing rate.
- The average math score in each grade level at each school.
- The average reading score in each grade level at each school.
- School performance based on budget per student.
- School performance based on school size.
- School performance based on the type of school.

## Resources
- Data source: schools_complete.csv, students_complete.csv
- Software: Anaconda 4.7.12, Pandas and Jupyter Notebook

## Challenge Overview
The math and reading scores for the ninth graders at Thomas High School have been compromised. The task is to remove the math and reading scores for all ninth graders at Thomas High School while keeping the rest of the data for each ninth-grade student.

## Challenge Questions
1. How is the district summary affected?
- The average math score went down slightly, 79 to 78.9, while the average reading score did not change.
- The percent passing each exam went down by 1%. Math: 75% to 74%. Reading: 86% to 85%.
- The overall passing percentage went down by 1%, 80% to 79%.

2. How is the school summary affected?

The school summary only showed changes to Thomas High School.
- The average math and reading scores were not noticeably changed.
- The percent passing math dropped considerably from 93% to 67%.
- The percent passing reading dropped considerably from 97% to 68%.
- The overall passing percentage dropped from 95% to 68%.

3. How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

When the scores from the 9th graders were removed, Thomas High School went from being the 2nd highest performing school to the lowest performing school, based on the overall passing percentage.

4. How does removing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type?
- The Math and Reading Scores by Grade table now shows nan for the Thomas High School 9th grade column.
- Because Thomas High School is in the $631-645 spending range, the percent passing went down for math, reading and overall in that row.
  - Math: 73% down to 67%
  - Reading: 84% down to 77%
  - Overall: 79% down to 72%
- Because Thomas High School is considered a Medium-sized school, the percent passing went down in all three categories in that row.
  - Math: 94% down to 88%
  - Reading: 97% down to 91%
  - Overall: 95% down to 90%
- Thomas High School is a Charter school, so removing the 9th graders lowered the passing percentages in all three categories in that row.
  - Math: 94% down to 90%
  - Reading: 97% down to 93%
  - Overall: 95% down to 92%

The biggest changes were seen in the school summary, which changed the performance relative to the other schools dramatically.
