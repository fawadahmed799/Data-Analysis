# Data Source: https://opendatatc.blob.core.windows.net/opendatatc/NCDB_1999_to_2017.csv

Data analysis of National Collision Database, that has records of police reported collisions(1999 to 2017) involving fatality or injury. 

# 1-Data Cleaning:
This dataset has 6772563 rows and 23 columns. Most of the columns have values in the form of codes, whose description is given in dictionary. We will be performing the following data cleaning step:
- Doing EDA to understand our data. What columns we have, what are the data types, how many unique values in categorical columns etc 
- Dropping unwanted columns
- Giving columns more meaningful names
- Dropping the rows with messy values e.g. 'UU' in AGE column
- Converting the data types
- Replacing the codes with their description as per dictionary
- Creating new columns
- Exporting the clean dataset to Power BI for further analysis

# 2-Analysis
We will be using various charts to analyse our data and to find the effect of various factors on fatality rate.

# 3-Findings:
1) Highest number of fatalities happen on Friday, 4pm!
2) 69.68% of fatalities happen on dry road surface. Only 6.48% happens on Icy road conditions.
3) Male fatality rate is almost double of female. Good part is that both have been declining constantly.
4) Fatality rate is highest on that NICE SUNNY day, i.e. 69.22%
5) 53.9% fatalities happen due to collision with opposite direction of traffic, 33% with involving single vehicle collisions and 13% with the vehicle travelling in the same direction.
6) 77.39% fatalities happen in light duty vehicles e.g. cars, SUV, trucks.
