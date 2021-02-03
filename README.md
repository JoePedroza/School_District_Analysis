# School_District_Analysis

## Project Overview 
A City School disrict would like to analyze grades for dishonesty reported at a particular high school.  The lead data scientist is tasked with performing some data mangering to remove the 9th grade reading and math scores to analyze the overall picture of testing.  The anlysis consist of the tasks below

- Create the district summary Dataframe.
- Create the school summary Dataframe. 
- Find the top 5 and bottom 5 performing schools. 
- Calculate the average math score received by students in each grade level at each school. 
- Calculate the average reading score received by students in each grade level at each school. 
- Calculate the school performance based on the spending per student. 
- Calculate the school performance based on the size of the school. 
- Calculate the school performance based on the type of school. 

## Resources 
- Data Source : schools_complete.csv , students_complete.csv 
- Tools : Python 3.8.5, Pandas, Jupyter Notebook 

## Results: 


How is the district summary affected?
### District Summary
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/district_summary.png)
The overall passing rate for the district is below the passing level and suffer in the areas of math.  


### Per School Summary
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/per_school_summary.png) 
How is the school summary affected?
Under the per school summary, we can see that the district schools grades are lower compared to teh charter schools.  The school size also has a higher teacher to student ration.  We can see that the per student budget is higher at the district schools.  District schools receive a higher total school budget yet produce lower grades in math and reading.


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![alt text](https://github.com/JoePedroza/School_District_Analysis/analysis/per_school_summary.png) 
By replacing the the night grade school scores at Thomas High School, it moved them up into the top performers overall.  The grade averages still place them as a top performer regardless of the ninth grade scores.


How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/top_performing_descending.png)
The grades still keep Thomas High School as one of the top performers overall across all other grade levels.  Most of the charters schools produce slightly higher averages amongst the grade levels.


Scores by school spending
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/spending_summary.png) 
Schools with less spending per student produce higher grade averages.  This seems to be more of the charter school as opposed to district schools.  Being given more money as a budget does not entail the students will score higher.  

Scores by school size
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/size_summary.png) 
Smaller schools tend to score higher in both reading and math as opposed to larger schools.


Scores by school type
![alt text](https://github.com/JoePedroza/School_District_Analysis/blob/main/analysis/type_summary.png) 
Charter schools have a significantly higher average overall and especially in math.  
This may be due to the teacher student ratio for charter schools.  Teachers can focus more time per student and manage a smaller class size.

## Summary: 
Overall the changes in grades for Thomas High School increases the overall averages for schools belonging in the charter type.  The math score seems to be higher for all grade levels across the board for charter schools.  The higher the school budget doesn't neccesarily mean that the grade averages will be higher.  In fact, the grades per school size have a direct correlation to the budget.  The higher budget per student shows that the averages underperform the lower budget per student case.  
