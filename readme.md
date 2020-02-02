# Ford GoBike System Data
## by Hanin Lutfi Falatah


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. this reserch is in the time peroied from 06/2017 to 01/2018, There are 519700 rows and 13 column in the DataFrame, 8 of the 13 column are numerical data, some of the data should be timestap like start_time, and end_timeand the others like geographic points the longitude point and latitude point, and rented bikes id.

**the issues:**
- the start_date, end_date data type should be timestamp
- Convert the duration_sec from seconds to minutes and hours
- divide the start_time into two column as the start_date and start_time
- divide the end_time into two column as end_date and end_time
- use start_date, end_date to obtain the day and the month
- calculate the distance between the station


## Summary of Findings

> most of the trips are 8 mintues and the trips avrage is 4 to 16 Mintues. lowest month in ranting the bikes is June.

Customers:
78.7% of the user in the GOBIKE system,
the usege is mostly in September,Augest, and Octber
Customes the usege is mostly in the weekends, usege is mostly between 11AM - 5PM.
Weekend: the usege is mostly is at 8AM and 5PM in and the peek is Friday.
Weekdays: the usege is mostly is at 10AM - 5PM in the Weekend and sturday at 1PM - 2PM is the peek.

Subscriber:
21.3% the user in the GOBIKE system
the usege is mostly in the weekdays and usege is mostly at 8AM and 5PM.
the Subscribers,the usege is mostly in Octber,and November.
Weekend: the usege is mostly is at 8AM and 5PM in and the peek is Tuesday.

Weekdays: there are a big drop in the system usege comperied to the weekdays.


## Key Insights for Presentation

> the prestention is for the GoBike System which offer subscribtion services and one trip servics, i analysis the weekly  habirs of the users,and used a heatmap to show the high domand time on the bikes 
