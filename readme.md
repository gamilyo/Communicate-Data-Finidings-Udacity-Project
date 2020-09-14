# Aug 2020 Bay Wheels Ride Exploratory Data Analysis
## by Abdulrahman Gamil Ali


## Dataset

> The system was originally launched as Bay Area Bike Share in August 2013. At launch, it became the first regional bicycle sharing system deployed on the West Coast of the United States and also the first regional system in the U.S. that services more than just a single city or adjacent cities. The original system was described as a pilot program and consisted of only 700 bicycles with 70 stations, 34 of which were in San Francisco. The program's original administrator was the Bay Area Air Quality Management District, which handed off the public management of the system to the Metropolitan Transportation Commission in 2016. The launch system was funded with $ 11.2 million of public funds from a variety of sources, including from the MTC and Air District. 


## Summary of Findings

> The Dataset Contains 13 Column describing the location of the start and the end and the time of the start and the end of the ride also it contains 152446 entries for Aug 2020 rides
>* we can extract a feature which is the difference in time, of the ride start and end (trip duration)
>* compare trip duration with rideable_type and member_casual
>* extract the approximated distance for long-lat and explore its relationship with other variables
>* i would like to investigate the correlation between the distance and the trip duration, also the rideable type and the trip duration relationship
> * both the distance and the trip duration are right skewed distributions, and they both have an outliers i guess there might be a positive corrleation between those two variables, 
* i am curious to investigate if there are relationship between the day of week and the hour of day also the trip duration and the day of week.
* there is 9833 rides where the start station is the same as the end station
>* the distribution of the ecludian distance was in a small scale as it depends on the long-lat data so i filtered the outliers also multiplied by 1000 to have a better visualization,
the Trip Duration distribution too, i filtered the outliers there was no need to change the scale.
* most of the trip start hours within 4 am to 6 am with peak at 5 am
* few trips starts at the middle of the night 

## Key Insights for Presentation

> * There are Three Main Region Where the rides take place
* Members Tend to finish faster than Casual Riders In all days of Weeks
* There is a Positive Correlation Between Distance and Trip Duration.
* The Ecludian distance might be zero this means that the start and the end are in the same station 