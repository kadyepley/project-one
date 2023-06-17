

#### **Project title:**
    Determining the Relationship between Temperature Variation and Water Usage Patterns in Austin
##### **Team Members:**
    Joel Rodriguez, Kady Epley, Sujatha Angajala
##### **Project Description/Outline:**
    This project aims to explore the relationship between water usage and temperature variation in Austin, as well as the impact of seasons on water consumption patterns. We will analyze historical data from 2013 to 2017 to gain comprehensive insights into these factors.

##### **Research Questions to Answer:**
    1. Is there a relationship between average monthly water usage in Austin and temperature variation? (2013-2017 data)
    2. How does water usage change throughout the year across different seasons?

    3. Which zip codes in the Austin metro area have the highest total monthly water consumption in gallons? (2013-2017 data)

    4. How does the total monthly water usage differ among the predominant customer classes (Residential, Multi-Family, and Irrigation) within each zip code?

##### **Datasets to be Used (timeframe: 2017 to 2022):**
    Data from data.austintexas.gov on water consumption
    Austin Weather dataset from Kaggle
##### **Rough Breakdown of Tasks:** 
    Everyone: Data collection, cleaning, and plotting
    Kady: GitHub/Organization
    Everyone: Presentation
##### **Research question 1:**
    Is there a relationship between average monthly water usage in Austin and temperature variation (2013-2017 data)?
##### **Results:**
    Based on the analysis of four years of data, we found a strong positive correlation (Correlation coefficient: 0.72) between average temperature and monthly water consumption. This indicates that as the average temperature increases, the monthly water consumption tends to increase as well.

    Additionally, the extremely low p-value (2.8001668828740518e-08) suggests strong evidence against the null hypothesis. Therefore, we reject the null hypothesis and accept the alternative hypothesis. The observed correlation is statistically significant.

    By analyzing the box plot, we observed that the median water consumption increases as the temperature ranges become higher. This suggests a positive linear relationship between temperature and water consumption
##### **Conclusion:**
    Based on the analysis, we can conclude that as the average temperature rises, we can expect an increase in monthly water consumption. This relationship is unlikely to be a coincidence.
##### Limitations: 
    The analysis has not considered other factors, such as city growth.
##### **Research question 2:**
    How does water usage change throughout the year across different seasons?
##### **Results:**
    Based on the observation of the monthly data over a span of four years, it is evident that the median monthly water consumption is higher during the Summer and Fall seasons, while it is lower during the Spring and Winter seasons. Specifically, the highest median water consumption is observed during the Summer, while the lowest median water consumption occurs during the Winter
##### **Conclusion:**
    The above observations suggets a seasonal influence on water consumption
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

