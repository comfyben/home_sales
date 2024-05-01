# home_sales

Navigating through a large dataset has never been easier thanks to pySpark. By using its SQL integration I was able to query with ease. 

The trickiest query was the one where it specifically asked for homes with an average price of greater than or equal to 350,000. I used the """HAVING""" function in SQL, which is similar to """WHERE""" but aggregation functions such as """avg()""" are available and won't throw an error. 

Here is my source for that:

https://stackoverflow.com/questions/6319183/aggregate-function-in-sql-where-clause