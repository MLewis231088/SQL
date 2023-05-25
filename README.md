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

#Contents
- Entity Relationship Diagrams (ERD)
- Create Table and Insert Commands
- SQL Queries
- RANK AND DENSE_RANK FUNCTIONS
- MOVING AVERAGE
- REPORTING ON A SUM
- RATIO OF A SUM
- LISTAGG() FUNCTION
- LAG() and LEAD() FUNCTIONS
- FIRST() and LAST() FUNCTIONS
- CUMULATIVE SUM FUNCTION
- PERCENT RANK FUNCTION
- NTILE() FUNCTION
- HYPOTHETICAL RANK FUNCTION
- PIVOT CLAUSE
- MODEL CLAUSE
- MODEL CLAUSE WITH RULES
- PIVOT CLAUSE FOR MULTIPLE COLUMNS
- FETCHING CONSECUTIVE RECORDS
- CASE GROUPING AND ROLLUP FUNCTIONS
- ROW NUMBER FUNCTION
- CORR FUNCTION
- LIST AGGREGATE FUNCTION FOR CATEGORIES
- Nth VALUE FUNCTION
- AGGREGATE FUNCTIONS
- LINEAR REGRESSION FUNCTION

Please refer to the specific sections in the document to access the SQL queries and functions explained in detail.
