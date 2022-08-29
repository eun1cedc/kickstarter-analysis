# kickstarter-analysis

## Overview of Project

This project serves as an analysis of Kickstarter data to uncover trends that will help the client, Louise, determine the parameters of a successful crowdfunding campaign for her play, *Fever*. The data spans from 2009 - 2017, features different categories of campaigns, and has international coverage of countries with different socioeconomic and geopolitical backgrounds. The projected budget for *Fever* is $10,000.

## Analysis and Challenges
Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered. The overview of the analysis is well described with screenshots (2 pt).
Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered 

### Analysis of Outcomes Based on Launch Date
![Line graph depicting Theater Campaign Outcomes based on Month of Lauch](https://i.postimg.cc/RFDCS7bB/Theater-Outcomes-vs-Launch.png)
After referencing [Microsoft's YEAR function guide](https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us), I created a pivot table to filter for the performance and count of campaigns across months. It isn't readily intuitive to determine the configuration so that the column for 'Successful' campaigns was sorted first. After creating a line chart from the table, it was possible to determine that successful campaigns are highest from May - July. On the other hand, failed and canceled campaigns remained consistent throughout the year as neither line demonstrated outliers from the established range. 


### Analysis of Outcomes Based on Goals
![Line graph depicting Outcomes Based on Launch Date for Successful, Failed, and Canceled Campaigns](https://i.postimg.cc/G22hn7KK/Outcomes-vs-Goals.png)
After setting the monetery goal amounts to the parameters dictated for the assignment, I used the [COUNTIFS function](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us) to retrieve the information needed to determine what percentage of the campaigns were successful, failed, or canceled based on their goal. 
![Table that depicts Goal Brackets in rows and Sum of Percentage of Campaigns that were Successful, Failed or Canceled in columns](https://postimg.cc/9DcBXxBX).
Then, I created a pivot chart that tracked the sum of each percentage compared to the goal bracket. The chart visualizes that the relationship between the sum of the percentage of successful and failed campaigns is a reflections of each other. 

### Challenges and Difficulties Encountered
My biggest challenge was in ensuring I had fully reset the original dataset after having manipulating it in different to extract several tables and charts. The amount of columns tracked in the dataset were difficult to review visually as they were not possibly to resize to fit within the window. Careful review had to be enacted to ensure no column remained in a filtered view before proceeding on to next stage of the assignment. 

## Results: 

### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
There is a spike in successful campaigns from May - July, but failed and canceled campaigns remain consistent throughout the year. Most theater campaigns will be successful except on December; the rate for failed and successful campaigns is similar on this month. 

### What can you conclude about the Outcomes based on Goals?
Overall, the chart shows that successful campaigns are more likely to have smaller monetary goals while failed campaigns tend to have larger monetary goals. 

### What are some limitations of this dataset?
While the average donation is provided, the median is not. This leaves us with no context to determine the skew of each campaign for individual donations. The dataset also does not provide the budget or other related details that each campaign had for publicity. Publicity strategies for campaigns are also a significant factor that help determine success. 

### What are some other possible tables and/or graphs that we could create?
I would create an additional column that calculated the total time the campaign was run by using the difference of the 'Date Created Conversion' and 'Date Ended Conversion' columns. I would then create a chart to see what impact campaign length had on successes, failures, and cancelations. I would also create a chart that determines if there is a correlation between average donation, total count of backers, and location. 

