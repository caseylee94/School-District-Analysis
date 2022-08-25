# School-District-Analysis

## Overview

The school board has notified Maria that there has been academic dishonesty in the reporting of grades, specifically for Thomas High School 9th graders. The purpose of this project is to remove the reading and math scores from Thomas High School for the 9th grade class, replace the scores with NaN, and repeat the school district analysis. The analysis is determining the district summary statistics, the individual school summary statistics, the math and reading scores by grade, the scores by school spending, the scores by school size, and the scores by school type. 

## Results

* District analysis:

  * The original district summary:
  * ![Original_District_Summary](/Resources/Original_District_Summary.png)

  * The new district summary:
  * ![New_District_Summary](/Resources/New_District_Summary.png)

  * All of the scores show a slight drop (except for average reading score) with the removal of the dishonest grades.

* School summary:

  * The school summary was only affected in regards to Thomas High School as all the other schools remained the same. The image showing the new school summary is shown below:

  * New School Summary:
![Original_School_Summary](/Resources/Original_School_Summary.png)

  * The percent overall passing dropped from 90.95% to 65.08%
  * The average math score dropped from 83.42% to 83.35%
  * The average reading score dropped from 83.85% to 83.90%
  * The reason the percent overall passing dropped much less than the average scores is because the NaN values are effectively appearing as "0" for some students and the average scores are based on the number of students; the grades that have been replaced with NaN are not being represented in the average causing the scores to appear lower. The percent overall passing is a better indicator of how the scores have changed and is only based on the remaining scores, still has lowered since the dishonest reportings were removed.

* Performance against other schools:
  * This affected Thomas High School's overall performance against the other schools; in the original analysis Thomas High School was in the top 5 performing school but once the 9th graders' scores are replaced with NaN, Thomas High falls to the 8th ranking. 
   * However, once the 9th graders were factored out by analyzing only the 10th, 11th, and 12th grade, which gives us greater insight into how Thomas High truly performed, Thomas High is once again in the top five:
  ![New_Top5_Schools.png](/Resources/New_Top5_Schools.png)
   * The scores have overall dropped slightly but Thomas High retains it's ranking as a top five school.

* Math and Reading Scores by Grade:
  * Replacing the reading and math scores with NaN did not affect the other scores by grade, it just replaced the 9th grade reading and math scores leaving all over the other data intact.

* Scores by School Spending:
 ![New_Scores_School_Spending.png](/Resources/New_Scores_School_Spending.png)
   * Replacing these grades did not affect the scores by school spending. Again, this is because removing the dishonest scores and analyzing the data just for the 10th, 11th and 12th graders gives a much clearer picture of the schools performance. 

* Scores by School Size:
![New_Scores_SchoolSize.png](/Resources/New_Scores_SchoolSize.png)
   * The values for the scores by school size remained relatively unchanged when the 9th graders scores were changed. This is likely because of how large the dataset is and removing one grade luckily does not have a great impact on the overall analysis of the scores by school size.

* Scores by School Type:
  ![New_SchoolType.png](/Resources/New_SchoolType.png)
   * The values for the scores by school type also were largely unaffected by this change in the data.

## Summary
In conclusion 
