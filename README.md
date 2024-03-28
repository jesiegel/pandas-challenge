# pandas-challenge

In this challenge, I used the student and school datasets to analyze student's math and reading scores. Before any observations were noted, I performed the following calculations:

District Summary
- total number of unique school
- total number of students
- total budget
- average math score
- average reading score
- % passing math
- % passing reading
- % passing both

The above was repeated, but based on each school, which required using the `groupby()` function. From this information, I was able to present the highest and lowest performing schools based on percent overall passing. I then separated the data based on what grade the student is in to present average scores and percent passing based on school and grade for both math and reading.

Lastly, `pd.cut` was used to create summaries of the students scores based on the variables per-student budget, size, and school type. 

From the calculations perform, I concluded that students in charter schools demonstrate higher reading and math scores and higher overall percent passing on average.
