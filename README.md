# School District Grading Analysis
## Purpose
The purpose of this analysis is to analyze the impact of different factors, such as spending per student and school type, on the average test scores for math and reading across different high schools. In addition, there was some evidence of academic dishonestly amongst the 9th grade for Thomas High School, so it was requested to have this information removed from the data set. It is necessary to understand the impact of this removal at the school and district levels before completing the removal. 
## Results of Score Removal 
* **How is the district summary affected by the removal of THS 9th grade scores?** 
Overall, the passing percentages did not significantly change with the removal of the 9th Grade Test Scores. In the tables below, the total number of students still includes the 9th graders from Thomas High School because they are still enrolled; however, the first table includes their test results and the second does not. 

    Results Including 9th Grade Test Results for Thomas High School
        ![district test scores original](https://user-images.githubusercontent.com/105991478/178161182-addd2ff5-df1b-4742-851c-eb13650e3e30.png)

    Results Excluding 9th Grade Test Results for Thomas High School
        ![district test scores](https://user-images.githubusercontent.com/105991478/178161268-39ceaf02-8df4-417a-ac06-1ad98d8259ab.png)

* **How is the Thomas High School summary affected by the removal of 9th grade scores?**
The impact of removing the 9th graders test results is minimal at the school level as well. Though there is some slight variation in the tables below, it is less than a full percentage point. For the table excluding the 9th grade test results, the denominator of the calculation for percentage passing rates was also changed to exclude these students. If these students remained, the score would have decreased significantly. 
      
     Results Including 9th Grade Test Results for Thomas High School
    ![Thomas Original](https://user-images.githubusercontent.com/105991478/178161506-b5bed48d-4e37-443c-a47b-7b5bde855cf0.png)
      
     Results Excluding 9th Grade Test Results for Thomas High School
      
    ![Thomas Scores 9th removed](https://user-images.githubusercontent.com/105991478/178161579-72c18fce-b4ce-4bd0-a92d-8eb475fabc81.png)

* **How does replacing the ninth grader's math and reading scores affect Thomas High School's performance relative to the other schools?**
Removing the ninth grade results does not change the school averages enough to affect Thomas High School's performance relative to the other schools. In both cases, it has the second highest overall performance percentage. 

   Results Including 9th Grade Test Results for Thomas High School
   
    ![ranking before removal](https://user-images.githubusercontent.com/105991478/178162038-76de38bb-f69f-4aa6-9358-98bb83448ca6.png)
    
  Results Excluding 9th Grade Test Results for Thomas High School 
  
  ![ranking after removal](https://user-images.githubusercontent.com/105991478/178162063-938684de-ba35-4ed7-a393-4cf2254f127f.png)

* **How are the math scores per grade affected by removing 9th grade scores?**
The charts below show that the other grades are not affected by the removal of the 9th grade math scores. The only change is the replacement of the 9th grade scores with "nan" for Thomas High School. 


<p align="center" width="100%">
    <img width="41%" src=https://user-images.githubusercontent.com/105991478/178162454-2b6d1f77-034b-4242-8500-b8966d9ffa45.png>  <img width="40%" src= https://user-images.githubusercontent.com/105991478/178162656-034d60af-ef5d-4be7-8f2c-a6cf1de1fe07.png>
</p>

* **How are the reading scores per grade affected by removing 9th grade scores?**
Similar to the math scores, the reading scores of the other grades and schools are not affected, but the results for 9th grade at Thomas high school are changed to "nan"
<p align="center" width="100%">
<img width= "40%" src=https://user-images.githubusercontent.com/105991478/178162736-0ff2e2fd-6c87-426a-b591-6b8eed313c43.png>
</p>


* **How are scores by school spending affected by the removal of ninth grade scoring?**

Thomas High School is in the $631-645 spending range, with a per student budget of $638.00. Because of this, it is possible to see a slight difference in the average scores for the $631-645 spending categories. Similar to before, this different is very insignificant and does not affect analysis in this case. 

Spending Ranges Compared to Average Scores with THS 9th Grade Included 
    ![spending before](https://user-images.githubusercontent.com/105991478/178163031-04738502-0fdc-4f3c-82fe-fee907bb2383.png)

Spending Ranges Compared to Average Scores with THS 9th Grade Excluded
    ![spending after](https://user-images.githubusercontent.com/105991478/178163057-dfde6d4b-a627-4036-8b4b-bec000fa487e.png)

* **How are scores by school size affected by the removal of ninth grade scoring?**
Thomas High School has 1635 total students and falls into the "Medium Size" category. Because of this, it is possible to see a slight difference in the results for medium sized schools before and after removal. However, this difference is very slight and insignificant to analysis. 

Relative School Size Compared to Average Test Scores with THS 9th Grade Included
    ![size before](https://user-images.githubusercontent.com/105991478/178163207-786611c7-d3f5-4103-ac4d-836ed84d852e.png)

Relative School Size Compared to Average Test Scores with THS 9th Grade Excluded
    ![size after](https://user-images.githubusercontent.com/105991478/178163224-4b4fb3d3-5b4c-466f-8096-63fcec1c9ab1.png)
    

* **How are scores by school type affected by the removal of ninth grade scoring?**
* 
Thomas High School is a charter school. The impact of removing the ninth grade test scores to the overall comparison for district versus charter schools is so small that it is eliminated by rounding. 

Average Scores for District Schools Compared to Charter Schools with THS 9th Graders Included
![type before](https://user-images.githubusercontent.com/105991478/178163551-f90503b2-7d85-483b-a2b5-364ebba9e218.png)

Average Scores for District Schools Compared to Charter Schools with THS 9th Graders Excluded 
![type after](https://user-images.githubusercontent.com/105991478/178163605-a7340527-7581-4d0c-b4f2-5599a8281b70.png)

## Summary

Generally, the removal of the ninth grade test scores from Thomas High School does not impact the test results at the district level. There is some impact at the school level, but even this is not enough to change school rankings or give different results to the relationships between test scores and school size, spending or school type. 
