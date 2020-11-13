
# Ford GoBike Data Visualization 
## by (Asmaa Mostafa)
 
## Dataset
The dataset containing information about Ford's bike-sharing system program for San Francisco area from june 2017 to April 2019 .The dataset are available through https://s3.amazonaws.com/fordgobike-data/index.html
The dataset consist of 3254325 rides with 16 features. The dataset is available through https://s3.amazonaws.com/fordgobike-data/index.html

In wrangling and cleaning include :

- Convert time variables(start_time ,end_time) from string to datetime 
- Convert the start station id  and end station id to int
- Add new variables (member_age,year,month and day) from existig variables.
- Only use ages <= 100

- duration_sec (in seconds)
- start_time 
- end_time 
- start_station_id 
- start_station_name 
- start_station_latitude
- start_station_longitude
- end_station_id 
- end_station_name 
- end_station_latitude 
- end_station_longitude 
- bike_id user_type (Subscriber,Customer) 
- member_birth_year
- member_gender (Male ,Female, Other)
- bike_share_for_all_trip

## Summary of Findings

The data set contain two users types Customer and Subscriber .
Subscriber users present 88.7% and customer users present 11.3%.

There are 3 gender types: males with ratio= 74.1% , females =24.2% and other =1.6% .Across all ages and users type Female and other riders have longer ride duration than male riders.

Most of users age fall between 20 to 40 .The youngest is 19 years old and the oldest is 142 I think it is wrong data . The mean of ages =36 years old  with  trips duration around 650 seconds.
It was surprising not only youth who use bike but even adults older than 50 years old and also have long rides It was surprising not only youth who uses bike but even adults older than 50 years old and also have long rides.
so the correlation between age and trips duration is considered slightly negative.

There is affect from weather on the number of trips .There was a low rides in (November and December) compared to other months but the highest rides rate fall in (March and April) as the numbers of rides keep upwards during spring and summer then it is decreased gradually.


Subscribers mostly use the bike service during the weekdays  (Monday to Friday)  with peak hours from 8 am to 6 pm, so it is mostly related to working routine ,
while customers ride mostly on the weekends (Saturday and Sunday) through day hours this means that the customers do not depend on a scheduled routine.
Customers ride longer than subscribers although their number less than subscribers.

The most commonly station used either to start or to end the trip are:

-San francisco ferry buliding
-San francisco caltrain
-Market st at 10th st

## Key Insights

- The analysis focused on The influence of variables (users type, users age and gender,location,date and time) on trip duration and numbers .

- Bike for all ages:  One might expect that only youth used bike but after analysis we found that adults older than 50 years used bike with long rides.

- Seasons impact on rides: November and December (autumn season) have lower trips compared to the other months while  March and April have higher trips. The numbers of rides keep upwards during spring and summer then it is decreased gradually.

- Gender has no impact on trip duration: It was surprising that females and other gender have long duration trips compared to males.

- Users types lifestyle with bike: Subscribers rides mostly in weekday while customers  mostly on the weekends (Saturday and Sunday).
