# Kickstarter-Analysis

## Overview of Project

### Purpose

After initially analyzing data that dealt with Kickstarter campaigns, we are now asked by Louise to analyze a more specific subset of this data set - theater campaigns, specifically plays. The purpose of this project then, is to give Louise a detailed look at the differing success rates of these Kickstarter campaigns with relation to their launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to give Louise a clearer idea on how well Kickstarter campaigns perform with relation to their launch date, a Pivot Table and Pivot Chart were created filtering out data by the Theater Category and only looking at Kickstarter campaigns which met one of three outcomes: succesful, failed, or canceled. The Pivot Table was first created by only looking at Kickstarter campaigns which fell under the parent category of theater and offers the option of further filtering by years and months. The Pivot Chart offers a visual representation of this time series showing how successful, failed, and canceled campaigns performed relative to one another at any given month during the year(s) selected.

### Analysis of Outcomes Based on Goals

We analyzed how different Kickstarter campaigns fared with relation to their funding goals by creating our own subset of data. This subset only looked at the number of successful, failed, and canceled projects provided in the initial Kickstarter data. These three groups were further grouped down by dollar amount ranges up to $50,000. After getting the number of campaigns that fell within each group, we were then able to calculate the percentage that succeeded, failed or were canceled respectively. Furthermore, this subset of data allowed us to create a visual representation of the data in the form of a line graph that compared the percentages of successful, failed, and canceled play campaigns at each dollar range.

### Challenges and Difficulties Encountered
  
Although I did not necessarily encounter any challenges while analyzing this data, there were certain aspects of the data sets and charts that may cause difficulties down the line. 
The charts used for each analysis did give a visual representation of the data in question, I do not believe that they truly represented the data in the most optimal way. There was too much data included for the analyses. While it may generally be better to include larger amounts of data, by including too many data points we may be muddying our results. For instance, in the two analyses conducted, all countries and years are included. By adding all of these data points we may be skewing data or failing to see trends that a more specific dataset, like theater campaigns within the US during 2015, would offer.

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

One of the conclusions that can be drawn from on our analysis of Outcomes based on Launch Date, is that Kickstarter Theater campaigns that are launched in the months of May and June are more likely to be successful. A quick look at the pivot chart shows us that the months of May and June account for nearly 25% of all campaigns examined in the dataset. More significantly, the higher volume during these months contributed mostly to successful campaign totals as opposed to failed or canceled totals. If someone wanted to increase their campaign's likelihood of success, they should choose to launch it towards the beginning or ideally during the middle of the year. 

The other conclusion that can be drawn from this analysis, is that Theater campaigns launched towards the end of the year, specifically in December, have much lower chance of being successful. Not only does the volume of kickstarter campaigns drop off beginning in May but this lower volume is mostly due to a decrease in the count of successful campaigns as failed and canceled counts remain relatively stable.

![Theater Outcomes Based on Launch Date](https://github.com/josem279/Kickstarter-Analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

**- What can you conclude about the Outcomes based on Goals?**

According to our analyis of Outcomes based on Goals, we can conclude that Kickstarter campaigns for plays have a higher likelihood of being successful if they set lower Goals. With the exception of Kickstarter campaigns that set goals between the ranges of $35,000 up to $44,999, Kickstarter campaigns lower their likelihood of success by every increase of $5000 in their goal. Alternatively, it can be said that as Kickstarter campaigns raise their Goals they are less likely to succeed and more likey to fail.

![Play Outcomes Based on Goals](https://github.com/josem279/Kickstarter-Analysis/blob/master/Resources/Outcomes_vs_Goals.png)

**- What are some limitations of this dataset?**

One of the limitations of this dataset is that it may have too much noise. By not filtering data by country, trends presented from this information may not necessarily be applicable to more refined/filtered data subsets. For instance, if we wanted to find out the Theater Goals based on Launch Date or the Outcomes based on Goals specifically for the U.S., there  would not be a need to include such a large sample size that includes information for other countries. In fact including these extra data points may be adding outliers and skewing analysis results. 
Furthermore, by including so much data the Outcomes based on Goals analyis does not operate by standardized units. For instance, the Pivot Tables and Charts do not differentiate between the different currencies used by each country. In order to get a more accurate analysis of successful Kickstarter campaigns for plays, we should first convert all monetary values into one currency so that they are comparable. 
Finally, I believe that the Analyses failed to use the most appropriate types of graphs. Although a line graph may be appropriate for the Outcomes based on Launch Date, by failing to distinguish years we are not accurately representing trends that may be seen by month. In the analysis conducted for the Outcomes based on Goals, a line graph may not be the most appropriate for representing the data in question. Typically, line graphs are better suited for representing data over time not by ranges. A bar chart may have been more appropriate for this visual representation of this data.

**- What are some other possible tables and/or graphs that we could create?**

Based on my previous observations, I believe that a bar chart should be created for the Outcomes based on Goals analysis to compare the percentage of succesful, failed, and canceled plays in each dollar range. For more accurate data representation, we should also include a table where all data points are operating under one currency or break out the data by country/currency.

Additionally, to give a better idea of Theater Outcomes Based on Launch Date to Louise, we should make use of the year filterin the existing Line graph or create line graphs for each year to more accurately represent the trends for Kickstarter campaigns over time. 
