# Kickstarting with Excel

## Overview of Project

### Purpose
The Kickstarter data set provides data for various types of entertainment including Kickstart goals, pledge amounts, launch dates, backers, and specific types of entertainment. This data set was utilized to inform proactive decision making around, our client, Louise's, theater production and to gauge the outcome of her performance against other similar productions. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The graph below depicts the outcomes of theater Kickstarter campaigns by month of the year. The number of successful campaings is shown by the blue line and has the widest range of in outcomes, from 37 to 111 successful performances depending on the month. Failed campaigns, shown in orange, remain in a much shorter range, from 33 failed campaigns to 50 failed campaigns depending on the month. Canceled campaigns remains consistently much lower and constant than both successful and failed campaigns with results showing less than 7 failed campaigns each month (depicted in gray).
ADD IMAGE HERE

### Analysis of Outcomes Based on Goals
The graph below depicts the outcomes of play campaigns based on their fundraising goals. This is shown as a percentage of the total. There are a few quantitative outcomes based on this data: 
- There were no cancelled plays for any goal range, so the percentage of plays that were canceled at any goal range remains 0%. 
- The percentage of successful plays declines as fundraising goals increase, except for the range from $35,000 to $45,000. There is also a small uptick from 0% to 13% from $45,000-$50,000 to $50,000+. However, it is important to point out the ranges where there was an uptick in successful campaigns had far few campaigns than ranges at a lower goal (<$24,999).
- Because the percentage of cancelled plays is 0% at all goal ranges, the percentage of failed plays follows the inverse of successful plays. That is to say that the percentage of failed plays increases as fundraising goals increase except for the fundraising goal ranges listed in the previous bullet point.
ADD IMAGE HERE  

### Challenges and Difficulties Encountered
There are a few challenges with the specifity of the data that could have been mitigated given more information about Louise's play, **Fever**, or more specific analysis of the Kickstarter data set. Without being given the specific date of Louise's launch or her fundraising goals, we cannot draw a full conclusion about whether her specific data points fell in line with what we would expect based on trends. For example, we do not know when she launched her play or her fundraising goal.

Additionally, we were not specific enough within our data given a few pieces of information. For example, we filtered the data for "Outcomes Based on Goals" for subcategory: plays. However, we only filtered the "Outcomes Based on Launch Date" by the parent category: theater. This gives us some noise in the data because other types of theater outside of plays is included.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

When deciding on a launch date for a theater performance, it is best to choose a summer date based on our Kickstarter data. This is true because there is the greatest difference between successful and failed campaigns between May, June, and July. It would be the least likely to launch a successful campaign in late fall/early winter (October, November, December, and January) because there is the least difference in the number of successful and failed campaigns.  

Launching in the summer also seems to be popular among those running theater campaigns because May, June, and July also have the highest number of launched campaigns according to our Kickstarter Data. 

Lastly, there are very few cancelled campaigns (4 or less in every month except January), but January does show our highest spick in cancelled campaigns with 7 cancelled campaigns. This is in line with our previous recommendation of avoiding launch in late fall/early winter months due to the decreased percentage of successful campaigns. 

- What can you conclude about the Outcomes based on Goals? 

As a general trend, the percentage of successful plays decreases as the fundraising goal increases and vice versa for the percentage of failed campaigns (given that canceled campiagns are constant at 0%). This means, that it would be best to launch a play with a more conservative fundraising goal to increase the propability that the campaign would be successful. There are a few ranges of fundraising goals for with this is not true ($35,000-$45,000 and $50,000+). However, these ranges have far less campaigns than other lower campaign goal ranges (<$24,999)

- What are some limitations of this dataset? 

A few limitations of the data set include our utilization of statistical analysis on the data set and a lack of specificity in our analysis based on both known and unknown conditions. Using a box and whisker play of our play goals would help us to identify outliers and ensure that they are relevant parts of the dataset. We also could more accurately identify skew to make a more informed decision about the most successful goal pricepoint. Our analysis could have also been more specific based on variables we know, like the subcategory vs. the parent category for our Launch Date analysis, and variables we do not know, like the year that the Louise's play was launched or her fundraising goals. 

- What are some other possible tables and/or graphs that we could create? 

One simple way to improve our data analysis would be to include statistical analysis for plays including mean, median, IQR, and standard deviation for our Outcomes Based on Goals. It would also be pertinent to include a box and whisker plot of this data. All of this analysis would help us to identify skew and outliers and would give Louise more information about launching **Fever** and any future plays.  
