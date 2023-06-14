

### Updated

Project title:
Determining the Relationship between Temperature Variation and Water Usage Patterns in Austin

Team Members:
Joel Rodriguez, Kady Epley, Sujatha Angajala

Project Descriptions / Outline 

This project investigates comprehensive insights into the relationship between water usage and temperature variation, as well as the impact of seasons on water consumption patterns in Austin, by analyzing historical data between 2013 and 2017. We will examine how water usage is affected by different seasons throughout the year.

Research Questions to Answers

Determine wheather is there any relationship between avrage monthly water usage in Austin and the variation in temperature by analyzing historical data between 2013 and 2017

Examine how water usage is affected by different seasons throughout the year. 

Which zip codes within the Austin metro area have the highest total monthly water consumption in gallons from monthly usage data between 2013 and 2017

How does the average monthly water usage differ among the predominant customer classes (Residential, Multi-Family, and Irrigation) within each zip code

Datasets to used – (timeframe of data: 2017 to 2022)
•	data.austintexas.gov – Water consumption
•	Kaggle – Austin Weather

Rough breakdown of Tasks 
•	Data collection and cleaning and plotting: Everyone
•	GitHub/Organization: Kady
•	Presentation: Everyone

Question 1
Determine wheather is there any relationship between avrage monthly water usage in Austin and the variation in temperature by analyzing historical data between 2013 and 2017
Cleaning up data:
Step 1:
    - Load data from  CVS file and convert them to data frames for both water consuption data and weather data.
    - Process raw data, by getting rid of all unwanted information, and selecting  water consuption data from only 2013 to 2022017.
    - Convert dates in the dataset to match their date format
    - Calculate the average temperature for each month in the weather dataset, as the data is provided for every day.
    - calculate the total water consumption for each month, as data provided for the total water consumption categorized by zip code and customer class.
    - Merge two data sets 
Step 2:

     plots


Step 2:

 - Bar plot is then used to depict the growth of population in 2 different years (2016 and 2021) in this 14th cities.
 - Geoview map is also used to depict the location of the cities and its growth in terms of the size of the points on the map. 

Step 3:
 - After narrowing the cities data, next is to search for nearest health facilities in the proximity.
 - Using Geoapify method to identify nearest hospitals and pharmacies in the research LGAs. 

Step 4:
 - Obtaining the health facilities distance from JSON format file from geoapify, horizontal bar plot is then used to depict how far is the nearest hospital and pharmacy for each cities. 
 - Similarly, geoview map is also used to illustrate how far apart are the hospital and pharmacy from each given cities location to each other.

Step 5:
 - From all these generated and tables, it is obvious that study needs to be done on 2 cities which are Baw Baw and Whittlesea that have shown no available of hospitals at nearby location. 
 - Cities such as Mitchell, Hume and Cardinia that takes longer to reach nearest hospitals would also be considered
 - Top 4 most populated cities would also be further explored to ensure they are capable to adapt to the increasing population growth.