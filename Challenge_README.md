# Kickstarting with Excel

## Overview of Project and Purpose
This project revolves around different types of productions and the related fundraising efforts.

Louise wants to produce a play.  She has historical data she needs analyzed.  The data includes productions of different types, from around the world, and spread over a period of years, 2009 - 2017.  The data includes, but is not limited to: Name of Production, Type of Production, Fundraising Goal, Total Donations, Total Number of Backers, and the time frame for which the fundraising occurred.

Louise wants to know the outcomes of the fundraising campaigns based on the campaign launch date and also on fundraising goals.  This information will help her make an educated decision on how to manage her fundraising and if her budget is reasonable.

## Analysis and Challenges
To create my analyses,

1. I created a pivot table for which I could filter on "Parent Category"="theater" and/or "Year" for which I could see the number of productions that were "Successful", "Failed", or "Canceled" for each month.  The outcome labels were sorted so "Successful" was shown first.

![Pivot_Theater_Outcomes.png](https://github.com/WagnerLisaK/kickstarter-analysis/blob/main/Resources/Pivot_Theater_Outcomes.png)

2. I created a line chart "Theater Outcomes Based on Launch Date" (shown further below).  This illustrates what months fundraising was most successful and which months to avoid.

3. I created and populated a table for the number of productions per campaign goal range, that were successful, failed, or canceled.

![Table_Campaign_Goal.png](https://github.com/WagnerLisaK/kickstarter-analysis/blob/main/Resources/Table_Campaign_Goal.png)

4. I created a line chart "Outcomes Based on Goal" (shown further below) that illustrates the percent of successful and failed campaigns per fundraising dollar category.

See below for chart-specific analyses.

### Analysis of Outcomes Based on Launch Date (Theater Productions)
![Theater_Outcomes_vs_Launch.png](https://github.com/WagnerLisaK/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

1. The month that launched the most successful Kickstarter campaigns was May. The 3 worst months to start a campaign were August, September, and December.
2. January, August, September, October, and December all had roughly the same number of failed campaigns launched as successful.


### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals1.png](https://github.com/WagnerLisaK/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals1.png)

1. The most successful campaigns had a fundraising goal of less than $5,000.

2. For campaigns with a fundraising goal of greater then $45,000 were failures. 

3. For the following fundraising goals, 50% were successful and 50% failed:
      a. $15,000 - $19,999
      b. $35,000 - $39,999
      c. $40,000 - $44,999

4. Generally speaking, the failed campaigns have a higher fundraising goal than the successful campaigns.

                                                                                      
### Challenges and Difficulties Encountered
I did not have any challenges completing this project.  It would be easy to make a mistake in the table data by forgetting to put an "=" sign in the formulas for the dollar ranges or get a "<" and ">" mixed up, even though you can take advantage of the copy formula function.  In that case, you would back track the data point(s) that didn't look correct and check for every detail in the formula.

Also, after I created the base formula for the =COUNTIFS(), I double-checked my numbers by manually filtering the raw data and comparing the resulted number.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     1. The month that launched the most successful Kickstarter campaigns was May. The 3 worst months to start a campaign were August, September, and December.
     2. January, August, September, October, and December all had roughly the same number of failed campaigns launched as successful.

- What can you conclude about the Outcomes based on Goals?
     1. The most successful campaigns had a fundraising goal of less than $5,000.
     2. For campaigns with a fundraising goal of greater then $45,000 were failures. 
     3. For the following fundraising goals, 50% were successful and 50% failed:
        a. $15,000 - $19,999
        b. $35,000 - $39,999
        c. $40,000 - $44,999
     4. Generally speaking, the failed campaigns have a higher fundraising goal than the successful campaings.

- What are some limitations of this dataset?
     1. Only the parent category = "Theater" data was used for the "Launch Date" analysis.
     2. Only the parent category = "Theater" and sub-category = "Plays" data was used for the "Fundraising Goal" analysis. 
     3. The latest data is 3-4 years old.

- What are some other possible tables and/or graphs that we could create?
     1. I was wondering how much "Theater" data was being excluded by filtering on the sub-category "Plays".  The chart below illustrates this and it is obvious that most of the data in the "Theater" data set is "Plays", which means the chart by fundraising goal is reliable.

![Graph_theater_subCats.pgn](https://github.com/WagnerLisaK/kickstarter-analysis/blob/main/Resources/Graph_theater_SubCats.png)

Submitted Lisa K Wagner - 06/25/2021
