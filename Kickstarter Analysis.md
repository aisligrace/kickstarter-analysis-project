# Kickstarting with Excel

## Overview: This project conducted an analysis on different types of outcomes, based on launch date and by original monetary goal. For the first part of our analysis, we looked specifically at theatre outcomes broken out by month of launch date. After creating a pivot table that examined how many successful, failed, and canceled theatre campaigns occurred in each month, we were able to conclude the best months and worst months for launching theater. We also created a line graph which helped us to clearly visualize our results. 

The second part of our analysis was looking at outcomes based on original financial goals. Using =COUNTIFS, =SUM, and Percentage formulas, we broke out different play outcomes into preset goal categories and categorized by number of successes, failures, and canceled. We created a line chart to help visualize our results. 

### Purpose

The purpose of this analysis was to better understand how launch date and original financial goals can affect how successful a play or theatre is. 

## Analysis and Challenges

For the first part, we first created a new column to identify launch date years using the =YEAR function. Once that was complete, we were able to build out our pivot table. We were able to break it out by month and filter to just parent category = theater and to only successful, failed, and canceled outcomes. We created our line graph based on our pivot table which helped in visualizing. The main challenge was getting the "Row Labels" column to correctly display months. One limitation is that you can't see different years broken out, only month. 

For the second part, we had to calculate many different numbers and percentages using the =COUNTIFS and =SUM functions. The 'CountIfs' function was challenging at first, since it includes many different pieces, including the range of goals. Once all the numbers were calculated, we created another line chart for visualization. One limitations is that the preset goal ranges means there is a wide range within each, and we did not analyze smaller financial differences. 

### Analysis of Outcomes Based on Launch Date

We concluded that the best months to launch are May and June and the worst were July and October. 

### Analysis of Outcomes Based on Goals

We concluded that campaigns with higher goals ( >10,000) have a much lower chance of success while campaigns with smaller goals (<1000) had a much higher Percentage Successful. There were no canceled plays in this dataset. 


