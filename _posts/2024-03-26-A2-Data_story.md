---
layout: post
title:  "A2: A short data story"
date:   2024-03-26 17:14:23 +0100
categories: jekyll update
---


# Assignment 2

**Description of the data**

The Government of San Fransisco publishes a variety of government datasets including a historical dataset on reports of crime incidents in San Fransisco. The dataset describes every report of a crime in San Fransisco during the years 2003-2018. The incident reports contain geographical information as well as details about the type and time of the crime. The dataset can be found [here](https://data.sfgov.org/browse?category=Public+Safety)
## Increases in property crime in San Fransisco
Examining the crime data, we see that San Fransisco has experienced a huge increase in theft and larceny since 2012. From 2003 to 2012 the number of thefts reported across San Fransisco was quite stable with an average number of thefts in 6 months of approx. 2100 reports. However, in 2013 there was a sudden spike in thefts, that continues until 2018.From 2013 to 2018 the number of reported thefts and larceny in San Fransisco doubled. 
![]( /docs/assets/Larceny_Theft_SF_2003_2017.png)

The increased number of reports of theft has been covered by the media in San Fransisco. In 2014 the [San Fransisco Cronichle](https://www.latimes.com/local/crime/la-me-aa2-snapshot-sf-crime-20141120-story.html) reported the massive spikes in property crime. Property crime is considered a poverty crime, but while theft rates went up, the city was also getting wealthier. From 2013 to 2018 the median household income in San Fransisco went [up](https://fred.stlouisfed.org/series/MHICA06075A052NCEN), while the unemployment rate went  [down](https://fred.stlouisfed.org/series/CASANF0URN). Further, the estimated number of people in San Fransisco living in poverty was  [decreasing](https://fred.stlouisfed.org/series/PEAACA06075A647NCEN) since 2013. However, underneath the increased wealth of the city was also an increasing income inequality. This was, according to the [San Fransisco Cronichle](https://www.latimes.com/local/crime/la-me-aa2-snapshot-sf-crime-20141120-story.html) the main driver of the increases in property crime such as theft. As the wealth was not distributed equally across the city, neither should the crime expected to be. In the following plot, I explore the geographical patterns of theft and larceny

## Geographical patterns in theft
To examine how reports of theft occurred over time and across the city, I map the percentual development in theft reports from 2003 to 2017 across the police districts in San Fransisco. I indexed the development in theft against the theft level in 2003. The plot displays the yearly increase or decrease in theft compared to the 2003 level. The plot shows that in most districts the crime level was going down until 2013. by 2013 the number of theft reports had increased across all districts by at least 20% compared to the 2003 level. The Districts Southern, Mission, and Richmond experienced a 50% increase in theft. From 2023 to 2018 theft has increased by at least 100% since 2003 in Central, Northern, Mission, and Richmond.  The plot reveals that while theft has increased in every district, the districts closes to the city center have seen the largest increase in theft. 
<embed type="text/html" src="/docs/assets/Thefts_sanfransisco_map_theft_increase_since_2003.html" width="1200" height="700"></embed>
The districts with the highest increase in theft, could be districts with low rates of theft in general. Is the increased theft rate caused by districts with high crime rates experiencing more crime or low crime districts experiencing more crime? Or has low crime districts seen an increase in theft. To answer that question, I calculated theft per square kilometer for each district across the years. Tenderloin was the most crime-torn district in 2003, followed by Southern, Central, Northern and Mission. The pattern is the same in 2011. 
Having that in mind the plot tells us that there is a tendency of districts with high rates of theft experiencing more theft (Northern, Southern, Mission, and Central), and districts with that had lower levels of theft experiencing a smaller increase in theft. However, two districts stand out.  Richmond, a low crime districts, has doubled the number of theft reports from 2003 to 2018. And Tenderloin, the district with the highest number of thefts pr square kilometer, has had the smallest increase in theft across all districts from 2003 to 2018. 

## Geographical patterns in other types of crime
I saw that district with high levels of theft, had experienced the biggest increase in theft. Does the increased theft rate reflect a general increase in all types of crime? To answer that question, I plot the raw number of reports across all types of focus crime. I compare the number of reports in three years. 2003, the index year in the prior plot, 2013, the year where theft rates spiked across San Fransisco, and 2017 the last year of the data. 

<embed type="text/html" src="/docs/assets/Crime_district_year_interact2.html" width="1200" height="700"></embed>

The plot shows that theft is by far the most frequent crime in San Fransisco, as well as the type of crime that has had the biggest increase in the number of incident reports. 
In general, most types of focus crime have decreased. While assaults and vandalism have increased since 2003, however not as drastically as theft, all other types of focus crime have decreased. Reports of drugs and narcotics have even dropped drastically. 
While theft has increased, other types of property crime have either decreased or been stable. The number of vehicle thefts have decreased, while the number of burglaries and robberies have been stable across the years in every district.  If the increase in theft is driven by income inequality one should expect to see other types of property crime increase similarly. 




