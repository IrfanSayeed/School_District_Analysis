# School_District_Analysis
# **School_District_Analysis**

## **Background:**

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

##### Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv
##### Software: Python 3.7.10 , Jupyter Notebook

## **Overview of the School District Analysis:**

The purpose of the school district anlaysis is to aggregate the data to provide insights on performance trends and patterns on all standardized test data for analysis, reporting and presentations. This will allow the school board to have informed discussions and make strategic decisios on student funding, budgets and school priorities.

## **Results:**

A re-assessment of both the school summaries and individual school performance, show that the altered grade 9 math and reading scores skewed the inital testing results.  The analysis was repeated using scrubbed data, where all grade nine math and reading scores for Thomas High School were replaced with "NaN" values.  This affected 461 students of a total of 39170 high school students in the district. Representing 1% of the student population test scores.

Noted changes to the School District Analysis are as noted below:

* **How is the district summary affected?**

 The overall district summary saw minimal impact, affecting only the overall average math score lowered by  0.1%.
 
  ##### Revised District Summary
  
  ![District Summary](https://user-images.githubusercontent.com/90229438/151922915-9b5038d8-2d6b-4e23-b1ae-1aaddbbfeeb6.PNG)

 * **How is the school summary affected?**

 A more significant change can be seen while reviewing the individual school summaries.  Noted below, Thomas High School sees a significant once re-assessed.  While average scores saw mininmal changes, all three KPI's for student Passing Math, Reading and Overall Combined percentages saw dramatic decreases.
 
  ##### Original Per School Summary
  
  
  
  ##### Revised Per School Summary
  
  
  ![ThomasHS](https://user-images.githubusercontent.com/90229438/151922959-d25b1a17-c9fa-4c3d-90ac-601e9789cdb7.PNG)

***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

 The grade 9 scores being replaced with NaN's saw a significant decrease to all three KPI's for student Passing Math, Reading and Overall Combined percentages.
 
 Decreased noted for Thomas High Scholl are noted below:
 
      * % Passing Math decreased by 26.4%
      * % Passing Reading decreased by 27.5%
      * % Overall Passing decreased by 25.9%
      
 **Top 5 and bottom 5 performing schools**
 
 The greater impact can be seen in the top 5 performing schools.  Initially, Thomas High School ranked 2nd in the top performing schools; however, upon reassessment we can see Thomas High School falling out of the top 5 schools, from 2dn to 8th place.
 


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
 
    
     
     * **Scores by school size**

      * % Passing Math decreased by 8%
      * % Passing Reading decreased by 6%
      * % Overall Passing decreased by 6%
 


     * **Scores by school type**
     
      * % Passing Math decreased by 4%
      * % Passing Reading decreased by 4%
      * % Overall Passing decreased by 3%
      


## **Summary:**

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
