



### Updated

Project title:
Determining the Relationship between Temperature Variation and Water Usage Patterns in Austin

Team Members:
Joel Rodriguez, Kady Epley, Sujatha Angajala

Project Description/Outline:

This project aims to explore the relationship between water usage and temperature variation in Austin, as well as the impact of seasons on water consumption patterns. We will analyze historical data from 2013 to 2017 to gain comprehensive insights into these factors.

Research Questions to Answer:

Is there a relationship between average monthly water usage in Austin and temperature variation? (2013-2017 data)
How does water usage change throughout the year across different seasons?

Which zip codes in the Austin metro area have the highest total monthly water consumption in gallons? (2013-2017 data)

How does the total monthly water usage differ among the predominant customer classes (Residential, Multi-Family, and Irrigation) within each zip code?

Datasets to be Used (timeframe: 2017 to 2022):

Data from data.austintexas.gov on water consumption
Austin Weather dataset from Kaggle

Rough Breakdown of Tasks:

Everyone: Data collection, cleaning, and plotting
Kady: GitHub/Organization
Everyone: Presentation

##### Research question 1:
Is there a relationship between average monthly water usage in Austin and temperature variation (2013-2017 data)?
##### Results:
Based on the analysis of four years of data, we found a strong positive correlation (Correlation coefficient: 0.72) between average temperature and monthly water consumption. This indicates that as the average temperature increases, the monthly water consumption tends to increase as well.

Additionally, the extremely low p-value (2.8001668828740518e-08) suggests strong evidence against the null hypothesis. Therefore, we reject the null hypothesis and accept the alternative hypothesis. The observed correlation is statistically significant.

By analyzing the box plot, we observed that the median water consumption increases as the temperature ranges become higher. This suggests a positive linear relationship between temperature and water consumption
##### Conclusion:
Based on the analysis, we can conclude that as the average temperature rises, we can expect an increase in monthly water consumption. This relationship is unlikely to be a coincidence.

Limitations: The analysis has not considered other factors, such as city growth.
##### Research question 2:
How does water usage change throughout the year across different seasons?
##### Results:
Based on the observation of the monthly data over a span of four years, it is evident that the median monthly water consumption is higher during the Summer and Fall seasons, while it is lower during the Spring and Winter seasons. Specifically, the highest median water consumption is observed during the Summer, while the lowest median water consumption occurs during the Winter
##### Conclusion:
The above observations suggets a seasonal influence on water consumption

##### Stastics
	    Total water consumed	Average Temperature

min	    1.45 Millions           48.82
max	    2.76 Millions	        89.16
Median	1.77 Millions	        71.73
mean	1.9 Millions            70.26
std	    .33 Millions	        12.625248

Temperature Range: <60	Temperature Range: 60-69		Temperature Range: 70-79		Temperature Range: 80-89

Mean: 1.68 Millions	    Mean: 1.72 Millions		        Mean: 1.89 Millions		        Mean: 2.27 Millions
Median: 1.7 Millions	Median: 1.73 Millions		    Median: 1.84 Millions		    Median: 2.26 Millions
Min: 1.45 Millions	    Min: 1.51 Millions		        Min: 1.64 Millions		        Min: 1.7 Millions
Max: 1.95 Millions	    Max: 1.95 Millions		        Max: 2.4 Millions		        Max: 2.76 Millions
SD: 0.13 Millions	    SD: 0.13 Millions		        SD: 0.23 Millions		        SD: 0.3 Millions

Spring	                           Fall	                        Summer 	         Winter			

min      1.54 Millions	min      1.84 Millions	min      1.70 Millions	min      1.45 Millions
median   1.720 Millions	median   2.10 Millions	median   2.134473e+09	median   1.66 Millions
max      1.98 Millions	max      2.68 Millions	max      2.763112e+09	max      1.77 Millions
std      .133 Millions	std       .30 Millions	std      3.126551e+08	std      1.09 Millions
mean     1.73 Millions	mean     2.17 Millions	mean     2.20 Millions	mean     1.65 Millions
