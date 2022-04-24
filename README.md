# School Distrcit Analysis
## Overview of the School District Analyis
While assisting Maria with an analysis of math and reading scores in her school district, it was discovered the grades for Thomas High School ninth graders have been altered. To uphold state-testing standards, I have replaced the math and reading scores for Thomas High School ninth graders with NaNs while keeping the remaining data intact. Then an analysis on the school district data was repeated. The changes to the overall analysis are documented below.

## Results
### How is the district summary affected?
As shown in the district summary below, before removing the Math and Readings scores for Thomas High School ninth graders; the average math score for the district was 79.0, average reading score was 81.9, percent passing math was 75%, percent passing reading was 85.8%, and overall passing percentage was 65%.
![School District Summary Before](https://github.com/jstearns1988/School_District_Analysis/blob/main/School%20District%20Summary%20Before.png)

After removing the scores from Thomas High School ninth graders; the average math score lowered to 78.9, average reading score did not change, percent passing math lowered to 74.8%, passing reading reduced to 85.7%, and overall passing is now slightly less at 64.9%.
![School District Summary After](https://github.com/jstearns1988/School_District_Analysis/blob/main/School%20District%20Summary%20After.png)

### How Each of the seven school district metrics are affected by changes in the data
  - Total Schools remains at 15
  - Total Students remains at 39,170
  - Total Budget remains at $24,649,428.00
  - Average Math Score slightly decreases from 79.0 to 78.9
  - Average Reading Score remains at 81.9
  - Percentage Passing Math drops from 75% to 74.8%
  - Percentage Passing Reading lowers from 85.8% to 85.7%
  - Overall passing changed from 65% to 64.9%

#### The results after removing Thomas High School's scores are a small change. We will next dig deeper into the individual school analysis data to see how signifant the Thomas High School ninth grade scores were affecting the final analysis.

### How is the school summary affected?
In the screenshot below, we see the summary of all schools before the changes to Thomas High School ninth grade scores were removed.
![School Summary Before](https://github.com/jstearns1988/School_District_Analysis/blob/main/School%20Summary%20Before.png)

As we can see below, all school data remained the same except for Thomas High School. After removing the ninth grade scores from Thomas High School; the average math score dropped from 83.41 to 83.35, reading actually improved slightly from 83.85 to 83.9, percent passing math lowered from 93.27% to 93.19%, passing reading went from 97.3% to 97.2%, and the overall passing percentage slightly decreased from 90.95% to 90.63%.
![School Summary After](https://github.com/jstearns1988/School_District_Analysis/blob/main/School%20Summary%20After.png)

#### After digging deeper into the results for Thomas High School post removing the ninth grade scores, the results were only changed by roughly a hundredth of a percent.


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Even though there were slight decreases in math scores and the overall passing percentage, Thomas High School remained in the top five schools with the tenth through twelfth grade scores.

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
Math and readings scores remained the same for all grades except Thomas High School's ninth grade category, which is showing NaN.
 - Math Scores by Grade
 
 ![Math Scores by Grade](https://github.com/jstearns1988/School_District_Analysis/blob/main/Math%20Scores%20by%20Grade.png)

 - Reading Scores by Grade

![Reading Scores by Grade](https://github.com/jstearns1988/School_District_Analysis/blob/main/Reading%20Scores%20by%20Grade.png)

### Scores by school spending
As seen in the data, the higher the spending ranges per student does not result in higher grades and overall passing percentages. The highest overall passing percentage can be found in the <$584 bin. As the spending ranges in each bin increase, the average scores and passing percentages decrease.

![Average Scores by Spending](https://github.com/jstearns1988/School_District_Analysis/blob/main/Average%20Scores%20by%20Spending.png)

#### Thomas High School falls in the $630-644 spending bucket.

### Scores by school size
The highest overall passing percentage belongs to the medium school size (1000-2000). The small school size (<1000) is closely behind by a 1% decrease in overall passing percentage, while the large schools (2000-5000) are only passing at a 58% rate.

![Average Scores by Size](https://github.com/jstearns1988/School_District_Analysis/blob/main/Average%20Scores%20by%20Size.png)

#### At 1635 students, Thomas High School is a medium sized school.

### Scores by school type
When reviewing charter versus district scores, the differences are significant, especially the percentage passing math and the overall percentage.

![Average Scores by Type](https://github.com/jstearns1988/School_District_Analysis/blob/main/Average%20Scores%20by%20Type.png)

#### Thomas High School is a Charter School.

## Summary
With the data provided and the results of the analyis, it would be unfair to to accuse Thomas High School of dishonest activity without more information. While there were four differences after altering the datasets, the results did not significantly change this school's scores, passing percentages, or overall ranking in the district.
#### The following are the four changes in the updated school district analyis:
  - Total number of students in the analysis
  - The average math and reading scores
  - The overall percentages for reading and math at Thomas High School
  - The number of students counted at Thomas High School
