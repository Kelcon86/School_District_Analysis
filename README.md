# School_District_Analysis

## Overview
I was given the task of helping the PyCity School District with an analysis of the overall district performance, individual school performances, the top and bottom performing schools, average math and reading scores for each grade from each school, and the scores by school spending, school size and school type. After the initial analysis was completed, there appeared to be evidence of altered math and reading grades for the ninth graders at Thomas High School. I reanalyzed the data after replacing the math and reading scores for Thomas High School's ninth graders with NaN. The results below show the affect the changes had on the overall analysis.

![StudentDataNaN](https://user-images.githubusercontent.com/60076980/150691125-823f2baf-5f6b-45f6-b91b-436f6e53b741.png)

## Results
The initial analysis was performed in the PyCitySchools.ipynb file using Jupyter Notebook.

**1. How is the district summary affected?**

There was a very slight decrease in district averages.
  - Average Math Score: Dropped from 79.0 to 78.9
  - Average Reading Score: Stayed consistent at 81.9
  - % Passing Math: Dropped from 75 to 74
  - % Passing Reading: Dropped from 86 to 85
  - % Overall Passing: Dropped from 65 to 64

![DistrictSummary](https://user-images.githubusercontent.com/60076980/150691135-370a8fee-08a6-4736-a8f6-d6bf4b15954b.png)

**2. How is the school summary affected?**

There was a drastic decrease in the percent of Thomas High School students passing math and reading.
  - % Passing Math: Dropped from 93.27 to 66.91
  - % Passing Reading: Dropped from 97.31 to 69.66
  - % Overall Passing: Dropped from 90.95 to 65.08
  
![SchoolSummary](https://user-images.githubusercontent.com/60076980/150691140-83718d8d-239d-4c22-abba-6fcb094ab381.png)

**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

  - Prior to replacing the scores, Thomas High School was ranked 2nd out of the 15 schools for % Overall Passing. 
  - After replacing the scores, Thomas High School was ranked 8th out of the 15 schools for % Overall Passing.

**4. How does replacing the ninth-grade scores affect the math and reading scores by grade?**

Only the Thomas High School's ninth-graders scores were affected.

  - The ninth-grade math scores for Thomas High School changed from 83.6 to nan
  - The ninth-grade reading scores for Thomas High School changed from 83.7 to nan

![MathScoresBeforeAndAfter](https://user-images.githubusercontent.com/60076980/150696185-f8d2cbb4-afed-47a9-9938-ebf5d0850416.png)
![ReadingScoresBeforeAndAfter](https://user-images.githubusercontent.com/60076980/150696188-b637736c-fb79-497c-a9d2-774e72c49715.png)

**5. How does replacing the ninth-grade scores affect the scores by school spending?**

The scores by school spending only saw a very small change in the $630-644 range. All of the other spending ranges were unaffected.

![SpendingRangesPerStudent](https://user-images.githubusercontent.com/60076980/150696843-c8af14f3-856e-4efe-8306-a5433915239c.png)

**6. How does replacing the ninth-grade scores affect the scores by school size?**

Only the medium sized schools (1000-2000) saw a change in scores and even then it was very minimal.

![SchoolSize](https://user-images.githubusercontent.com/60076980/150697056-e4014011-3d99-4b57-a951-5d455d782363.png)

**7. How does replacing the ninth-grade scores affect the scores by school type?**

District schools were unaffected by the change. Charter schools saw a very slight change in scores as seen below.

![SchoolType](https://user-images.githubusercontent.com/60076980/150697221-2c5542c6-2101-462d-a7d5-3fbcf594da23.png)

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
