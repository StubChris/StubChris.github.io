---
layout: post
title:  "Copenhagen has gotten richer and it has increased electoral participation in European elections"
date:   2024-05-04 11:57:26 +0100
categories: jekyll update
---

## The problem of low electoral participation in European elections
The next European election is close. The 9th of June 2024 Copenhageners will go to the polls to elect their representatives for the European Parliament. As election day comes closer campaigns are launched to motivate voters to cast their ballot in the election. The attempts to get voters out and vote, stem from the fact that the Danish elections for the European Parliament are known for low electoral participation. Whereas 84-87% of the Danish voters participate in national elections [(dr.dk)](https://www.dr.dk/nyheder/politik/folketingsvalg/valgdeltagelsen-var-den-laveste-i-mere-end-30-aar-der-er-grund-til), only 66% of the voters participated in the last European election in 2019. The reasons for low voter turnout are many, but researchers point toward socio-demographic factors such as income, age and education in explaining why some people decide to vote and others don’t. [(Møller 2020)](https://cvap.polsci.ku.dk/forskning/valgdeltagelse/papers_og_rapporter/valgdeltagelse_ev19.pdf).
In this article we draw on data from the Danish electoral database, to explore the patterns of electoral participation in European elections in Copenhagen. We examine how the socio-demographic development of the city is intertwined with trends in democratic participation. By uncovering the patterns, we might be able to better understand what to expect in the upcoming election in June.

## Voter turnout in Copenhagen

The electoral participation in European elections in Copenhagen have increased. From 2004 to 2019 the voter turnout has increased from 48% to 68%. The map below displays the development in voter turnout in the European elections in 2004, 2009, 2024 and 2019. For each year the turnout in the polling area of Copenhagen are displayed. Polling areas are the smallest geographical unit in an election setup, and describes the area within which all citizens has to vote at the same poll. 

<embed type="text/html" src="/docs/assets/Final/Voter_turnout_2004_019_timeslider.html" width="1200" height="700">


![]( /docs/assets/Final/Turnout_df19s_EP_2019_barplot.png)

In the last European election in 2019, the turnout in Copenhagen was slightly above the national level, with 68.1% of the voters casting their ballot. However, there is a huse variation in turnout between polling areas in Copenhagen. While the 77% of the voters living in Østerbro cast their ballot, only 42.6% of the voters in the outskirts of Brønshøj voted in the election. Within Copenhagen the difference between the polling area with the highest electoral participation and the polling area with the lowest electoral participation is 36 percentage points.  


When we examine voter turnout across the polling areas of the city we see, that the polling areas with the highest voter turnout are the residential areas on Østerbro close to the lakes (3. Nord, 1. Syd, 5. Øst) and the polling area on Vesterbro covering Enghave Plads. Here at least 77% of the voters cast their ballot. 
Meanwhile voters in Brønshøj (7. Nord, 7. Vest) and Bispebjerg (6. Vest) where the most reluctant in casting their vote. The areas where the least voters decided to participate are Brønshøj  and Bispebjerg . The northern part of Bispebjerg stands out with an electoral participation of 42.6%. The turnout in the northern part of Bispebjerg is 12 percentage points lower than the turnout in the neighboring area which has the second lowest turnout in Copenhagen. 


**When we explore the electoral participation of Copenhageners over time, we see that some districts are falling behind**. Meanwhile the electoral participation of the city has increased, the difference between the turnout at the polling areas across the city has also increased. In 2004 the difference between the polling area with the highest participation and the area with the lowest participation was 25 percentage points. In 2019 the number has increased to 36 percentage points. The average difference between the turnout in each polling area and the city level turnout also increased som 2004 to 2019. 

### **We plot the polling areas with the highest and lowest increases in turnout.** 
The polling areas in the periphery of Copenhagen that had a low voter turnout in 2019 are also the polling areas that have had the smallest increase in voter turnout since 2019. Meanwhile, areas in Amager, Nordvest and Vesterbro have seen the biggest increase in turnout. 


<embed type="text/html" src="/docs/assets/Final/Voter_turnout_development_2004_2019_highlight.html" width="1200" height="700">


The area that has seen the largest increase in voter turnout is in Amager (2. Øst), where there the past decase has been build a lot of new private housing. Here the Voter turnout has increased by 27 percentage points. The area with the smallest increase is in Brønshøj (7. Nord), where the electoral participation was also the lowest in 2019. The district on the other hand covers a large area with public housing. In Brønshøj the voter turnout has increased with 8 percentage points from 2004 to 2019, meanwhile the turnout of the entire City had increased by 20 percentage points. 


![]( /docs/assets/Final/Most_least_turnout_increase_districts_top2.png)

## What explains differences in voter turnout across Copenhagen?
The turnout in European elections has increased in Copenhagen. However, the difference in voter turnout across the city has also increased. What explains this? **To answer the question we explore the relationship between turnout and socio-demographic indicators in the election in 2019**. 

The correlation plot shows that wealth indicators such as **median household income** and the **percentage of people recieving social benefits** holds the strongest explanatory power in why electoral participation is higher in some districts than others. We also see that the percentage of women living in the polling area is better at explaining the voter turnout than the crime level of the area (measured as the number of arrests in an area). 

Lastly, age displays a curious pattern. Areas with a higher percentage of young people below 25 and areas with a high percentage of people above 70, tend to have lower turnouts. Meanwhile, areas with a larger group of voters in the age from 44 to 55 tend to have higher turnouts. 


![]( /docs/assets/Final/scatterplot_cor.png)


### The population is getting richer

Over the past decades, Copenhagen has transformed from a poor working-class city to an expanding city with a wealthier population [(politikken)]( https://politiken.dk/debat/kroniken/art5479094/K%C3%B8benhavn-er-genrejst-ndash-men-hvad-nu) [(ritzau)]( https://via.ritzau.dk/pressemeddelelse/13670874/ti-ars-indkomstfremgang-er-mest-gaet-til-nordsjaelland-og-kobenhavn?publisherId=13560159)[(Danmarks Statistik)]( https://www.dst.dk/da/Statistik/nyheder-analyser-publ/nyt/NytHtml?cid=47272).  **We see in the data, that the median household income of the Copenhageners has increased in the past 10 years. Meanwhile the percentage of the population receiving social benefits has dropped drastically**. The percentage of people receiving social benefits dagpenge, sygedagpenge, kontanthjælp, folkepension, fortidspension, etc) have dropped from 36% in the 2009 election year to 21% in the 2019 election year. 


<embed type="text/html" src="/docs/assets/Final/sorted_social_benefits_data.html" width="900" height="400">

<embed type="text/html" src="/docs/assets/Final/sorted_income_data.html" width="900" height="400">

- **With the two stronges indicators of high electoral participation in 2019 where the percentage of people recieving social benefits and the median household income, we examine how income and social benefit reciepients have developed over the years in Copenhagen**


In 2019 the richest part of the city was Østerbro (1. Syd) and Nordhavn (1. Øst).However the areas in the city that experienced the largest increase in median household income was Amager (2. Sundbyvester), Norvest(6. Bispebjerg) and Sydhavn (9. Sudhavn). Meanwhile the parts of the city that had the largest drop in recipients of social benefits, where Nordvest (6. Nord), Christianshavn (3. Syd)) and Amager (2. Sundbyvester). Sundbyvester in Amagaer has had the largest increase in median household income and at the same time the largest drop in people reciving social benefits.

Bellow the biggest changes in median income and social benefits over the years.

##### Social Benefits Percentage changes

<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_2._Sundbyvester.html" width="900" height="400">


<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_3._Syd.html" width="900" height="400">

<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_6._Nord.html" width="900" height="400">


##### Median Income changes

<embed type="text/html" src="/docs/assets/Final/income_difference_2._Sundbyvester.html" width="900" height="400">

<embed type="text/html" src="/docs/assets/Final/income_difference_6._Bispebjerg.html" width="900" height="400">

<embed type="text/html" src="/docs/assets/Final/income_difference_9._Sydhavn.html" width="900" height="400">


The biggest changes in income and recipients of social benefits, are happening in the parts of Copenhagen that have expanded over the years, and where the municipality of Copenhagen have invested a lot of money in renovating the city [(KK.dk)](https://www.kk.dk/sites/default/files/agenda/b61fbc4f-8f28-4908-868e-ea5d04fd9f59/daea7250-d16e-4755-84a4-62741ea9acb8-bilag-2.pdf). 

On one hand one could think, that the increase in income is due to people on benefits getting jobs. However , while this might explain part of the increase, the majority of recipients of social benefits tend to be far from the labour market somewhat marginalized and less likely to get high paid jobs when they enter the labour market. The increase in median income is to big to be eplained by the social benefits reciepints getting jobs,  rather it suggest that the areas are drawing in people with well paid jobs, decreasing the share of the population receiving benefits. Meanwhile we see that these areas experience some of the largest increases in voter turnout. The city expansion of Copenhagen with new construction of private housing and renawal of old parts of the city, has lifted the economic capacity of some areas, and it seems to affect the electoral participation in the area as well. 


#### Concluding
What is highlighted in the graphs so far, if there is a positive change in median income then the turnout gets affected and increases. So they are in a way positively correlated.

As for the social benefits, it seems that it negatively impacts the turnot percentage of the area. As shown above, the bigger the social benefits of population decreases, the bigger the turnout of votes.

And because in population, the median income and the social benefits are the opposite sides of the coin, that is why they are both similar in explaining the data and correlation metrics in the end of the day.

### Do women vote more?

In the polling areas where many women live, the electoral participation in European elections tends to be higher.The areas with higer percentages of female inhabitants are assosiated with higher voter turnout. However, there has not been an increase in the female population in Copenhagen over the past decade. It is therefore not an increase in the female population that explains the overall increase in voter turnout from 2004 to 2019. 

Gender can still be part of the explanation for why voters in some districts are less prone to vote. As the data only contains aggregated information about the population in the polling areas, and not data on an individual level, we cannot test if female voters are more prone to cast their ballots in the European elections. However, we can plot the development the percentage of women in areas with the highest and biggest increases in voter turnout. 


![]( /docs/assets/Final/Most_least_turnout_increase_districts_gender.png)


We see that most areas that have had a large increase in voter turnout, have also seen a slight increase in the female population. Oppositely the areas with the smallest increase in voter turnout have seen a slight decrease in female population over the years. 

**The results might indicate, that female voters are more prone to cast their ballot. This might be explained by more young women moving to the city to study than men, and therefore could reflect a difference in educational level rather than a gender difference.**

### More young people, higher turnout?   

The population in Copenhagen is not only growing, but it is also getting younger. The data shows a general increase in population, that is mostly driven by young people moving to the city. The visualisation below, explores the development across different age groups from 2004 to 2019.

<embed type="text/html" src="/docs/assets/Final/plot_for_doc.html" width="1000" height="500">


Our analysis also shows that the areas that have seen the biggest increase in the young population are Amager (2. Syd, 2. Sundbyvester), Nørrebro (5. Nord, 5. Nørrebro) and Nordvest (6.Bispebjerg). While a large young population is associated with lower voter turnout, the areas that have seen an increase in young people have also seen an increase in electoral participation. 

**Bispebjerg, Amager and Nørrebro are also some of the areas that have seen a large increase in median household income.** This is curious as young people often have low incomes as they are studying or in the beginning of their carrer. This suggest that while more young people are moving to an area, an other group of voters with higher incomes move with them to the same areas. This counters the influence that young people could have on the voter turnout. 


#### How can we group the districts? Clustering as an interpretation of insights

We know that age, gender, social benefits recipients and income influence turnout. We want to group the polling areas of Copenhagen into groups of areas with similar charatcaristics and turnout. To do that we used a Gaussian Miture Model, which is unsupervised machine learning model. We find that the polling areas can be divided into 3 groups. The clustering model shows, that gender plays no role in dividing the areas into groups that are the most similar to each other. 


![](/docs/assets/Final/clusters.png)

**Cluster 1 : Low income areas with low voter turnout more people on benefits, and a younger population**  
Characterized by a low turnout, a high percentage of people on benefits and low level of income. However the cluster also has a larger percentage of young people. This charactarizes areas in the perephery of Copenhagen as in Brønshøj and outskirts of Nordvest. 

**Cluster 2: High voter turnout, but middle income and a large share of people in on social benefits**   
The areas in this cluster have a high voter turnout but only has a middle income, no particular difference in gender og the percentage of youn people living there. There is a large share of people recieving social benefits. This group, shows that income, social benefits and age are not sufficient in understanding why some polling areas vote less. 

**Cluster 3: Rich areas with high voter turnout**
In this group of clusters, we find voting areas in Østerbro, Amager, Sydhavn, Vesterbro, and Nordhavn. 
 

**These results could indicate that the median income and social benefits over the years, affect turnout rate by a great impact and can be an identifier for the turnout of different areas. That means that if voter turnout should be increased, campaigns should target areas with many social benefit recipients and low income**


### What to expect in the upcomming election?

The data shows that the population living in areas that used to be the outskirts of Copenhagen, such ad Nordvest, Sydhavn, Amager and Nørrebro, have changed. 

These areas have seen a drop in social benefits recipients, and an increase in inhabitants with high incomes. Meanwhile young people are moving to these areas. This is likely caused by the extensive city renewval plans, as well as increasing construction of private housing. 

As a side effect, the electoral participation in these areas have increased. While large parts of the city have experienced increases in income and a younger population, the Northern part of Brønshøj and Vanløse, have not seen the same changes in population, and the voter turnout in these areas have changes only little in comparison to the rest of the city. 


**Contribution**

- Sofie : preprocessing, geographical plotting, gender analysis part, voter turnout, project report, merging
- Ilias : correlations, median income analysis part , social benefits analysis part, clustering, project report, merging
- Dimitris : basic stats and analysis, age analysis and plots, merging, project report, insights
