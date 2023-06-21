# project-one


### **Project title:**
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

**Local governments** can use the analysis of water consumption by pin code to identify areas with water scarcity or excessive usage. This helps them develop conservation programs, implement water-saving initiatives, and create fair policies for water distribution in the region 

--------

#### **Question One**

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

-------

#### **Question Two**
#### **Research question:**
Which zip codes in the Austin metro area have the highest total monthly water consumption in gallons? (2013-2017 data)

#### **Results**
The datasets that were used for this question were from Kaggle and from the Austintexas.dataset.gov website. The datasets gathered data on water usage in the Austin-metro area, the temperature, humidity, and customer classes. Cleaning and analyzing the data from the two used data sets for the water consumption for the zip codes in the Austin-metro area we found that the usage is consistent throughout. The top ten zip codes with the most water consumption in the metro area are shown below in the graph, which shows the consistency in the usage of water.

![image](https://github.com/kadyepley/project-one/assets/131110404/4fc7189b-f4ed-4891-9d17-f0f551ef3aa7)

##### **Conclusion:**
The conclusion that could be gathered for this question is that there isn't one geographical area in Austin that consumes more water than the others in or around the city. The data could help local government find a solution to water usage in the city if access to water becomes a bigger issue with climate change affecting the planet as time passes by.

---------

#### **Question Three**
#### **Research question:**
How does the total monthly water usage differ among the predominant customer classes (Residential, Multi-Family, and Irrigation) within each zip code?

#### **Results**
To display the water usage by customer class, we created a line graph that displays the four customer classes, Residential, Multi-Family, Irrigation - Residential, and Irrigation - Multi-Family's total water usage over the course of each year. This allows us to observe the seasonal patterns in relation to the other customer classes. From this visualization, we can tell that the Residential customer class has the most dramatic responses to the seasons, mirroring the pattern displayed in our seasonality findings.  The Multi-Family customer class has much small increases in the summer and fall months and is more consistent in its usage. Inversely, the Irrigation - Multi-Family customer class line shows more seasonal increases compared to the Irrigation - Residential's water usage. This could be linked to residential homes using less water for agriculture, landscaping, and shared resources like pools compared to apartment complexes, mobile and trailer home parks, and shared living facilities. 

![image](https://github.com/kadyepley/project-one/blob/main/Austin_Weather_Water/Images/q3_lineplot.png)

Our bar chart emphasizes the difference in water volume by customer class. This visual really nails home the sheer amount of water that is being used by Residential compared to the other three customer classes. This would be useful for lawmakers and other key community stake holders when considering the demographics to further research and link to water usage, incentivizing reduced water usage, and considering water restrictions within the community.  

![image](https://github.com/kadyepley/project-one/blob/main/Austin_Weather_Water/Images/q3_bar.png)

##### **Conclusion:**
Water usage by the Residential customer class is the largest user of water by volume and the behavior associated with the usage is very seasonal. This would be a key information in developing strategies to curb water usage amoung this customer class. 

The Irrigation extension of the Residential customer class is less than its Irrigation - Multi-Family counterpart and more resistent to season increases identified in question 1. More investigation into the routines of these communities would be needed to identify the behavior causing this difference in Irrigation practices. However, this would be a lower priority than reducing the volume used by Residential and Multi-Family customer classes. 

------------

##### Limitations: 

_City Growth_
We were not able to account for population growth and changes in customer classes over time. This would be useful to see how the water usage changes in relations to population growth.

_Limited Data_
This data is limited in the years that it covers. It does not account for trends across decades in relation to population. 

_Exclusion of Commercial Water Usage_
When stakeholders in the community are making decisions, our analysis does not include the commercial water use. This would be another signification use of water that would be worth exploring when researching ways to reduce water usage in the wake of water restrictions due to climate change. 


