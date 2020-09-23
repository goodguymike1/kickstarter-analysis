# Kickstarter Analysis
## Overview of Project
This project was created to provide analysis of Kickstarter data from 2009 to 2017 to uncover trends.  The data analysis can be used to determine the best month to launch a campaign and the best goals to set, in order to have the best chance of success
## Analysis and Challenges
The analysis of this data is broken down into 2 different categories.
1. Outcomes Based on Launch Date. This breaks down Kickstarter data by month vs the success of the campaigns.  There is a screenshot using the Theater category as an example.
2. Outcomes based on Goals. This breaks down Kickstarter data by goal amount vs the success of the campaigns.  There is a screenshot comparing the success percentage vs the goals broken down into categories.
3. There were no challenges noted on during this analysis. There is a potential challenge should the COUNTIF formula be incorrectly entered when breaking down by goal amounts since this cannot be easily copied and pasted and the formula must be individually entered. 
## Results
### Results based on Outcomes Based on Launch Date [Theater_Outcomes_vs_Launch](https://github.com/goodguymike1/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)
1. Theater Campaigns launched in the month of May had the highest successful campaigns with only a small apike in failures.  The amount of successful campaigns more than doubled the amoung of failed campaigns (111/52 respectrully).
2. Theater Campaigns launched in the month of December had thelowest amount of successful campaigns, whaile also having an uptick in failed campaigns.  This resulting in the success/failure rate to be about even (37/35 respectfully).
### Outcomes based on Goals [Outcomes_vs_Goals](https://github.com/goodguymike1/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)
1. Kickstarter Campaigns with a Goal of less than $1000 have the highest percentage of success and trends downward as the goals are higher, causing the failure rate to increase.
### Limitations & Recommendations
1. The campaigns where the datapoints in a goal category were limited (less than 100 projects), the data presented trajectories inconsistent from the direction of the goal categories with more than 100 projects. More data in those thresholds should produce a more accurate graph in order to better predict outcomes no matter the goal.  
2. I recommend a table & graph based on cuntry of in which the Kickstarter was deployed.  Cultural differences and country wealth could be taken into account for possible success rate differences.
