# PyCitySchools Analysis



In the aggregate of the data to there are certain observable trends in school performance:
    * Generally, Charter schools have much higher overall passing rates with having a lower per student budget as compared to the District schools.
        * Top 5 performers are all Charter schools, bottom 5 performers are all District Schools.
    * The more dollars spent per pupil does not equate to better passing scores.
    * Average math and reading scores stay consisten across all schools.

Your final report should include each of the following:

### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
![District Summary](Images/District_Summary.png)

### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/SchoolSummary.png

### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/TopPerformer.png

### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/BottomPerformer.png

### Math Scores by Grade

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/MathGrade.png

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/ReadGrade.png

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (per student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/SpendScores.png
  
### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/SizeScores.png

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

As final considerations:

* You must use the Pandas library and a Jupyter Notebook.
* You must submit a link to your GitHub repo that contains your Jupyter Notebook.
* You must include a written description of at least two observable trends based on the data.
* See [Example Solution](PyCitySchools/PyCitySchools_starter.ipynb) for a reference on the expected format.

https://github.com/klharp/pandas-challenge/blob/main/PyCitySchools/Images/TypeScores.png
