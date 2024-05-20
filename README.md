# Home_Sales

This ReadMe serves to:
   1. Certify that this work is my own,
   2. Specify code source and its location in my 'Home_Sales' repository,
   3. Explain the process of the challenge

1. 
My name is Brittney Watts, and I am in the UNCC/EdX Data Analytics Bootcamp. This challenge is a product my own work.

2. 
The source code is my interpretation of the information we have learned in class with some help from class activities, and here
is a breakdown of the locations of each element of my assignment:

    Home_Sales
        CODE
            home_sales.ipynb   
        README.md

Home_Sales:
   My task was to read the data from the "home_sales_revised.csv" file and use SparkSQL to determine key metrics about the home sales data! For this deliverable, I used Spark to create temporary views, partition the data, and cache and uncache to demonstrate changes in processing time. 
   
3.
Steps:     

    - Read in the home_sales_revised.csv into a Spark DataFrame
    - Create a temporary table for the home_sales data
    - Run queries on the dataset to answer the following questions:
        1. What is the average price for a four-bedroom house sold for each year?
        2. What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
        3. What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
        4. What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Find the runtime.
    - Cache the temporary table 'home_sales' and verify that it is cached
    - Run the 4th query again and find the runtime. Compare it to the runtime before caching the table.
    - Partition by the 'date_built' field on the formatted parquet home_sales data.
    - Create a temporary table for the parquet data
    - Run the 4th query and determine the runtime again. Compare this runtime to the two previous runtimes.
    - Uncache the home_sales temporary table and verify that it is uncached using PySpark.

Thanks!!