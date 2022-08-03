# Kickstarting with Excel
## Overview of Project 
### Purpose
This project was created to help Louise understand how successful her crowdfunding project was for her play ‘Fever’ in relation to other campaigns based on their launch date and monetary goal. To complete this project, I accessed data from a multitude of Kickstarter projects from all over the world occurring between 1970 to 2017.  
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
	Based off the ‘Theater Outcomes Based on Launch Date’ line chart, it appears that during the spring months of the year, crowdfunding campaigns are more likely to reach their fundraising goals. This is evident due to the steady upwards incline of the ‘successful’ line between March and May. It also appears the month for the highest number of failed theater campaigns being in October. 

![This is an image]( https://imgur.com/a/Z3Ncyo5)
### Analysis of Outcomes Based on Goals
	Based off the ‘Outcomes Based on Goals’ line chart, it is evident that crowdfunding campaigns with a goal of less than $1,000 to $4,999 has the highest success rate of 73%-76%. The goal amount with the highest failed rate of 100%, were the campaigns with an amount between $45,000 and $49,999. Though, a better representation of failed campaigns would be anything greater than $45,000. This is since the goal range of $45,000 and $49,999 was based on one project, the range of $50,000+ had a total of 16 projects with a fail rate of 88% making the outcome more reliable. 

![This is an image]( https://imgur.com/cS2Nw7y)

### Challenges and Difficulties Encountered
	I did not experience any specific difficulties during this project; however, I can see how an individual may encounter such issues. For example, I can understand how an individual could’ve had a problem creating the pivot table for the ‘Theater Outcomes Based on Launch Date ‘graph, as we had to separate the data by month though the information was only presented by the year. To convert the years into months, when sorting your data source into the appropriate columns/rows, on the section where it has the years, the individual must right click to group the data into only the months. 
	Another challenge an individual could’ve experienced was the proper use of the ‘COUNTIFS’ formula for the ‘Outcomes Based on Goals’ chart. The formula I used is: “=COUNTIFS(Kickstarter!F:F, "=successful", Kickstarter!R:R, "=plays", Kickstarter!D:D, "<1000")”. Choosing the correct columns to use may have been a challenge for some, along with formatting the formula in the tight area regarding the criteria and range.  
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
Kickstarter crowdfunding campaigns launched in the month of May and June are most likely to be successful. 
It also appears that launch date and funding goals have little to no correlation. 
- What can you conclude about the Outcomes based on Goals?

An outcome that can be drawn from the ‘Outcome Based on Goals’ chart is that crowdfunding campaigns with goals of $1 to $4,999 are most likely to reach their funding goals.  
- What are some limitations of this dataset?
One of the limitations of this dataset is the timeframe. Instead of analyzing the theater outcomes based on the launch date, the analysis would’ve been more useful if the time frame it took to reach its crowdfunding goal was studied. This is due to the lack of relationship between the month the campaign was launched and the goal, which could just be by pure luck. The dataset could’ve also been centered around the different genre of plays as that may have an impact on how much funding a campaign received. 

- What are some other possible tables and/or graphs that we could create?
	A clustered bar chart could’ve also been created to analyze the relationship between the various success rates, even though, that would not have been useful to analyze trends overtime. 

