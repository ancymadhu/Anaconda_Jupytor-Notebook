# School_District_Analysis

## Overview
Maria is the Chief Data Scientist for a city school district. She has requested an analysis of school spending and standardized test scores.

## Resources
  * Data Source: schools_complete.csv, students_complete.csv
  * Software: Python 3.7.7, Anaconda Navigator 1.9.12, Jupyter Notebook 6.0.3
  
## Challenge Overview
Some of the students were caught with academic dishonesty from Thomas High School. The data for the math and reading scores must be removed and the following information should be recalculated.

```
  1. Recreate the district and school summary DataFrames.
  2. Recalculate the top 5 and bottom 5 performing schools.
  3. Recalculate the average math score received by students in each grade level at each school.
  4. Recalculate the average reading score received by students in each grade level at each school.
  5. Recalculate the school performance based on the spending per student.
  6. Recalculate the school performance based on the size of the school.
  7. Recalculate the school performance based on the type of school.
```

## Challenge Summary

##### ✓ How is the district summary affected?

The average math score decreased by 0.1 points while the average reading score stayed the same. The percentage of students passing math decreased by 1% as did the percentage of students passing reading. The overall passing percentage also decreased by 1%.

![1](https://user-images.githubusercontent.com/73450637/98776288-a12f7d80-23bc-11eb-9912-be0f5c443d0c.png)

##### ✓ How is the school summary affected?

The only change in data is with Thomas High School. The overall math and reading passing numbers decreased.

##### ✓ How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

Thomas High School overall passing percentage with the ninth graders were ~65% [Refer the image below]



