# bikesharing

## Overview

The purpose of this analysis is to present data to support a business proposal for a new bike-sharing venture in Des Moines, Iowa. An angel investor is interested in providing seed funding, but first they need to be convinced of the viability of the business. Data collected from citibike, a bike-sharing program in New York City, is being used to glean insights on the business model and explore how a similar program could be executed in Iowa.

## Results

After cleaning data using Pandas, data was imported in Tableau and analzyed across various sheets and dashboards before being placed in the Tableau story below.

[link to dashboard](https://public.tableau.com/app/profile/sean3063/viz/CitiBikeChallenge_16236031764730/CitiBikePresentation "Link to dashboard")


The first story point showcases that a significant opportunity exists for a bike-sharing program in Des Moines if it can learn from citibike's success in New York City. More than 2 million trips were taken in NYC during the time period analyzed. An investment in roughly 14K bikes provided users all across the city with the option to explore "the Big Apple" on two wheels. 
![Opportunity](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Opportunity.png)

Citibike's most common users are male subscribers. Subscribers represt 4/5ths of the company's userbase.

![Users](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Users.png)

Trip starting and ending locations can be collected and analyzed to determine the best locations for our bikes. As an example, a significant number of New York trips occur in Manhattan, south of Central Park. 

![Starting & Stopping Locations](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Starting%20%26%20Stopping%20Locations.png)

A vast majority of  trips in NYC are under 30 minutes in length. This metric is likely strongly impacted by the density of New York City. However, one can assume that trip durations in downtown Des Moines will follow a similar trend. 

![Trip Duration](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Trip%20Duration%20by%20Gender.png)

Gender was also analyzed to gauge its impact on trip duration. No significant differences were noted. 

![Trip Duration by Gender](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Trip%20Duration.png)

The busiest times of day coincided with morning and evening rush hours during the work week and between 10 AM - 7 PM on Saturdays.

![Trips per Weekday per Hour](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Trips%20per%20Weekday%20(per%20Hour).png)

Gender was analyzed once again for its impact on popular trip times. Men and women followed similar usage patterns for trips by weekday per hour.

![Trips by Gender Weekday per Hour](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

Lastly, the number of bike trips by gender for each hour of each day of the week was also analyzed across customer types. Customers with an unknown gender are most frequenly riding on Saturdays and Sundays. Among days of the typical work week, male & female subcribers are least likely to take a bike trip on Wednesdays. 

![User Trips by Gender by Weekday](https://github.com/tysonseang/bikesharing/blob/main/Story%20images/User%20Trips%20by%20Gender%20by%20Weekday.png)

## Summary
Overall, citibike has a strong business that has provided more than 2 million rides during the time period analyzed. The business has a large subscription pool of users that covers more than 80% of its customer base, indicating long-term, repeat interest by its riders. Its customer base in largely male, and a majority of trips are under 30 minutes in length. Riders are also most likely to access the service during typical commuting hours during the workweek and throughout the day on Saturdays.

Further analysis can be conducted on station locations and citibike's typical customers/subscribers. The following visualziations are suggested:

- In addition to a worksheet that maps out ride count by location, a bar chart on the same dashboard that shows the Station ID sorted by ride count would be useful. This list could be used to determine the necessary inventory levels at each station in order to better serve the most popular locations. 

- Secondly, an analysis of ride counts by customer/subscriber birth years would provide additional customer insights for targeted marketing campaigns. 






