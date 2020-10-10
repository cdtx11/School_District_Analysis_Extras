# School_District_Analysis

## Overview of Analysis
During this school district analysis I replaced the ninth grade Math and Reading scores at Thomas High School with NaNs because there was evidencec of academic dishonesty. I redid the analysis with these new numbers to look at a school and district summary of reading and math scores by grade, school spending, school size, and school type. 

## Results
**How is the district summary affected?** The changes were pretty small since the overall summary incldues so much data. The average math score decreased by .1, the average reading score stayed the same, % Passing math decreased by .2, % passing reading decreased .1, and overall passing decreased .3.

**Original District Summary**
![](/original_district_summary.png)
**New District Summary**
![](/new_district_summary.png)

**How is the school summary affected?**
Because changes were only made to Thomas High School numbers, the only changes in the school summary are for Thomas High School. The changes were slight, since changes were only made to one grade. Average math and reading scores increased a small amount, while % Passing Reading and % Passing Math decreased by a small amount. Overall Passing % went down a small percentage as well.

**Original School Summary**
![](\original_school_summary.png)
**New School Summary**
![](\new_school_summary.png)


**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
While replacing the ninth graders' scores at Thomas High School lowers their overall passing percentage a little bit, they are still in line with the other High Schools in the school summary.

**How does replacing the ninth-grade scores affect the following:**

**Math and reading scores by grade** : Because we replaced all ninth grade math and reading scores at Thomas High School with NaN, the math and reading scores by grade shows NaN for Thomas High School 9th grade in the redone analysis. No other schools or grades were affected.


**Scores by school spending:** The average math and reading scores in the $585 - 629 spending range increased a little bit, as well as the math and reading scores in the $$630 - 644 range. Following this trend, the percent passing math and reading also increase a few points, with the biggest changes being % Overall Passing for the spending range $585 - 629 increasing by 8.8%


**Scores by school size:** Scores by school size were not affected by any significant amount because the groupings are so large.


**Scores by school type:** Scores by school type were not affected by any significant amount because the groupins are so large. 

## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for ninth grade at THS have been replaced with NaNs.
1. The largest change I noticed was the % Overall Passing in the spending range $585-629. There was an 8.8% incease from the original passing percentage of 81.4% to 90.2%.
2. The biggest change in the district summary was the Overall Passing % decrease, which decreased .3% from 65.2% to 64.9%. Considering we only changed one grade's scores at one high school, this is a significant change.
3. The next biggest change I saw was with the average numbers specifically for Thomas High School in the School Summary. Their original overall passing percentage was 90.94, but decreased by about .3 to 90.63 when I replaced the 9th grade math and reading scores with NaN.
4. Finally, the fourth significant change I noticed was in the District Summary, where the % Passing Math decresed by .2. 