# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project was to provide Louise with a detailed look at the success 
rates of different kickstarter campaigns with relation to their launch dates and funding 
goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To address Louise's first question, "How well do Kickstarter campaigns do in relation to their launch date?",  
a Pivot Table and Pivot Chart were created filtering out data by the Theater Category and only looking at
Kickstarter campaigns which met one of three outcomes: succesful, failed, or canceled. 

### Analysis of Outcomes Based on Goals

As for the second inquiry that Louise had, "How do different Kickstarter campaigns fare with relation to their 
funding goals?", we analyzed subset of data consisting of the number of successful, failed, and cancelled projects
 grouped by dollar amount ranges up to $50,000. After getting the number of campaigns that fell within each
group, we were then able to calculate the percentage that succeeded, failed or were canceled respectively. 
Furthermore, this subset of data allowed us to create a visual representation of the data in a line graph that highlighed
which campaigns based on goals succeeded the most by the dollar range.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	One of the concluseions that can be drawn from on our analysis of the Outcomes based on Launch Date, is that
there are more successful Theater campaigns are launched in the months of May and June. Conversely, it can also be said
that there are fewer succesful Theater campaigns launced towards the end of the year - specifically in December. This 
means that if someone wanted to increase their campaign's likelihood of success, they should choose to launch it towards the
middle of the year and avoid launching it towards the later months of the year (September-December).
	The other conclusion that can be drawn is that overall Theater campaigns have a much higer success rate than 
a failure or canceled rate. Generally, there is always a significant difference between succesful and failed campaigns. This
difference is largest in the Summer months of May and June and smallest near the end of the year - practically no difference
in the month of December. This not only reinforces the first conclusion regarding campaign launch timing but also highlights
that Theater based Kickstarter campaigns tend to be more likely to be successful than fail or be canceled.

- What can you conclude about the Outcomes based on Goals?

	According to the analyis of the Oucomes based on Goals, we can conclude that Kickstarter campaigns for plays tend to 
be less successful the higher they base their goals, with the exception of Kickstarter campaigns that set goals between
the ranges of $35,000 up to $44,999. Alternatively, it can be said that if we wanted to have a higher chance for a Kickstarter
campaign for plays to succeed is for the campaign to set their goals within the lower ranges.

- What are some limitations of this dataset?

	Some possible limitations of this dataset are that the Kickstarter campaigns were not filtered by country, so trends that may
have been observed in this population may not necessarily be applicable to more refined/filtered data subsets. For instance, 
if we wanted to find out the Theater Goals based on Launch Date or the Outcomes based on Goals specifically for the U.S., there 
would not be a need to include such a large sample size that includes information for other countries. In fact including these extra
data points may be adding outliers.
	Furtheremore because we include so many countries, the Outcomes based on Goals analyis does not take into account that different 
currencies are used by each country. In order to get a more accurate analysis of successful Kickstarter campaigns for plays, 
we should first convert all monetary values into one currency so that they are comparable.
	Finally, I believe that the type of chart used for the Outcomes based on Goals analysis may not be the most appropriate
for representing the data in question. Typically, line graphs are better suited for representing data over time not by ranges. A 
bar chart may have been more appropriate for this visual representation of the data.

- What are some other possible tables and/or graphs that we could create?

	I believe that a bar chart should be created for the Outcomes based on Goals analysis to compare the percentage of succesful,
failed, and canceled plays in each dollar range. Additionally, to give a better idea of Theater Outcomes Based on Launch Date to Louise,
we should break out the existing Line graph by country as this may address the currency problem and may show underlying trends specific to
some countries that may not be applicable to all Kickstarter theater campaings.
