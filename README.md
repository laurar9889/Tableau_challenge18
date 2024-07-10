# Tableau_challenge18
New York Citi bike analysis 
Data taken from citi bike website. https://citibikenyc.com/system-data. 
Most of the analysis performed with Dec 2023 dataset.

## Unexpected phenomena
1. Number of bikes in Dec 2023 versus Dec 2022. 
-	96% increase in Dec 2023 in total classic bikes, compared to Dec 2022
-	73% increase in Dec 2023 in total electric bikes, compared to Dec 2022
Classic bikes dynamic:
-	In Dec 2022, the total classic bikes were 39,000 units. Similarly, the number of rides recorded during the month were also 39,000 trips. 100% utilization of total capacity. (see total_membership_Dec22)
-	On the contrary, Dec 2023 total classic bikes were 965,000 units, with a utilization of 6% of their total capacity (55,000 trips). (see total_membership_De23)
Electric bikes dynamic:
-	In Dec 2022, the total electric bikes were 9,500 units. Similarly, the number of rides recorded during the month were about 10,000 trips, with a 105% of utilization of total capacity. (see total_membership_Dec22)
-	On the contrary, Dec 2023 total electric bikes were 35,000 units, with a utilization of 8% of their total capacity (3,000 trips). (see total_membership_De23)
-	
Conclusions: 
The percentage of increase in classic bikes is very ambitious. Assuming that December is a slow month due to the season, there is still a good chance that the total utilization of the float does not justify the investment on the assets. Even when the number of rides increases exponentially during summer months, I suggest reconsidering the optimal classic bike capacity to maximize revenue. More classic bike availability also means more maintenance cost per bike, more parking stations, and idle investment.
A similar scenario can be observed in electric bikes. Users preference is classic bike when they become available. In Dec 2022, the total number of electric bike rides went up to 10,000 which is mainly due to lack of classic bike availability. However, having the option, users prefer to ride a classic bike.
I propose a revision on the marketing campaign, as well as pricing campaigns. How can New York city incentives the usage of bikes? Is there a need of more bike paths in certain parts of the city? Is there any other neighborhood that is worthwhile to be explored to increase the number of stations there?

## Unexpected phenomena
2.	Trip time analysis and their final bike station destination. Which ones are the most popular stations according to the trip times?
The most popular trip length in December is 0-5 minutes. The users with membership are the taking the citibike service to commute on a regular basis. As shown in the map, the most popular bike stations (by number of trips) are located in Jersey City and the downtown, predominantly, in bike stations near train stations. (see trip_time_range_Dec23 and end_station_mostly_used) (*)
The longest trip times recorder in December 2023 had final destinations in turistic places and medical centers. The data shows that casual members have similar number of bike rides than users with a membership, when it comes to trips longer than 16 minutes. In fact, in trips greater than 46 minutes duration, casual members had more number of rides recorded. (see membership_longest_ride) 
Conclusion: There is a potential to continue exploring options for tourism while biking, in order to increase the percentage of utilization.

(*) The dataset to visualize all stations in the map was not supported by Tableau public free version. Therefore, I only show the stations with more than 1,000 trips in December 2023.



