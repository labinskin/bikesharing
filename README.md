## Background

Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results

![](https://github.com/labinskin/bikesharing/blob/main/Resources/Check%20Times%20for%20Users.png)

The highest number of trips, 146, 752, lasted only five minutes. This indicates that a majority of our users use the bikes for quick trips around town.

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

This first chart shows the beginning locations for the bikes. The second one shows the ending locations for the bikes. The majority of trips both started and ended in Manhattan, NY. This would correlate with our average trip data (highest being 5 minutes, but most trips being only a few minutes long). This would suggest that most bikers use these bikes for quick commutes.
## Summary
Overall, the data suggests that our bikes are used for short commutes and end up a short distance from their starting location. This would suggest that Des Moines would be a good place to expand to because it is a city location, where users could use bikes to commute short distances within the city. Like New York, they could bike for their daily commute or they could bike around downtown areas for entertainment and enjoyment (like shopping or eating at restaurants). According to the US Census Bureau, Des Moines has a breakdown of 50.7% female and 49.3% male. This is actually a higher percentage of males than New York City (52.3% female and 47.7% male). Since our data above shows that men are more likely to ride bikes, at a much higher percentage, it would indicate that the overall percent of the population would be more predisposed to ride a bike (noted caveat that there are more people in New York than Des Moines, but if we scaled the number of bikes to Des Moines size, they might get more use).

As for future visualizations, we have worked on age data, as this would be critical in helping us understand who uses bikes. Unfortunately, some of the data indicates that birth years stretch back to the 1890's, which would be highly unlikely. This probably comes from users inputting any age, so they can use the bike. We would need to gather and clean more data on age, ensuring our data is correct. But data analysis of age, gender, and usage would be very important in understanding where to expand--finding cities and communities that match high usage areas would be useful in figuring out where to expand our presence. We could also use the start/stop time, along with the starting/ending location data to figure out how riders use our bikes, along with Bike ID. This would allow us to track routes, figure out which stations might be used most often and when, and when combined with other data on age and gender, we would have a fairly complete understanding of our riders.
