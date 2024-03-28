---
layout: post
title:  "A2: A short data story"
date:   2024-03-26 17:14:23 +0100
categories: jekyll update
---

# Assignment 2

**Description of the data**
The Government of San Fransisco publishes a variety of government datasets including a historical dataset on reports of crime incidents in San Fransisco. The dataset describes every report of a crime in San Fransisco during the years 2003-2018. The incident reports contain geographical information as well as details about the type and time of the crime. The dataset can be found [here](https://data.sfgov.org/browse?category=Public+Safety)

### Increases in property crime in San Fransisco
Examining the crime data, we see that San Fransisco has experienced a huge increase in theft and larceny since 2012. From 2003 to 2012 the number of thefts reported across San Fransisco was quite stable with an average number of thefts in 6 months of approx. 2100 reports. However, in 2012 there was a sudden spike in thefts, that continues over the years. Following the next 6 years, the number of reported thefts and larceny doubled. 

![]( /docs/assets/Larceny_Theft_SF_2003_2017.png)

The spike in property crime has been noticed by legislators and media in San Fransisco. In 2014 the [San Fransisco Cronichle](https://www.latimes.com/local/crime/la-me-aa2-snapshot-sf-crime-20141120-story.html) reported the massive spikes in property crime, arguing that the increases in income inequality in the city was to blame. Property crime is considered a poverty crime, and while San Fransisco has benefited economically from the tech industry, the wealth has been unequally distributed across the population. The increased inequality in income became a subject of [academic research](https://siliconvalleyindicators.org/pdf/income-inequality-2015-06.pdf) in the following years. 

However, when examining trends in unemployment and median household income from 2012 to 2018, the unemployment rate seems to be going [down](https://fred.stlouisfed.org/series/CASANF0URN), while the median household income is [going up](https://fred.stlouisfed.org/series/MHICA06075A052NCEN). Further, the estimated number of people in San Fransisco living in poverty has been [decreasing](https://fred.stlouisfed.org/series/PEAACA06075A647NCEN) decreasing since 2012. 

As the aggregated statistics indicate that the city overall is getting wealthier, the question remains if the spike in property crime is caused by poor districts getting poorer and driving up the crime. In the following plot, I explore the geographical patterns of theft and larceny

## Geographical patterns in theft


Is the increase in theft driven by one specific district? I map the development in theft reports from 2003 to 2017 across the police districts in San Fransisco. I indexed the development in theft against the theft level in 2003. The plot displays the yearly increase or decrease in theft compared to the 2003 level. The plot shows that in most districts the crime level was going down compared to 2003. In 2013 the number of theft reports increased across all districts by at least 20% compared to the 2003 level. The Districts Southern, Mission, and Richmond experienced a 50% increase in crime levels compared to 2003. From 2023 to 2018 theft has increased by at least 100% since 2003 in Central, Northern, Mission, and Richmond. 
<embed type="text/html" src="/docs/assets/Thefts_sanfransisco_map_theft_increase_since_2003.html" width="1200" height="700"></embed>
To identify the most crime-torn districts I have calculated theft per square kilometer. Tenderloin was the most crime-torn district in 2003, followed by Southern, Central, and then Northern. The pattern is the same in 2011. Having that in mind, the plot tells us that, the spike in thefts in San Fransisco, is due to increases in theft in districts Mission and Richmond, which before 2012 had low rates of theft, and increases in theft in districts that were already crime-torn.   

Tenderloin is a curious district because the district there has only been a 12% increase in thefts since 2003, but it is still the district with the highest number of thefts reported per square kilometer. 

In conclusion, increased property crime has spread across the city from 2012 to 2018. After 2012 areas close to the city center experienced an increase in property theft, while the rate of property theft in the city center also increased. 

The question is, if it is only theft that follows this tendency, or if the districts have seen similar developments in other types of crime.

## Geographical patterns in other types of crime


<embed type="text/html" src="/docs/assets/Crime_district_year_interact.html" width="1200" height="700"></embed>
