# home_sales

Navigating through a large dataset has never been easier thanks to pySpark. By using its SQL integration I was able to query the data to determine key metrics about home sales data. i also used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

The trickiest query was the one where it specifically asked for homes with an average price of greater than or equal to 350,000. I used the """HAVING""" function in SQL, which is similar to """WHERE""" but aggregation functions such as """avg()""" are available and won't throw an error. 

Here is my source for that:

https://stackoverflow.com/questions/6319183/aggregate-function-in-sql-where-clause
