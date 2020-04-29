---
title: >-
  Life Expectancy, Trump, and the Future of Rural America
author: Basil Team
date: 2020-04-27 00:00:00
image: /img/posts/walking.png
layout: post_covid
---

<style type="text/css">
	  li{
    &:before{
      content: "-";
      text-indent: -2em;
      display: inline-block;
    }
</style>

<h2 class="head" style="text-align: center;max-width: 700px;margin: auto;">
Who is at Most Risk?
<br>
COVID-19 Community Risk Factors & the Politicization of the Virus</h2>


<img src="/../img/posts/walking.png" style="width:30%;max-width:800px;min-width:300px;  display: block;margin-left: auto;margin-right: auto;padding:15px;" />

<p style="color:#777777;text-align: center;">
Theo Goetemann, Linbo Ruan, Kyle Costello, Nikita Jakkam
<br>
Who is at Most Risk: Population Factors — Kyle Costello
<br>
Who is at Most Risk: Transportation — Nikita Jakkam
<br>
The Political Nature of the Virus — Linbo Ruan

</p>
<br>



## **Context**  
<br>
America is going to have to make some very tough decisions in the coming months — as individuals, as groups, neighborhoods, and communities, as companies, nonprofits, and educational institutions, and as city, state and federal decision makers.  

Embedded at the heart of our research at Basil Labs are two fundamental questions:  
<p style="color:blue;padding-left: 10px;">
Who is at most risk?
<br>
How do we go forward responsibly?
</p>

Our analyses focused on possible contributing factors to higher numbers of Coronavirus cases as well as the increasingly political path the virus has taken in America and the potential repercussions from this path.  

These analyses are meant to evaluate normative beliefs about the spread of the virus and begin conversations on how to approach the crisis at hand as well as going forward in coming years. 
<br>
<br>
## **Data Sources & Methodology**
<br>
Data was obtained from the ACS via [data.census.gov](https://data.census.gov/), the [Community Mobility Reports](https://www.google.com/covid19/mobility/) from Google, the New York Times [COVID-19 Github repository](https://github.com/nytimes/covid-19-data), Johns Hopkins' [Coronavirus Resource Center](https://coronavirus.jhu.edu/), [Gallup](https://news.gallup.com/poll/125066/state-states.aspx), and Basil Labs' own [testing center locator platform](http://covid19testing.today/).  

**Census:**  Population, transportation, and insurance data (2017)  
**Google:**  Mobility and social distancing data (as of April 2020)  
**NYTimes:**  COVID-19 number of cases and deaths (as of April 19, 2020)  
**Gallup:** Trump approval % (2017)  
**Basil Labs:**  Coronavirus testing center locations (as of April 2020)  

The following analyses employ linear regressions where the independent variable for all tests are the number of cases, growth rate of COVID-19, and number of deaths by US county. Given the different years at which the data was collected as well as the real-time nature of the number of cases and deaths of COVID-19, all findings must be taken with a grain of salt.  

Nevertheless, while formal, in-depth analyses with the proper rigor will eventually be conducted in the future after this crisis has subsided, the purpose of these analyses now is to present preliminary findings which in turn can help craft responsible policies at the local and national levels to help mitigate this crisis, and all variances in the years of data collection are a reality of the current conditions and data availability during which this study was developed.
<br>
<br>
## **Part 1: Who is at the Most Risk?**
<br>
Our team sought to better understand these risk factors and examined a number of potential variables influencing the spread of COVID-19. While we found that some variables — such as the percentage of individuals within a county with health insurance or the average household income by county were poor predictors of the number of cases or COVID-19 related deaths, two narratives became clear through our analysis.  

<p style="color:blue;padding-left: 10px;">
There are more deaths when the virus isn't caught early in a community;
<br>
Common modes of transportation must be taken into account when shaping policies to mitigate the spread of COVID-19.
</p>

**i) Population Density**  
There is a strong, positive and linear correlation between population density in people per square mile and the percent of patients in a state who tested positive for COVID-19 (p<0.001, r²=0.78).

**ii) % Positive Tests**  
There is a moderately strong, positive and linear correlation between the percent of patients who tested positive for COVID-19 and the number of COVID-19 deaths in a state (p<0.001, r²=0.63).

**iii) Public Transportation**  
There is a strong, linear and positive correlation between public transportation usage and the number of positive COVID-19 cases per county in the United States (p<0.001, r²=0.82). Public transportation usage is calculated using the percent of the population commuting to work via public transportation by county.

**iv) Commuting**  
There is a moderate, linear and negative correlation between the percent of the population who has a 30-90 minute commute alone via personal vehicle and the number of positive COVID-19 cases per county. 
<br>
<br>
# **What Does This Mean?**
<br>
<img src="/../img/posts/drive_thru.jpg" style="width:30%;max-width:800px;min-width:300px; float:left;padding:15px;" />
As states who were hit hard first by the virus reach their COVID-19 "peak," legislators and other decision makers are caught between a rock and a hard place: economic vitalization and the potential of a second wave of cases and deaths.  

While there are a number of factors that may influence the number of cases in counties, the correlation between population density and the number of COVID-19 cases, when put in context of the slow rollout of testing availability in the United States, suggests that high density areas have quicker COVID-19 spread — thus when tests are actually made available to these communities, the % of total individuals who test positive are higher than other areas.  

Sadly, areas that have a higher % of total individuals who test positive also have higher death rates. While this finding may seem unsurprising at first glance, when the amount of time America took to deploy testing across the country, this statistic similarly suggests that areas that had the Coronavirus circulating throughout their communities for longer - thus the higher % of positive tests - are areas where the death rate will be higher.  

