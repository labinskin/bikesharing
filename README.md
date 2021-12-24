## Background

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Check%20Times%20for%20Users.png)

The highest number of trips, 146, 752, lasted only five minutes. This indicates that a majority of our users use the biks for quick trips around town.

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Checkout%20Times%20by%20Gender.png)

Male, female, and unknown genders, all follow a similar pattern for duration, using our bikes for quick trips. But male riders use the service at much higher rates.

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Trips%20by%20Weekday%20for%20Each%20Hour.png)

Highlighted here are all the times over 15,000 of our bikes are out. As you can see the darkest colors during the week are around 8 AM and 5/6 PM, times when people are commuting from work. While during the weekend, during the daytime hours are our bikes the most popular. The weekday data indicates our bikes are used for commuting to and from work.

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Trips%20by%20Gender.png)

Comparisons between male and female correlate with the previous charts for time and gender use, re-emphasizing males typically use our bikes more often, especially for times typically used for commuting to and from work. Females use bikes then too, but at less intense rates, especially on Wednesdays. Males also use them an hour earlier in the morning, and an hour earlier and later in the evenings than females.

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Trips%20by%20Gender%20by%20Weekday.png)

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Number%20of%20Males.png)

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Number%20of%20Females.png)

This first chart supports our previous findings that our most likely user is male. Additionally, our heaviest subscribers are male; they also use our service every day of the week. Female users are moderate subscribers, with use on all of the days, except Sunday and Wednesday being lighter days. In total, as the second chart shows, we have 1,530,272 male users in the month of August and 588,431 female users in August.

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Top%20Starting%20Locations.png)

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Top%20Ending%20Locations.png)

This first chart shows the beginning locations for the bikes. The second one shows the ending locations for the bikes.

## Summary

