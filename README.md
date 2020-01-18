# Kickstarter_Analysis
## An Analysis of Kickstarter Projects for Louise's Kickstarter Campaign 

**1. Background**

Louise estimated a budget of US$10,000+ to fund her new campaign, a Play named "Fever", on Kickstarter.  She wanted to understand more the factors that would help to make a project campaign more successful. 

**2. Initial Analysis**

a) In the Theater category (which includes Musicals, Plays, and Spaces) in US, 525 out of 912 projects (57.6%) were successful. 

![theater category outcome](https://github.com/pegkhiev/Kickstarter_Analysis/blob/master/theater_category_chart.png)

b) Within Theater category, the sub-category of Plays in US is the most successful, with a 61% success rate (412 out of 671 projects).

![theater subcatory category outcome](https://github.com/pegkhiev/Kickstarter_Analysis/blob/master/parent%20category%20outcome%20chart.png)

c) For all Plays projects in US, the successful projects have a mean goal of $5,049 and a median goal of $3,000; whereas for the failed projects have a higher mean goal of $10,554 and a higher median goal of $5,000.  The successful projects resulted in a mean and median pledged amount fairly similar to the goal; whereas for the failed projects the mean and the median pledged amount is much lower. 

|   |Successful|Failed|
---| --- | ---
Mean Goal | $5,059 | 10,554| 
Median Goal | $3,000 | $5,000| 
---| ---| ---
Mean Pledged | $5,602 | $559|
Median Pledged | $3,168 | $103|

d) Among all Plays projects in US, the upper percentile (75%) of goal and pledged amounts are $5,000 and $5,699 respectively.  Louise's funding target of $10,000+ means that her project will be among the top 25% of Kickstarter Plays projects in US. 

|   |Successful|Failed|
---| --- | ---
Mean Goal | $5,059 | 10,554| 
Median Goal | $3,000 | $5,000| 
**Upper Percentile Goal** | **$5,000** | **$10,000**|
---| ---| ---
Mean Pledged | $5,602 | $559|
Median Pledged | $3,168 | $103|
**Upper Percentile Pledged** | **$5,699** | **$501**|

Note: Louise was also interested in project outcomes for musicals in UK, but they will not be discussed here. 

**3. Initial Conclusion** 

Louise's Kickstarter campaign for Plays in the US will have a higher chance of success over musicals, and her funding goal of US$10,000 puts her Kickstarter campaign in the top 25% of all Kickstarter "Plays" projects in the US. 

### Challenge

**Background**
Louise's play "Fever" project came close to its fundraising goal in a short amount of time.  he wanted to know how many other projects were able to do this as well. *For the purpose of this analysis, it is assumed that her funding goal was US$10,000.

**1. Outcome Based on Goals**

The following chart shows Play projects (in the US) success and failure rates based on fundraising goals.  Non-US projects were excluded as the currency was different and without proper currency conversion it would skew the result. 
 
![Outcome Based on Goals](https://github.com/pegkhiev/Kickstarter_Analysis/blob/master/Outcome_goals_USPlays.png)

**2. Outcome Based on Launch Dates**

The following chart shows the outcomes of all Theater projects in Kickstarter.  It shows that projects launched in May have the highest sucess rate. 

![Outcome Based on Launch Dates](https://github.com/pegkhiev/Kickstarter_Analysis/blob/master/Outcomes_launchdate_Allcountries_theater.png)

**3. Conclusions**

a) 54% of Plays projects in US with a funding goal of US$10,000-$14,999 were able to achieve success.  In the future, if Louise lowers her fundraising goal to $4999, she will have 17% more chances to achieve success. 

b) Within the Theater category, projects launched in May have a higher success rate.  Therefore in the future, Louise should consider launching her fundraising campaigns on Kickstarter in May for a higher chance of success. 

c) In the future, Louise should try to avoid launching campaigns in December is the month with the lowest success rate in the year. Only around 1/3 of the campaigns launched in December were successful. 

**4. Limitations of Dataset Analysis and Recommendations** 

a) Currently the analysis only looked at the relationship between the launch date and outcomes.  It does not take into account the actual duration of the campaigns, and how that might affect the outcomes. We should consider building another chart to look at the relationship between fundraising campaign duration and outcomes. 

b) Louise came close to her goal within a short period of time.  However, we don't have data analysis to understand the relationship between duration and pledged amount.  We should consider building another chart to look at the relationship between duration of campaigns and the highest pledge percentage (over goal) campaigns to understand how much the highest  



