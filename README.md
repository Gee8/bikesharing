# bikesharing
## Overview of the analysis: 
In this analysis we look at the CitiBike data from August 2019 to try to determine if a similar program can be set up outside of NYC. Using the CitiBike data, we formatted the trip duration column to a Datetime format using Pandas in Jupyter Notebook. After we had our updated data, we imported it into Tableau to create visualizations. These visualizations include: `Checkout Times for Users`, `Checkout Times by Gender`, `Trips by Weekday per Hour`, `Trips by Gender (Weekday per Hour)`, `User Trips by Gender by Weekday`, `August Peak Hours`, and `Top Starting Locations`. These are displayed in a Tableau story [here](https://public.tableau.com/app/profile/kyle.gee/viz/NYCCitiBikeStory_16238069468120/NYCCitibikeStory).

## Results: 
Shown below are each of the visualizations followed by a small summary.

<img width="400" alt="viz1" src="Images\Checkout Times for Users.png">

Shown above is the `Checkout Times for Users`. Within this chart we notice that most all trip durations are less than an hour long, with largest number of trips lasting 5 minutes.

<img width="400" alt="viz2" src="Images\Checkout Times by Gender.png">

Shown above is the `Checkout Times by Gender`. This chart is similar to the `Checkout Times for Users`, but breaks down the trips by gender. We are able to see the graph broken into three lines, Female, Male and Unknown. From here we can see that males make up a significant number of the rides, but regardless of gender, the trip duration seems to be unaffected by gender.

<img width="400" alt="viz3" src="Images\Trips by Weekday per Hour.png">

Shown above is the `Trips by Weekday per Hour`. In this vizualization we have a heatmap to display which times of the day for each day of the week there are trips. From this, we can see that 7-9 AM and 4-7 PM are very busy, while 11 PM - 6 AM there are very few trips being taken. This would be a good time to maintain and transport the bikes.

<img width="400" alt="viz4" src="Images\Trips by Gender (Weekday per Hour).png">

Shown above is the `Trips by Gender (Weekday per Hour)`. This heatmap is similar to the previous one, but broken down by gender. The same patterns hold in this, but we can again see that there are more males taking trips than females.

<img width="400" alt="viz5" src="Images\User Trips by Gender by Weekday.png">

Shown above is the `User Trips by Gender by Weekday`. This graph shows that for both males and females, the most trips are taken on Thursdays and Fridays, respectively.

<img width="400" alt="viz6" src="Images\August Peak Hours.png">

Shown above is the `August Peak Hours`. From this chart, we can see the number of trips for each hour of the day for each day of August. There are very few trips in the hours of 12 AM to 5 AM, and the most trips are in the hours of 4-6 PM. 

<img width="400" alt="viz7" src="Images\Top Starting Locations.png">

Shown above is the `Top Starting Locations`. From this, we can determine where the most popular areas users start a trip from are, and make sure that there are enough bikes in those locations. 


## Summary:
From the vizualizations, we can conclude that the vast majority of trips are short, with the most frequent duration being 5 minutes. From this we may be able to conclude that the bikes are not being used for pleasure, but more likely for quick transportation. We also know at which times of the day/week have high/low usage. We can plan to maintain and transport bikes during the times of low usage, and be certain there are enough bikes in the areas were there is a high demand for bikes. From the charts that were filtered by gender, we can see that while there are more males taking trips, the trends for usage are the same regardless of gender. For further analysis, we should consider creating vizualizations for the bike rides outside of Manhattan. This could tell us more about how viable a program similar to CitiBike would fare in a more rural area with less tourist traffic. We should create a chart to determine average trip duration by user type and another chart for number of trips by user type. This should be able to tell us if it would be worth the effort to try to increase the number of members, and how members and non-members are using the service in a rural area.

