# Kickstarter-Fundraising-Success-Analyisis-in-Excel
## *Analysis of Worldwide Kickstarter Crowdfunding Success and Failure rates 2009-2017 in Excel.*

<img width="653" alt="README kickstarter header image" src="https://user-images.githubusercontent.com/93171738/144171262-14e00235-b2cf-4708-98de-3b955ccd2040.png">

### Overview of Project
  This project intends to work with data from worldwide Kickstarter crowdfunding campaigns in various categories in an attempt to extract information that can provide valuable insight in regards to the Success and Failure rates of distinct Kickstarter projects.
### Purpose
 The purpose of this analysis is to use the vast amount of Kickstarter crowdfunding campaign data available to us to help our dear friend, Louise determine the Best strategy moving forward to help fund her play, ***Fever*** which she has worked so hard to bring to fruition. 
### Analysis and Challenges
 Our analysis was completed by sorting through the vast sea of Kickstarter data and honing in on only the most relevant pieces of information that would answer the following questions in the **Theatre/Plays** category:
  ```
  What time of year and what month(s), specifically would be best to launch the campaign to ensure maximum success?
  
  And,
  
  What dollar amount would be best to strive for as a Kickstarter goal to ensure the highest probability of success? 
  ```
The most challenging aspect was knowing how to take the sheer volume of raw Kickstarter data (***see image below***) and convert it into useful knowledge that could intelligently be analyzed and interpreted to make valid recommendations that would indeed help our friend, Louise to successfully find funding for her play. 

<img width="949" alt="sheer_amount" src="https://user-images.githubusercontent.com/93171738/143505530-afd95b05-a58a-4876-8824-1be71b394157.png">

To solve this challenge and to make sense of the large amount of data, specifically, in terms of the information we were looking for, I used statistical calculations (***see image below***) to locate the ranges where prior campaigns in the theatre and plays category had found success. 

By knowing what had worked before in the past and equally important, by knowing what had ***not*** worked in the past, we could make future suppositions as to what would still work, today with all other things being equal. 

<img width="350" alt="statistics" src="https://user-images.githubusercontent.com/93171738/143509470-4f00b2ec-a524-4772-82da-cf3ce14af9c5.png">

Having completed the steps above, we were now ready to apply the statistical findings to the filtered and refined theatre/plays campaigns data and drill down to the core factors that would answer the questions (***above***) to the problem we had set out to solve. 

### Results
The first question we wanted to answer was to see what time of year and specifically, what month(s) had shown to have the highest number of successful campaigns to give us an idea when it would be best suited for Louise to launch her crowdfunding campaign 

This question led us to create a pivot table where we could filter the isolated theatre and plays data, allowing us to create a line chart to visually represent the optimum times to launch a successful campaign. 

<img width="535" alt="outcome months" src="https://user-images.githubusercontent.com/93171738/143510976-a913fe15-dfe5-4fe9-a4d9-6fa8cab2e947.png">

As you can see from the chart, the time of year when most campaigns were successful was in mid-spring, and, specifically the month of May was when the most successful campaigns were launched. Knowing this we could deduce two key action plans that would help to improve the chances of Louise having a successful launch and campaign. 

```
A. She could start preparing in September, as that is when activity begins to slow down for the year, 
   in anticipation for a successful launch. 

B. She now knows that she needs to have all of her ducks in a row by May 1st, so that she can give herself 
   the best odds of raising the money necessary to stage her play. 
```
The next question we had to answer was finding out the optimal dollar amount range that Louise should ask for as her goal amount. If the goal is not set right she could find herself where a majority or 60% of the unsuccessful campaigns lived, at the bottom of the charts. 

So we cycled through all the theatre and plays data using countifs command to determine the most successful dollar amount ranges asked according to the date. What we discovered was in one way totally expected and in another, surprising in a good way. 

<img width="689" alt="outcome based on goals" src="https://user-images.githubusercontent.com/93171738/143656978-37704340-10a7-45c1-bf18-4e9980b4b253.png">

As you can see from the line chart above, we find that, just as we might expect, there a large percentage of successful Kickstarter campaigns (approx. 70%) between less than a thousand and five thousand dollars. As we can imagine people are more inclined to donate money when a goal seems attainable. A $5000 dollar goal would fall into the category of attainable. 

However, what I did find surprising about the results was a jump to about the 60% success rate for goals in the ***$35K to $45K range***. This is telling as it will inform Louise's decision-making process. 

If she is looking to just scrape by with the minimum funding possible, she should set her goal at less than $5,000. However, if she is ready to take a leap of faith and is confident in her plays ability to connect with people then she may consider setting her goal higher to the, **$35,000 - $45,000 range.** 

These two ranges have proven to be the most successful as to the asked for goal amount. 

<img width="677" alt="README kickstarter footer image" src="https://user-images.githubusercontent.com/93171738/144173606-22b0a3e2-f16a-46c3-8452-94a35620a21b.png">

### Limitations

Although there was much insight to be gleaned in our analysis on Kickstarter crowdfunding campaigns, I feel there is still more information that can be extracted from the data we have available. With further investigation I am sure we can find deeper insights and concrete actionable steps that will lead Louise, and many others for that matter, to make wise decisions when it comes to launching their hoped for, successful crowdfunding campaign. 

For Louise, specifically I would be very interested to discover the reason why there is a 60% success rate at the ***$35k to $45k*** level when it was down less than 20% just $10K less in the $25k range. If she can discover what it is that makes these campaigns enticing to donors, she would then be able to mimic what they did to be successful and claim a goal on the higher end of the spectrum which, can only help her chances of finally launching her play, ***Fever***.

### Conclusion
Our friend, Louise has a very good opportunity of cashing in on the Kickstarter data we were able to clean up and analyze. According to our research it seems there is a strong possibility **(70% - 80%)** of finding success in the month of May for the $1000 to $5000 dollar goal amount. This would be a nice amount to get her started on the necessary basics of launching her play. 

If she was further along in the development of her play she could, potentially increase the goal amount she asks for to the ***$35,000 to $45,000*** range and have an approx. **75%** chance of finding success. By further studying the data to find what unique factors the 'successful' plays possessed, she can increase her chances of funding her dream through the "**magic**" of crowdfunding Kickstarter campaigns.

