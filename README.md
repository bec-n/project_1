# project_1
 

**PROJECT TITLE**

Impact of COVID on Overseas Migration to Australia 

**TEAM MEMBERS**

Bec, Anuja & Luz 

**RESEARCH QUESTION**

How has COVID affected migration arrivals to Australia overall pre and post 2020, and specifically for the following factors:
1.	State / Location;
2.	Gender;
3.	Age; 
4.	Purpose (visa status); and 
5.	Work Hours. 


**ANALYSIS SUMMARY**

**Data Analysis - Code: Project1.ipynb**

The graph below shows the total migration arrivals to Australia on a financial year basis.  
The COVID pandemic had a significant impact on travel and migration to Australia. In response to the pandemic the Australian government imposed travel restrictions in approximately late March 2020, which were gradually eased until no restrictions were in place by March 2023. 
The graph below shows the total number of migrant arrivals in Australia was the lowest in FY2021 since FY2005. This was the year with the most severe travel restrictions, totalling a -71.2% decrease in total migrant arrivals from the previous year. 
With travel restrictions easing from FY2021 onwards total arrivals increased by 170.4% in FY2022 compared to the previous year. Despite the increase the total number of migrant arrivals was still lower than in FY2020 being the year prior to the COVID pandemic. 

![image](https://user-images.githubusercontent.com/126390405/236679387-0243d42a-e47d-4383-9e6a-a7494d923bc8.png)

The line graph below shows the total migration arrivals by state and year. In summary the state / location arrivals are most commonly moving to in Australia appear to be consistent throughout the years, with New South Wales, Victoria and Queensland being the top 3 states for migrant arrivals from 2005 until 2022. 
Similar to the ‘Total Arrivals to Australia’ graph, there was a significant decrease of arrivals to all states in FY2021 due to the travel restrictions imposed during COVID. 

![image](https://user-images.githubusercontent.com/126390405/236680268-86a694f9-4edc-4d6b-9b9a-c2fe31c93a9f.png)

The heat map below shows a different visualisation of the total migrant arrivals per year, which are consistent with the graph above. 

![image](https://user-images.githubusercontent.com/126390405/236680286-64341c10-78ea-4805-87bf-2d698b552172.png)

Next, the pie charts below show if there has been any variation on the percentage of arrivals by location pre (FY2020), during (FY2021) and post (FY2022) COVID per state.  

![image](https://user-images.githubusercontent.com/126390405/236680605-6e31af47-815e-4cc6-ae43-efcf24e7c060.png)

![image](https://user-images.githubusercontent.com/126390405/236680545-28d1ce07-2e94-4e90-b782-49cf07b91e86.png)

While there are minor variations between the migration arrivals by state, overall there does not appear to be any change pre and post COVID for the location most migrants are moving to. 
On the other hand during the COVID year FY2021 there was a significant increase in the percentage of migrants moving to NSW with a corresponding decrease to migrants moving to VIC. This appears to be mainly made up of Australian citizens returning to Australia per the ‘Visa by Region (After COVID’ graph below. All other states appear to be consistent with the pie charts above. 

![image](https://user-images.githubusercontent.com/126390405/236680552-9eecd626-5284-4a23-a3f6-05b9fa4e8f76.png)

![image](https://user-images.githubusercontent.com/126390405/236778811-dd4e7d1b-5fcb-441a-85f8-6bb4247bc588.png)

As the pie charts above pre and post COVID don’t show a significant variation in location, a map visualisation has been completed below showing the migrant arrivals in FY2022. 

![bokeh_plot](https://user-images.githubusercontent.com/126390405/236680614-9f730968-6c1a-43a8-b7f9-b783effea4f1.png)


**Data_Analysis - Code: project1 - Submission.ipynb**

**Statistical Analysis:**

We performed independent Ttest to confirm the number of arrivals has been affected by covid.
Null hypothesis: Covid has had no impact on the number of arrivals
Alternate hypothesis: covid has impacted on the number of arrivals i.e. reduced the number of people entering the country
Test Result: 
Ttest_indResult(statistic=6.889103112023368, 
pvalue=1.0747455813994277e-11)
Based on the P value we can conclude that our alternate hypothesis is correct i.e. covid has impacted on the number of arrivals i.e. reduced the number of people entering the country

**Number of arrivals by gender between 2005 and 2022**

![image](https://user-images.githubusercontent.com/126873540/236676421-ea60f2e3-c035-4c6b-9c68-c40fa6cb6b30.png)

Prior to COVID number of Male arrivals were higher than number of Female arrivals leading up to 2014. Years 2015, 2016 the gap was almost non-existent, 2017 and 2018 it increased again making number of Male arrivals higher than Females. In 2020, number of Male arrivals dropped and number of Female arrivals increased for the first time since 2005 only for a small period and is now again going back to the original state.


**Number of people arrived based on different age brackets between 2005-2022**

![image](https://user-images.githubusercontent.com/126873540/236676457-4816b49c-c39d-470a-945f-9a7d051e2ac2.png)

Overall 'A20: 20-24' is the most popular category followed by 'A25: 25-29', 'A30: 30-34' and 'A15: 15-19'
During years 2016 - 2019 we had the maximum number of arrivals
It appears that covid has made no impact on the popular age bracket categories and the same trend continues after covid.

 
**Popular states per gender:**

**Males**

![image](https://user-images.githubusercontent.com/126873540/236676483-79aac97a-9cba-43ef-82bf-fa99d66e79c6.png)


**Females**

![image](https://user-images.githubusercontent.com/126873540/236676499-b8a8a4d9-bd48-4db5-83c2-f4f812e8c588.png)

There appear to be no difference and the same trend continues after covid.
Popular States:
1. NSW
2. VIC
3. QLD
4. WA


**Number of people entering each state per age bracket before and after covid**

**Before covid**

![image](https://user-images.githubusercontent.com/126873540/236676518-2f7f5656-ac67-4c2e-9f88-daa0c664f049.png)


**After covid**

![image](https://user-images.githubusercontent.com/126873540/236676528-8670486d-33ad-4d00-a72f-60727ee955ac.png)

We can see that the trend is changing specially with number of arrivals in NSW, VIC and QLD between the age brackets starting from 15 to 44. We did following analysis to dig further.


**Correlation matrix to show changes between different age brackets before and after covid**

**Combined Matrix:**

![image](https://user-images.githubusercontent.com/126873540/236676562-67c4e2ae-d379-403a-ba97-731467d1ec3b.png)
 
**Before Covid correlation matrix between different age brackets**

![image](https://user-images.githubusercontent.com/126873540/236676587-6bd0766b-5c52-4777-adeb-260eb5f33ab3.png)

**After Covid correlation matrix between different age brackets**

![image](https://user-images.githubusercontent.com/126873540/236676602-7a72d098-ad7b-4b12-83b2-892827176675.png)

We can see clear differences in the trend/patterns e.g. before covid there was correlation between the age bracket 15-19 and 20-24 with different age brackets but since covid this has dropped significantly. This aligns with the fact that we had drop in number of international student arrivals since covid. 

**Change in ‘Male-Female Ratio’ entering each state per age category**

![image](https://user-images.githubusercontent.com/126873540/236676637-168cdce9-9fab-4a8b-ad9c-590aaecc211d.png)

Here positive change indicates ‘Number of Male arrivals’ has increased for the specific category while the negative change indicates ‘Number of Female arrivals’ has increased for the specific category.
We can also observe that since covid number of Male arrivals in TAS has increased significantly while NT and ACT had increase in number Female arrivals.

**Data Analysis Code: visa.ipynb**

**Types of Visa**
![image](https://user-images.githubusercontent.com/125717794/236707622-3acee36d-ebbd-4cfa-8e6a-56587158aca3.png)

This graph shows the drop in the Total Migrant Arrivals with Visas to Australia during the pandemic year 2021. It can be noticed that only a few visas were granted during this period, and only Australian citizen arrivals were above 60000 people.

 ![image](https://user-images.githubusercontent.com/125717794/236707627-3290c124-c10d-4dcf-a866-a01e31f7259a.png)

On the other hand, the heatmap above shows that Temporary Visas for the Higher Education Sector are the category with more visas granted before and after covid. Also, it can be concluded that the Temporary type Visa – Visitor has not returned to the same approved visa quantity that it had before covid.

**Total Hours Worked over years**
![image](https://user-images.githubusercontent.com/125717794/236707638-81556ad1-8792-4334-9267-5a665820cd8e.png)

The above graph shows that during the pandemic period, the total hours worked decreased as expected. During this time, many jobs were ended, mainly in the hospitality sector, for instance.

At this point of the investigation, it is interesting to examine if there is any relationship between specific types of visas and the total number of hours worked in Australia in that same period. To find these relationships, it was calculated the correlation coefficients and the results are as follows:

**Correlation**
 ![image](https://user-images.githubusercontent.com/125717794/236707655-7df50832-235c-4bcf-8391-328977ba90bb.png)

If we focus our attention only on examining how the Visas Categories are correlated with the Total hours worked, we can find that there is a strong positive correlation between Permanent Visas and Hours worked. In contrast, the correlation between the Permanent Visa Skill and Hours Worked seems moderately negative.

**Linear Regression Permanent Visa - Skill vs. Total Hours Worked per Year**
![image](https://user-images.githubusercontent.com/125717794/236707677-04ba1c6e-6459-4bcd-80d3-8b6cc1da14ea.png)

The r-squared is: 0.7147064639603282
The correlation between both variables is 0.85.


This strong positive correlation shows that migrants with permanent visas significantly influence the Australian labour force. In this case, it shows that the arrivals with permanent visas are working part-time jobs.

![image](https://user-images.githubusercontent.com/125717794/236707684-24a658c9-9f41-4f63-9981-54ffaac995c7.png)

The r-squared is: 0.6695475831917412
The correlation between both variables is 0.82.

As mentioned earlier, this is another positive correlation that shows that migrants with permanent visas significantly influence the Australian labour force. In this case, it shows that the arrivals with permanent visas are contributing to the Total Hours Worked in the Country.

**Linear Regression Permanent Visa - Skill vs. Total Hours Worked per Year**
![image](https://user-images.githubusercontent.com/125717794/236707707-b7e2de0f-d29f-4e8b-bc95-6fe7c2bbf8bd.png)

The r-squared is: 0.2606771283638466
The correlation between both variables is -0.51.

 ![image](https://user-images.githubusercontent.com/125717794/236707717-9d1dd709-cb01-46b2-8c4d-5e22e046e6d1.png)

The r-squared is: 0.27715381701514324
The correlation between both variables is -0.53.

The two graphs above show a moderate negative relationship between Migrant Arrivals with Permanent visas – Skills, and the Total Hours Worked. This result would indicate that with more migrants with skilled visas, the total hours worked decreases. One of the insights we could get from here is that with a more specialised labour force, the work can be done more efficiently and in fewer hours.




**DATA SOURCE**

The data has been sourced from the Australian Bureau of Statistics (ABS) using the link: https://www.abs.gov.au/statistics/people/population/overseas-migration/2021-22-financial-year#key-statistics 
The data has been collected based on a financial year. 

The Labour Force Data has been sourced from the Australian Bureau of Statistics (ABS)  using the link:  https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia/mar-2023/6202019.xlsx

Information on COVID travel restrictions were sourced using these links: https://www.aph.gov.au/About_Parliament/Parliamentary_departments/Parliamentary_Library/pubs/rp/rp2021/Chronologies/COVID-19StateTerritoryGovernmentAnnouncements. [Table 3: initial border restriction announcement by state and territory governments]. 

https://www.health.gov.au/health-alerts/covid-19/international-travel 

ABC news article on migration: https://www.abc.net.au/news/2023-04-29/australian-migrant-population-growth-hits-all-time-record-high/102281798 

