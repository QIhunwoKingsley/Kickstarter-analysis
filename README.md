# Kickstarter Analysis 
Performing an analysis on Kickstarter dataset that will show us trends based on specific factors that makes the campaigns successful.
## Overview of the Project
Louise is an upcoming play writer who wants to start a crowdfunding campaign to help fund her play "Fever" for which she is estimating a budget of $10,000. She wants us to help her determine the specific factors that makes her campaigns successful.
## The Purpose of This Analysis
I need to provide a visual representation feedback to Louise with insights to help her gain a better understanding of her campaigns from start to finish. This report will aid her to set her campaign to mirror other campaigns that are successful in the same category.
## Analysis and Challenges
In the Kickstarter raw data I sorted and prepared for the analysis by creating new columns to show parent category, subcategory, Average Donation, convert dates, convert times, and a new column for the year of the Launched date.

![](https://github.com/QIhunwoKingsley/Kickstarter-analysis/blob/main/TableRead.png)



- The following chart is based on the Outcomes of the Parent Category. This shows that Theater was the most successful overall. Whene I filtered Theater by United States and Great Britain campaigns. US had a total of 525 successful Theater kickstarters campaign and GB had a total of 258 successful Theater kickstarters campaign.

![](https://github.com/QIhunwoKingsley/Kickstarter-analysis/blob/main/Stacked%20Chat%20Week%201.png)



- The following chart is based on the overall outcomes on Launched Dates. This chart shows that the month that launched the most successful Kickstarter campaigns was May. Also, January, June, July, and October all had the same number of failed campaigns launched.

![](https://github.com/QIhunwoKingsley/Kickstarter-analysis/blob/main/Stacked%20Line%20Chat%20Week%201.png)


## Difficulties and Challenges Encountered
- I faced some difficulties with the pivot table. Later, I realized where the error was and ammended the pivot table.
- I faced a lot of challenges using the CountIfs() formular. Read the questions asked in slack about it, and the video resources in the challange.
- The line chart I created didn't look like the sample given. Did some research and found and fixed the errors.


# Kickstarter Challenge Results
The information below tells us the conclusions based on Theater and Goals of the Kickstarte campaign.

### Conclusions Drawn for Theater Outcomes by Launch Date
Looking at the line graph below, we can see a detailed trend. May and June had a relatively high number of Successful theater campaigns and December had the least. So it's good to say that the Play should be launched during May or June.
- Knowing the right time to launch the campaign is very important for it to be successful.
- We can also consider the duration or length of the campaign is also important to analyze. 

![](https://github.com/QIhunwoKingsley/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


### Conclusions Drawn fro Outcomes Based on Goals
The line chart below helps us to understand that Goals less than $1000 were 76% successful and most of the unsuccessful campaigns were around $45000 - $49999. Goals around $10000 - $14999 were 54% successful and 46% failed. 
- From the data gathered, we can conclude that Louise's goal had a 54% chance of it being successful.
- Having a considerable high goal can also affect the campaign.

![](https://github.com/QIhunwoKingsley/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


### Limitations of the Dataset
- US and UK are the countries where most of the plays were successful. If we had more information about the cities and the age group of people going and watching the play would have been interesting to see.
- Information on the Genre of plays would have helped determine the success of plays and give better analysis to Louise. 


### Other possible tables and/or graphs that we could create
- A clustered column chart can be used to show the outcomes based on Launched Date.
- A stacked column, Clustered column chart can be used to show Outcomes based on goals. 
