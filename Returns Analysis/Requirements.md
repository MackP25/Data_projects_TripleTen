# Returns Analysis									

  The project covers:
    
      -Compares overall sales and return rates to evaluate return behavior.
      
      -Analyzes return rates by quantity and by month/year to identify potential seasonal trends.
      
      -Examines return rates by product category and sub-category to pinpoint items with higher return frequencies.

# RETURNS ANALYSIS

## Executive Summary
* This project is focused on analyzing patterns and trends in product return rates within Superstore's operations. The ultimate goal is to provide strategic recommendations that can help Superstore reduce return rates, improve customer satisfaction, and enhance overall operational efficiency.

### Research Question/Project Guidelines

1. What is causing returns?
2. Build a dashboard for monitoring returns.

### Methodology
* A calculated field was created to convert the Returned values into binary form (1 for "Yes," 0 for null), enabling analysis of return rates across product subcategories, categories, customers, states, and time periods to explore potential correlations and seasonal trends.
* A customer filter was applied to exclude those with only one order, focusing the analysis on identifying patterns among repeat customers who are more likely to make returns.

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

[Click here to see live Version --> ](https://public.tableau.com/app/profile/mack.pickar/viz/ReturnsAnalysis_17458624776980/ReturnsAnalysis)
