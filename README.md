# School_District_Analysis
Module 4: Pandas School District Analysis 

# Overview
This analysis was performed at the request of a local school district to determine the performance of students across the district and to then correlate that information with data related to the sizes of schools, types of schools, and school spending per student. Due to concern about academic dishonesty with the 9th graders at Thomas High School, the original report has been rerun with modified data to eliminate any reading or math grades related to those students.  This report will compare the original analysis and one run after the scores for 9th graders at Thomas High School were changed to NaN, so that the data sets could still be used without risk of inaccuate grades skewing the outcomes. 

![Thomas High School 9th Graders Math And Reading Scores Removed](https://github.com/ghynox/School_District_Analysis/blob/main/Images/ths%209th%20graders%20reading%20and%20math%20removed.png)


# Results:

## District Summary
As shown in the images here, the district summary shows that when removing the 9th graders from Thomas High School, the changes were very small. Average Math Scores dropped by 0.1, Average Reading Score stayed the same, % Passing Math reduced by 0.2%, % Passing Reading dropped by 0.1%, and % Overall Passing dropped by 0.3%

### District Summary With Thomas High School 9th Graders:
![district summary with 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/district%20summary%20with%209th%20graders.png)

### District Summary Without Thomas High School 9th Graders:
![district summary without 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/disctrict_summary_df.png)


## School Summary
The School Summary tables below show that when removing the 9th graders from Thomas High School, the values do shift, but again, like with the District Summary, these changes are very small. All changes were less than 1% or 1 grade point.

### School Summary With Thomas High School 9th Graders
![school summary with 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/school%20summary%20with%209th%20graders.png)

### School Summary Without Thomas High School 9th Graders
![school summary wihtout 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/school_summary_df.png)


## Comparison of Thomas High School vs Other Schools
As seen in the Top 5 Performing Schools tables below it can clearly be seen that Thomas High School standing was not affected by the removal of 9th graders' scores. 

### Top 5 Schools By Overall Passing % With Thomas High School 9th Graders
![top 5 with 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/top%205%20schools%20with%209th%20graders.png)

### Top 5 Schools By Overall Passing % Without Thomas High School 9th Graders
![top 5 without 9th graders](https://github.com/ghynox/School_District_Analysis/blob/main/Images/high_performing_schools.png)


## Removal Of Thomas High School 9th Grader Data Effects:
The removal of 9th grader data from Thomas High School has no effect on the reading or math scores of other grades, and when shown in a table format, only shows the intended "nan" indicating the information was removed. 

![avg math scores by grade](https://github.com/ghynox/School_District_Analysis/blob/main/Images/avg_math_scores_by_grade.png)
![avg reading scores by grade](https://github.com/ghynox/School_District_Analysis/blob/main/Images/avg_reading_scores_by_grade.png)

Scores By School Spending, Scores By School Size, and Scores By School Type were unchanged when removing the 9th grader data as well.
![scores by spending](https://github.com/ghynox/School_District_Analysis/blob/main/Images/scores_by_spending.png)
![scores by size](https://github.com/ghynox/School_District_Analysis/blob/main/Images/scores_by_school_size.png)
![scores by type](https://github.com/ghynox/School_District_Analysis/blob/main/Images/scores_by_school_type.png)



# Summary 
When combining all of the assessments and comparisons from the data before and after removing the Thomas Hhigh School 9th Graders, we see that we do have minor changes with <1 or <1% changes noted in Average Math Scores, % Passing Math, % Passing Reading, and % Overall Passing, and a <1 increase in Average Reading Scores. No other schools are affected, and when reviewing the original data of the scores for 9th graders at Thomas High School, we can see that their performance is very close to the other grade levels at the school. It should also be mentioend that Total School Budget, Total Students, and Per Student Budget will not be affected because while we are removingt he performance data from the 9th graders, we are not teleporting them to an alternate dimension, and thus they will still be counted as registered and the funcding was not changed. 

This report also shows no data-driven proof that any large scale academic dishonesty happened among the reading or math grades for 9th Graders at Thomas High School. Assessment of individual students grades in comparison to students prior grades may be in order to confirm or deny the suspiscions of academic dishonesty. 
