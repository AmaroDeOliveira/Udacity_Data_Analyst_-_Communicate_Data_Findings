# Communicate Data Findings - Flight Arrival and Departure Data Exploration
## by Lucas Amaro de Oliveira

Project to Udacity in partial fulfillment of the requirements for the Danalyst Nanodegree.

## Table of Contents

* [Investigation Overview](#Investigation-Overview)
* [Dataset Overview](#Dataset-Overview)
* [Summary of Findings](#Summary-of-Findings)
* [Key Insights for Presentation](Key-Insights-for-Presentation)

## Investigation Overview

In this investigation, I am interested in finding out which characteristics have the most influence on flight delay and cancellation. The main focus is the time parameters: Month, day of the week, time of the day; the carrier; The aircraft tail number; and the flight distance.

## Dataset Overview

This data is part of "Data Expo 2009: Airline on time data" form American Statistical Association (ASA) Statistical Computing Dataverse. The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. In this project, only the year 2007 is used. The oririnal data is avaible from [ASA](http://stat-computing.org/dataexpo/2009/the-data.html) and [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7). The data comes originally from [RITA](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp).
In the year 2007, there are 7453215 flights in the dataset with 29 features.


## Summary of Findings

The number of flights is evenly distributed over the months. Look at the day of the week, the number of flights is also evenly distributed during workdays. At the weekends there is a small decrease in the flight counts. During workhours the flights are more or less evenly distributed. In the schedule, ther is some peaks and vallies that are smoothed out in the actual departure and arrival data. Furthermore, there are much more flights between 0h and 3h in the actual arrival data than in the schedule data. This indicates that the schedule was quite optimistic.

Carriers was the most responsible for the delays. However, the weather is very close.

December has the highest proportion of delayed flights. June to August has also a high proportion of delayed flights.
Monday has a high proportion of the delayed flights. Tuesday presented a less proportion of delays which builds up until Friday. Saturday has the lowest proportion of delays, as is also the least busy day of the week. Sunday, despite bean less bused than the weekdays, has a high proportion of delays.
As the busy time starts at 6h, the delays starts to build up util 21h. At this time, the delays proportion starts to decrease.


## Key Insights for Presentation

Although the number of flights is evenly distributed over the month, the proportion of delayed or cancelled flights are not. December has the highest proportion of delayed or cancelled flights, probably due to holidays. The summer months (June to August) also have a high proportion. The proportion in December is almost twice as in September.

From 3:00 to 9:00 is the best time to fly since this period presents no more than 20% of delayed or cancelled flights. Next is between 9:00 and 12:00 and on Saturday with 26% or less cancelled or delayed flights. On Thursday and Friday between 18:00 and 21:00 we have the impressive value of 41% of cancellations or delays. It is definitely not a good time if we want to fly without these inconveniences.