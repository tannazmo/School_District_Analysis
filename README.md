# School District Analysis

## Overview
The school district would like to look at the data from schools in the district to be able to define their budget for the following school year. They are requesting an analysis of how each school is performing based on their math and reading scores and their budgets allocated to them. 
One the schools in the school district seemed to have dishonest math and reading scores for their 9th grade, so the district decided to disregard that data and redo the analysis without that data.

## Results
We look at District summary, school summary and look at the different metrics to see how they are affected with the changes made.

### District Summary
By looking at the district summary before and after removing math and reading scores for Thomas High school, we see the following changes:

Before

![District_Summary](/Resources/district_summary_before.png "District Summary BEFORE update")

After

![District_Summary](/Resources/district_summary_after.png "District Summary AFTER update")


### School Summary

Looking at the different metrics requested by the school district for each school with the original data and then after replacing math and reading scores for THS's 9th graders, we see the following changes:

Before

![School_Summary](/Resources/school_summary_before.png "School Summary BEFORE update")

After

![School_Summary](/Resources/school_summary_after.png "School Summary AFTER update")

Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools in a way that the overall performance was at about 91% before and after removing that dishonest data, the overall percentage of passing is now at about 65%

### The effect of replacing Math and Reading scores for THS

Before

![Math_and_Reading_Scores](/Resources/math_reading_scores_bygrade_before.png "Math and Reading Scores BEFORE update")

After

![Math_and_Reading_Scores](/Resources/math_reading_scores_bygrade_after.png "Math and Reading Scores AFTER update")

 
After we replaced the math and reading scores for THS, we see that it is not affecting any other place, and just the THS 9th grade for math and reading.
 
### Scores by School Spending
THS's budget per student falls into the $631-645 band
So we now look at how the spending was affected before and after the replacement.

Before

![Scores_by_School_Spending](/Resources/spending_before.png "Scores by school budget BEFORE update")

After

![Scores_by_School_Spending](/Resources/spending_after.png "Scores by school budget AFTER update")

It has not been affected.

### Scores by School Size
We now check the same metrics when grouped by school size:
With the student size of 1635, THS falls into medium sized schools, as we see the metrics have stayed the same after replacement.

Before

![Scores_by_School_Size](/Resources/size_summary_before.png "Scores by school size BEFORE update")

After

![Scores_by_School_Size](/Resources/size_summary_after.png "Scores by school size AFTER update")

### Scores by School Type
And Finally, we look at the data frame when the schools are grouped by their type (District and Charter). Noting that THS is a Charter school:

Before

![Scores_by_School_Type](/Resources/type_summary_before.png "Scores by school type BEFORE update")

After

![Scores_by_School_Type](/Resources/type_summary_after.png "Scores by school type AFTER update")


And as we see both are showing the same results.

## Summary
We compared the results in the previous analysis and the results from the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. And we see that it impacts the Average math score, average reading score and the passing percentages of math and reading and the overall passing percentage. But the updates do not impact the higher level reports such as summary by school size and summary by school type or the school budget per student.

