# Ford GoBike System Data
## by Hesham Khalil


## 201902-fordgobike-tripdata

>dataset downloaded from udacity  (201902-fordgobike-tripdata.csv), This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
Added another dataset on it of Chicago city from [here](https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q1.zip)
* Some data wrangling done on the data set by downloading the Chicago set programmatically
* combined the two dataset together using pandas library in one date frame named (gobike)

## Summary of Findings

### What is the structure of your dataset?
There are 174877 unique bike share entries in the data set mostly are categorical variables
### What is/are the main feature(s) of interest in your dataset?
I'm interested in figuring out what features are impacting the rides of bikes
### What features in the dataset do you think will help support your investigation into your feature(s) of interest?
I think the dates and address where the ride started from will have the highest impact on the frequency of the rides
- Member Year of Birth
- Member Gender
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Trip Duration(in seconds)
- Bike ID
- Start Time and Date
- End Time and Date
- Start Station ID
- End Station ID
- Start Station Name
- End Station Name
- End Station Latitude
- End Station Longitude
- Start Station Latitude
- Start Station Longitude


## Key Insights for Presentation
* In this investigation I wanted to look at what affects the bike sharing system and how other features affect the rides and the durations of it.

* the end of the month was the most number of rides have been done and specifically in 20, 21 ,22 and 28 of the February had the most rides with over 5000 rides each day.
* most of the trips starts between morning and afternoon time.
* highest trip duration are at morning
* Between 20 and 40 years old the users are having the most durations and specifically in 30s they have the most duration
* the duration is decreasing whenever age increasing
* Subscribers have 90.8% of the rides while Customers made only 9.2% of the rides
* most of the rides that bike sharing system gets from Males
