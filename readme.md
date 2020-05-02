# Ford GoBike Dataset

## Dataset

The data consists of information regarding 2,50,6983 ride data from Ford GoBike Bike renting service. The attributes included duration_sec, start_time, end_time, start_station_id, end_station_id, start_station_name, end_station_name, bike_id, user_type, month, day, and hour details. 


## Summary of Findings

In the exploration, I found the following thing  

- Most of the users are subscribers.
- Ridership is has increases form June 2017 to October 2017 and then decreases on followng months November, December.
- Ridership is almost constant on weekdays (Mon-Fri) then decreses on weekends. Also, ridership is highest on 8:00 and 17:00, suggests that users are office commuters.
- San Francisco Caltrain (Townsend St at 4th St) is station with highest deficit on no. of bikes. That is more no. of bikes given then no. of bikes deposited.
- starting_station and ending_station are highly related. This means that the users are chosing same set of starting and ending stations.
- Customer uses the bike for more duration on average than Subscribers.
- The no. of rides by customer increases as the no. of rides by subscribers decreases. At 14:00 the subscribers ridership is min (local) while the customer ridership is at maximum.
- On weekdays ridership increased at 8:00, and 17:00 while on weekends the ridership increases between 11:00 to 15:00
- At weekends ridership increases at night.
- The no. of office commuters increased form July, to August drastically.


## Key Insights for Presentation

For the presentation, At the start I introducded with the User type and its
distribution.Later, I explained the effect of user decisions on day wise and hour wise
ridership details. Also, how the rides are distributed day wise and hour wise.

I also introducted the ride duration distributon with respect to other categorical variables. Then I high
lighted between the relation of starting station and ending station. And at last highlighted the traffic at stations
on weekdays vs weekends.  

## Slides
Access the slides by running the following command on terminal
```
jupyter nbconvert slide_deck.ipynb --to slides --post serve --template output_toggle
```