# School_District_Analysis
## Overview of the school district analysis: 
We have been working closely with Maria to interpret the data and categorize the grades/ performance across grades 9 through 12. However, it has been brought to Maria's attention by the school board that the students_complete csv file we were working with appears to have showed tampered grades, specifically for the reading and math grades of 9th graders of Thomas High School thus implying academic dishonesty. Since we have already performed an analysis on this specific data set before, Maria has tasked us in repeating it but this time omitting the Thomas High School 9th grades reading and math scores in order to better represent the overall school district data.

# Results: 
## How is the district summary affected?
### Before
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/DSummary1.png)

### After
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/DSummary2.png)
> - There was pracatically no difference between the district summaries as expected. Since the student dataset is so large, removing the 9th grader data wouldn't change it too much.

## How is the school summary affected?
### Before
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/SchoolSummary2.png)

### After
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/SchoolSummary1.png)
> - Even after removing the 9th graders' math and reading scores Thomas High School is still 2nd of all the schools in overall passing % in the district.

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
-Replacing the ninth graders scores didn't change anything to the data specifically other than the value for those scores becoming NaN. After that we were able to delete those records and get a full analysis of the dataset for overall percentage etc.

### Scores by school spending
#### Before
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/SchoolSpending2.png)

#### After
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/SchoolSpending1.png)
> - There is no impact on the spending per student because because the number of students for the spending calculation did not change.

### Scores by school size
#### Before
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/Scores1.png)

#### After
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/Scores2.png)
> - Again, there is no impact when removing 9th graders from the data. Because the data is so large, calculating the school size didn't have a large enough change in average scores to see a big (or any) difference.

### Scores by school type
#### Before
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/Type1.png)

#### After
![school](https://github.com/mooshak21/School_District_Analysis/blob/main/Resources/Type1.png)
> - No surpise,  but there is no impact when removing 9th graders from the data because the dataset is so large.

## Summary: 
- A big change was in the overall passing percentage from 90.95 to 90.63 which is a 0.35% decrease.
- % Passing Math went from 93.27% to 93.19%
- % Passing Reading went from 93.31% to 97.02%
- Average Math score went from 83.41% to 83.35%
Overall, we can see that there was a change in data with the altered 9th grader data, but it isn't very significant in the overall picture of the school. 