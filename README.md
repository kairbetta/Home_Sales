# Home_Sales

### Findings
1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/1.png)


2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/2.png)


3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/3.png)


4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
- Original data

![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/4.png)

5. Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
Partition by the "date_built" field on the formatted parquet home sales data.

- Cached data
  
![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/5.png)

- Parquet formatted data

![image](https://github.com/kairbetta/Home_Sales/blob/master/Images/6.png)

