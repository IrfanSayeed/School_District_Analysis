# School_District_Analysis
# **School_District_Analysis**
##### Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv (Saved in Source folder)
##### Jupyter Codes: PyCitySchools_Challenge.ipynb

## **Background:**

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## **Overview of the School District Analysis:**

The purpose of the school district analysis is to provide understandings on school performance trends and data analysis for accuracy. This will allow the school board to to see the full extent of academic dishonesty of Thomas High School.

## **OUTCOMES:**

Re-assessment of school summaries and individual school performance identified that grade 9 math and reading original scores were changed. The analysis was repeated using cleaned data, where all grade nine math and reading scores for Thomas High School were replaced with "NaN" values.  This affected 461 students of a total of 39,170 high school students in the district. 

* **How is the district summary affected?**

 The overall district summary explain minimal impact, affecting only the overall average of math score.
 
  <img width="705" alt="District_Summary_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134528624-bc9d17c2-a820-42e5-b825-332fcb0b8603.PNG">
  
 * **How is the School Summary Affected?**

 A more significant change can be seen while reviewing the individual school summaries.  Noted below, Thomas High School sees a significant once re-assessed.  While average scores saw mininmal changes, all three KPI's for student Passing Math, Reading and Overall Combined percentages saw dramatic decreases.
 
- The district summary was affected due to the decrease in the total amount of students, which lead to changes in values like "Spending Ranges (Per Student)".
- The same can be said about the school’s summary with the values of the overall summery, percent passing in reading and math scores.
- The replacement of the Ninth grade from the data caused a decrease in total student count, which in turn increased alot of the school's previous values.

## How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade: No change
Scores by school spending: Increase
Scores by school size: Increase
Scores by school type: Increase
  
***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

 The grade 9 scores being replaced with NaN's saw a significant decrease to all three KPI's for student Passing Math, Reading and Overall Combined percentages.
 
 Decreased noted for Thomas High Scholl are noted below:
 
      * % Passing Math decreased by 26.4%
      * % Passing Reading decreased by 27.5%
      * % Overall Passing decreased by 25.9%
      
 **Top 5 and bottom 5 performing schools**
 
 The greater impact can be seen in the top 5 performing schools.  Initially, Thomas High School ranked 2nd in the top performing schools; however, upon reassessment we can see Thomas High School falling out of the top 5 schools, from 2dn to 8th place.
 
![Top5_Bottom5](https://user-images.githubusercontent.com/89538802/134688731-95e8e0b2-fd86-45e1-b7ca-9363db73444e.PNG)

* **How does replacing the ninth-grade scores affect the following:**

     * **Math and reading scores by grade**
   
       The grade nine scores for Thomas High School will display NaN (Not a Number) for both Math and Reading scores with the re-assessment.  This ensured
       that the tampered scores did not affect future calculations.  Had all grade nine scores or all of Thomas High School been subjected to NaN scores,
       both district and school averages would have been negatively impacted.
       
       As with the district summary impact to the KPI's for student Passing Math, Reading and Overall Combined percentages can be seen per below:
       
     * **Scores by school spending**
   
      * % Passing Math decreased by 6%
      * % Passing Reading decreased by 7%
      * % Overall Passing decreased by 7%
 
     ![Scores_By_Spending](https://user-images.githubusercontent.com/89538802/134687928-c469fd5f-6758-40bd-aec2-2f0aaa76e661.png)
     
     * **Scores by school size**

      * % Passing Math decreased by 8%
      * % Passing Reading decreased by 6%
      * % Overall Passing decreased by 6%
 
![Scores_By_Size](https://user-images.githubusercontent.com/89538802/134689485-20e0b7d8-df47-481e-b854-9db7e350e862.png)

     * **Scores by school type**
     
      * % Passing Math decreased by 4%
      * % Passing Reading decreased by 4%
      * % Overall Passing decreased by 3%
      
![Scores_By_Type](https://user-images.githubusercontent.com/89538802/134690305-2cd896c0-7b6c-4439-ad31-4ba1040885fb.png)

## **Summary:**

In this analysis we removed all the values for the “Ninth Grade” students at Thomas High School. We did a summary for the scores of each school in math and reading. The Binning of the schools according to "Budget" and "school size", and to top it all of we formated the dataframe to make the values more presentable.

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Thomas High School dropped in overall ranking performance from 2nd place to 8th place.

2. School Spending (Per Student) in bin $630-644 saw a decrease by:
     
      * % Passing Math decreased by 6%
      * % Passing Reading decreased by 7%
      * % Overall Passing decreased by 7%
  
3. Medium (1000-2000) schools saw a decrease by:

      * % Passing Math decreased by 8%
      * % Passing Reading decreased by 6%
      * % Overall Passing decreased by 6%
 
4. Charter schools saw a decrease by:

      * % Passing Math decreased by 4%
      * % Passing Reading decreased by 4%
      * % Overall Passing decreased by 3%
