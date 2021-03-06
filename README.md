# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.
As we worked through this module, we managed to gather plenty of data to help with this analysis. We performed calculations including taking the average scores for each school in math, reading, and then overall, as well as the percentages for the same categories. We also calculated the total budget per each school, as well as the amount spent per each student. In working through the data, we are able to go through different schools and zoom in on their different statistics, if needed. In this specific analysis, we are focusing on Thomas High School and replacing the ninth grade's math and reading scores with NaNs in order to evaluate the data properly without any dishonesty. We are exploring how making these changes will affect the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
#### ***Note: For the pictures, the top picture is the original analysis and the bottom picture is the challenge analysis.***

- ### How is the district summary affected?
  - ![District_Summary.png](Images/District_Summary.png)

  - While looking at the district summary, we can see the subtle differences in the average math scores and in the passing math, reading, and overall percentages. For the average math score, there is approximately a 0.1 difference in the scores; 79.0 in the original and 78.9 in the Thomas Analysis. For the passing math percentage, there is approximately a 0.2 difference in the percentages; 75% in the original and 74.8% in the Thomas Analysis. For the passing reading percentage, there is approximately a 0.3 difference in the percentages; 86% in the original and 85.7% in the Thomas Analysis. For the overall passing percentage, there is approximately a 0.1 difference in the percentages; 65% in the original and 64.9% in the Thomas Analysis. Overall, the Thomas Analysis has a slight change -- lower percentage -- in its percentages.

- ### How is the school summary affected?
  - ![School_Summary.png](Images/School_Summary.png)

  - Comparing the Thomas High School data from the original to the one in the challenge, there are significants changes for the percentage categories. If we look at the average math and reading scores, there are minimal differences between the two: 1) approximately a 0.07 difference (when rounding to the hundreth place) between the original summary (83.42) and the Thomas summary (83.35) in the average math score and 2) approximately a 0.05 difference between the original (83.85) and the Thomas summary (83.90) in the average reading score. Between the original analysis and the Thomas analysis, the passing percentages dropped extensively with the drop estimating from 17% to 25%. We can conclude that the school summary was significantly affected by the change in scores.


- ### How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
  - When using the School Summary data, we can see that replacing the ninth graders' math and reading scores drops their passing rates significantly. Especially, if we only look at the charter schools, Thomas High School has the lowest passing percentages compared to the others. When compared to the other schools, regardless of type, Thomas High School seems to be average.

- ### How does replacing the ninth-grade scores affect the following:

- ##### Math and reading scores by grade
  - [Original Math and Reading Scores](Images/Original_MathReading_Scores.png)

  - [Thomas Math and Reading Scores](Images/Thomas_MathReading_Scores.png)

    - No changes in the scores.
 
- ##### Scores by school spending
  - [Original Spending Summary](Images/Original_Spending.png) 
  
  - [Thomas Spending Summary](Images/Thomas_Spending.png)
   
    - Looking at the $631-645 category, it is obvious there are changes in each category. The differences range from approximately 0.01 to 0.08. The average math and reading scores have approximately a 0.01 difference. The % passing math has approximately a 0.02 difference. The % passing reading and % overall passing have approximately a 0.08 difference.
 
- ##### Scores by school size
  - [Size Summary with decimal points](Images/Size_Summary.png)
    - When we look at the Medium (1000-1999) category, it is obvious there were changes in the scores and percentages across the board. For the Average Math Score, Average Reading Score, and % Passing Math categories, there is approximately a 0.01 difference. For the % Passing Reading and % Overall Passing, there is approximately a 0.6 difference.
  
  - [Size Summary with formatted decimal points](Images/SIze_Summary_2.png)
    - Rounding to the nearest whole number, there are no changes apparent in the data.
    
- ##### Scores by school type
  - [Type Summary with decimal points](Images/Type_Summary.png)
    - Within the charter type, there are slight changes in the scores and percentages. For the average math and reading scores and the % passing math, the difference is approximately 0.01; even less than 0.01 of a difference. For the % passing reading and the % overall passing, the difference is approximately 0.04.

  - [Type Summary with formatted decimal points](Images/Type_Summary_2.png)
    - When we rounded to the nearest whole number, the data remained the same.


## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. While looking at the types, Thomas High School has the lowest scores and passing percentages amongst the other charter schools. When compared to the district schools, Thomas High School scores at about their level.
2. If we examine the data from the size summary and type summary from the formatted versions, there are no changes. However, when we look at the data with more decimal points, we can see there are changes. Within the original analysis, charter schools had slightly higher scores and percentages than the ones exhibited in the challenge (Thomas) analysis. Within the the original analysis, Medium (1000-1999) sized schools also had slightly higher scores and percentages than the ones seen in the challenge analysis. It should be noted that the only category in which it was not higher was in the Average Reading Score.
3. When we look at the school summary, the percentage of students who passed reading, math, and overall dropped astronomically. Out of all the summaries, the school summmary percentages were the most affected by the change in data.
4. Overall, if we look at the data while rounding scores and percentages to the nearest whole number, it looks like there's not much difference in the data, besides in the school summary. 
