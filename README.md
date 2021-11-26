# Kickstarter-Fundraising-Success-Analyisis-in-Excel
## *Analysis of Kickstarter Crowdfunding Success and Failure rates 2009-2017 in Excel*
### Overview of Project
  This project intends to work with data from worldwide Kickstarter crowdfunding campaigns in various catagories in an attempt to extract information that can provide valuabe insight in regards to the Success and Failure rates of distinct kickstarter projects. 
### Purpose
  The purpose of this anaysis is to use the vast amount of kickstarter crowdfunding campaign data available to us to help our dear friend, Louise determine the **Best** stratagey moving forward to help fund her play, ***Fever*** which she has worked so hard to bring to fruition. 
### Analysis and Challenges
  Our analysis was completed by sorting through the vast sea of kickstarter data and honing in on only the most relevent pieces of information that would  answer the follwing questions in the **Theatre/Plays** catagory:
  ```
  What time of year and what month(s), specifically would be best to launch the campaign to ensure maximum success?
  
  And,
  
  What dollar amount would be best to strive for as a Kickstarter goal to ensure the highest probablilty of success? 
  ```
The most challenging aspect was knowing how to take the sheer volume of raw kickstarter data (***see image below***) and convert it into useful knowledge that could intellegintly be analyzed and interpreted to make valid recomendations that would indeed help our friend, Louise to succesfully find funding for her play. 

<img width="949" alt="sheer_amount" src="https://user-images.githubusercontent.com/93171738/143505530-afd95b05-a58a-4876-8824-1be71b394157.png">

To solve this challenge and to make sense of the large amount of data, specifically, in terms of the information we were looking for, I used statistical calculations (***see image below***) to locate the ranges where prior campaigns in the theatre and plays catagory had found success. 

By knowing what had worked before in the past and equally important, by knowing what had ***not*** worked in the past, we could make future suppositions as to what would still work, today with all other things being equal. 

<img width="350" alt="statistics" src="https://user-images.githubusercontent.com/93171738/143509470-4f00b2ec-a524-4772-82da-cf3ce14af9c5.png">

Having completed the steps above, we were now ready to apply the statistical findings to the filtered and refined theatre/plays campaigns data and drill down to the core factors that would answer the questions (***above***) to the problem we had set out to solve. 

### Results
The first question we wanted to answer was to see what time of year and specifically, what month(s) had shown to have the higest number of successful campaigns to give us an idea when it would be best suited for Louise to lauch her crowdfunding campaign. 

This question led us to create a pivot table where we could filter the isolated theatre and plays data, allowing us to create a line chart to visually represent the optimum times to launch a successful campaign. 

<img width="535" alt="outcome months" src="https://user-images.githubusercontent.com/93171738/143510976-a913fe15-dfe5-4fe9-a4d9-6fa8cab2e947.png">

As you can see from the chart, the time of year when most campaigns were successful was in mid-spring, and, specficially the month of May was when the most successful campaigns were launched. Knowing this we could deduce two key action plans that would help to improve the chances of Louise having a successful launch and campaign. 

```
A. She could start preparing in September, as that is when activity begins to slow down for the year, 
   in anticipation for a successful launch. 

B. She now knows that she needs to have all of her ducks in a row by May 1st, so that she can give herself 
   the best odds of raising the money necessary to stage her play. 
```
The next question we had to answer was finding out the optimal dollar amount range that Louise should ask for as her goal amount. If the goal is not set right she could find herself where a majority or 60% of the unsuccesful campaigns lived, at the bottom of the charts. 

So we cycled through all the theatre and plays data using countifs command to determine the most successful dollar amount ranges asked accoriding to the date. What we discovered was in one way totally expected and in another, surprising in a good way. 

<img width="560" alt="outcomebasedongoals" src="https://user-images.githubusercontent.com/93171738/143512203-bed24886-d8ec-48f8-b8b9-dcf91bb16345.png">



'what is the correlation between months of the year and success.. why is it so successful in may? And, why is there a gap from <$5000 to right around $25K sweet spot.. what is it about the $25K sweet spot that makes it special?
