Assignment 1: Data Exploration

1.Sum, Count, Average:
the total price of all products in the dataset calulated using '=sum(firstrange:last Range)'fn
no of products in the dataset calulated using '=count(firstrange:last Range)' fn
average price of the products are calculated using '=AVERAGE(firstrange:last Rang)'fn

2.Min and Max: 
the minimum price among all products is calulated using'=MIN(firstrange:last Rang)'fn
he maximum price among all products is calulated using'=MAX(firstrange:last Rang)'fn

3.IF Function:
created a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price' using'=IF(D2>=500,"High Price","Standard Price")'fn and autofill

4.SUMIF and COUNTIF:
Calculated the total price for products in the 'Electronics' category using the SUMIF function
Determined the count of products with a price less than $100 using the COUNTIF function.

5.Text Formatting - LEFT, RIGHT, MID:
Created a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function. 
Created a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
Created a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
