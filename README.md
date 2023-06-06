# Home_Sales

Import the necessary PySpark SQL functions for this assignment.

1.  Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

2.  Create a temporary table called home_sales.

3.  Answer the following questions using SparkSQL:

    i.  What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

    ii. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal              places.

    iii.  What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000               square feet? Round off your answer to two decimal places.

    iv. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two 
        decimal places.

4.  Cache your temporary table home_sales.

5.  Check if your temporary table is cached.

6.  Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime      and compare it to uncached runtime.

7.  Partition by the "date_built" field on the formatted parquet home sales data.

8.  Create a temporary table for the parquet data. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

9.  Uncache the home_sales temporary table.

10. Verify that the home_sales temporary table is uncached using PySpark.
