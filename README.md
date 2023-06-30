# Home_Sales

## Overview of the Analysis

* The purpose here is to use SparkSQL to determine key metrics about a fictional home sales dataset. 
Then, create temporary views, cache a temporary table and partition the data, comparing the runtime performance.


## Questions

**1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.**

**2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.**

**3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.**

**4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.**



## Performance

**Temporary table runtime** ![Temporary table runtime](https://github.com/cami5326/Home_Sales/blob/main/Pictures/Temporary%20table%20runtime.PNG)

**Partition parquet** ![Partition parquet](https://github.com/cami5326/Home_Sales/blob/main/Pictures/Partition%20parquet.PNG)

**Cache your temporary table** ![Cache temporary table](https://github.com/cami5326/Home_Sales/blob/main/Pictures/Cache%20your%20temporary%20table.PNG)
  






