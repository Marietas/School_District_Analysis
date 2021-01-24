# School_District_Analysis

## Overview of the School District analysis
The purpose of this analysis is to help the School Board identify a piece of evidence that the results for the Math and Reading tests were manipulated, specifically the ones for ninth graders at Thomas High School. To accomplish this, Thomas High School's data was removed (by replacing it with NaNs) to describe how these changes affected the overall analysis.

## Results
-	How is the district summary affected?

Overall, the district summary analysis shows that removing the data for just 461 students of Thomas High School from ninth grade for Math and Reading will not significantly impact the results. The % of passing in math and reading reduced by 0.2% and 0.3%, respectively. 

See comparison on Figure 1 “District Summary Analysis before and after replacing with NaNs”

![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%201%20-%20District%20summary%20analysis%20before%20and%20after%20replacing%20with%20NANs.PNG)

- How is the school summary affected?

Considering that the data remained the same for all the schools, except for Thomas High School, the comparison of the analysis before and after shows no significant changes in the school summary. Once the Math and Reading scores were removed from the database (ninth-grader at Thomas High School),  we can see that the only metric slightly impacted was the % Overall passing with a decrease of 0.31% approximately. 

See Figure 2 “School Summary Analysis before and after replacing with NaNs”

![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%202%20-%20School%20summary%20analysis%20before%20and%20after%20replacing%20with%20NANs.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

As shown in Figure 3 “School Performance before and after replacing with NANs,” the school's performance was not affected, as the % Overall passing was slightly impacted by only 0.31%. In both cases, Thomas High School's ranking remained the same, second place.  

![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%203%20-%20School%20peformance%20before%20and%20after%20replacing%20with%20NANs.PNG)

- How does replacing the ninth-grade scores affect the following:

(i) Math and reading scores by grade
  
As shown in Figure 4, “Math and reading scores by grade before and after replacing with NANs”, replacing the ninth-grade scores only affected Thomas High School’s results, as they were not considered for the analysis. Therefore, ninth-graders data for this specific high school will display NaNs.


![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%204%20-%20Math%20and%20reading%20scores%20by%20grade%20before%20and%20after%20replacing%20with%20NANs.PNG)

(ii) Scores by school spending
 
Considering that Thomas High School belongs to the group with a spending per student between 630 dollars and 644 dollars, Figure 5 shows a slight impact on all outcomes since we removed the math and reading data for ninth graders at this high school.

See figure 5 “Scores by school spending”

![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%205%20--%20Scores%20by%20School%20speeding%20before%20and%20after%20replacing%20with%20NANs.PNG)


(iii) Scores by school size

Similarly described for the Scores by school spending, Figure 6 shows a slight decrease in all outcomes related to the range where Thomas High School belongs (Mid-size), as a consequence of removing the math and reading data for ninth graders at this high school.

See figure 6 “Scores by school size”

![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%206%20-%20Scores%20by%20School%20size%20before%20and%20after%20replacing%20with%20NANs.PNG)

(iv)    






![](https://github.com/Marietas/School_District_Analysis/blob/main/Resources/figure%207%20-%20Scores%20by%20School%20type%20before%20and%20after%20replacing%20with%20NANs.PNG)


