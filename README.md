

<!-- ### **Project title:**
Determining the Relationship between Temperature Variation and Water Usage Patterns in Austin
#### **Team Members:**
Joel Rodriguez, Kady Epley, Sujatha Angajala
#### **Project Description/Outline:**
This project aims to explore the relationship between water usage and temperature variation in Austin, as well as the impact of seasons on water consumption patterns. We will analyze historical data from 2013 to 2017 to gain comprehensive insights into these factors.

#### **Research Questions to Answer:**
1. Analyze the  impact of weather and seasons on water consumption?

3. Which zip codes in the Austin metro area have the highest total monthly water consumption in gallons? (2013-2017 data)

4. How does the total monthly water usage differ among the predominant customer classes (Residential, Multi-Family, and Irrigation) within each zip code?

#### **Datasets to be Used (timeframe: 2013 to 2017):**
Data from data.austintexas.gov on water consumption
Austin Weather dataset from Kaggle
#### **Rough Breakdown of Tasks:** 
Everyone: Data collection, cleaning, and plotting

Kady: GitHub/Organization

Everyone: Presentation
#### **Target audience:**

**Water utility companies** can benefit by analyzing how water consumption changes with temperature fluctuations. This helps them manage resources better and plan for different water demand in different seasons.

**Local governments** can use the analysis of water consumption by pin code to identify areas with water scarcity or excessive usage. This helps them develop conservation programs, implement water-saving initiatives, and create fair policies for water distribution in the region -->

#### **Research question:**
Analyze the impact of weather variations, such as temperature and humidity, as well as seasons on water consumption

#### **Results:**
**Temperature Variations**
Calculations results: Correlation coefficient: 0.72 , pvalue: 2.8001668828740518e-08 for avrage temperature per month vs Average water consumed per month
                      Correlation coefficient: -0.25 , pvalue: 0.09610620068416795 for humidity vs water consumed 

Based on the analysis and calculation of four years of data, as well as the scatter plots with regression lines generated using this data, we found a strong positive correlation (Correlation coefficient: 0.72) between average temperature and monthly water consumption. This indicates that as the average temperature increases, the monthly water consumption tends to increase as well.

Additionally, the extremely low p-value (2.8001668828740518e-08) suggests strong evidence against the null hypothesis. Therefore, we reject the null hypothesis and accept the alternative hypothesis. The observed correlation is statistically significant.

Box plot analysis shows that median water consumption tends to increase as the temperature ranges become higher, indicating a positive relationship between temperature and water consumption.

**Humidity Variations**

Correlation coefficient: -0.25 , pvalue: 0.09610620068416795 for humidity vs water consumed

The p-value of 0.09610620068416795 suggests that there is not enough evidence to reject the null hypothesis. The null hypothesis states that there is no correlation between water usage and humidity level .We found very week negative correlation (-.25 )

**Seasonal Variations**

Based on the observation from  scatter plot and boxplot for each season showing water consumption , it is evident that the average monthly water consumption is higher during the Summer and Fall seasons, while it is lower during the Spring and Winter seasons. Specifically, the highest average water consumption is observed during the Summer, while the lowest average water consumption occurs during the Winter


##### **Conclusion:**
Based on the analysis, we can conclude that as the average temperature rises, we can expect an increase in monthly water consumption.This relationship is unlikely to be a coincidence.

There is no correlation between water usage and humidity persentage

Based on the observation from  scatter plot and boxplot for each season showing water consumption , it is evident that the average monthly water consumption is higher during the Summer and Fall seasons, while it is lower during the Spring and Winter seasons. Specifically, the highest average water consumption is observed during the Summer, while the lowest average water consumption occurs during the Winter

##### Limitations: 
The analysis has not considered other factors, such as city growth.




##### **Statistics**
| Statistic | Total water consumed (Millions) | Average Temperature |
| --------- | ------------------------------ | ------------------- |
| min       | 1.45                           | 48.82               |
| max       | 2.76                           | 89.16               |
| Median    | 1.77                           | 71.73               |
| mean      | 1.9                            | 70.26               |
| std       | 0.33                           | 12.62               |



| Temperature Range   | Mean (Millions) | Median (Millions) | Min (Millions) | Max (Millions) | Standard Deviation (Millions) |
| ------------------- | --------------- | ----------------- | -------------- | -------------- | ---------------------------- |
| <60                 | 1.68            | 1.7               | 1.45           | 1.95           | 0.13                         |
| 60-69               | 1.72            | 1.73              | 1.51           | 1.95           | 0.13                         |
| 70-79               | 1.89            | 1.84              | 1.64           | 2.4            | 0.23                         |
| 80-89               | 2.27            | 2.26              | 1.7            | 2.76           | 0.3                          |



| Season  | Min (Millions) | Median (Millions) | Max (Millions) | Standard Deviation (Millions) | Mean (Millions) |
| ------- | -------------- | ----------------- | -------------- | ---------------------------- | --------------- |
| Spring  | 1.54           | 1.720             | 1.98           | 0.133                        | 1.73            |
| Fall    | 1.84           | 2.10              | 2.68           | 0.30                         | 2.17            |
| Summer  | 1.70           | 2.134473e+09      | 2.763112e+09   | 3.126551e+08                 | 2.20            |
| Winter  | 1.45           | 1.66              | 1.77           | 1.09                         | 1.65            |

