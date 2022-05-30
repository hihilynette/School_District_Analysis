# School_District_Analysis

## Overview of the school district analysis:
This project is help Maria, the data analyst for the school district, to analyze data on the student fundings and student standardized test scores among 15 different schools. Our task is to aggregate the data and showcase the trends and school performace. The results will help school boards to make decisions regarding the school budgets and priorities. In addition, after finding out the dishonesty of Thomas High School ninth graders, we exclude this set of numbers and re-analyze the data to see how these changes affected the overall analysis.

## Results: 

#### How is the district summary affected?
Below is the comparison of including Thomas High School's ninth grade and excluding the numbers. We can see the overall passing percentage dropped from 65.2% to 64.9% which shows a big impact on the overall results. 

Original:

![original results](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/school%20district%20summary%20-%20original.PNG)

Adjusted:

![adjusted results](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/school%20district%20summary%20-%20adjusted.PNG)

#### How is the school summary affected?
In the original result, the overall passing percentgae for Thomas High is around 90.95%. However, after removing the cheating ninth grade, it shows only 65.08%. There is a significant drop due to the dishonesty.

Original:

![original results](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/THS_ORIGINAL.png)

Adjusted:

![adjusted results](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/THS_adjust.png)

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing ninth graders’ math and reading scores affects Thomas High School's performance only, not including other schools' performance.

#### How does replacing the ninth-grade scores affect the following:

###### Math and reading scores by grade
After replacing the ninth-grade scores to NA, the adjusted math and reading scores by grade are showing as below:
![math score by grade_adjusted](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/math%20score%20by%20grade_adjusted.PNG)
![reading score by grade_adjusted](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/reading%20score%20by%20grade_adjusted.PNG)

###### Scores by school spending
After dropping the ninth-grade scores, the scores by school spending still remain in the same range.

Original:

![Scores by school spending_original](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/scores%20by%20school%20spending_original.PNG)

Adjusted:

![Scores by school spending_Adjsuted](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/scores%20by%20school%20spending_adjusted.PNG)

###### Scores by school size & Type
Similar to scores by school spending, the replacement of ninth grade has little impacts on the results. Thomas High school still belongs to the medium school size and
it falls under "Charter" school tye.

Adjusted school size and Type

![Adjusted school size](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/adjusted%20school%20size.PNG)

![Adjusted school type](https://github.com/hihilynette/School_District_Analysis/blob/main/Resources/adjusted%20school%20type.PNG)

## Summary

1. Thomas High School's ninth grade are dropped and replaced with NaNs due to dishonesty.
2. The overall passing percentage for Thomas High school dropped sharply from 91% to 65%.
3. The replacement of ninth grade has big impacts on Thomas High school's performance.
4. After dropping the ninth-grade scores, the scores by school spending, size and type got little impact.
