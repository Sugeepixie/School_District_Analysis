# School_District_Analysis - PyCitySchools_Challenge
School districy analysis with Python

## Overview of Project
The purpose of the project is to assist Maria, the chief data scientist for a city school district in analyzing the standardized testing results from a large number of schools state-wide. Analysis involves Math and Reading test scores for different high school grades and see how removing test results from Thomas High School's 9th grade class affect the overall results.

In this analysis, we replaced Thomas High school's 9th grade reading and math scores with NaN then renalyzed the following
  * The District summary
  * The school summary
  * The top and bottom 5 performing schools based on the overall passing rate
  * The average reading score and math score for each grade level from each school
  * The scores by school spending per student, by school size and by school type

 ## School_District_Analysis Results
 
 * How is the district summary affected?
    After removal of Thomas High school 9th grade results, the district summary shows slight decrease in passing percentage of math, reading, and overall passing. Review the snippet below for original vs revised summary.
    
   District Summary -original
   
  ![DistrictSummary_original](https://user-images.githubusercontent.com/76926148/188770652-86128638-27e9-4289-b5e2-e6671186f9d2.PNG)
  
  District Summary - revised
  
  ![DistrictSummary_revised](https://user-images.githubusercontent.com/76926148/188770704-79a760f4-b1e0-434c-b461-96a491373243.PNG)


 * How is the school summary affected?
     The school summary changed by slight increase in avarage reading score and decrease in other areas.
     
     School Summary -original
     
    ![SchoolSummary_original](https://user-images.githubusercontent.com/76926148/188770743-bd4b6e7f-4c3e-48a4-9bd5-c68d21dd9382.PNG)
    
    School Summary - revised
    
    ![SchoolSummary_revised](https://user-images.githubusercontent.com/76926148/188770767-e068a585-8d08-4fdd-9809-6d29d9fa2ef5.PNG)

 * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    Removing ninth graders math and reading scores did not impact on Thomas High school's performance. when the revised calculations are rounded to the nearest whole number the percantages remained  the same.

 * How does replacing the ninth-grade scores affect the following:

    * Math and reading scores by grade
      - slight increase in avarage reading score and decrease in avarage math score

 Math -original
 
![MathScoresByGrde_original](https://user-images.githubusercontent.com/76926148/188770846-5e832288-28e0-41e9-b68d-1bf4c70d7bef.PNG)

 Math - revised
 
![MathScoresByGarde_revised](https://user-images.githubusercontent.com/76926148/188770854-97854178-0565-48bd-8bb9-ab27d86bd398.PNG)

 Reading -original


![ReadingScoresByGrade_original](https://user-images.githubusercontent.com/76926148/188770890-35702a6c-e57f-40a5-86a7-9d73b930cf99.PNG)

Reading -revised

![ReadingScoresByGrade_revised](https://user-images.githubusercontent.com/76926148/188770894-8bf98f67-573c-4c5b-bf4b-c18ed5b87484.PNG)


 * Scores by school spending
 
      - No change
      
  ScoresBySpending - original  
  
 ![ScoresBySpending_original](https://user-images.githubusercontent.com/76926148/188771210-f0cbfa5f-b1fc-4bc5-b6a2-e4b9e747017d.PNG)
 
  ScoresBySpending - revised
  
 ![ScoresBySpending_revised](https://user-images.githubusercontent.com/76926148/188771223-77dd6cbe-d87d-4f3a-9a9e-45286cbd5bd7.PNG)

      
 * Scores by school size
    
      - No change
      
     ScoresBysize - original
     
  ![ScoresBysize_original](https://user-images.githubusercontent.com/76926148/188771279-0e9e731f-5017-4c46-a7cb-01dbf3132c7f.PNG)

    ScoresBySize - revised
    
  ![ScoresBySize_revised](https://user-images.githubusercontent.com/76926148/188771289-73d0a324-b19a-411f-9cfa-a411c3edbe3b.PNG)

      
  * Scores by school type
      - No change
      
ScoresByType - original

![ScoresByType_original](https://user-images.githubusercontent.com/76926148/188771309-8acdb9d3-7906-4f71-8058-337a1d51cb78.PNG)

ScoresByType - revised

![ScoresByType_revised](https://user-images.githubusercontent.com/76926148/188771317-f96d742a-3976-4183-b583-bdfb7c310d40.PNG)


 ## School_District_Analysis Summary
 
    The changes that appeared after removing reading and math scores for the 9th grade at Thomas High School were the following:
  * Decrease in total number of students
  * Increase in avarage reading score and decrease in avarage math score
  
