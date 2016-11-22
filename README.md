# PUI Extra Credit Proposal

# Best time to drive a cab?
## When are the longer trips and higher average fares likely to happen? 

<Le Xu, github: lx565, NYU ID: lx565>

## Problem Description:
It is generally known that: Fridays’ and Saturdays’ nights are the busiest time period during the week, or bad weather could also help to drive up taxi demands. After the CUSP hack-day working on NYC Taxi dataset, I would love to further study the taxi fares by analyzing with the taxi trip occurring time and the daily weather.  In my data analysis, I will answer questions like: when is the time of the day has better chance of longer trips or higher average trip fare? How bad weather (rain/snow) could affect taxi ridership, etc. 


## Data: 
1. Taxi trip data
Source: NYC Taxi & Limousine Commission - NYC.gov
Since there will be time series analysis, the taxi data from NYC.gov has included the time of the trip occurring, both the pick-up time and drop-off time, and the total fare as well as the total tip amount. 
The anticipated data processing will mainly include: binning the timestamps, to discover the trend/periodicity of the taxi income during the day/week/month. 
2. Daily Central Park weather data
Source: National Climatic Data Center, 
https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail

*Since the size of the taxi data is rather huge, so I might consider take a subset of the dataset, however I am not sure currently.

## Analysis Tools:  Pandas, matplotlib

## References: 
Analyzing 1.1 Billion NYC Taxi and Uber Trips, with a Vengeance - Todd W. Schneider
http://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/

Visual Exploration of Big Spatio-Temporal Urban Data: A Study of New York City Taxi Trips - Nivan Ferreira, Jorge Poco, Huy T. Vo, Juliana Freire, and Claudio T. Silva

NYC Taxi Trip and Fare Data Analytics using BigData - Umang Patel #

## Deliverable:  Several Plots of regarding the time series and weather related ridership. 
