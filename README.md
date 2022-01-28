# PyCity School District Analysis
## Overview
We are assigned the task to help Maria perform analysis on PyCity school district for the school board. Analysis includes overview of key metrics for each school, average math and reading score, overall passing rate and school performances based on budget per student, school size and types. Analysis is performed using Jupyter Notebook by Python. Upon discovery of academic dishonesty from Thomas High School ninth graders, the math and reding scores for Thomas High School are replaced with NaNs to uphold the state-testing standards. The same school district analysis is performed with altered grades excluded and we compare the analysis to show the impact of the changes on the overall analysis.
## Results
All math and reading scores from Thomas High school ninth graders are replaced with NaNs and passing percentages for math, reading and both scores are recalculated based on 10th-12th graders from Thomas High School.
- The tables for old and updated district summary tables show that the overall average scores and percentage of students who pass the exam all decrease after excluding ninth grader scores. The average math score decreases from 79.0 to 78.9. Average reading score decrease by 0.02 but after rounding it remains the same as 81.9. Percentage of students who pass math decreases from 75% to 74.8%, percentage of students who pass reading decreases from 85.8% to 85.7%; percentage of students who pass both decrease from 65.2% to 64.9%.

District Summary Comparison (Top: orignal; Bottom: updated)
![district_summary_comparision](/Resources/district_summary_comparison.png)

- The school summary generally remains the same except minor difference in the average score and student passing percentage in Thomas High School. The summary for Thomas High School before and after replacement is shown in table below (top: original summary; bottom: updated summary). After excluding the ninth grader scores, average math score deceases by 0.1, average reading score increases by 0.05 points. Percentage of students who pass math decreases by 0.11% while percentage passing reading decreases by 0.3%, percentage of students who pass both decrease by 0.3%.

School Summary Comparison (Top: orignal; Bottom: updated)
![school_summary_comparison](/Resources/school_summary_comparison.png)

- Each school’s performance is ranked by percentage of students who pass both math and reading and top five schools from original (top panel) and updated (bottom panel) analysis shows below. Even though replacing ninth grader’s scores decreases the overall percentage passing from 90.948% to 90.630%, Thomas High School’s performance still ranks third compared to the other schools.

Top Schools Comparison (Top: orignal; Bottom: updated)
![top_schools_comparison](/Resources/top_schools.png)

- Replacing the ninth-grade scores also affect math and reading scores by grade, school spending, school size and school types.
   - Math and reading scores by grade
   The average math and reading scores by grade are not affected for other schools and 10th to 12th grades. The only difference is that the average math and reading scores from 9th grade in Thomas High School changes from 83.6 and 83.7 to NaN.
   
   Math Scores by Grade (Top: orignal; Bottom: updated)
   ![math_scores_bygrade](/Resources/math_scores_bygrade.png)
   
   Reading Scores by Grade (Top: orignal; Bottom: updated)
   ![reading_scores_bygrade](/Resources/reading_scores_bygrade.png)
   
   - Scores by school spending
   Average scores for spending range per student remained affected by the change except minor difference in $630-644, which Thomas High School belongs to. Average math score in this range decreases by 0.01 point; average reading score increases by 0.01. Percentage student passing math decreases by 0.02%; Percentage student passing reading decreases by 0.08%; students passing both decreases by 0.1%. Because the difference is in 0.1%, after rounding, the scores by school spending remain the same.  
   
   Scores by School Spending (Top: orignal; Bottom: updated)
   ![score_spending](/Resources/score_spending.png)
   
   - Scores by school size
   Average scores for different school sizes remained the same based on rounded up numbers. However, similarly to scores by school spending, there is minor difference from the raw data in medium size schools, which Thomas High School belongs to. Average math score from medium school size decreases by 0.01 point; average reading score increases by 0.01. Percentage student passing math decreases by 0.01%; Percentage student passing reading decreases by 0.06%; students passing both decreases by 0.1%. Because the difference is in decimal ranges, after rounding, the scores by school spending remain the same.  
   
   Scores by School Size (Top: orignal; Bottom: updated)
   ![scores_school_size](/Resources/scores_school_size.png)
   
   - Scores by school type
   Average scores for different school types remained the same based on rounded up numbers. However, similarly to scores by school spending and size, there is minor difference from the raw data in Charter, which Thomas High School belongs to. Average math score from medium school size decreases by approximately 0.01 point; average reading score increases by 0.01. Percentage student passing math decreases by 0.01%; Percentage student passing reading decreases by 0.03%; students passing both decreases by 0.04%. Because the difference is in decimal ranges, after rounding, the scores by school spending remain the same.  
   
   Scores by School Type (Top: orignal; Bottom: updated)
   ![scores_by_school_type](/Resources/score_type.png)
   
## Summary
Replacing reading and math scores for the ninth grade at Thomas High School made a slight impact on the school district metrics. 
1.    The major impact is on school district summary, excluding the ninth graders decrease overall average math score, average reading score, the percentages of students who pass math, reading and both.
2.    The school summary from Thomas High School has slightly higher average reading score after the replacement, but average math score, percentages of student passing math, reading and both all decrease slightly. However, the minor change in the scores doesn’t impact the overall ranking of Thomas High School.
3.    Replacing the math and reading score didn’t change scores from other schools or from 10th to 12th grade from Thomas High School. The only difference is ninth grader’s cores are shown as NaN.
4.    When categorizing average scores by spending per student, school size and school type, the scores in the categories with Thomas High School are affected slightly. Overall, average reading scores are increased by decimal amount while average math scores, percentage of student passing math, reading or both all decrease by decimal amounts. After rounding up, the differences disappear so the impact is generally small but not insignificant. 
     

