# PyCitySchools with Pandas

## Overview of the School District Analysis
Upon completing an analysis of school district data relating to standardized testing scores, it was discovered that the reading and math scores for the 9th grade class at Thomas High School (THS) appear to have been altered.  Though the full extent of academic dishonesty is not known, the school board would like to uphold testing standards and evaluate upon removal of the altered scores.  We will explore the impact of the data removal on the district and school summaries, the impact upon THS performance compared to other schools in the district, and the impact upon

## School District Analysis Results
* District Summary Impact
  * Before Removing THS 9th Grade Scores:  ![Old_District_Summary](Resources/district_summary_old.PNG)
  * After Removing THS 9th Grade Scores:  ![New_District_Summary](Resources/district_summary_new.PNG)
  * Upon review of changes to district summaries, the average math scores decreased by .1%, reading average scores remained the same, percent of students passing math decreased by .2%, passing reading decreased by .1%, and the percentage of overall passing students decreased by .3%.  Removing THS 9th graders' scores has a seemingly minor impact on score averages and passing percentages for the district as a whole.

* School Summary Impact
  * Before Removing THS 9th Grade Scores:  ![Old_School_Summary](Resources/school_summary_old.PNG)
  * After Removing THS 9th Grade Scores:  ![New_School_Summary](Resources/school_summary_new.PNG)
  * Of course, removing the dishonest THS 9th grade scores from the data did not have an impact on any high school but THS.  Removing these scores had an impact on the THS averages and passing rates.  Average math scores decreased by .07%, average reading scores increased by .05%, percent of students passing math decreased by .09, percent passing math in THS dcecreased by .29%, and overall passing students decreased by .32%.  Again, removing the scores did not appear to have a significant impact on average school scores and average passing rate at THS.

* Impact on THS Performance (Relative to Other Schools)
  * Top 5 Schools Before Removing THS 9th Grade Scores:  ![Old_Top_Five](Resources/old_top_five.PNG)
  * Top 5 After Removing THS 9th Grade Scores:  ![New_Top_Five](Resources/new_top_five.PNG)
  * Relative to the other schools, while the values for THS overall did change, the changes were not significant enough for THS to lose its standing as the #2 school in the disctict.

* Additional Impact Analysis:
  * *Math Scores (Before Removing THS 9th Grade Scores): 
  ![Old_Math_Scores](Resources/math_scores_by_grade_old.PNG)
  * Math Scores (After Removing THS 9th Grade Scores):  
  ![New_Math_Scores](Resources/math_scores_by_grade_new.PNG)
  * Reading Scores (Before Removing THS 9th Grade Scores):  
  ![Old_Reading_Scores](Resources/reading_scores_by_grade_old.PNG)
  * Reading Scores (After Removing THS 9th Grade Scores):  
  ![New_Reading_Scores](Resources/reading_scores_by_grade_new.PNG)

  * Scores by school spending
  * Scores by school size
  * Scores by school type

## School District Analysis Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Regardless, there are minimal changes required to utilize this script to analyze any election data.
