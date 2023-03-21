
## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.
#### District Summary and Total Budget
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
- Total number of unique schools
- Total students
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

![image](https://user-images.githubusercontent.com/62813833/226746091-d9325329-a13a-4c31-bfc0-28fa697da888.png)


#### School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

![image](https://user-images.githubusercontent.com/62813833/226746186-89522bc3-6d50-4307-beb7-e383214b075e.png)


#### Highest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in descending order and display the top 5 rows.
- Save the results in a DataFrame called "top_schools".

![image](https://user-images.githubusercontent.com/62813833/226746257-e9a31658-324d-4b4b-a5d3-3dee01c3dd01.png)



#### Lowest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
- Save the results in a DataFrame called "bottom_schools".

![image](https://user-images.githubusercontent.com/62813833/226746318-1227de30-5700-41f3-b5d3-7ef12319811d.png)


#### Math Scores by Grade
- Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

![image](https://user-images.githubusercontent.com/62813833/226746406-5fc5a885-4031-4337-9627-097786857a64.png)


#### Reading Scores by Grade
- Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

![image](https://user-images.githubusercontent.com/62813833/226746478-7f3fcdf4-8fc6-4c3a-ab86-315903189006.png)


#### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Include the following metrics in the table:
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

![image](https://user-images.githubusercontent.com/62813833/226746535-26200cfe-f20b-426e-a30b-10f4c64a07c5.png)


#### Scores by School Size
- Use the following code to bin the per_school_summary.

![image](https://user-images.githubusercontent.com/62813833/226746624-9f301fb7-b8bc-42fe-8b3a-3626e38a330d.png)


#### Scores by School Type
- Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
- This new DataFrame should show school performance based on the "School Type".

![image](https://user-images.githubusercontent.com/62813833/226746679-7bcb4690-975e-4f60-8b31-926d679dc94a.png)
