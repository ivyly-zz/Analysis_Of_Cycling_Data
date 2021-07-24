# DataScience-analysis-of-cycling-data

This repository contains 3 portfolio projects for COMP2200/COMP6200 for Session S2-2020 @ Macquarie University.

## 1. Portfolio 1:

### Goal: 
Analysis of CSV data for cycling, with GoldenCheetah, Strava data sets from Strava and GoldenCheetah applications, as well as weather data from Bureau of Meterology. (Combining those rows of data that appear in both data frames so that a dataframe  with 243 observations and 372 features/ variables)

### This project explores: 

The distributions of some key variables, such as time, distance, average speed, average power, and TSS;

The relationships between Distance, Moving Time, Average Speed, Heart Rate, Power (watts), Normalised power (NP), Training Stress Score, Elevation Gain. Distance, Moving Time, Training Stress Score, Elevation Gain, Average Speed, and Heart Rate are discovered as strong correlated with each other. More specifically, the longer the distance is, the harder the ride is, then, the larger your training stress score is. The larger elevation gain you can achieve, the longer distance that you can make. Also, when you exercisefor longer and longer, your speed will be slower and slower. If you put more effort to the ride, your heart rate will rise;

 The differences between the three categories: Race, Workout and Ride. The experiment is conducted with different variables such as distance and TSS, Heart Rate. Comparing to Races and Workouts, Rides have longer distance and higher training stress score. Race is a workout type causing higher Heart Rate among riders comparing to Workout and Ride. Ride is a workout type least causing Heart Rate because of less presure and longer elapsed/ moving time comparing the other two.

 - The relationship between rides and weather. Distance travelled per ride is negatively correlated with the temperature. Similarly, average speed is also negatively correlated with the temperature.

 - Distance, Moving Time, and Training Stress Scored are positively correlated with kudos. Therefore, longer distance, longer moving time, higher trainning stress score are more likely to lead to more kudos. In other words, rides with longer distance and moving time are more popular. 
    
This project also illustrates an overall summary of activity each month over the period 2018-2019 and an overall summary of activity of Jan 2019, with the number of km ridden each month, the sum of the Training Stress Score, and the average of the Average Speed.
