# School_District_Analysis

## Overview
I was given the task of helping the PyCity School District with an analysis of the overall district performance, individual school performances, the top and bottom performing schools, average math and reading scores for each grade from each school, and the scores by school spending, school size and school type. After the initial analysis was completed, there appeared to be evidence of altered math and reading grades for the ninth graders at Thomas High School. I reanalyzed the data after replacing the math and reading scores for Thomas High School's ninth graders with NaN. The results below show the affect the changes had on the overall analysis.

![StudentDataNaN](https://user-images.githubusercontent.com/60076980/150691125-823f2baf-5f6b-45f6-b91b-436f6e53b741.png)

## Results
The initial analysis was performed in the PyCitySchools.ipynb file using Jupyter Notebook.

1. **How is the district summary affected?**
There was a very slight decrease in district averages.
  - Average Math Score: Dropped from 79.0 to 78.9
  - Average Reading Score: Stayed consistent at 81.9
  - % Passing Math: Dropped from 75 to 74
  - % Passing Reading: Dropped from 86 to 85
  - % Overall Passing: Dropped from 65 to 64

![DistrictSummary](https://user-images.githubusercontent.com/60076980/150691135-370a8fee-08a6-4736-a8f6-d6bf4b15954b.png)

2. **How is the school summary affected?**
There was a drastic decrease in the percent of Thomas High School students passing math and reading.
  - % Passing Math: Dropped from 93.27 to 66.91
  - % Passing Reading: Dropped from 97.31 to 69.66
  - % Overall Passing: Dropped from 90.95 to 65.08
  
![SchoolSummary](https://user-images.githubusercontent.com/60076980/150691140-83718d8d-239d-4c22-abba-6fcb094ab381.png)

3. **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

4. **How does replacing the ninth-grade scores affect the math and reading scores by grade?**

5. **How does replacing the ninth-grade scores affect the scores by school spending?**

6. **How does replacing the ninth-grade scores affect the scores by school size?**

7. **How does replacing the ninth-grade scores affect the scores by school type?**








## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
