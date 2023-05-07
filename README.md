# project_1
Project 1 Analysis 

PROJECT TITLE

Impact of COVID on Overseas Migration to Australia 

TEAM MEMBERS

Bec, Anuja & Luz 

RESEARCH QUESTION

How has COVID affected migration arrivals to Australia overall pre and post 2020, and specifically for the following factors:
1.	State / Location;
2.	Gender;
3.	Age; 
4.	Purpose (visa status); and 
5.	Work Hours. 


ANALYSIS SUMMARY

Data Analysis - Bec Project1

The graph below shows the total migration arrivals to Australia on a financial year basis.  
The COVID pandemic had a significant impact on travel and migration to Australia. In response to the pandemic the Australian government imposed travel restrictions in approximately late March 2020, which were gradually eased until no restrictions were in place by March 2023. 
The graph below shows the total number of migrant arrivals in Australia was the lowest in FY2021 since FY2005. This was the year with the most severe travel restrictions, totalling a -71.2% decrease in total migrant arrivals from the previous year. 
With travel restrictions easing from FY2021 onwards total arrivals increased by 170.4% in FY2022 compared to the previous year. Despite the increase the total number of migrant arrivals was still lower than in FY2020 being the year prior to the COVID pandemic. 

![image](https://user-images.githubusercontent.com/126390405/236679387-0243d42a-e47d-4383-9e6a-a7494d923bc8.png)


Data_Analysis -Anuja

Statistical Analysis:
We performed independent Ttest to confirm the number of arrivals has been affected by covid.
Null hypothesis: Covid has had no impact on the number of arrivals
Alternate hypothesis: covid has impacted on the number of arrivals i.e. reduced the number of people entering the country
Test Result: 
Ttest_indResult(statistic=6.889103112023368, 
pvalue=1.0747455813994277e-11)
Based on the P value we can conclude that our alternate hypothesis is correct i.e. covid has impacted on the number of arrivals i.e. reduced the number of people entering the country

Number of arrivals by gender between 2005 and 2022
![image](https://user-images.githubusercontent.com/126873540/236676421-ea60f2e3-c035-4c6b-9c68-c40fa6cb6b30.png)

Prior to COVID number of Male arrivals were higher than number of Female arrivals leading up to 2014. Years 2015, 2016 the gap was almost non-existent, 2017 and 2018 it increased again making number of Male arrivals higher than Females. In 2020, number of Male arrivals dropped and number of Female arrivals increased for the first time since 2005 only for a small period and is now again going back to the original state.
 
Number of people arrived based on different age brackets between 2005-2022
![image](https://user-images.githubusercontent.com/126873540/236676457-4816b49c-c39d-470a-945f-9a7d051e2ac2.png)

Overall 'A20: 20-24' is the most popular category followed by 'A25: 25-29', 'A30: 30-34' and 'A15: 15-19'
During years 2016 - 2019 we had the maximum number of arrivals
It appears that covid has made no impact on the popular age bracket categories and the same trend continues after covid.

 
Popular states per gender:
Males	
![image](https://user-images.githubusercontent.com/126873540/236676483-79aac97a-9cba-43ef-82bf-fa99d66e79c6.png)

Females
![image](https://user-images.githubusercontent.com/126873540/236676499-b8a8a4d9-bd48-4db5-83c2-f4f812e8c588.png)

There appear to be no difference and the same trend continues after covid

Number of people entering each state per age bracket before and after covid
Before covid
![image](https://user-images.githubusercontent.com/126873540/236676518-2f7f5656-ac67-4c2e-9f88-daa0c664f049.png)

After covid
![image](https://user-images.githubusercontent.com/126873540/236676528-8670486d-33ad-4d00-a72f-60727ee955ac.png)

Correlation matrix to show changes between different age brackets before and after covid
Combined Matrix:
![image](https://user-images.githubusercontent.com/126873540/236676562-67c4e2ae-d379-403a-ba97-731467d1ec3b.png)
 
Before Covid correlation matrix between different age brackets
![image](https://user-images.githubusercontent.com/126873540/236676587-6bd0766b-5c52-4777-adeb-260eb5f33ab3.png)

After Covid correlation matrix between different age brackets
![image](https://user-images.githubusercontent.com/126873540/236676602-7a72d098-ad7b-4b12-83b2-892827176675.png)

Change in ‘Male-Female Ratio’ entering each state per age category
![image](https://user-images.githubusercontent.com/126873540/236676637-168cdce9-9fab-4a8b-ad9c-590aaecc211d.png)

Here positive change indicates ‘Number of Male arrivals’ has increased for the specific category while the negative change indicates ‘Number of Female arrivals’ has increased for the specific category.






DATA SOURCE

The data has been sourced from the Australia Bureau of Statistics (ABS) using the link: https://www.abs.gov.au/statistics/people/population/overseas-migration/2021-22-financial-year#key-statistics 
The data has been collected based on a financial year. 

Information on COVID travel restrictions were sourced using these links: https://www.aph.gov.au/About_Parliament/Parliamentary_departments/Parliamentary_Library/pubs/rp/rp2021/Chronologies/COVID-19StateTerritoryGovernmentAnnouncements. [Table 3: initial border restriction announcement by state and territory governments]. 

https://www.health.gov.au/health-alerts/covid-19/international-travel 

ABC news article on migration: https://www.abc.net.au/news/2023-04-29/australian-migrant-population-growth-hits-all-time-record-high/102281798 

