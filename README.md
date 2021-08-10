# (Ford Go-bike system data)
## by (Khaled Yaseen)


## Dataset

> I used data from Ford Go-bike system Dataset to be analyzed and explored, this data icludes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
This data set contains information about 183,000 rides collected from bike-sharing system, including 16 different variables like ride duration, start & end times for each trib , location for start & end stations , gender , member birth year and and other atrractive information to be explored .


## After loading data from CSV file of Ford Go-bike system Dataset, i started assessing data visually and programatically to be cleaned and I found some limitations i need to handle it before starting analysis ,for instance: 

- convert duration_sec to duration minutes to be more readable.
- convert start & end time to date time
- convert all ids to object
- make new column to start and end stations location
- convert user type category
- convert birth year to object
- convert gender to category
- convert bike_share_for_all_trip to category
- convert birthday year less than 1919 and it coeesponding gender to Nan.
- rearrange columns.
- make new column for the user age.
- i didn't drop or change the data with Nan value for start and end stations name and id because all other data are existed.
- the data of gender and birth year for about 8265 rides are dropped from the source CSV file but i decided to accept it.


## Summary of Findings

 1 : The most number of trips occurs on thrusday with percentage of 19.2% of total number of trips.
 2 : The use of bikes occurs most in the hours to go to work (7.00, 8.00, 9.00) and the hours to leave work (16.00, 17.00, 18.00), the time to go at 8 am and leave at 5.00 pm is the peak time for bike use .
 3: Unlike the weekdays , in holdays (weekends) The use of bikes occurs most in the hours of the mid-day from 11.00 A.m to 4.00 P.M
 4: Subscribers are the largest proportion of bikes users with percentage of 89.2% of users and in weekends the percentage of customer users almost doubled. 
 5 : Most of bike-share users are in the age from 24 to 34  .
 6 : The largest start station in trips count is Market St at 10th St  with 3904 trips.
 7 : The less used start station is 16th St Depot  with only 2 trips .
 8 : The largest end station in trips count is San Francisco Caltrain Station 2  (Townsend St at 4th St)  with 4875 trips.
 9 : The less used end station is Willow St at Vine Stt  with only 5 trips  .
 10 : The most relative start and end station happen when Berry St at 4th St  is the start station and San Francisco Ferry Building (Harry Bridges Plaza) is the end station with total number of trips : 337 trips. 
 11 : The most bike used in ford go-bike system is bike with ID 4794 with total trips : 191 trips.
 12 : The trips with duration range from 3 to 8 minutes have the largest count of trips in bike-share system.
 13: The most number of trips for subscribers happen in less time duration than customers  .
 14 : the most bike used when bike shared all trip is bike with ID 3967 with total trips : 91 trips.
 15 : The trip duration for bikes that don't share all trip is larger than bikes that share all trip.
 16 : Bikes which don't share all trip has percentage 90.5% of total bikes used .
 17 : User age when using bike don't share all trip is larger thang user age using bike share all trip .
 18 : Trip duration time for customers is larger than subscribers .
 19 : Males are more used for ford go-bike system.
 20 : Subscriber males are more used for ford go-bike system by 119069 trips.
 21 : there are no customers to use bikes for share all trip.
 22 :  subscribers who use bikes don't share all trip are the most with 146185 trips.
 23 : Males who use bikes don't share all trip are the most with 117510 trips.
 24 : The mean time duration of trip for gender(other) which use bike don't share all trip is the largest with 17 minutes.
 25 : The mean time duration of trip for gender(other) and  customer is the largest with 26.5 minutes.
 26 : The mean age for gender(other) which use bike share all trip is the largest with 36.2 years in average.
 27 : The mean age for gender(other) and subscriber is the largest with 36 years in average


## Key Insights for Presentation

 -The use of bikes occurs most in the hours to go to work (7.00, 8.00, 9.00) and the hours to leave work (16.00, 17.00, 18.00), the time to go at 8 am and leave at 5.00 pm is the peak time for bike use so i suppose the most of users are employees or students.
 -Subscribers are the largest proportion of bikes users with percentage of 89.2% of users and that Confirms the first insight 
