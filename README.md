# School_District_Analysis

## Overview of School District Analysis
My boss maria tasked me with the analysis of multiple schools in a state in relation to budget, school size, various grades
and various scores including math and reading.
Analysis was done with following criteria in mind:
1. Determine the budget relation to student scores in differnet grades.
2. establish a relation between the size of the school and the overall pass rate of student
3. Answer the question Does the school type affect the outcome ?
4. Investigate wether the manipulated data from TH school for the 9th grade would affect the result

## School District Analysis Results:
The analysis concluded the following outcomes:
- Top 5 Schools:
  - Cabrera High School
  - Griffin High School
  - Wilson High School
  - Pena High School	
  - Wright High School	
- Bottom 5 schools :
  - Rodriguez High School
  - Figueroa High School
  - Huang High School	
  - Hernandez High School	
  - Johnson High School	
- Passing rate per Capita:
![PassPerCapita](https://github.com/A-Mossa/School_District_Analysis/blob/main/SDAImages/SchoolSpend.png)
  - When investigating the spending relation to overall passing, we found that strange enough the schools with the least spending budget per student, had a relatively higher overall pass rate
-School Size:
![schoolsize](https://github.com/A-Mossa/School_District_Analysis/blob/main/SDAImages/SchoolSize.png)
  - It was concluded from thorough analysis that the smaller the size of a school, the higher the overall passing rate. and the bigger the size of the school, the more the probability of failure increases.
-School Type :
![schooltype](https://github.com/A-Mossa/School_District_Analysis/blob/main/SDAImages/Schooltype.png)
  - The two types of schools in the dataset were District and Chartered. Across the board, Charter type schools enjoyed higher passing rates in all areas, that includes reading, mathematics, and overall passing rate.


- Which county had the largest number of votes?
  - Denver was the county with the largest number of votes (306,055)
- The Candidate results were:
  - Charles Casper Stockham: recieved 23.0% of the total votes ,(85213)
  - Diana DeGette: recieved 73.8% of the total votes ,(272892)
  - Raymon Anthony Doane: recieved 3.1% of the total votes ,(11606)
- The winner of the election was:
  - Diana DeGette, who recieved 73.8% of the total votes (272892)

## Election-Audit Summary
The code utilized this audit is sufficient to carry out the same analysis of results to almost any similar situation with minor tweaks.
given the next project posses a similar database, the code can be slightly refactored to accomodate difference and changes if the desired outcome is of the same nature as this audit.

![Code_screenshot](https://github.com/A-Mossa/Election-Analysis/blob/main/PyPollCode.png)

For example, if in the future should the stake holders wish to include additional attributes, then more variables would be created and code would be slightly modified to govern the interaction between said variables.
