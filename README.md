goit-rdb-hw-08 Relational Databases

Tasks:
1. Download data:
Create the pandemic schema in the database using the SQL command. Select it as the default schema using the SQL command.
Import the data using the Import wizard- infectious_cases.csv Look at the data for context.

2.  Normalize the infectious_cases table. Save two tables with normalized data in the same schema.

3.  Analyze the data:
- For each unique combination of Entity and Code or their id, calculate the average, minimum, maximum value and sum for the Number_rabies attribute.
- Sort the result by the calculated average value in descending order.
- Select only 10 lines to display
- 💡 Note that the Number_rabies attribute can contain empty values ​​'' - you need to filter them first.

4. Construct a column of the difference in years.
For the original or normalized table for the Year column, build using the built-in SQL functions:
- an attribute that creates the date of January 1 of the corresponding year,
💡 For example, if the attribute contains the value '1996', then the value of the new attribute should be '1996-01-01'.
- attribute equal to the current date,
- attribute equal to the difference in years of the two columns mentioned above.
💡 It is not necessary to enumerate all other attributes such as Number_malaria.

5.  Build your own function.
Create and use a function that constructs the same attribute as in the previous task: the function should take a year value as input, and return the difference in years between the current date and the date created from the year attribute (year 1996 → '1996-01-01 ').