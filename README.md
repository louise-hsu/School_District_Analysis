# School_District_Analysis

## Project Overview


By Performing the tasks, I learned the following:

1. The Pandas Library- data manipulation and analysis
2. Jupyter Notebook
    - Read raw data
    - Clean and inspect data
    - Merge data sets
    - Perform Calculations
    - Create Table
3. And more...

## Resources Folder
- clean_students_complete : Given to check 
- missin_grade: an example
- school_scomplete : MAIN DATA 
- studnet_complete : MAIN DATA 

##  School District Analysis (files other than resources)
- gitignore
- jupyter_practice: new file open
- pandas_practice: practice
- functions: function examples
- cleaning_student_name : cleaning the student data
- cleaning_data: how to clean data example
- readme. md
- PyCitySchools: data and analysis with all data from students and school - nothing taken out
- PyCitySchools_Challenge: The Module 4 Challenge

## Summary
***Please note: The summary is found in the PyCitySchools.ipnyb. in the School_District_Analysis Folder in Github***

The analysis of the school district show that:
 - There are a total of 15 schools and 39,170 students in the district, with a total budget of $24,649,428. The total average math score  is 79, average reading score is 81.9, % Passing Math is 75, % Passing Reading is 86, and % overall passing is 80. 
 - To find more details on the values per school - please go to per_school_summary_df in the file.
 - The 5 top schools with highest % overall passing are Cabrera, Thomas, Pena, Griffin, and Wilson High School. (Highest ---> lowest order)
 - The 5 top schools with the lowest % overall passing are Rodriguez, Figueroa, Huang, Johnson, and Ford High School. ( worst ---> best order)
 - The average math and reading scores per grade per school seem to be very similar.
 - The spending range of less than $584 per student received the highest average math/reading scores, %passing math/reading, and % overall passing. As the spending ranges per student increased to $675 per student, the average math/reading score, % passing math/reading, and % overall passing decreased. 
 - The school size of small and medium seem to have not shown a difference in performance scores in math, reading and passing scores. However in large size schools, the scores, % Passing math and reading, and % overall passing is lower than small and mdedium sized schools. 
 - The School Type: Charter School Types have a higher math, reading, and % Passing math and reading, and overall % passing completed to District School Types. 
 
 ## Challenge Overview
 The grades of the ninth graders at Thomas High School have been changed. We decided the best approach is to remover the ninth grade amth and reading scores from Thomas High School, and keep all other data associated with the ninth-grade students and Thomas High School in tact. 
 
 1. Filter DataFrames using logical operators
 2. Replace the incorrect values with NaN
 3. Explain how your PyCitySchool analysis changes after you handle the incorrect data
 
 ## Challenge Summary
 ***Please note: The summary/answers to the questions are found in the PyCitySchools_Challenge.ipynb***

- After removing the reading and math scores, answer the following questions:
How is the district summary affected?

The district summary % overall passing decreased by 1%. Even though this is not an immense change, the decrease indicates that the average of the values converted to NaN were above the average. Thomas High School 9th grades as a whole performed above average with the previous scores. 

- How is the school summary affected?

The overall school summary was not affected. The other values for other schools were unchanged. The only values that changed were values for Thomas High School. 

- How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

In the previous data with the 9th grade Thomas High School, Thomas High School had the 2nd highest % overall passing. Without 9th grade Thomas Highschool reading/math scores, Thomas High school became the school with the lowest % overall passing. The 9th grade Thomas High School math/reading scores previously helped the school's performance and metrics. 

- How does removing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 

Removing the ninth grade scores affected the math and reading scores by Grade cause there was no data for 9th grade scores at Thomas High School, therefore it showed as "NaN". All other values were unchanged. 

The math/reading scores, % passing math/reading, and %overall passing of School Spending ranges $630-644 decreased because Thomas High School falls under this spending range per student. Since ninth grade Thomas high school scores were good and increased overall scores/% passing, the absence of these score data caused this spending range bin to decrease in math/reading scores, % passing math/reading, and % overall passing. 

The % passing math/reading, and %overall passing of the Large School Size  decreased because Thomas High School falls under this school size. Since ninth grade Thomas high school scores were good and increased overall scores/% passing, the absence of these score data caused this school size category to decrease in  % passing math/reading, and % overall passing. 

Since Thomas High School falls under the category of a Charter type, the absence of the 9th grade Thomas High School math/reading scores lowered the % math/reading and % overall of the Charter type data. 
