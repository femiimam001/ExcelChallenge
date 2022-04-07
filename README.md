# Kickstarting with Excel

## Overview of Project

In this project, i shall be helping an up-coming playright **Louise** . She wants to start a **crowdfunding campaign** to help fund her play **FEVER** .
She has estimated a budget of over ten thousand dollars and was very hesitant in jumping into her first fund raising campaign.This project will include the use of power excel to organise,sort and analyse crowdfunding data. Using excel to analyse current site data will help her gain a greater understanding of campaign from start to finish and she will be able to set her campagn to mirror other succcessful ones in the same category.

### Purpose

This project involve the use of excel power funtions and calculation to determine wether there are specific factors that make a project campaign succesful or fail. We will use this insight help Louise to set her self up for success.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Pivot tables and pivot lines charts were used in detremining the outcome based on lunch dates and are extremely versatile and powerful tools. They allow us to pick and choose the data we want to analyze and then tweak it with visual customizations. Pivot tables also let us continue to tweak the view by filtering our chosen data after it's been set to the line graph. to show outcomes based on trends.

The following steps were taken in determining the outcome based on launch date line graph:

-Convert Unix Timestamps to Readable Format

-Create a New Pivot Chart

-Rename the new sheet "Outcomes Based on Launch Date."

-Right-click the chart image and hover over "Change Chart Type."

-Select "Line" from the pop-up menu.

-Select the "Line with Markers" chart type from the next pop-up menu.

Looking at our new chart, it shows the months of May and June both have a greater success rate:

![Theater_outcome vs Lauch date](https://github.com/femiimam001/ExcelChallenge/blob/main/Resources/Theater_outcome_vs_Launch_date.PNG)

# Analysis of Outcomes Based on Goals

Using Excel skills to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.We would need to use a new function, COUNTIFS(), to collect the outcome and goal data for the “plays” subcategory.

![Outcomes_vs_Goals](https://github.com/femiimam001/ExcelChallenge/blob/main/Resources/Outcomes_vs_Goals.png)

![use_of_function_on_data](https://github.com/femiimam001/ExcelChallenge/blob/main/Resources/use_of_function_on_data.PNG)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

This simple table allows us to determine a few things. For one, failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Louise is asking for more than twice the average successful Kickstarter goal, so this isn't great news for her campaign. In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money. In other words, if the failed projects were also getting a median pledge amount of around $3,000, it's possible that those that failed just asked for too high of a price. Since the median is much lower, there must be another factor keeping people from pledging to those unsuccessful projects.

- What are some limitations of this dataset?

. The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.

. The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.

. Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. There must be some failed Kickstarters with really high goals.

What are some other possible tables and/or graphs that we could create?

**Box Plots**
We'll use box plots, also called box and whisker plots, to compare the distribution of campaign goals and the distribution of total amounts.

**Bar chart**
We'll use bar charts to analyse trends and distribution of points and comparison of the amounts in campaign goals of data.
