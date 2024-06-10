# home_sales

Navigating through a large dataset has never been easier thanks to pySpark. By using its SQL integration I was able to query the data to determine key metrics about home sales data. i also used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Answer the following questions using SparkSQL:

1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

2. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

3. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

4. What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places

The trickiest query was the one where it specifically asked for homes with an average price of greater than or equal to 350,000. I used the """HAVING""" function in SQL, which is similar to """WHERE""" but aggregation functions such as """avg()""" are available and won't throw an error. 

Here is my source for that:

https://stackoverflow.com/questions/6319183/aggregate-function-in-sql-where-clause
