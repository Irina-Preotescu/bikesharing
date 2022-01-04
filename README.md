# bikesharing

## Overview of the Analysis

For this analysis, we used Python and Pandas to change the "tripduration" column data type from an integer to datetime. Then, using the converted "tripduration" column, we created several visualization portraying the most important findings.

The analysis is focused on the following, with the purpose of proving to investors that a bike-sharing program in Des Moines is a solid business proposal:

1. The length of time that bikes are checked out for all riders and genders
2. The number of bike trips for all riders and genders for each hour of each day of the week
3. The number of bike trips for each type of user and gender for each day of the week.



## Results


![Checkout times for users viz_fig1](https://github.com/Irina-Preotescu/bikesharing/blob/d988ce4ef177d8ccf36eb3b2cdbf2a92c6d6dd11/Checkout%20times%20for%20users%20viz_fig1.png)

Description: the length of time that bikes are checked out for all riders.



![Checkout times by gender viz_fig2](https://github.com/Irina-Preotescu/bikesharing/blob/a8bd34007a9b88e15aea43fc2b1fcad45fefbdad/Checkout%20times%20by%20gender%20viz_fig2.png)

Description: the length of time that bikes are checked out based on gender.



![Trip by Weekday per Hour_fig3](https://github.com/Irina-Preotescu/bikesharing/blob/a8bd34007a9b88e15aea43fc2b1fcad45fefbdad/Trip%20by%20Weekday%20per%20Hour_fig3.png)

Description: the number of bike rides by weekday for each hour of the day.



![Trips by Gender Weekday per Hour_fig5](https://github.com/Irina-Preotescu/bikesharing/blob/a8bd34007a9b88e15aea43fc2b1fcad45fefbdad/Trips%20by%20Gender%20Weekday%20per%20Hour_fig5.png)

Description: the number of bike rides by gender for each hour of each day of the week.
IMPORTANT NOTE: Due to the fact that I could not convert the Gender column and create a calculated field (because of the M1 chip), I could not get the right outcome for my heatmaps, even though I did all the correct steps. I was advised by the TAs to ignore that step and move forward and leave a note about it.


![User Trips by Gender by Weekday Viz_fig4](https://github.com/Irina-Preotescu/bikesharing/blob/a8bd34007a9b88e15aea43fc2b1fcad45fefbdad/User%20Trips%20by%20Gender%20by%20Weekday%20Viz_fig4.png)

Description: the number of bike rides by gender for each day of the week, by each type of user.
IMPORTANT NOTE: Due to the fact that I could not convert the Gender column and create a calculated field (because of the M1 chip), I could not get the right outcome for my heatmaps, even though I did all the correct steps. I was advised by the TAs to ignore that step and move forward and leave a note about it.


![fig1](https://github.com/Irina-Preotescu/bikesharing/blob/6227aadd98607795ee76d6f4eb25b1135c18fbde/fig1.png)

Description: the top starting locations for bike rides in NYC.



![fig2](https://github.com/Irina-Preotescu/bikesharing/blob/6227aadd98607795ee76d6f4eb25b1135c18fbde/fig2.png)

Description: the top stopping locations for bike rides in NYC.



![Screen Shot 2022-01-04 at 7.21.08 PM](https://github.com/Irina-Preotescu/bikesharing/blob/6227aadd98607795ee76d6f4eb25b1135c18fbde/Screen%20Shot%202022-01-04%20at%207.21.08%20PM.png)

Description: the level of bike utilization of each bike id, proportionate to the size of the bubbles.



## Summary


* It is clear that starting and ending stations are similar, which is to be expected.
* It is significant to note the large proportion of male customers who use Citi Bikes. The company might increase the number of customers by launching a marketing campaign targetting women of all ages. More research can be done regarding the potential reasons why women do not use the bike service as much as men.
* Most bike rides tend to be approximately 10 minutes, with a heavy decrease from that point onwards. However, women tend to have slightly longer bike rides, on average. 



![fig3](https://github.com/Irina-Preotescu/bikesharing/blob/fad6218ce7016072cb7db3ecdf25269aaa019822/fig3.png)

Given that the 7 AM to 10 AM period (with a peak at 8 AM) and the 4 PM to 8 PM period (with a peak at 6 PM) are the most popular for bike rides, the company should ensure that more locations have bikes available during that time, in additional locations, based on the top starting locations.



![fig4](https://github.com/Irina-Preotescu/bikesharing/blob/383645df9f592ebeb0d40883c913f97f92cee5a7/fig4.png)

Given that the 1 AM to 4 AM period is the least popular for bike rides, the company should aim to undertake bike maintenance operations during that time, in order to avoid a lack of supply during high-demand periods.
