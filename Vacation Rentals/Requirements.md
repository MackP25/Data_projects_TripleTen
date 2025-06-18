# Vacation Rentals									

  The project covers:
    
      -User's purchase activity.
      
      -Conversion and Retention Rates.
      
      -Tracking cohort age.

# VACATION RENTALS

## Executive Summary
* The following analysis is to determine which neighbourhoods and property sizes are most attractive for vacation rentals and how much revenue they generate, to assist our client in deciding which properties to invest in.

### Research Question/Project Guidelines

1. Which neighborhoods and property sizes (i.e. number of bedrooms) are most attractive for vacation rentals?
2. How much money did the most attractive listings generate?

### Methodology
* The business analytics dataset was downloaded as a spreadsheet and then cleaned and prepared for analysis. The specific columns used were `event_type`, `event_date`, and `user_id`. I filtered the data to include only purchase events and created a new sheet to calculate the `first_purchase_month` for each user. The conversion funnel displays the number of unique users at each stage and shows the conversion rates between stages. Additionally, I calculated the retention rate of active users within four months of their first purchase date.
* Microsoft Spreadsheets was the primary technological tool used in the collection and analysis of the business analytics dataset for this project.

### Data Analysis
1. Customer Conversion Rates:
    * Conversion rates were calculated for unique users at each stage of the funnel, including the overall conversion rate from the view page to the purchase page.

2. Cohort Metrics:
    * The first purchase date was determined for each user_id, and cohort age was calculated for each user. A conversion funnel was then created to count the number of unique users in each cohort, broken down by the number of months since their first purchase date.

3. Retention Rates:
    * Retention rates were calculated for each cohort, and a table was created to display the retention rates by cohort age as percentages.

### Results
This analysis focused on three key areas: evaluating how effectively the company converts product page views into purchases, determining the first_purchase_month for each user to segment cohorts by monthly age, and calculating retention rates for each cohort.
  * According to our analysis, 29% of users who view the product page add the item to their shopping cart and only 36% of those users who add to their carts finalize a purchase through the company's website. Only 10% of users who viewed the product page ended up making a purchase. 
  * A comparison of unique user_id counts across cohort ages reveals a significant decline in user numbers as the cohorts age.
  * The calculations show that retention rate dramatically decreases after the user's first month on the website.

### Conclusion
* The analysis indicates that only 10% of users who view the product page ultimately complete a purchase. A comparison of unique user_id counts by cohort age shows a significant decline in user engagement over time, highlighting a drop-off as cohorts age. Additionally, retention rates appear to be higher toward the end of the calendar year, suggesting a seasonal influence on user activity.
* Notably, the cohorts from January and February 2021 exhibit unusually low retention rates, which may point to incomplete or missing data in the raw_user_data for those periods.
* To improve conversion rates, the company could consider increasing advertising efforts on social media platforms to drive more product page views. Implementing time-sensitive incentives—such as discount codes or free shipping for users who complete a purchase shortly after adding items to their cart—may also encourage quicker conversions.
* To enhance user retention, offering random discounts or free gifts to returning users could serve as an effective strategy to boost long-term engagement.

[Click here to see live Version --> ](https://docs.google.com/spreadsheets/d/1XGy0eCdSyyz_avJ2ikeeh4g6DTfHpYiuE-8i02rU_4U/edit?gid=1185972781#gid=1185972781)
