# SQL


# Private Function Entertainment
This repository contains an SQL project focused on managing data related to jockeys and the events they perform at. The data is organized into two tables: "Disc_Jockey" and "Function." The "Disc_Jockey" table serves as the parent table and stores information about 30 jockeys, while the "Function" table acts as the child table and contains details of 70 events where the jockeys performed.

# Disc_Jockey Table
The "Disc_Jockey" table consists of the following attributes:

- Disc_Jockey_Id: The identification number of the jockey.
- Fname: The first name of the jockey.
- Sname: The surname of the jockey.
- Address: The address of the jockey.
- Town: The town where the jockey resides.
- County: The county where the jockey resides.
- Date_Of_Birth: The date of birth of the jockey.
- Email: The email address of the jockey.
- Music_Type: The genre of music performed by the jockey.
- Availability: The availability of the jockey, categorized as Midweeks, All Weeks, or Weekends.

#Function Table
The "Function" table includes the following attributes:

- Function_Id: The identification number of the event.
- Function_Date: The date when the event was organized.
- Function_Type: The type of event, such as Birthday, Retirement, Wedding, or Corporate Event.
- Food_Details: The type of food served during the event, including options like Finger Food, Sit Down Meal, Buffet, or Tea and Sandwiches.
- Num_Guests: The number of guests who attended the event.
- Bar_Details: Information about the bar where the event was organized, specifying if it had No Alcohol, a Free Bar, or All Drinks Charged to Guests.
- Start_Time: The start time of the event.
- Disc_Jockey_Id: The identification number of the jockey who performed at the event.
- Disc_Jockey_Fee: The fee charged by the jockey for the event.
- Venue_Name: The name of the venue where the jockey performed.
- Venue_Location: The location of the venue.
- Venue_Capacity: The capacity of the venue to accommodate guests during an event.

# Contents:

- Entity Relationship Diagrams (ERD):
This section provides visual representations of the database structure using ERDs, allowing for a clear understanding of the relationships between entities.

- Create Table and Insert Commands:
Here, you will find the necessary SQL commands to create tables and insert data into the database, ensuring the foundation for data manipulation and analysis.

- SQL Queries:
Explore a variety of SQL queries that leverage different functions and techniques to extract specific information from the database.

- RANK AND DENSE_RANK FUNCTIONS:
Learn how to use the RANK and DENSE_RANK functions to assign rankings to rows based on specified criteria, enabling efficient sorting and analysis.

- MOVING AVERAGE:
Discover how to calculate the moving average of a dataset, a useful technique for identifying trends and smoothing out fluctuations over time.

- REPORTING ON A SUM:
Explore methods for generating reports that provide insights into the sum of specific data points, facilitating effective data analysis and decision-making.

- RATIO OF A SUM:
Learn how to compute the ratio of sums, allowing for comparisons and analysis of different data categories within the database.

- LISTAGG() FUNCTION:
Understand how the LISTAGG() function can be used to concatenate values from multiple rows into a single string, simplifying data presentation and analysis.

- LAG() and LEAD() FUNCTIONS:
Discover how the LAG() and LEAD() functions can retrieve data from previous and subsequent rows, respectively, enabling time-based comparisons and analysis.

- FIRST() and LAST() FUNCTIONS:
Learn how to use the FIRST() and LAST() functions to retrieve the first and last values within a specific data set, aiding in identifying important data points.

- CUMULATIVE SUM FUNCTION:
Understand how to calculate the cumulative sum of a dataset, allowing for the tracking of running totals and cumulative values over time.

- PERCENT RANK FUNCTION:
Explore the percent rank function, which assigns a percentile rank to each row based on specified criteria, aiding in data comparison and analysis.

- NTILE() FUNCTION:
Learn how to divide data into equal-sized groups using the NTILE() function, facilitating data segmentation and analysis.

- HYPOTHETICAL RANK FUNCTION:
Discover the hypothetical rank function, which assigns hypothetical rankings to rows based on specified criteria, providing additional analytical possibilities.

- PIVOT CLAUSE:
Understand how to use the PIVOT clause to transform rows into columns, enabling easier data analysis and comparison across different categories.

- MODEL CLAUSE:
Explore the MODEL clause, a powerful tool for performing complex calculations and simulations within SQL queries, facilitating advanced data analysis.

- MODEL CLAUSE WITH RULES:
Discover how to use the MODEL clause in conjunction with rules to define complex calculations and manipulate data within SQL queries.

- PIVOT CLAUSE FOR MULTIPLE COLUMNS:
Learn how to utilize the PIVOT clause with multiple columns to pivot and transpose data, facilitating efficient data analysis and reporting.

- FETCHING CONSECUTIVE RECORDS:
Understand techniques for fetching consecutive records based on specified criteria, allowing for the extraction of sequential data points for analysis.

- CASE GROUPING AND ROLLUP FUNCTIONS:
Discover how to use CASE grouping and ROLLUP functions to group and summarize data based on specified criteria, aiding in data aggregation and analysis.

- ROW NUMBER FUNCTION:
Learn how to assign a unique row number to each row within a result set, enabling efficient data identification and analysis.

- CORR FUNCTION:
Explore the CORR function, which calculates the correlation coefficient between two sets of data, providing insights into their relationship.

- LIST AGGREGATE FUNCTION FOR CATEGORIES:
Discover how to use the list aggregate function for categorizing and summarizing data, simplifying data analysis and presentation.

- Nth VALUE FUNCTION:
Understand how the Nth VALUE function can be used to retrieve the value of a specific row within a result set, aiding in data analysis and extraction.

- AGGREGATE FUNCTIONS:
Learn about various aggregate functions available in SQL, such as SUM, COUNT, AVG, MIN, and MAX, enabling data summarization and analysis.

- LINEAR REGRESSION FUNCTION:
Explore the linear regression function, a statistical tool used to model and analyze the relationship between variables, providing insights into trends and predictions.

Please refer to the specific sections in the document to access the SQL queries and functions explained in detail.
