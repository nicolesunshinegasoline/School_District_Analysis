# School_District_Analysis

There is evidence of academic dishonesty in the math and reading grades of ninth graders coming from Thomas High School. For the school board to uphold state-testing standards, math and reading scores of these ninth graders must be replaced with NaNs while keeping the rest of the data intact.

## Purpose
The purpose of this analysis is to recreate the school district analysis,in which replaces the math and reading scores for the ninth graders of Thomas High School with NaNs. Then we will analyze how these changes affected the overall analysis.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?

![](Resources/Images/district_summary_before)

![](Resources/Images/district_summaey_after)

There was little to no change on any of the metrics on the district level.


## How is the school summary affected?

school_summary_before
school_summary_after

In the school summary, there is little to no change on the average math and reading scores. However, in the recreated analysis, we see a big percentage drop in the average math and reading scores, as well as a big drop in percentage of overall passing rate.
- Math went from a % passing rate of 94.3% to 69.7%
    - A difference of 23.6%
- Reading went from a % passing rate of 97.3% to 69.7%
    - A difference of 27.6%
- % overall went from 90.9 to 65.1
    - A difference of 25.8%

 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In terms of "% overall passing", Thomas High School was one of the top schools, landing #2 on the list. However, after replacing the ninth grader's math and reading scores with NaN, THS ended up being the lowest ranking school in terms of "% overall passing".

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
There was not much change in the average math or reading scores. 

### Scores by school spending
We see that the more the school spends per student, the less the % of passing. Thomas High School was an outlier compared to all the other schools that spent more per student and had low passing

### Scores by school size
Even when you remove the ninth grader's math and reading scores, Thomas High School is still considered a medium sized school. The overall % passing rate decreased, bringing down the school's ranking. 

### Scores by school type
Across all charter schools, the average percentage of  overall passing students is 90%. In the original school district analysis, Thomas High School had around the same average as the rest of the charter schools, an average of 90.95%. However, by removing the ninth grade test scores, the % overall passing rate for Thomas High School droped to 65.08%.
