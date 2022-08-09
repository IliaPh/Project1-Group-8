# Project 1, Group 8
Group Project 1

Principal Findings

======================================================================
Exploratory Data Analysis Jupyter Notebook

All - Interest in Crime changes in twin cities, that focused our inquiry on The George Floyd (GF) killing and its effect on crime in Minneapolis neighborhoods. 
 
Ryan - cleaning and wrangling the data, initial visualizations to see what our data looks like

Ilia - plotting longer term crime trends, showing GF “spike”

Loukya - plotting distribution of property and violent crimes before and after GF

William - plotting aggregate neighborhood % change crime data for month before and after GF 

======================================================================
Final Analysis Jupyter Notebook



Ilia’s Analysis

During a 2-year period before the George Floyd event, the total crime cases reflect ups and downs.  The crime cases  significantly increased after February 2019 and went down from July 2019. The crime cases remained relatively stable until the George Floyd event with the slight changes.
The crime noticeably increased for a few months after the George Floyd event, and it started to decline from August 2020 to February 2021. After February, it started to increase again, the same as it was shown before the George Floyd killing. 
The line plot of total crimes combined before and after the George Floyd killing reflects a 4-year period, two years before and after the event. Based on the graph, the crime rates increased after the George Floyd killing but at the same time the trend remained the same. The crime rate tends to increase during Spring and Summer, and starts to decrease in Fall and Winter. The George Floyd killing did not reflect a significant impact on the total crime in Minneapolis. However, some of the neighborhoods in Minneapolis were negatively impacted, which is detailed in the analysis below.



William’s Analysis

Minneapolis has 87 officially recognized neighborhoods.
87 ticks on a plot seemed too unwieldy, so I searched for a way to group them.
Upon examining our dataset, we discovered that some neighborhoods around the former “Lake Calhoun” also changed their names. Once we did some detective work on these name changes, we were able to tidy the dataset and arrive at the same number of data points per neighborhood. 

It turns out that there are 11 officially recognized neighborhood “communities” which are conglomerate groups of individual neighborhoods, so I chose to arrange the data by these 11.  (https://en.wikipedia.org/wiki/Neighborhoods_of_Minneapolis)
Our dataset was ordered by date, neighborhood, and type of crime. There were 8 types of crimes, with 4 being property crimes and 4 being violent crimes.  


Property crime categories = Arson, Auto Theft, Burglary,  Larceny
(https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/topic-pages/property-crime)

Violent crime categories = Aggravated Assault, Homicide, Rape, Robbery
(https://ucr.fbi.gov/crime-in-the-u.s/2016/crime-in-the-u.s.-2016/topic-pages/violent-crime) 

In order to understand any relationship between the George Floyd killing and crime in Minneapolis, I thought it prudent to examine crime data for the month before the killing and the month after the killing (George Floyd was killed on 5/25/2020, so we used 6/1/2020 as our midpoint.  We considered all of 5/2020 as 1 month before, and all of 6/2020 data as 1 month after.)  
I looked at changes in numbers of property and violent crimes by neighborhood community, then also calculated % change for this time period. 



Which neighborhoods in Minneapolis experienced the greatest increases in crime during the George Floyd period? 
For property crime, the Southwest neighborhood community experienced the greatest % change (25%), followed closely by Camden (22%). 
For violent crime, the Central and Northeast neighborhood communities tied for the greatest % change (100%), followed closely by University (92%).
For overall crime (i.e. property + violent), the Southwest neighborhood community experienced the greatest % change (29%). 
FYI: 38th Street and Chicago Avenue (aka “George Floyd Square”) is in the Powderhorn community



T-test results 
Null Hypothesis = “GF killing had no effect on crime in Minneapolis one month post-killing.”

Property Crime (1 month before and after GF)

Ttest_indResult(statistic=-0.11594176548185957, pvalue=0.9088550319514616)

Violent Crime (1 month before and after GF)

Ttest_indResult(statistic=-1.1424975576593623, pvalue=0.2689013645089005)

All Crime (1 month before and after GF)

Ttest_indResult(statistic=-0.5902953307278089, pvalue=0.5617522529882506)

Since the p-values for all t-tests are not < 0.05, we cannot reject the null hypothesis. 



Ryan's Analysis

Based off of the data for 2 years before and 2 years after the George Floyd event, you can see that violent crimes rates rose (excluding rape) and that property crime rates of arson and theft rose but burglary and larceny fell. 
Before the George Floyd event there were a total of  46,108 crimes reported in the previous 2 years but after there were 50,318 crimes reported which is roughly a 9% increase.
Violent crimes before the George Floyd event totaled 7,558 while after they totaled 10,304 cases. This tracks to roughly a 36% increase in violent crimes.
Property crimes before the George Floyd event totaled 38,550 while after they totaled 40,104 cases. This tracks to roughly a 4% increase in property crimes.



Loukya's Analysis

Based on the visualizations :

We can say that before the incident Larceny accounts for almost 55.6% of the total crime whereas it is reduced to 48.7% after the incident.
There is a huge increase in Auto Theft and Robbery after the incident from 12.8% to 17.8% and   from 5.7% to 8.5% respectively.
Crimes like Homicide and Arson also increased by little percentage.
Crime rate of Burglary and Rape reduced after the incident.
Aggravated assault also increased after the incident.
When 
