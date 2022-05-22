# Exploring "Fordgobike" data
## by Mostafa Mohamed Mohamed Imam


## Dataset

> the dataset provides info about trips made by ford go bike's users such as duration, birth year, start and stop stations with ids and coordinates for each station for each trip as well as the start time of each trip from year to minutes and seconds. 

the dataset had 183412 rows before cleaning and 174952 rows after cleaning and 16 columns
  - the dataset offers the following info about bike trips:
      -  duration_sec : duration of the trip in seconds
      -  start_time : starting time of the trip in from year to second
      -  end_time : ending time of the trip in from year to second
      -  start_station_id : id of the start station
      -  start_station_name : name of the start station
      -  start_station_latitude  : latitude coordinates of the start station
      -  start_station_longitude : longitude coordinates of the start station
      -  end_station_id : id of the end station
      -  end_station_name : name of the end station
      -  end_station_latitude : latitude coordinates of the end station
      -  end_station_longitude	: longitude coordinates of the end station
      -  bike_id : id of the bike in the recorded trip
      -  user_type : type of user (subscriber or customer)
      -  member_birth_year : birth year of the member who made the recorded trip
      -  member_gender : gander of the member
      -  bike_share_for_all_trip : yes or no status of it the trip was a "bike share for all trip"



## Summary of Findings

- it was found that :
    - 90.5% of users are subscribers and 9.5% customers
    - 74.6% of users are males, 23.3% females and 2.1% other
    - most trips were made during the middle of the week (thurs, tue)
    - most users are between 20 and 40 years old
    - subscriber users generally made more longer duration rides across genders
    - the longer duration rides were made on weekend days (sat, sun)
    - the longest rides with the most variability on average were made by users under 20 and users over 70 
    


## Key Insights for Presentation

> it was shown that most trips were made during the middle of the week and are generally shorter than those made in the end of the week which combined with most of the users being between 20 and 40 may suggest that shorter trips are made for commute or other shorter time purposes on the middle of the week with lack of time and by looking at trip duration stats across weekdays and ages the effect of time and job nature becomes more clear on trips because it can be clearly noticed that ages under 20 make the longest duration trips in general and especially on weekends with most variability in durations in these days and also people older than 70 make long duration trips with significant variability during weekends, which shows a theme that most ages that have less time and more busy days have generally shorter trips with less variability between trip durations and ages that are younger than 20 or older than 70 or even 60 make some of longer trips and have greater variability between trip duration which may state variability of purposes suggested by more free time than the other age groups.