# <b> School District Analysis </b>

## <u>Overview of Analysis</u>
This is an analysis of school data. The csv file contained the student name, id, grade, school, school type, school budget, standardized math scores, and standardized reading scores of 19,514 students. The students come from 6 charter high schools (6,711 students) and 9 public high schools (8,120 students).  

<img width="400" alt="student count by type" src="https://user-images.githubusercontent.com/116980760/204167136-f5996752-92b9-473d-bc9a-812fe4dfd4ce.PNG">

### Purpose of Analysis   
How does school type and grade level influence standardized math and reading scores in the school district? The purpose of this analysis is to determine patterns and trends in the data that mighht be a basis for school decisions at a district level.  

## <u>Analysis and Challenges</u>
The original data set contained information about 19,514 students. 1,968 reading scores and 982 math scores were missing for students in the dataset. Students who were missing one or both scores were excluded from the analysis. After those students were dropped, there was still 1,836 duplicated rows of student data. The duplicates were also removed. 

### Analysis of Outcomes based on School Type  
The average math score for all students was about 64.68 %.
<img width="700" alt="summary stats for all" src="https://user-images.githubusercontent.com/116980760/204164775-92896de4-5cef-4699-9bab-f50d540f790c.PNG">

Charter schools scored above average for each grade except for 12th. While public schools consistently scored below average. 

<img width="300" alt="math score by school type and grade" src="https://user-images.githubusercontent.com/116980760/204166350-73c88d47-d04f-4a7f-9c6b-acbad3b67bb9.PNG">

Reading scores between the two types of schools were fairly similar with no clear pattern. 

<img width="300" alt="reading by grade and type" src="https://user-images.githubusercontent.com/116980760/204170362-28734fcf-af4c-4732-9d6a-83c2fb610cb0.PNG">

### Analysis of Outcomes by School Budget
Public schools had a higher average budget ($911,195.56) than charter schools ($872,625.66). The average budget for all schools was about $893,742.75

<img width="300" alt="school budget by school type" src="https://user-images.githubusercontent.com/116980760/204167988-99fd2f8c-8ad0-44a4-b0e9-a1289c2eabfe.PNG">

School budget did not seem to affect the average math score. 

<img width="500" alt="math score on budget" src="https://user-images.githubusercontent.com/116980760/204172328-d089e02a-c98b-4e1e-846c-11cefb51b24a.PNG">

Nor did the budget seem to affect reading scores.

<img width="500" alt="reading score by budget" src="https://user-images.githubusercontent.com/116980760/204172693-36faa1ec-538e-4b05-9b89-a80acf82f98f.PNG">


### Analysis of Outcomes Based on Grade Level

The lowest reading score (10.5%) comes from a 10th grader from Dixon High School. Dixon 10th graders score below average (72.36%) with an average score of 	67.78%.

9th and 10th grades scored above average on math tests and 11th and 12th scored below average (64.68%). Each year of high school there seems to be a decline in acheiving proficiency. 

<img width="300" alt="math score based on grade" src="https://user-images.githubusercontent.com/116980760/204173212-0d473189-e371-4cfe-96f8-a165691637f3.PNG">

The average reading score is 72.36%. All of the grades scored below average except for 11th.

<img width="300" alt="reading score by grade" src="https://user-images.githubusercontent.com/116980760/204173204-629b89cd-3a41-4611-94fa-cf46d4dfb82f.PNG">



### Challenges and Difficulties Encountered
The student grades were string variables: 9th, 10th, 11th, and 12th. The data was converted into integers to be more accessible for analysis. 


## <u>Results</u>
- Charter schools seem to outperform public schools on math standardized test scores.
- Budget does not seem to be a large influence on either type of test score.
- An analysis over multiple years would be interesting to see if these trends hold or if others appear.
