# Ford gobike
## by Mohamed Momen


## Dataset

The dataset I used in my investigation is Ford Gobike dataset for April 2019
the dataset consists of of 239111 records of duration by seconds, user type (customer - subscriber) , time of the trip and gegraphical location and start and end time
The data wrangling I  made were 
1- convert start and end time to time format
2- Extract the day of the week from the start and end time and add them to dataframe as columns
3- Extract the hour of the day from starting and end timme and add them to dataframe as columns


## Summary of Findings

1- Trips' duration in the dataset take on a very large range of values, from about 1 minute at the lowest, to near 24 hours at the highest and with average 12.8 minute. Plotted on a logarithmic scale, the distribution of trip duration in minutes takes on a multimodal shape squeezed to the lift.
2- Almost 85% of the users are subscriper users.
3- The number of trips on weekdays is greater than on weekends and reaching the maximum on tuesday.
4- Although the number of trips decreases in weekends the average time of the trip increases.
5- On average the subscriper users rent bikes for shorter time duration than the customer on log scale.
6- It is clear that in the weekends (Sundays and Saturdays) average duration in minutes increses from 10:00 till 18:00 over the other days in the same period of time.
7- It is also clear that in the along a day there are different pattern of duration in minutes increses see time priod between 04:00 to 05:00.

## Key Insights for Presentation

-The user type and day of the week have strong relation with the number of trips
-The starting hour and day of the week have strong relation with the average rental duration time.