In other words, if the virus entered and circulated around a community earlier than other parts of America before mass testing was deployed in America, there will be a higher percentage of individuals who test positive when the tests become available. Population density factors into the spread of the virus and these communities will also be the ones to lose more lives.  

**Tl;dr To reduce deaths, we need to catch the virus early on in communities.**
<br>
<br>
## **Part 2: The Political Nature of the Virus in America**
<br>
As we learn more about the virus and factors that influence its spread, states are planning phased reopenings of businesses and COVID-19 protests have swept the news. Georgia's Governor Brian Kemp has (in)famously already allowed restaurants to resume dine-in service and certain other businesses  like hair salons, gyms and tattoo parlors to reopen under specific conditions to minimize the virus’ spread. His decision and President Trump's rebuke, alongside the anti-lockdown protests in a number of states illustrate the ever-increasing political nature that the virus has taken in America. 

The second component of our analysis focused on this political aspect and we sought to better understand:
<p style="color:blue;padding-left: 10px;">
The relationship between Trump support and social distancing;
<br>
The relationship between social distancing and the COVID-19 growth rate.
</p>

<img src="/../img/posts/residential.png" style="width:70%;max-width:700px;min-width:300px;" />
<br>
<br>
**i) Residential Mobility**
There is a strong, negative linear relationship between residential mobility and Trump support by state (p<0.001, r=-0.80).  

Residential mobility data was obtained from the COVID-19 Community Mobility Reports from Google. The reports break each state down by county and highlight the percent change in visits to places like grocery stores, parks, transit stations, retail & recreation areas, residential and workplaces. The baseline for these data is the median value of the corresponding day of the week from January 3 to February 6, 2020.  

<img src="/../img/posts/support.png" style="width:70%;max-width:700px;min-width:300px;" />
<br>
<br>
**ii) Retail Mobility**
There is a strong, positive linear relationship between retail and recreation areas and Trump support by state (p<0.001, r=0.71).  

<img src="/../img/posts/retail.png" style="width:70%;max-width:900px;min-width:300px;" />
<br>
<br>
**iii) Retail Mobility & COVID-19 Growth Rate**
When examining the growth rate of COVID-19, we found that retail mobility has a higher propensity than any other form of mobility to contribute to the growth rate of COVID-19. In the figure above, the p-value of retail mobility for each state is visualized with a red dotted line to indicate 0.05 and a blue dotted line to indicate a 0.1 p-value.  

24 out of the 50 states included in our analysis exhibited p-values below 0.1. Comparatively, workplace mobility had 8/50 states, grocery stores had 9/50 states, transit stations mobility had 10/50 states, and parks had 15/50 states. Retail mobility alone had 15 states which fit under p-values of 0.05.  

It is important to note that there can be other factors that affect growth rate — this model only considers retail mobility's effect on the growth rate of COVID-19.  
<br>
<br>
## **What Does This Mean?**
<br>
<img src="/../img/posts/reopen.jpg" style="width:30%;max-width:800px;min-width:300px; float:left;padding:15px;" />
If social distancing were practiced correctly, we would expect the mobility rate of residential areas to increase. However, the relationship between Trump support and residential mobility indicates that states with higher Trump support are not practicing social distancing at rates similar to states with less Trump support.  

Similarly, our findings suggest that states with higher Trump support also have higher rates of retail and recreation mobility. In fact, Trump support correlates to higher rates of grocery and pharmacy mobility (p<0.001, r=0.67), transit station mobility (p<0.001, r=.80), and workplace mobility (p<0.001, r=0.79). The only type of mobility in which Trump support does not reflect a similar relationship is mobility at parks (p<0.07, r=0.27).  

Troublingly, out of all forms of mobility, retail mobility exhibited the more prevalent relationship to the growth rate of COVID-19. Out of the 15 states which showed the highest significance of this relationship, 12 were states where Trump won in 2016.  

As the pressure on politicians increases to end the lockdowns, some of the first states to do so will be states with Republican leadership, states which may follow the pattern of COVID-19 growth in relation to retail mobility.  
<br>
<br>
## **Part 3: Where Do We Go From Here? What Do Responsible, Data-Driven Policies Look Like?**
<br>
There are a myriad of considerations to take in when considering to reopen a state or city — however, two particularly influential variables to consider are:
<p style="color:blue;padding-left: 10px;">
The growth rate of COVID-19
<br>
The impact on businesses, employment, and the economy
</p>

<img src="/../img/posts/railways.jpg" style="width:30%;max-width:800px;min-width:300px; float:left;padding:15px;" />

Our findings suggest caution in reopening retail, and the recent initiatives from Governors on opening state park land before confined, indoor spaces like workplaces or retail may ease the public while maintaining proper precautionary measures.  

Furthermore, findings from this study suggest that immediate detection of the virus in a community is necessary to prevent deaths. Again, while this may seem like an unsurprising analysis, given the availability of testing across the United States and the numerous barriers to testing, from provider network requirements to pre-screenings to actual transportation to the nearest testing facility, the reality in America is that immediate detection most likely will not come to pass — this costs lives.  

This study is not meant to be rigid nor static in nature — as the crisis continues to evolve and spread to areas that have not been impacted greatly yet, we must continue to research and develop responsible, data-driven policies to limit the growth and mitigate the loss of life. There is the potential for a second wave in already-hit areas as well as a potential hit on rural areas of America this summer and fall. If there is one conclusion to take away from this study, it is that **this crisis cannot be treated as a short-term event — it is ongoing and there is no one silver bullet. Different areas show different propensities to increase the spread of the virus and our policies and public engagement must reflect this reality.**










