# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel Challenge 

## Overview of Project

### Campaigns for Theater plays can successfully performed when the timing of their launch date and funding goals is right. Data shows campaign outcomes can be determined based the month they launch and the appropriate funding goals.

## Analysis and Challenges

### The first factor we analyze is the theater outcomes based on launch date. We analyzed this by creating a pivot table displaying launch dates in months against the total count of outcome (whether the plays were successful, failed or canceled). Gaining popularity since 2014, in recent years, data shows theater campaigns are highly successful during the month of May. This could be to the summer days bringing people out for some summer entertainment, as shown in *Theater outcomes Based on Launch Date* image [Theater_Outcomes_vs_Launch.png]. Theater popularity are followed by June and July. Other small peaks can be seen in the months of February and October. With February being the month of *love* this could be an indicator for campaigns to propose more plays as this season approaches.

### A second factor to considered for successful theater campaigns is how much funding is enough to hit goal. We analyze this by creating buckets of 5,000 dollar increments. By using the <sub>=countifs</sub> function we were able to calculate total count of project outcomes and its percentages.  According to our *Outcome based on Goal Chart* [Outcomes_vs_Goals.png] we can point out that theater plays with a goal of less than $5,000 were generally more successful. With theater play at less than $1,000 we see a 73% success rate with 24% failing rate. As the goal amount increases, the less successful.

## Challenges and Difficulties Encountered

### Challenges encountered for the first analysis are the findings are strictly to campaigns with theater in mind. If we break down the theater category into it's subcategory we have different data story telling for musical, plays and spaces. Keep in mind this analysis is not applicable for other categories such as Technology. View image [Technology_Outcomes_vs_Launch.png] for additional details - no true seasonal peak is observed as it is for Theater.

### Another challenge encountered in the second analysis funding goals is that it is redundant. Although more successful plays were seen in the low goal, there was also that chance that they could fail. We looked at the number of backers and average donations but these values are not in correlation to success rates. We also saw two plays from a total of 12 were successful, yet being in the highest bucket goal of $50,000 goal plays.

## Results

### We can conclude on the Theater campaigns can be successful if the by launch Dates is closer to the summer months. Perhaps create seasonal focused theater shows for a given month to gain popularity. 
### We can also conclude that there is 73% chance one a theater play can launch successfully if the campaign funding goal is less than $5,000.

### Additional factors to consider are 
Campaigns of different category different from launch dates to funding goals.
