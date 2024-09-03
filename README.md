# Capstone-Project-Python

Dataset Explanations
Attributes
1) id - Assigned number for Project head who will be in charge of the
project.
2) name - person handling the project.
3) gender – Male(M), Female(F)
4) city - locations of the project
5) age - number of years the project will be active.
6) status - status of the project
7) designation level - position of the project head
o excessive failures indicate designation grades to reduce.
o a person with a good reputation means a very high chance to
increase his designation.
Designation scale -
a) 1-highest
b) 2, 3 mid positions and 4 being the least
c) If anyone crosses 4 then he loses eligibility
for heading the project.

Dataframes

Employee DataFrame
ID Name Gender City Age
A001 John Alter M Paris 25
A002 Alice 
Luxumberg F London 27
A003 Tom 
Sabestine M Berlin 29
A004 Nina Adgra F Newyork 31
A005 Amy Johny F Madrid 30

Seniority Level DataFrame
ID Designation Level
A001 2
A002 2
A003 3
A004 2
A005 3

Project DataFrame
ID Project Cost Status
A001 Project 1 1002000 Finished
A002 Project 2 2000000 Ongoing
A003 Project 3 4500000 Finished
A004 Project 4 5500000 Ongoing
A005 Project 5 Finished
A002 Project 6 680000 Failed
A005 Project 7 400000 Finished
A003 Project 8 350000 Failed
A001 Project 9 Ongoing
A003 Project 10 300000 Finished
A001 Project 11 2000000 Failed
A004 Project 12 1000000 Ongoing
A004 Project 13 3000000 Finished
A005 Project 14 200000 Finished
Problems
Task 1
There are three different tables as given above. Please make three dataframe in python
and save them as three .csv files. From Task 2 to Task 10, use the saved .csv files only.
Task 2
The cost column in the dataframe “Project” has some missing values. Your task is to
compute these missing values. Replace the missing values by running average. You
should use the “For” loop for this task.
Task 3
Split the name column in the Employee dataframe into two new columns “First Name”,
and “LastName” and remove the older “name” column.
Task 4
Join all three dataframes in one single dataframe. Name it “Final”
Task 5
Add a new bonus column in the Final dataframe. Give a 5% bonus concerning project 
cost only to employees who have finished the projects.
Task 6
Demote the designation level by 1, whose projects have status “fail”. Delete the
employees record whose designation level is above 4.
Task 7
Add “Mr.” and “Mrs.” to the first name column and drop the gender column.
Task 8
Promote designation level by 1 for the employees whose age is more than 29 years using
IF condition.
Task 9
Add the cost of all projects for each Employee and save it in new dataframe
“TotalProjCost” with three columns ID, First Name, and Total cost
Task 10
Print all the employee details whose city name contains the letter “o” in it.
