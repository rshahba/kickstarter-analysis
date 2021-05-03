# kickstartet-analysis
Performing analysis on Kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to help Louise’s play Fever succeed in her campaign. This project analyzes how different campaigns fared in relation to their launch dates and their funding goals. A visual graph of campaign outcomes based on their launch dates and their funding goals is also necesssary in order to illustrated the findings. 

## Analysis and Challenges

This section explains how the analysis was performed using images and links to code. It will also include any challenges that I encountered.

### Analysis of Outcomes Based on Launch Date
In this section, theater outcomes by launch date was analyzed to understand the number of successful, failed, and canceled musical's, plays', and spaces' fund raising from 2009-2017 based on each month, starting from January. Please note that all the subcategories mentioned are part of the theater industry.

Data demonstrates that campaigns had the most successes in achieving their goals in the months of May, June, and July and the lowest rate of successes were seen in the month of December. It is also useful to understand that none of the campaigns have been cancelled during the month of October in the years 2009-2017.

![Outcomes Based on Launch Date](https://github.com/rshahba/kickstartet-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
This analysis makes it clear to us that play campaignes with goals of $1000 and less have the highest chance, %76, in succeeding. There is a downward trend of successful campaigns for projects with the $1,000-$34,999. However, the rate of success increases in projects with $35,000 - $44,999. No plays campaigns with any goals have ever cancelled. It is important to call out that 100% of play campaigns with the goals of $45,000 - $49,999 fail.

![Outcomes Based on Goal](https://github.com/rshahba/kickstartet-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
    - Ordering the "successful", "failed", and "canceled" coloumns in the pivot table 
    - Due to then nature of the goal ranges, cell formulas must be percisely checked, as a minor number misstype greately affects the results.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. May has the highest number of successes and failed theater campaings, however, the number of success campaigns is almost double the number of failed campaigns.
    2. No theater campaigns between 2009 and 2017 have been canceled

- What can you conclude about the Outcomes based on Goals?
    - It is best to run play compaignes with less than $1000 goals
- What are some limitations of this dataset?
    - The total number of campaigns each brand has had
    - The pledge amount for "live" campaigns does not get updated live on the data set

- What are some other possible tables and/or graphs that we could create?
    - Box & Whisker graph could be used to illustrate the outliers in data
    - A pie chart to illustrate the total percentage of successful, failed, and cancelled campaigns
