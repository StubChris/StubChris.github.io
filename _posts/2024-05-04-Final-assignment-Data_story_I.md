---
layout: post
title:  "Getting younger and richer has increased electoral participation in Copenhagen"
date:   2024-05-04 11:57:26 +0100
categories: jekyll update
---

## The problem of low electoral participation in European elections
The next European election is close. The 9th of June 2024 Copenhageners will go to the polls to elect their representatives for the European Parliament. As election day comes closer campaigns are launched to motivate voters to cast their ballot in the election. The attempts to get voters out and vote, stem from the fact that the Danish elections for the European Parliament are known for low electoral participation. Whereas 84-87% of the Danish voters participate in national elections [(dr.dk)](https://www.dr.dk/nyheder/politik/folketingsvalg/valgdeltagelsen-var-den-laveste-i-mere-end-30-aar-der-er-grund-til), only 66% of the voters participated in the last European election in 2019. The reasons for low voter turnout are many, but researchers point toward socio-demographic factors such as income, age and education in explaining why some people decide to vote and others don’t. [(Møller 2020)](https://cvap.polsci.ku.dk/forskning/valgdeltagelse/papers_og_rapporter/valgdeltagelse_ev19.pdf).
In this article we draw on data from the Danish electoral database, to explore the patterns of electoral participation in European elections in Copenhagen. We examine how the socio-demographic development of the city is intertwined with trends in democratic participation. By uncovering the patterns, we might be able to better understand what to expect in the upcoming election in June.

## Voter turnour in Copenhagen

The electoral participation in European elections in Copenhagen have increased. From 2004 to 2019 the voter turnout has increased from 48% to 68%. The map below displays the development in voter turnout in the European elections in 2004, 2009, 2024 and 2019. For each year the turnout in the polling area of Copenhagen are displayed. Polling areas are the smallest geographical unit in an election setup, and describes the area within which all citizens has to vote at the same poll. 

<embed type="text/html" src="/docs/assets/Final/Voter_turnout_copenhagen_Eurpean_election_2004_019_timeslider.html" width="1000" height="500"></embed>

![]( /docs/assets/Final/Turnout_df19s_EP_2019_barplot.png)

In the last European election in 2019, the turnout in Copenhagen was slightly above the national level, with 68.1% of the voters casting their ballot. However, there is a huse variation in turnout between polling areas in Copenhagen. While the 77% of the voters living in Østerbro cast their ballot, only 42.6% of the voters in the outskirts of Brønshøj voted in the election. Within Copenhagen the difference between the polling area with the highest electoral participation and the polling area with the lowest electoral participation is 36 percentage points.  


When we examine voter turnout across the polling areas of the city we see, that the polling areas with the highest voter turnout are the residential areas on Østerbro close to the lakes (3. Nord, 1. Syd, 5. Øst) and the polling area on Vesterbro covering Enghave Plads. Here at least 77% of the voters cast their ballot. 
Meanwhile voters in Brønshøj (7. Nord, 7. Vest) and Bispebjerg (6. Vest) where the most reluctant in casting their vote. The areas where the least voters decided to participate are Brønshøj  and Bispebjerg . The northern part of Bispebjerg stands out with an electoral participation of 42.6%. The turnout in the northern part of Bispebjerg is 12 percentage points lower than the turnout in the neighboring area which has the second lowest turnout in Copenhagen. 



When we explore the electoral participation of Copenhageners over time, we see that some districts are falling behind. Meanwhile the electoral participation of the city has increased, the difference between the turnout at the polling areas across the city has also increased. In 2004 the difference between the polling area with the highest participation and the area with the lowest participation was 25 percentage points. In 2019 the number has increased to 36 percentage points. The average difference between the turnout in each polling area and the city level turnout also increased som 2004 to 2019. 

We plot the polling areas with the highest and lowest increases in turnout. The polling areas in the periphery of Copenhagen that had a low voter turnout in 2019 are also the polling areas that have had the smallest increase in voter turnout since 2019. Meanwhile, areas in Amager, Nordvest and Vesterbro have seen the biggest increase in turnout. 


<embed type="text/html" src="/docs/assets/Final/Voter_turnout_copenhagen_European_election_development_2004_2019_highlight_percentile.html" width="1000" height="500"></embed>


The area that has seen the largest increase in voter turnout is in Amager (2. Øst), where there the past decase has been build a lot of new private housing. Here the Voter turnout has increased by 27 percentage points. The area with the smallest increase is in Brønshøj (7. Nord), where the electoral participation was also the lowest in 2019. The district on the other hand covers a large area with public housing. In Brønshøj the voter turnout has increased with 8 percentage points from 2004 to 2019, meanwhile the turnout of the entire City had increased by 20 percentage points. 



![]( /docs/assets/Final/Most_least_turnout_increase_districts_top2.png)

## What explains differences in voter turnout across Copenhagen?
The turnout in European elections has increased in Copenhagen. However, the difference in voter turnout across the city has also increased. What explains this? To answer the question we explore the relationship between turnout and socio-demographic indicators in the election in 2019. 

The correlation plot shows that wealth indicators such as median household income and the percentage of people recieving social benefits holds the strongest explanatory power in why electoral participation is higher in some districts than others. We also see that the percentage of women living in the polling area is better at explaining the voter turnout than the crime level  of the area (measured as the number of arrests in an area). 

Lastly, age displays a curious pattern. Areas with a higher percentage of young people below 25 and areas with a high percentage of people above 70, tend to have lower turnouts. Meanwhile, areas with a larger group of voters in the age from 44 to 55 tend to have higher turnouts. 


![]( /docs/assets/Final/scatterplot_cor.png)


### Copenhagen – a city in growth (Income, social benefits and electoral particpation)

Over the past decades, Copenhagen has transformed from a poor working-class city to an expanding city with a wealthier population [(politikken)]( https://politiken.dk/debat/kroniken/art5479094/K%C3%B8benhavn-er-genrejst-ndash-men-hvad-nu) [(ritzau)]( https://via.ritzau.dk/pressemeddelelse/13670874/ti-ars-indkomstfremgang-er-mest-gaet-til-nordsjaelland-og-kobenhavn?publisherId=13560159)[(Danmarks Statistik)]( https://www.dst.dk/da/Statistik/nyheder-analyser-publ/nyt/NytHtml?cid=47272).  We see in the data, that the median household income of the Copenhageners has increased in the past 10 years. Meanwhile the percentage of the population receiving social benefits has dropped drastically. The percentage of people receiving social benefits dagpenge, sygedagpenge, kontanthjælp, folkepension, fortidspension, etc) have dropped from 36% in the 2009 election year to 21% in the 2019 election year. 

With the two stronges indicators of high electoral participation in 2019 where the percentage of people recieving social benefits and the median household income, we examine how income and social benefit reciepients have developed over the years in Copenhagen


In 2019 the richest part of the city was Østerbro (1. Syd) and Nordhavn (1. Øst).However the areas in the city that experienced the largest increase in median household income was Amager (2. Sundbyvester), Norvest(6. Bispebjerg) and Sydhavn (9. Sudhavn). Meanwhile the parts of the city that had the largest drop in recipients of social benefits, where Nordvest (6. Nord), Christianshavn (3. Syd)) and Amager (2. Sundbyvester). Sundbyvester in Amagaer has had the largest increase in median household income and at the same time the largest drop in people reciving social benefits. 

<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_2._Sundbyvester_perc_pop_social_benefits_and_turnout.html" width="800" height="300"></embed>


<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_3._Syd_perc_pop_social_benefits_and_turnout.html" width="800" height="300"></embed>

<embed type="text/html" src="/docs/assets/Final/social_benefit_difference_6._Nord_perc_pop_social_benefits_and_turnout.html" width="800" height="300"></embed>

<embed type="text/html" src="/docs/assets/Final/Vincome_difference_2._Sundbyvester_median_household_income_and_turnout.html" width="800" height="300"></embed>

<embed type="text/html" src="/docs/assets/Final/income_difference_6._Bispebjerg_median_household_income_and_turnout.html" width="800" height="300"></embed>

<embed type="text/html" src="/docs/assets/Final/income_difference_9._Sydhavn_median_household_income_and_turnout.html" width="800" height="300"></embed>


The biggest changes in income and recipients of social benefits, are happening in the parts of Copenhagen that have expanded over the years, and where the municipality of Copenhagen have invested a lot of money in renovating the city [(KK.dk)](https://www.kk.dk/sites/default/files/agenda/b61fbc4f-8f28-4908-868e-ea5d04fd9f59/daea7250-d16e-4755-84a4-62741ea9acb8-bilag-2.pdf). 

In these polling areas, the The increase in median household income and the drop in people receiving social benefits, does not reflect that more people get paid jobs instead of living on benefits, rather it suggest that the areas are drawing in people with well paid jobs, decreasing the share of the population receiving benefits.  Meanwhile we see that these areas experience some of the largest increases i voter turnout. The city expansion of Copenhagen with new construction of private housing and renawal of old parts of the city, has lifted the economic capacity of some areas, and it seems to affect the electoral participation in the area as well. 

### Do women vote more?

In the polling areas where many women live, the electoral participation in European elections tends to be higher.The areas with higer percentages of female inhabitants are assosiated with higher voter turnout. However, there has not been an increase in the female population in Copenhagen over the past decade. It is therefore not an increase in the female population that explains the overall increase in voter turnout from 2004 to 2019. 

Gender can still be part of the explanation for why voters in some districts are less prone to vote. As the data only contains aggregated information about the population in the polling areas, and not data on an individual level, we cannot test if female voters are more prone to cast their ballots in the European elections. However, we can plot the development the percentage of women in areas with the highest and biggest increases in voter turnout. 


![]( /docs/assets/Final/Most_least_turnout_increase_districts_gender.png)


We see that most areas that have had a large increase in voter turnout, have also seen a slight increase in the female population. Oppositely the areas with the smallest increase in voter turnout have seen a slight decrease in female population over the years. 

The results might indicate, that female voters are more prone to cast their ballot. This might be explained by more young women moving to the city to study than men, and therefore reflect a difference in educational level rather than a gender difference. 

### Copenhagen – a young city (Age and electoral participation)


The population in Copenhagen is not only growing, but it is also getting younger. The data shows a general increase in population, that is mostly driven by young people moving to the city. 

<embed type="text/html" src="/docs/assets/Final/plot_for_doc.html" width="1000" height="500"></embed>


The areas that have seen the biggest increase in young population are placed in Amager and Nørrebro. While a large young population is associated with lower voter turnout, the areas that have seen an increase in young people have also seen an increase in electoral participation. 

Bispebjerg, Amager and Nørrebro are also some of the areas that have seen a large increase in median household income. This is curious as young people often have low incomes as they are studying or in the beginning of their carrer. This suggest that while more young people are moving to an area, an other group of voters with higher incomes move with them to the same areas. This counters the influence that young people could have on the voter turnout. 


