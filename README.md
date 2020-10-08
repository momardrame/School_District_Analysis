<img src="Resources/school.png" alt="drawing" width="300"/>

# School District Analysis

## Project Overview
In a school district dataset, the  average scores for ninth graders from one high school are incorrect. This project aims to replace the math and reading scores for that high school, before reassessing academic performance for the school district.

## Resources
Data Source: clean_students_complete.csv, missing_grades.csv, schools_complete.csv and students_complete.csv
Software: Jupyter Notebook, Python

## Objective
The goals are to:
- Filter DataFrames using logical operators.
- Replace the incorrect values with NaN.
- Explain how your PyCitySchools analysis changes after handling the incorrect data.  

## Summary
After replacing the reading and math scores, complete the following steps and answer the questions for each step.

### How is the district summary affected?
The altered district summary produced a lower percentage for passing Math, Reading and the Overall passing scores decreased

#### Original District Summary                 
  - % Passing Math = 75
  - % Passing Reading = 86
  - % Overal Passing = 65
  
#### Altered District Sumary
   - % Passing Math = 53
   - % Passing Reading = 61
   - % Overall Passing = 46
   
####  How is the School Summary affected?
  The altered school summary was affected by producing for the most part lower percentages scores but the averages
  in a few high school were a bit higher
  
#### Original School Summary
   - Bailey High Average Math and Reading score = 77.04843 & 81.03396
   - Cabrera High Average Math and Reading score = 83.0619 & 83.97578
   - Figueroa High Average Math and Reading score = 76.71177 & 81.15802
   - Ford High Average Math and Reading scoe = 77.10259 & 80.74626
   - Griffin High Average Math and reading score = 83.3515 & 83.81676

#### Altered School Summary
 - Bailey High Average Math and Reading score = 77.03383 & 80.9224
 - Cabrera High Average Math and Reading score = 83.04887 & 84.04887
 - Figueroa High Average Math and Reading score = 76.83803 & 81.14142
 - Ford High Average Math and Reading score = 76.98951 & 80.79591
 - Grifin High Average Mate and Reading scores 83.85647 & 67.64305

####   Recalculate the high- and low-performing schools.
  - After recalculating the high and low performing schools, Thomas Hhigh School was in the top-five high performing schools
  - Average Math and Reading score = 83.350937 & 83.896082
  - % Passing Math and Reading Score = 66.911315 & 69.663609
  - % Overal passing score = 65.076453
  
#### Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
 - How does replacing the ninth-grade scores affect the following?
  - math_scores_by_grade Original and Altered dataframe: changes occured in the altered dataframe for the 9th grade
  - reading_scores_by_grade Original and Altered dataframe: changes occured in the altered dataframe for the 9th grade
 
#### Scores by School Spending
- How does replacing the ninth-grade scores affect the following?
 - The %PassingMath, %Passing Reading and %Overall Passing scores were less in the Altered dataframe compared to the original dataframe
 - Spending Range(per Student) <$584 
    - Original dataframe: Average Math Score and Average Reading Score  = 83.5 and  83.9
    - Altered dataframe: Average Math Score and Average Reading Score = 83.5 and 84.0
    - For the remaining spending ranges in the Original and Altered dataframe the Average Math Score and Average Reading Score                 
      experienced a very slight change in their scores
      
#### Scores by school size
- How does replacing the ninth-grade scores affect the following?
  - For all school sizes, small, medium and large, the %PassingMath, %Passing Reading and %Overall Passing scores were less in the   
    Altered dataframe compared to the original dataframe.
  - For the remaining school size, small, medium and large; in the Original and Altered dataframe the Average Math Score and Average               
    Reading Score and the Average Math Score experienced a very slight change in their scores
    
 #### Scores by School type
- How does replacing the ninth-grade scores affect the following?
 -For Charter and District Schools, the %PassingMath, %Passing Reading and %Overall Passing scores were less in the   
  Altered dataframe compared to the original dataframe.
 - For the remaining  Charter and District School Type; in the Original and Altered dataframe the Average Math Score and Average Reading                  
    score experienced a very slight change in their scores.


## Background
## Project Overview
## Resources
## Data Source
## Machine Learning Model
## Findings and Recommendation
