# School_District_Analysis
## Overview
The purpose of this challenge was to manipulate school grade data collected across various high schools because it is believed that there has been academic dishonesty among math and reading grades from Thomas High School. Thus THS math and reading grades were changed to NaNs. The school analysis was then repeated to visualize any impact this data manipulation may have caused.
## Results
The following questions will be addressed
- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following
  -  math and reading scores by grade
  -  scores by school spending
  -  scores by school size
  -  scores by school type
### How is the district summary affected?
The district summary changes are small but visible in our analyses. Below is our district summary before and after our data manipulation.
Before:

![district_summary_before](https://user-images.githubusercontent.com/82029390/118407133-47e72600-b64d-11eb-8a1c-dfa5b94b9ab1.png)

After:
![district_summary_after](https://user-images.githubusercontent.com/82029390/118407170-78c75b00-b64d-11eb-89a9-f01aa67bff19.png)

While there is not a noticeable difference among the average math and reading scores, we can see a small change in our "% passing math," "% passing reading," and "% overall passing." 

### How is the school summary affected?
   The changes appear to be very minimal when comparing the average reading and math scores. 
   
![math_reading_before](https://user-images.githubusercontent.com/82029390/118406862-d8bd0200-b64b-11eb-9404-03c8d41a7ae9.png)

Before our analysis, Thomas High School had an average math score of 83.418349. It's average reading score was 83.84893.


![math_reading_after](https://user-images.githubusercontent.com/82029390/118406920-2f2a4080-b64c-11eb-9877-2b3f9c93c5f3.png)

After our analysis, the high school's average math score is reported at 83.350937 and their average reading score is 83.896082.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before our analysis, Thomas High School was in the top five schools as seen below:

![top_schools_before](https://user-images.githubusercontent.com/82029390/118407481-e6c05200-b64e-11eb-97d4-133e71d0e9f6.png)

After our analysis, Thomas High School is still in the top five.
![top_schools_after](https://user-images.githubusercontent.com/82029390/118407488-fb044f00-b64e-11eb-949b-90af86d816ea.png)

Thus no significant change is observed when assessing Thomas High School's placement relative to the other schools.

### Effects of replacing ninth grade scores
#### Math and reading scores by grade
The effects of this analysis were minimal, only seen in the tenths and hundreths place of a decimal.
### Scores by school spending
There was no significant change in our school spending
### Scores by school size
There was no significant change in scores by school size
### Scores by school type
There was no significant change in our scores by school type

## Summary
For the most part, there was no drastic change in our data after removing ninth grade reading and math scores from Thomas High School. This was to be expected as we only removed 461 data points from a dataset of 39,171. We did however see a small change in both the reading and math scores among Thomas High School scores alone. Their scores decreased ever so slightly. We also obeserve a decrease in overall passing percentage. The passing percentage for math and reading also dropped slightly.
