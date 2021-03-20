# School District Analysis

## Overview
In general, this analysis was intended to demonstrate the differences in math & reading scores when you consider factors like grade, school, school-type, school-size, and spending. However, since we found out that there were allegations of academic dishonesty, this particular analysis sought to find any discrepancies with this data when filtering out the results from 9th graders at Thomas High School. While we do not know the full extent of the academic dishonesty, the school-board would still like to replace all the Thomas 9th grade values with null values to take note of any differences. 
  
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- District Summary 
  - The number of 9th graders at Thomas High School was fairly minimal compared to the dataset as a whole. These numbers in the district summary dataframe did change, but did not change by any more than 0.1-0.3 percentage points. The biggest numerical difference between these dataframes is that the "% Overall Passing" shrunk from 65.2% to 64.9% after filtering out the 9th grade Thomas test scores.

- School Summary 
  - When filtering out the Thomas 9th grade scores, the school summary dataframe remains exactly the same for all other schools. This makes sense because only data for Thomas High School has been altered. After removing the 9th grade values, we can see that the average math score declined from 83.41 to 83.35 while average reading score for THS rose from 83.85 to 83.90. And even though the average reading score increased, the toal % of students from Thomas High School who passed reading still decreased from 97.30 to 97.02%. The overall passing percentage for Thomas High School also decreased from 90.95 to 90.63%. 


- Thomas High School’s Relative Performance
  - As explained above, Thomas High School's overall passing percentage only decreased by about 0.3%. Using this metric, Thomas was the 2nd best performing school in their district prior to replacing the 9th grade math and reading scores with null values. Even after editing the data, this 0.3% change was not enough to move them out of the 2nd spot in the highest performing schools. 

How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - The math and reading scores by grade essentially remain unaffected when these scores by grade are sorted by their schools. Since the only data being replaced was for Thomas 9th graders, all other grade values for other schools remain the same while Thomas 9th grade scores were replaced with null values. 
  - Scores by school spending
    - 
  - Scores by school size
  - Scores by school type

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
