# School_District_Analysis
# Overview 
## Purpose
The purpose of challenge 4 was to learn how to use pandas to organize a large dataset and make sense of the information given. Module 4 utilizes two datasets, schools_complete.csv and students_complete.csv. 
Schools_complete.csv contains information about 15 different schools. This dataset can be easily read and understood, but the information is very broad and doesn’t give much in-depth information on the academic success of these schools. students_complete.csv. contains information on over 39,000 students, including grade levels, and math and reading scores. Although useful information can be found in this dataset, the amount of information can be very daunting to read. In module 4 we are able to merge and organize these two datasets, so that the information is more useful for the client. 

# Results
In the module 4 challenge we analyzed information before and after omitting all math and reading scores for 9th graders attending Thomas High School. 
## How is the district summary affected?
Compared to the district summary dataframe created while following Module 4 instructions, all average scores and percentages changed in the new challenge 4 district summary dataframe. Average math scores were previously 79.0, and was lowered to 78.9 after changing the data. The average reading scores changed negligibly and remained at 81.9. Percentage passing math went from 75.0 to 74.8. Percentage passing reading went from 85.8 to 85.7. Lastly, the percentage of students passing both math and reading went from 65.2 to 64.9. 
## How is the school summary affected?
The school summary dataframe shows the school type, total students, budget, budget per student, average math and reading scores, and percentage of students passing math, reading, and both math and reading. Since we didn’t change any information specific to any other schools, the information was only altered for Thomas High School. 
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After omitting the scores for 9th graders attending Thomas High School - and before replacing these fields with information from students in grades 10 through 12 - the metrics for average math scores, percentages of students passing math, reading, and both math and reading, were all reduced. 
## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
Removing the data of math and reading average scores of 9th graders attending Thomas High School the two datasets, math_scores_by_grade and reading_scores_by_grade were altered to show ’NaN’ for 9th grade Thomas High School average scores. 
### Scores by school spending
Omitting the data for 9th grade students, which amounts to 461 students, has a negligible affect on the scores by school spending dataframe. This could be because these metrics are taking into account a much larger amount of students - over 39,000 - so in comparison the data of 461 students doesn’t have a significant impact on the overall calculations for this dataframe. 
### Scores by school size
Scores by school size did not have a noticeable change for Thomas High School. This is because removing the data for 9th graders did not change which size bin the high school falls into. The total amount of students attending the school is 1635 before removing the 9th graders information, and after removing the data this value changes to 1174. In both instances Thomas High School falls into the size category ‘Medium (1000-1999)’. 
### Scores by school type
Removing the 9th graders data from Thomas High School does not have an effect on the school type. 

# Summary 
In conclusion, removing and replacing the data for 9th graders attending Thomas High School had an affect on the average scores and percentages for the school. Math and reading scores for Thomas High School, after removing scores from the 9th grade class, are 83.35 and 83.89 respectively. The percentage of students passing these classes are 66.91 for math, 69.66 for reading, and 65.07 for both math and reading. 
After replacing the information with that of students in grades 10 through 12 the percentages were bumped up to 93.18 for math, 97.01 for reading, and 90.63 for both math and reading. 
