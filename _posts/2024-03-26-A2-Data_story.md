---
layout: post
title:  "A2: A short data story"
date:   2024-03-26 17:14:23 +0100
categories: jekyll update
---

# Assignment 2

**Description of the data**
The Government of San Fransisco publish a variaty of government datasets including a historical dataset on repports of crime incedents in San Fransisco. The dataset describes every repport of a crime in San Fransisco during the years 2003-2018. The incident repportes contain geographical information as well as details about the type and time of the crime. The dataset can be found [here](https://data.sfgov.org/browse?category=Public+Safety)

### Increases in property crime in San Fransisco
Examening the crime data, we see that San Fransisco has experienced a huge increase in theft and larceny sinze 2012. From 2003 to 2012 the number of thefts repported across San Fransisco is quite stable with an average number of thefts in 6 months of apporx. 2100 repports. However in 2012 there is a sudden spike in thefts, that continues over the years. Following the next 6 years, the number of reported thefts and larceny doubled. 

![]( /docs/assets/Larceny_Theft_SF_2003_2017.png)

The spike in property crime has been noticed by legislators and media in San Fransisco. In 2014 the [San Fransisco Cronichle](https://www.latimes.com/local/crime/la-me-aa2-snapshot-sf-crime-20141120-story.html) reported the massive spikes in property crime, arguing that the increases in income inequality in the city was to blame. Property crime is considered a poverty crime, and while San Fransisco has benefited economically from the tech industry, the wealth has been unequally distributed across the population. The increased inequality in income became a subject of [academic research](https://siliconvalleyindicators.org/pdf/income-inequality-2015-06.pdf) in the following years. 

However when examining trends in unemployment and median household income from 2012 to 2018, the unemplyoment rate seems to be going [down](https://fred.stlouisfed.org/series/CASANF0URN), while the median household income is [going up](https://fred.stlouisfed.org/series/MHICA06075A052NCEN). Further, the estimated number of people in San Fransisco living in poverty has been [descresing](https://fred.stlouisfed.org/series/PEAACA06075A647NCEN) decreasing since 2012. 

As the aggragated statistics indicate that the city overall is getting wealthier, the question remains if the spike in property crime is caused by poor districts getting poorer and driving up the crime. In the following plot i explore the geophaphical patterns of thelft and larceny

## Geographical patterns in theft

We examine the geographical pattern in the increase of theft in San Fransisco from 2012 to 2017. We plot the number of repports of theft in each district in each year. We see that the increase in thefts is happening in the districts Southern, Central, Northern and Mission. 
The district Tenderloin is surrounded by districts where crime increases, but sees almost no increase in thefts over time. That is extremely weird? is it because there is no crime or is it because the police is somewhere else/or the people are underrapportering the crime. According to wikipedia tenderloin is a district with a high amount of violent crime. It is partielly because the plot shows the raw counts of crime, and tenderloin is smaller than all the other districts and the comparison of raw counts of crime between tenderloin and the other districts is not meaningfull.Ideally the crime would be normalized against something the number of inhabitants. 

Tenderloin has a lot of crime pr square kilometer, that is a lot of crime for its size. There is however not any noteworthy increases in crime in the district across the years

The surrounding districts also experience increases in theft but the magnitude is smaller. 

Is the pattern similar for other types of crime?



<embed type="text/html" src="/docs/assets/Heatmap_drugs.html" width="600" height="400"></embed>


<embed type="text/html" src="/docs/assets/Thefts_sanfransisco_map_raw_count.html" width="600" height="400"></embed>

## Geographical patterns in focus crime


<embed type="text/html" src="/docs/assets/Crime_district_year_interact.html" width="600" height="400"></embed>
