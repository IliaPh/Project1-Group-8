<img
  src="gf_pic.jpg"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">



# Project 1, Group 8


## The Effect of the George Floyd Killing on Crime in Minneapolis


## Research Team: *Ilia, Loukya, Ryan, William* (Group 8)


## Executive Summary



###*The Project's Conception*

Our plan was to obtain and analyze City of Minneapolis crime data to determine whether the George Floyd killing on May 25, 2020 affected crime in the city. We easily discovered a relatively tidy dataset in .csv file format from the City of Minneapolis itself, published online as part of the city's "Open Data Minneapolis" (https://opendata.minneapolismn.gov/) initiative. The dataset provided crime data from 2017 to the present, arranged by neighborhood and type of crime. 



###*Our Research Questions*

Each member of the research team developed a research question to help us frame our inquiry: 

- Did the distribution of crimes change after the George Floyd killing? LOUKYA

- Did the violent crime rate change after the George Floyd killing? RYAN

- Did the property crime rate change after the George Floyd killing? ILIA

- Which neighborhoods experienced the greatest increases in crime after the George Floyd killing? WILLIAM



###*Our Hypothesis*

As we explored the dataset to begin to answer these research questions, we developed the following hypothesis for testing purposes:

"Crime worsened in Minneapolis after the George Floyd killing."

The *null hypothesis* thus became:

"The George Floyd killing had no effect on crime in Minneapolis."

###*Our Strategy*


Our strategy was three-fold: 

**(1) Examine the crime data with a "wide" lens** 

We looked at 2 years worth of data *before* the George Floyd killing and 2 years *after* the George Floyd killing. Wrangling the dataset, we were able to visualize crime rate trend lines and the distribution and aggregation of 8 particular types of crime.  When it was possible to do so, we rendered separate visualizations for property crime, violent crime, and overall crime.        

**(2) Examine the crime data with a "narrow" lens** 

We looked at 1 month worth of data *before* the George Floyd killing and 1 month *after* the George Floyd killing, and added year-over-year comparisons of these months to see what "typical" May and June crime data in Minneapolis looked like. Our visualizations for this narrow time period also represent property crime, violent crime, and overall crime.  They focus in on numerical difference and percent change by neighborhood community.   

**(3) Run student t-tests on our dataset to attempt to reject the *Null Hypothesis***

Since we wanted to compare "before George Floyd" and "after George Floyd" for both the "wide" and "narrow" crime datasets, we chose the independence "Student's t-test" (comparing the means of one population with the mean of another). 



6 t-tests were conducted in total: 

1. **Property Crime (1 month before and after GF)**
    Ttest_indResult(statistic=-0.11594176548185957, pvalue=0.9088550319514616)

2. **Violent Crime (1 month before and after GF)**
    Ttest_indResult(statistic=-1.1424975576593623, pvalue=0.2689013645089005)

3. **All Crime (1 month before and after GF)**
    Ttest_indResult(statistic=-0.5902953307278089, pvalue=0.5617522529882506)

4. **Property Crime (2 years before and after GF)**
    Ttest_indResult(statistic=-0.048305062358812385, pvalue=0.963048404307157)

5. **Violent Crime (2 years before and after GF)**
    Ttest_indResult(statistic=-0.45243726308686233, pvalue=0.6686713891255816)

6. **All Crime (2 years before and after GF)**
    Ttest_indResult(statistic=1.925793725429242, pvalue=0.06022527196564675)



###*Principal Findings*


Our t-test results showed that we failed to reject the *null hypothesis*, as each p-value did not meet the p-value < 0.05 threshold. Thus, our analysis must conclude that we have not discovered any statistically significant relationship between the George Floyd killing and crime in Minneapolis. 

Since the p-values for all t-tests are not < 0.05, we failed to reject the null hypothesis. 

Nevertheless, we were able to answer our research questions to our satisfaction. 

- Did the distribution of crimes change after the George Floyd killing? 

*We can say that before the incident Larceny accounts for almost 55.6% of the total crime whereas it is reduced to 48.7% after the incident.*

*There is an increase in Auto Theft and Robbery after the incident from 12.8% to 17.8% and   from 5.7% to 8.5% respectively.*

*Crimes like Homicide and Arson also increased by a small percentage.*

*Crime rate of Burglary and Rape reduced after the incident.*

*Aggravated Assault also increased after the incident.*


- Did the violent crime rate change after the George Floyd killing? 

*Based off of the data for 2 years before and 2 years after the George Floyd event, you can see that violent crimes rates rose (excluding rape) and that property crime rates of arson and theft rose but burglary and larceny fell.* 

*Before the George Floyd event there were a total of  46,108 crimes reported in the previous 2 years but after there were 50,318 crimes reported which is roughly a 9% increase.*

*Violent crimes before the George Floyd event totaled 7,558 while after they totaled 10,304 cases. This tracks to roughly a 36% increase in violent crimes.*



- Did the property crime rate change after the George Floyd killing?

*During a 2-year period before the George Floyd event, the total crime cases reflect ups and downs.  The crime cases  significantly increased after February 2019 and went down from July 2019. The crime cases remained relatively stable until the George Floyd event with the slight changes.*

*The crime noticeably increased for a few months after the George Floyd event, and it started to decline from August 2020 to February 2021. After February, it started to increase again, the same as it was shown before the George Floyd killing.*

*The line plot of total crimes combined before and after the George Floyd killing reflects a 4-year period, two years before and after the event. Based on the graph, the crime rates increased after the George Floyd killing but at the same time the trend remained the same. The crime rate tends to increase during Spring and Summer, and starts to decrease in Fall and Winter. The George Floyd killing did not reflect a significant impact on the total crime in Minneapolis. However, some of the neighborhoods in Minneapolis were negatively impacted, which is detailed in the analysis below.*


- Which neighborhoods experienced the greatest increases in crime after the George Floyd killing?

*For property crime, the Southwest neighborhood community experienced the greatest % change (25%), followed closely by Camden (22%).* 

*For violent crime, the Central and Northeast neighborhood communities tied for the greatest % change (100%), followed closely by University (92%).*

*For overall crime (i.e. property + violent), the Southwest neighborhood community experienced the greatest % change (29%).* 

**FYI: 38th Street and Chicago Avenue (aka “George Floyd Square”) is in the Powderhorn community**


###*Take-aways*

While we were able to answer our research questions, the research team was surprised with the t-test results. Although we were unable to reject the null hypothesis, the data show alarming upticks in some categories of crime across certain neighborhoods of Minneapolis. Moreover, our line plots clearly show that crime in Minneapolis fluctuates seasonally to a large degree. Further analysis should be conducted to guide Minneapolis policy-makers in their pursuit of crime-reducing measures. 


## Dataset 

This data set covers Minneapolis Neighborhoods from 2017-2022 and is a live data set that gets updated regularly. 

https://opendata.minneapolismn.gov/datasets/neighborhood-crime-stats/explore
