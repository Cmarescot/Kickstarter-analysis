# Kickstarting with Excel
---
## Overview of Project
 ---

### Purpose
We'll be looking for trends between launch dates and funding goals on campaign outcomes 
Louise wants to know how different campaigns performed based on their launch dates and their funding goals. 
---
## Analysis and Challenges
---
### Analysis of Outcomes Based on Launch Date
To perform the analysis on launch dates I began by creating a pivot table and chart that visualized outcomes based on months for all theater campaigns. Our analysis of outcomes based on launch shows that there are no significant relationship between launch date and amount of cancelations. The "canceled" line on the chart is extremely low and steady. 
Our graph shows that there is a an incline in successful outcomes from January, with a peak in May. In the months following May, the graph shows that there is a gradual decrease of sucessful campaigns for the rest of the year.The failed campagin line follows the same trend as the successful campaign. The highest amount of failed campaigns fall in May.



![Theater_Outcomes_vs_Launch.png](https://github.com/Cmarescot/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
---
### Analysis of Outcomes Based on Goals
To perform the analysis on goals I organized the "play" data into tiers based on different goal ranges for outcomes "successful" "failed" and "canceled. In order to get a visual representation on how much data were in each tier, I converted each tier into percetanges of a whole (total projects). Our analysis of outcomes based on goals shows that there is a gradual decrease in successful campaigns as the goal amount began to increase (inverse relationship). Towards the end of the data set(35000-44999) there is a sudden increase but only for a small portion of projects. 


![Outcomes_vs_Goals.png](https://github.com/Cmarescot/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
 ---
### Challenges and Difficulties Encountered
There were some challenges making sure that the correct data were being filtered. For while, my numbers were off because I accidentley but "49000" instead of "49999". I was able to catch this error by using the "sum" and "countifs" greater than 0 function. 
---

## Results
The fact that there were no significant relationship between launch date and the amount of cancelations lets us know that campaign cancelations happened for other reasons outside of launching at the "wrong times". As pointed out by the graph, there is an increase in success among campaigns that launched in May. Louise statistically would be better off launching a campaign in May as the most successful campaigns were launched in May. 
---
The fact that the highest failed campagins are also in March doesnt mean that May is a "bad" time to launch campaign but rather that there is just a bigger sample size (May in general has the MOST total campaigns). 
---
The fact that there is a steady decline in success as campaign goals increase concludes that smaller goals have a better chance of being successful (goals are more likely to be reached). There was a sudden and step spike around the 3000 to 4500 marks but those only make up for a small portion of the total projects, so their data arent really significant (there likely outliers). 
---
Some limitations to this dataset are its filters. It doesnt focus on a specific country. Also, the "Outcomes based on Launch Date" analysis focuses on theater campaigns overall and not just plays. 
---
Box and Whiskers would definetly help gain a bigger picture and help identity which data points can be looked over. For example in the "Outcomes based on Goals" analysis, If we knew for sure if the sudden spikes were outliers than we would have a reliable case to make. 
