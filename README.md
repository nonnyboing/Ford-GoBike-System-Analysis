# Ford GoBike System
## by Nonso Ukwuma


## Dataset

> This data set contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area over a certain period. The dataset contains over 183k records and has details of each ride such as the gender of the rider, the year of birth, destination, duration of trip, user type etc. Prior to exploration of the data, I had to change the data type of the member_birth_year column to a numeric data type from string. I also created a member_age and duration_hours columns to aid my exploratory data analysis. The member_gender column contained records for 'Other' which is not specific and hence all records of this anomaly was removed from the data as well other columns which will not be useful in my analysis such as 'start_time', 'end_time','start_station_id', 'end_station_id', 'end_station_latitude', 'start_station_latitude', 'start_station_longitude', 'end_station_longitude'.


## Summary of Findings

> I discovered that the bike share service had a very large number of subscribers when compared to users who are just customers without subscription. Also, the bike share service had more male users than female users and majority of these users fall between the ages of 21 and 43. Further, even though bike share service had majority of their users as subscribers, just about 10% of the users utilize the bike share service while 90% do not. Finally, more of the younger users aged 30 or below were found to use the bike share service for all trips while the majority of the users who did not use the service for all trips were aged between 31 and 41 years. These findings will be communicated in my presentation.



## Key Insights for Presentation

> The main point of my presentation will be to show the relationship between the bike share for all trips user segment and the member age, member gender and user type. The relationships between these 3 categorical variables and 1 numeric variable will be used to establish the characteristics of the bike share users who either use the bike share service for all trips or those that do not use the servcie for all trip. I used mostly boxplots and countplots to showcase the relationships between my main features. 
