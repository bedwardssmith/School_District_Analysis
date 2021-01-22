# School_District_Analysis
The school board is required to provide analysis of math and reading schools for reporting purposes.  After completion of the initial analysis the school board had reason to believe that the reading and math grades for Thomas High School ninth graders had been altered.  Although the school board does not know the full extent of the academic dishonesty they have asked that the ninth grade math and reading scores for Thomas High School be removed from the reports.


## Project Overview
This project included the updating of the reports noted below to exclude the ninth grade math and reading scores for Thomas High School and an analysis completed to determine how the removal of these scores affected these reports.

### Reports
* District Summary 
* School Summary
* School Performance
* Math and Reading Scores By Grade
* Scores By School Spending
* Scores By School Size
* Scores By School Type


## Resources
* Data Source: schools_complete.csv and students_complete.csv
* Jupyter Notebook: 6.0.3
* Software: Python 3.8.3

## School District Analysis Results
The analysis, as reflected below, reviewed the various results both before and after the exclusion of the Thomas High School ninth grade math and reading scores.

### District Summary
* Due to the total total student population in comparison to the number of ninth grade Thomas High School students, 39,170 and 461 respectively, there were minimal differences between the original summary and the summary excluding the marks of these students.  Specifically we can see from the comparison that there is a .1% decrease in the average math score, .2% decrease in the % passing math score, .1% decrease in the % passing read score, and a .3% decrease in the overall passing rate.  Links are provided below to both summaries.

  Original Report: https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/District_Summary_Original.png
  Revised Report: https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/District_Summary_9th_Grade_Removed.png

### School Summary
* In reviewing the school summary, specifically for Thomas High School, it is important to note that of the 1,635 Thomas High School student population there were 461 ninth gradestudents for which math and reading scores were removed from the caluclations.  This reduction accounts for 28% of the student population of Thomas High School.  Although 28% is not an insignificant % we can see from the summaries that there was an immaterial change between the results including the ninth grade student marks and the results excluding the ninth grade student marks.  The specific changes are summarized below:

  * The average math score decreased from 83.42% to 83.35%, or a decrease of .07%.  
  * The average reading score increased from 83.85% to 83.90%, or an increase of .05%.
  * The % passing math decreased from 93.27% to 93.19%, or a decrease of .08%
  * The % passing reading decreased from 97.31% to 97.02%, or a decrease of .29%
  * The % overall passing decreased from 90.95% to 90.63%, or a decrease of.32%

  Original Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Per_School_Summary_Original.png
  Revised Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Per_School_Summary_9th_Grade_Removed.png

### Performance of Thomas High School Relative To The Other Schools
* This particular summary ranked schools within the district based on reading and math marks.  Thomas High School ranked 2nd where the grade 9 reading and math scores were included and excluded.  This is not surprising given the immaterial differences in scores noted in both the district and school summaries.

  Original Report: https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Top_5_School_Original.png
  Excluding Ninth Grade Thomas High School:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Top_5_Schools_9th_Grade_Removed.png

### Math and Reading Scores By Grade
* The math and reading scores by grade summarized the scores on a per school basis, therefore, the only change between the original summary and that which had the 9th grade Thomas High School scores removed was the 9th grade scores reflecting NaN in the revised summary.  It is important to point out as we continue the analysis that the Thomas High School ninth grade math and reading score at 83.7% was not significantly different then other schools the lowest being Hernandez High School at 90.9% and the highest being Shelton High School at 84.1%.  

  Original Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Math_and_Reading_Scores_By_Grade_Original.png
  Excluding Ninth Grade Thomas High School: https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Math_and_Reading_Scores_By_Grade_9th_Grade_Removed.png

### Scores By School Spending
* As can be seen in the per school summary Thomas High School budget spend per student was $638, thereby, placing them in the third bucket in the scores per school spending analysis.  In reviewing the score by school spending analysis there is no change between the schedule including the grade 9 Thomas High School math and reading scores and that which excludes these scores.

  Original Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_School_Spending_Original.png
  Revised Report: https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_School_Spending_9th_Grade_Removed.png

### Scores By School Size
* As noted within the District Summary Thomas High School has a student population of 1,635 placing it in the medium category. We can see from comparing the score by school size summary including the grade 9 Thomas High School math and reading grades and the summary excluding these grades that there are no changes in the scores reported.

  Original Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_Size_Original.png
  Revised Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_Size_9th_Grade_Removed.png

### Scores By School Type
* Thomas High School is a Charter School, therefore, when looking at the scores by school type the focus is Charter schools.  Similiar to the scores by school spending and scores by school size there is no impact to the removal of the grade 9 Thomas High School math and reading scores which can be seen when reviewing the summary including these scores to the summary excluding these grades.

  Original Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_School_Type_Original.png
  Revised Report:  https://github.com/bedwardssmith/School_District_Analysis/blob/main/Resources/Scores_By_School_Type_9th_Grade_Removed.png
 
 ## School District Analysis Summary
The Thomas High School grade 9 student population is 461 which amounts to 1.18% of the total student population which is 39,170.  As expected the removal of the grade 9 Thomas High School scores had minimal impact on the district summary.  As can be seen in the attached and as summarized above the change resulted in a .2% decrease in the % passing math score, .1% decrease in the % passing read score, and a .3% decrease in the overall passing rate and no change to the average reading score.

 
 
