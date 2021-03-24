# COVID- 19 pandemic analysis by countries 

## Background:

The Covid-19 has impacted every aspect of people’s livelihood around the world. This pandemic has led to new cases and deaths every day for over an year. While this is a global pandemic, the number of cases and deaths differ for every country. We have decided to measure total cases, new cases, and total deaths in selected countries to find a trend for the pandemic as well as to find an association with the government policies using Stringency Index.

Stringency Index is a composite measure of nine of the response metrics. The nine metrics used to calculate the Stringency Index are: school closures; workplace closures; cancellation of public events; restrictions on public gatherings; closures of public transport; stay-at-home requirements; public information campaigns; restrictions on internal movements; and international travel controls.

Sources used: https://ourworldindata.org/covid-government-stringency-index
https://ourworldindata.org/covid-cases

### Business Question:
What is the trend of Covid-19 pandemic in the following countries: United States, Russia, Italy, South Korea, United Kingdom, and India? How does government policies affect the new cases and deaths in these countries? 
    
### Data Question	
Is stringency index correlated with how Covid-19 cases evolved in selected countries? Is there any correlation between human development index in the country and how many cases the country had per 1M?

### Analysis

*Justin*

**South Korea**

General trends in Covid development: 

![Covid 19 South Korea](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/SK%20general%201.png)
![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/SK%20general%202.png)

Graph shows that there was a significant increase of new cases in October due to the cluster infections in vulnerable facilities. As the South Korean government implemented new policies such as night curfew and limiting gatherings of 5 or more people in January, we were able to see a decline of new cases. 
Sources: https://edition.cnn.com/world/live-news/coronavirus-pandemic-10-23-20-intl/h_9cfa568f49e19518f5c21111ea2f98c5
http://www.koreaherald.com/view.php?ud=20201221000855

Multiple Linear Regression:

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/korea_regression.png) 

**United Kingdom**

General trends in Covid development: 

![Covid 19 UK](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/UK%20gen%201.png)
![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/UK%20gen%202.png)

In the United Kingdom, there was a dramatic increase of new covid cases in October and November due to the government’s attempts to help the restaurant industry. Many restaurants and cafeterias were reopened, and face-masks were not required in most eating establishments. The number of cases started to decline through January and February due to the number of people getting vaccinated and new lockdown policies.

Source:
https://www.vox.com/2020/10/10/21508165/covid-19-uk-cases-news
https://www.vox.com/2020/10/10/21508165/covid-19-uk-cases-news

Multiple Linear Regression:

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/UK%20regression.png)

**India** 

General trends in Covid development: 

![Covid 19 India](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/India%20gen%201.png)
![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/India%20gen%202.png)

India saw a significant increase of cases in August and throughout the Fall as there was no central coordination from the government and thus there was an increase of cases in rural areas. India is going through a second peak of the pandemic in March 2021 as people are not adhering to government policies and health guidelines of wearing masks and maintaining social distance.

Sources: https://www.ctvnews.ca/health/coronavirus/why-india-covid-19-cases-are-rising-to-multiple-peaks-1.5019183
https://www.bbc.com/news/world-asia-india-53969118
https://www.aljazeera.com/news/2021/3/19/why-is-india-staring-at-a-second-peak-of-covid-cases

Multiple Linear Regression:

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/India%20regresssion.png)

Multiple linear regression results: I have conducted a multiple linear regression analysis to find a correlation between stringency index with total cases, new cases, and total deaths in South Korea, United Kingdom, and India. Low significance F and the P-value under 0.05 for all three countries suggest an association between these variables. Thus, total cases, new cases, and total deaths would be a good predictor for stringency index. 

*Durdona*

**United States**

General Analysis US: 

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%206.45.11%20PM.png)
![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%206.45.43%20PM.png)

Cases in the US decreased during September and October, 2020 and then spiked again starting November, 2020 to January, 2021 causing the second wave. We can see that the case spike is directly related to a light decrease in the stringency index. 

Sources: https://www.theguardian.com/world/2020/nov/12/us-coronavirus-cases-deaths-november
https://www.cbsnews.com/news/covid-november-cases-united-states/

Multiple Linear Regression: 
![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%206.49.57%20PM.png)

Results: This multiple linear regression analysis display the relationship between an independent variable- Stringency Index and dependent variables: total cases, new cases, and total death. According to the low p values of dependent variable, we can concule that those three variables would be a good predictors of stringency index. Low significance F and the P-value under 0.05 suggest an association between these variables. Therefore, all dependent variables: total cases, new cases, and total deaths would be a good predictor for stringency index. 

Correlation between stringency index in the US and total and new cases: 

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%206.51.38%20PM.png)

Results: Following correlation analysis displays that total cases and new cases are correlated,, while surprisingly, correlation between stringency index and total cases is low. 

How cases evolved in the United States compared to the Conid-19 development in the world: 

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%208.14.02%20PM.png)

**Italy**

General analysis:

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/General%20Italy.png)

Italy saw significant increase in cases starting from October, 2020. Italy registered more deaths in 2020 than in any other year since World War Two, according to data that suggest COVID-19 caused thousands more fatalities than were officially attributed to it. Total deaths in Italy last year amounted to 746,146, statistics bureau ISTAT said, an increase of 100,525, or 15.6%, compared with the average of the 2015-2019 period. Looking at the period from when Italy’s COVID-19 outbreak came to light on February, 21 to the end of the year, the “excess deaths” were even higher at 108,178, an increase of 21% over the same period of the last five years.

Sources: https://www.bbc.com/news/world-europe-54937699
https://www.bmj.com/content/371/bmj.m4279
https://www.reuters.com/article/us-health-coronavirus-italy-dead/italy-2020-death-toll-is-highest-since-world-war-two-as-covid-19-hits-idUSKBN2AX1VJ

Multiple Regression: 


**Russia**

General analysis: 

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/General%20Russia%20.png)

Russian authorities have announced on Tuesday, November 10, that they will impose restrictions on the opening times of clubs, bars, restaurants, and other entertainment venues in Moscow from Friday, November 13 until January 15 due to a surge in coronavirus disease (COVID-19) cases. Colleges and universities in the capital were also be required to return to online teaching. In late October, the federal government ordered local authorities to enforce the mandatory use of face masks in some public places. Under the new nationwide measures, people are required to wear face masks in parking structures, lifts, and taxis, as well as on public transport. Mask requirements were already in place in some cities, including Moscow, but had not previously been introduced in many other areas of the country. Russia also follows the trend as US, with having Covid spikes starting December, 2020 to January, 2021.

Source: https://www.garda.com/crisis24/news-alerts/398321/russia-authorities-to-tighten-covid-19-restrictions-in-moscow-november-13-update-49

Multiple Regression: 




**Human Developmet Index**

The Human Development Index is a statistic composite index of life expectancy, education, and per capita income indicators, which are used to rank countries into four tiers of human development. This analysis examines if the covid case numbers depend on the human development index of the country. Ten countries with the highest human development index and 10 countries with the lowest human development index were taken to compare whether the Covid- 19 cases per 1 M people depend on the Human Development Index of the country. Looking at the correlation coefficient = 0.68, we can tell that there is a moderate positive relationship between human development index and Covid cases by country. 

![](https://github.com/DurdonaG/MidtermProject_COVIDCaseAnalysisByCountry/blob/main/Images/Screen%20Shot%202021-03-23%20at%207.22.11%20PM.png)

Sources: http://hdr.undp.org/en/content/human-development-index-hdi
https://news.google.com/covid19/map?hl=en-US&mid=/m/0ms6_&gl=US&ceid=US:en

## Conclusion 

  
  
  
