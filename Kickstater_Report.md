# Kickstarting with Excel

## Overview of Project:
Using the global Kickstarter dataset and focusing specifically on Plays we looked to determine if campaign outcomes are related to launch date or funding goals. Please see Excel file for further detail.
### Purpose
This analysis is aimed at guiding the launch of future Kickstarter campaigns by targeting goals and launch windows that have the highest probability of success.

## Analysis and Challenges
First data was organized in order to sort by the target parent category, "theater" and then narrowed further to "plays". We then used goal and pledged amounts to determine if a campaign was successful or had failed. We then cleaned the date stamps in order to look for seasonality by launch month in the success or failure of a campaign. 


### Analysis of Outcomes Based on Launch Date
* The greatest number of successful Theater campaigns were launched in May. This is also true on a % of total basis with 67% successful.
* Theater campaigns launched in December had the highest percentage of fails, at 51%. 
* Both on an absolute and percentage basis, successful Theater campaigns peak in May and steadily decline to December.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/86166117/122725391-ce34f000-d229-11eb-94da-97838838e88e.png)

### Analysis of Outcomes Based on Goals
- The greatest number of campaigns had funding goals between $1,000 and $5,000
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/86166117/122726395-cf1a5180-d22a-11eb-96a6-2e6a27cd66af.png)


### Challenges and Difficulties Encountered

## Results

Conclusions from Outcomes based on Launch Date
- 1 Launching in May has the highest likelihood of success
- 2 December has the lowest likelihood of success

Conclusions from Outcomes based on Goals
- Campaigns launched with a goal of less than $1,000 had the highest percentage of success

Dataset Limitations:
- The data did not include deeper levels of detail which may have impacted our conclusions, such as: the profiles of the doners, the success history of the campaign sponsor, among others. 
- The sample may need to be narrowed down to US plays in order to draw better conclusions
- Do not know if funding is measured in the same currency for all projects

Other Possible Analysis
- Look at ranges of goals within years. Was a campaign more likely to be successful if it was competing against higher or lower goals?
- Graph the relationship between total kickstarter goals in all categories vs. plays in a given month. 
