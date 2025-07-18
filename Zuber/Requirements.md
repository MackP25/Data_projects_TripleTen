# Zuber

  The project covers:
    
      -Developing SQL queries to perform analysis on the Zuber dataset.
      
      -Calculating trips_amount for each taxi company and identifying the most popular.
      
      -The impact of external factors on the number of rides.

# ZUBER

## Executive Summary
* This analysis aims to uncover patterns in the Zuber dataset, explore passenger preferences, and assess the impact of external factors on ride behavior.

### Research Questions/Project Guidelines
1. Find the number of taxi rides for each taxi company for November 2017 and group them by most popular.
2. Determine if and how the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays compared to other days of the week and other weather conditions.

### Methodology
* The project was conducted on the TripleTen platform, utilizing SQL as the primary language to query, filter, group, and sort transportation and weather datasets.
* SQL queries were used to calculate the number of taxi rides completed by each company during November 15–16, 2017, and to determine total rides for companies whose names contain “Yellow” or “Blue.”
* Hourly weather data was retrieved and classified using a CASE statement—records were labeled as "Bad" if the weather description included "rain" or "storm," and "Good" otherwise. Results included the timestamp (ts) and corresponding weather_conditions to enable trend analysis over time.
* Saturday trips starting at the Loop and ending at O'Hare were extracted and matched with hourly weather data. The final dataset included start_ts, weather_conditions, and duration_seconds, excluded rides lacking weather data, and was sorted by trip_id for consistency.

### Data Analysis
1. Analysis of Taxi Rides by Company (November 15–16, 2017):
    * Taxi ride activity was analyzed across all companies for the period of November 15–16, 2017. The resulting dataset included each company’s name and corresponding ride count, labeled as trips_amount. The analysis revealed that Flash Cab was the most active provider during this timeframe, with a total of 19,558 rides.
  
2. Company Ride Counts by Keyword and Popularity (Nov 1–7, 2017):
    * During the week of November 1–7, 2017, total ride counts were calculated for companies whose names contain "Yellow" or "Blue," grouped by company_name and labeled as trips_amount. Additionally, ride volumes for Flash Cab and Taxi Affiliation Services—the two most popular providers during this period—were identified separately, while all other companies were combined under a unified "Other" category. The final results were sorted by total trip volume.

### Results
* Trip volume analysis revealed that Flash Cab, Taxi Affiliation Services, and Medallion Leasing ranked as the top three most popular taxi companies among riders. 
* The dataset was filtered to highlight only Flash Cab and Taxi Affiliation Services, with all other companies grouped under an "Other" category. The results showed that Flash Cab completed 64,084 rides, while Taxi Affiliation Services accounted for 37,583 rides during the specified period.
* Analysis showed that most trips occurred on days with good weather, while trips during bad weather conditions were associated with longer ride durations.

### Conclusion
* SQL data analysis identified Flash Cab, Taxi Affiliation Services, and Medallion Leasing as the most popular taxi companies. Flash Cab completed 64,084 rides, Taxi Affiliation Services recorded 37,583 rides, and Medallion Leasing accounted for 10,367 rides during the period of November 15–16, 2017. The analysis also revealed that most trips occurred on days with good weather, while bad weather conditions were linked to longer ride durations.

[Click here to see live Version --> ](https://tripleten.com/trainer/bi-analyst/lesson/32ddb20e-3ada-4aea-88d7-3ba42f2bd09c/task/d102902d-9759-41d6-8121-d35db6e9b511/)
