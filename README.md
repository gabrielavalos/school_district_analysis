# school_district_analysis

## Purpose
The purpose of this analysis was to deliver:
 * A high-level snapshot of the district's key metrics, presented in a table format
 * An overview of the key metrics for each school, presented in a table format
 * Tables presenting each of the following metrics:
   * Top 5 and bottom 5 performing schools, based on the overall passing rate
   * The average math score received by students in each grade level at each school
   * The average reading score received by students in each grade level at each school
   * School performance based on the budget per student
   * School performance based on the school size 
   * School performance based on the type of school
   
Our findings will help determine the impact of spending per student, school size, and school type on math and reading scores so future budgeting can be determined by the state. This analysis had to be run twice. The first one included math and reading scores for 9th-12th for all 15 schools in the district (Initial). However, due to academic dishonesty in Thomas High School, the 9th grade math and reading scores for the respective school had to be removed and the analysis had to be rerun. (Updated)

## Results

 * Overall, the ditrict was not significantly effect by the exclusion of the 9th grade math and reading scores. Only Student Total changed between the two DataFrames as the 9th grade math and reading scores for Thomas High School were excluded from the calculations. (Initial: Top, Updated: Bottom)
 
![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/District_Summary_Initial.PNG)
![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/District_Summary.PNG)

 * The Per School Averages and Percentages for all the schools, except Thomas High School, were not effect. See bullet point below for a close up. (Initial: Top, Updated: Bottom)
![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/per_school_summary_initial.PNG)
![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/per_school_summary.PNG)
    * Thomas High School percentages (math, reading & overall) decreased significantly by the exclusion of the Thomas High School 9th grade math and reading scores. This highlighs how the scores of a single grade can have a major impact on overall metrics. (Initial: Top, Updated: Bottom)
    ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Thomas_High_School_Initial.PNG)
    ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Thomas_High_School_Updated.PNG)
    
 * Top five performing schools were not effected by the exlusion of the Thomas High School 9th grade math and reading scores. (Initial: Top, Updated: Bottom)
 ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Top_Performing_Schools_Initial.PNG)
 ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Top_Performing_Schools_Updated.PNG)
 
 * Bottom five performing schools were not effected by the exlusion of the Thomas High School 9th grade math and reading scores. (Initial: Top, Updated: Bottom)
 ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Bottom_Performing_Schools_Initial.PNG)
 ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Bottom_Performing_Schools_Updated.PNG)
 
 * Math and reading averages were only effected in 9th grade for Thomas High School
    * Math Average. Thomas High School 9th grade average is not available in updated analysis.  (Initial: Top, Updated: Bottom)
      ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Average_Math_by_School_Initial.PNG)<br>
      ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Average_Math_by_School_Updated.PNG)
    * Reading Averages. Thomas High School 9th grade average is not available in updated analysis. (Initial: Top, Updated: Bottom)
     ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Average_Reading_by_School_Initial.PNG)
     ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Average_Reading_by_School_Updated.PNG)

  * Average and percentage scores by school spending per student before and after removing the 9th grade scores cannot be conpared as different spending ranges were used. However, The schools with smaller budgets per students outperformed the school with higher budgest per students. (Initial: Top, Updated: Bottom)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Scores_by_Spending_per_Student_Initial.PNG)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Scores_by_Spending_per_Student.PNG)
  
  * Average and percentage scores by school size before and after removing the 9th grade scores cannot be conpared as different size ranges were used. However, Small schools outperform both Medium and Large schools. (Initial: Top, Updated: Bottom)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Scores_by_School%20Size.PNG)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Scores_by_School_Size_Updates.PNG)
  
  * Average and percentage scores by school type before and after removing the 9th grade scores were not effected. However, Charter schools significantly outperform District schools. (Initial: Top, Updated: Bottom)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Initial%20DataFrames/Scores_by_School_Type_Initial.PNG)
  ![](https://github.com/gabrielavalos/school_district_analysis/blob/main/Resources/Images%20for%20README/Updated%20DataFrames/Scores_by_School_Type_Update.PNG)

## Summary
Major Change 1: Student Total in District DataFrame change due to de exclusion of the 9th grade math and reading scorse from Thomas High School.
<br>
<br>
Major Change 2: Thomas High School Math, Reading, and Overall percentages decreased significantly due to the high 9th grade math and reading scores that were excluded.
<br>
<br>
Major Change 3: Math and Reading Averages are completely unavailable for Thomas High School 9th grade; therefore there performance cannot be analyzed at all.
