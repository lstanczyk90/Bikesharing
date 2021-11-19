# Citi Bike Anlaysis

## Summary and Purpose

[Link to Tableau Story](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/CitiBikeAnalysis#1)

The overall purpose of this project is to support the viability of operating a bike sharing program in Des Moines, Iowa by utilizing publically available data for the most successful bike sharing program in the USA, namely New York's Citi Bike program. TO support certain conclusions and our analyses, we utilized Tableau to craft meaningful and interactive visualizations to make the data come to life.

## Results

Our analysis yielded the following:

### Checkout Time for Users:

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Checkout%20Time%20for%20Users.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/CheckoutTimeforUsers)

Per the above visualization, we noted the following key takeaways:

- It is clear that the vast majority of trips are under one hour. 
- In fact, trip duration peaks at 5 minutes.
- As demonstrated in another Viz, this might further be evidence of the success of the subscription model, as users with subscriptions may feel more justified in using the bikes with greater frequency and for shorter durations.

### Checkout Times by Gender

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Checkout%20Times%20by%20Gender.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/CheckoutTimesbyGender#1)

Per the above visualization, we noted the following key takeaways:

- The trends are fairly similar to the ones identifeid in the "Checkout Time for Users" viz, with no notable differences between genders insofar as peak usage time.
- However, it is very clear that the male population sees much greater usage. As such, marketing of the program should be targeted at the male demographic during our pilot launch in Des Moines.

### Trips by Weekday Per Hour

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Trips%20by%20Weekday%20per%20Hour.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/TripsbyWeekdayperHour#2)

Per the above visualization, we noted the following key takeaways:

- Perhaps unsurprisingly, this Viz demonstrates that Citi Bike is very popular during regular commute times during the work week (i.e around 9AM and 5PM).
- On weekends, the bikes have greater consistent usage throughout the entire day, suggesting tourism is a driving force.

### Trips by Gender (per Weekday per Hour)

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/TripsbyGenderWeekdayperHour#3)

Per the above visualization, we noted the following key takeaways:

- As with other male and female comparisons throughout this analysis, we noted no notable differences between males and females with regards to usage patterns.
- However, males tend to utilize the service more than females (as noted throughout our analysis).

### User Trips by Gender by Weekday

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/User%20Trips%20by%20Gender%20by%20Weekday.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/UserTripsbyGenderbyWeekday#4)

Per the above visualization, we noted the following key takeaways:

- Male subscribers are the biggest user group (as supported throughout the analysis). 
- A subscription service makes sense because it ensures a consistent revenue stream and proves popular with end-users.
- Workdays remain slightly more popular than weekends, further supporting that many use the bike sharing service for their commutes.

### Top Starting Locations

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Top%20Starting%20Locations.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/TopStartingLocations#5)

Per the above visualization, we noted the following key takeaways:

- The map suggests that Citi Bike is most widely used in tourist-heavy destinations (like midtown and Times Square), but also in the financial distrinct (perhaps for commuting).

### Customers

![alt text](https://github.com/lstanczyk90/Bikesharing/blob/94739e8e6ad571094f85f2d08888fa8b2c4305a6/Visualizations/Customers.png)
[Link to Worksheet](https://public.tableau.com/app/profile/lukasz.stanczyk/viz/CitiBike_Challenge_16372808837040/Customers#6)

Per the above visualization, we noted the following key takeaways:

- As noted previously, this viz further supports the need for a subscription service.

## Conclusion

Our overall analysis yielded the following takeaways:

- A subscription service is a must, as it provides a constant revenue stream and proves popular with end-users.
- Although it is popular with all groups, special care should be taken to advertise to the male population, as they provde to be the largest population of end-users.
- The program should be targeted at both tourism-heavy areas, as well as commercial/industrial/workplace areas. It is popular both as a method of commuting and site-seeing.

Additionally, for future reference, we suggest the following additional visualizations:

- Start vs. End Station: It may be helpful to visualize whether most bikes are returned to their starting stations, or to difference ending stations. This can be plotted using the respective start and end station IDs. This will demonstrate to us valuable information about consumer usage patterns.

- Usage by Birthyear: We can plot age (by creating a calculated field on birth year) against usage count to see whether the program is more popular within certain age groups, as this may influence advertising goals and targets. 