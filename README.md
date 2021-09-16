# Module 1 Challenge: Kickstarter Analysis
An analysis of a data set containing data from 4000 Kickstarter crowdfunding projects with the goal of discovering hidden trends. 
## Overview of Project
A client who is recently came close to her fundraising goal for a play that she wrote is interested in how different fundraising campaigns fair in their sucess with respect to their launch dates and funding goals. Using Kickstarter, she was able to gather data on 4000 different campaigns and has shared the data with our team. The current objective is to analyze the data in order to inform our client about what makes or breaks the success of fundraising campaigns for plays specifically with respect to the date that they are launched as well as the goal of money they hope to raise.

## Analysis and Challenges
### Process of Analysis
The process of analysis involved isolating the useful data from the unuseful data in the data set. Data that was useful can be defined as data that will help to achieve the goal of this project. Because our client is a playwrite interested in knowing more about the sucess of fundraising campaigns with respect to their launch date and fundraising goals, our team removed all of the data that were not relevant to: fundraising for plays, fundraising launch dates, fundraising goal amounts, the success of the fundraiser. After the relevant data had been isolated, we were able to perform calculations and manipulations that allowed us to address our client's curiousity. An image of the table that we created from the isolated data is below:

<img width="1116" alt="Screen Shot 2021-09-16 at 3 57 44 PM" src="https://user-images.githubusercontent.com/89808050/133691208-bc61c1e3-454c-40aa-9c26-2952d2b442dd.png">

<img width="388" alt="Screen Shot 2021-09-16 at 4 02 49 PM" src="https://user-images.githubusercontent.com/89808050/133691770-4b1996fc-1336-4fcb-ab41-4824b7ddef6e.png">

The first image displays the number and percentages of fundraising campaigns for plays that were successful, failures, or were canceled. The second image displays the number of successful, failed, or canceled campaigns for play fundraisers for each month of the year.

From these simplified tables of data, we were able to construct charts that clearly depicted the changes in success rate over months of the year as well as the changes in fundraising goal. 

### Challenges
Some challenges that were encounter mostly surrounded reformatting. In other words, the initial data set displayed information that was either not readable or not easily computable. More specifically, all launch dates were displayed in Unix Timestamps, so one of our first tasks was converting all of these dates to a conventional format. To confirm that the 10 digit strings were in fact Unix Timestamps, we used an online Unix Timestamp Converter. The link to this converter is displayed below:

https://www.epochconverter.com/

## Results
### Theatre Outcomes by Launch Date
We can conclude from the data that some months out of the year are more successful for play fundraising campaigns. 
First, we learned that play fundraising campaigns are most likely to succeed in May and June, however we also see that play fundraising campaigns are also the most likely to fail in May and June. From this, we can conclude that May and June are the busiest months of the year for these types of fundraisers. See chart displayed below: 
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89808050/133692644-4e5240f9-d6be-4d86-b5ea-e7d8326b10d6.png)

Second, we learned that the likelihood of the success of a campaign decreases as the goal amount increases.See chart displayed below:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89808050/133692943-f7376fbd-b750-4fef-bf8a-e07f2bbd5c08.png)
### Limitations
The main limitation in the current analysis is that we did not take into account how long each campaign lasted. In other words, we are unable to see how the duration of a campaign affected its success rate. It could be possible that the high goal campaigns were not successful because their duration was too short. This information would be helpful in future analyses and charts. All calculation and code used in this analyses can be viewed in the excel file stored in this repository. 


