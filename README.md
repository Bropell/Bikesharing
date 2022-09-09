# Bikesharing
## Overview
The purpose of this analysis was to inspect NYC Citibike data to convince
investors that a similar system could be established in Des Moines Iowa 
with success. The challenge specifically focuses on generating a story from 
visualizations created to explain the findings. The story link is attached
below and screenshots of the individual plots are shown in the results section.

[Tableau Story](link goes here "CitiBike Story")

## Results
There are seven different visualizations provided below that appear in order
as seen in the story. The first image shows the checkout times for users. It 
is easy to see that most of the travel durations for the users occurs around
6 minutes and almost none are longer than an hour. 

![alt text](https://github.com/Bropell/Bikesharing/blob/main/Images/Checkout_Times_for_Users.png)

The second visualization shows checkout times by gender. This is a buildoff
of the last one in that separate plots are generated and can be filtered 
by gender. The filter legend shows which plot is which. The data shows the 
same trend as before with most travel occuring around 6 minutes and almost
none after an hour. The added take away here is that mostly males are taking
the bikes out.

![alt text](https://github.com/Bropell/Bikesharing/blob/main/Images/Checkout_Times_by_Gender.png)

The third visualization shows the trips by weekday for each hour as a heatmap. 
The time of day is being compared to the starttime of the trip on a 12-hour time
scale. The darker areas show a higher count of bikes. According to this, around
6 pm on Thursday has the highest count of starttimes where there's a general low
between 1am and 4am.

<p align="center">
    <img src= "https://github.com/Bropell/Bikesharing/blob/main/Images/Trips_by_Weekday_for_Each_Hour.png"/>
</p>

The fourth visualization is another heatmap that shows the trips by gender for 
weekday per hour. This plot shows a similar trend to the last heatmap but with
three maps separated by gender. The heatmap for the males shows a higher concentration
of trips than other genders, around the same times which coincides with the results
from the second visualization based on gender. 

![alt text](https://github.com/Bropell/Bikesharing/blob/main/Images/Trips_by_Gender_Weekday_per_Hour.png)

The fifth visualization is another heatmap that shows the user trips by gender 
by weekday. This plot separates the trips by gender into two categories, 
customer and subscriber. Again, it is easy to see that the majority of the trips
are done by male subscribers whereas the least trips are done by the unknown 
category throughout the week.

<p align="center">
    <img src= "https://github.com/Bropell/Bikesharing/blob/main/Images/User_Trips_by_Gender_%20by_Weekday.png"/>
</p>

The sixth visualization shows the overall bike utilization as a circular scatter plot.
This is a very visually appealing plot that has varying point sizes based off the total
trip duration of each bike and varying color based off the trip count.

![alt text](https://github.com/Bropell/Bikesharing/blob/main/Images/Bike_Utilization.png)

The last visualization shows the likelihood of repairs for each bike in a heatmap
type format. The points are arranged from biggest and darkest in color, representing
the most used bike, to smallest and lightest in color, representing the least used bike.
Assuming the most used bike will be the first in need of repairs, bike 38124 seems to
be the first in line. 

![alt text](https://github.com/Bropell/Bikesharing/blob/main/Images/Bike_Repairs.png)

## Summary
There are several take away points here that can be extrapolated from the many different
visualizations. Looking at the first two visualizations together, as mentioned before the
vast majority of the users are males that have trip durations of about six to twenty
minutes. Perhaps all of the users making these trips, regardless of gender, use the bikes 
for their work commutes which just happen to be around a six to twenty minute ride. This 
also coincides with the results seen in visualizations three and four. The most popular 
trip times for all genders occurs around 8am and 5pm on weekdays which would be when people 
are commuting to and from work. The user trips by gender by weekday heatmap provides data
that agrees with that statement as well. People who would be using the bikes for commuting
would be more likely to be a subscriber and this heatmap shows a much higher use all week long,
and across all genders, in subscribers versus customers.<br><br>

Two additional visualizations can be suggested for future analysis and to further convince
investors that setting up a bike-sharing program in Iowa would be a success. One possible
visualization would be analyzing the location and/or availability of bikes in Iowa that 
match the same parameters in NYC. The program seems very successful where users can take
a bike for their work commutes because there is availability of bikes and their jobs are close
enough to make bike travel the most efficient way to get around. The second visualization
could be seeing which locations are the most popular in terms of use. In doing this, inactive
locations can be moved or the bikes from less popular locations can be swapped with the ones
that get a lot of use in order to spread out the potential repair costs.   