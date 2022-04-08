# Analysis of Successful Kickstarter Campaigns
Description: This analysis suggests criteria for a successful Kickstarter campaign based on launch date and goal amount in the area of performing arts.

# Overview of the Project
**Background**

Louise wanted an analysis to show how campaigns performed in relation to their launch dates and their funding goals. Using a Kickstarter dataset, we were able to organize and analyze the data for these key trends and recommend several goals to help her reach her fundraising goal. The following analysis includes explanations and visuals to better illustrate these recommendations. 

**Goal**

The goal of this project was providing my client, Louise, with two criteria in ensuring a successful Kickstarter campaign in the area of performing arts. These are a preferred launch date and a suggested goal amount. Through analzying over 1000 successful and failed campaigns, ranging back nearly ten years and from less than $1000 to more than $50,000, it is possible to provide suggestions on these two key metrics. 

# Outcomes

**Categorical Outcomes**

Louise was interested in performances of theatrical nature such as theater and plays. Fortunately, an initial analysis determined these as some of the most successful campaigns compared to other performance types. The data demonstrated a success rate for theater of nearly 60%. This supports Louise in her desire to launch a theatrical campaign. One challenge in the data was the location. Much of this analysis focused on successful campaigns in the US, but further analysis could potentially improve or identify other geographical areas which could encounter the same success rates or greater. 

<p align="center">
<img src="https://github.com/teachjanderson/SuccessfulKickstarters/blob/main/images/LouiseParentOutcomes.png" width="600" />

**Outcomes by Date**

Louise was also interested in the best time of year to launch her campaign. After careful review of the data, May, June, or July provided the best success rates throughout the year. May provided the most successful outcomes with over 100 successful campaigns compared the fall or winter which averaged 60 or fewer successful campaigns. The data displays a steep rise beginning in March, cresting at May, and gradually falling until September. This suggests preparing in early spring and launching in May. The worst time for Louise to launch would be the winter months with December at the lowest rate of success. 

<p align="center">
<img src="https://github.com/teachjanderson/SuccessfulKickstarters/blob/main/images/OutcomesBasedonLaunch.png" width="600" />
  
  **Outcomes by Goal**
  
The goal amount Kickstarters aim to achieve does play a factor in success of the campaign. Based on data found in the Descriptive Statistics tab of the  [Kickstarter Challenge Spreadsheet](https://github.com/teachjanderson/SuccessfulKickstarters/blob/main/Kickstarter_Challenge.xlsx), successful campaigns set a mean goal for $5000 with the median being closer to $3000. Scrolling down to the chart Outcomes Based on Goals reveals Louise will want to carefully select her goal amount to achieve success. Kickstarters with a goal amount of less than $1000 to $5000 have the hichest rates of success. 
  
  <p align="center">
<img src="https://github.com/teachjanderson/SuccessfulKickstarters/blob/main/images/GoalAmounts.png" width="600" />
    
<p align="center">
<img src="https://github.com/teachjanderson/SuccessfulKickstarters/blob/main/images/Outcomes_vs_Goals.png" width="600" />

# Recommendations
    
**There are three recommendations for Louise to achieve a successful campaign.** 
    
  1. Theater and play Kickstarters are both successful in the US. The recommendation is to choose a play Kickstarter. 
  
  2. Kickstarters launched in May are more successful than those in other months of the year. The latest recommended launch date is late spring or early summer. 
  
  3. The target goal range for success is a key factor and Louise will want to set her goal carefully. A range of $1000-$5000 has the highest chance of success with the greatest number of Kickstarters demonstrating success.
  
  # Limitations
This dataset and analysis does come with limitations. The data from Kickstarter does go back several years. With changes in pandemic culture and the rise of different venues for entertainment, it's important to recognize that much of this data is around 2015. Identifying how long Louise plans to run her campaign could also provide avenues for determining success, with asking whether a shorter or longer duration will achieve the most pledge support. This does highlight another limitation of the data and that is some of the Kickstarters were still live at the time the data was pulled, thus limiting determining the amount raises and success/failure rates. With such variance in success during different times of year, it could be worthwhile to analyze why spring demonstrates greater success than fall or winter. Finally, analzying the communication modes to reach her audience may help create avenues for how she spreads word about her Kickstarter. Analyzing which social media outlets foster the most success could help her plan a better campaign. 
  
  # Challenges
  The data set did contain UNIX timestamps. This took conversion steps to make the data useable. Determinig the outcomes by goal did prove challenging at first due to an error in the coding. It was quickly apparent that campaigns were either complete failutres or too successful. This led to a careful review of the formulas and found one consistent error pattern. After fixing this mistake, the data revealed trends. One challenge that could be better addressed is compensating for the percent of successful campaigns. While a few higher goal amounts were achieved, telling the story of a high percent and understanding the limited number of successful campaigns at that amount is important. Adding an additional graph which shows the percent of success along with the specific number of campaigns at that percent could improve the story of which campaigns will achieve success. 
