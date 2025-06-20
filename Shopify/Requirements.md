# Shopify									

  The project covers:
    
      -DAX Calculations
      
      -Review Analysis
      
      -Dashboard Design

# SHOPIFY

## Executive Summary
* This project analyzes app reviews, ratings, developer responsiveness, and engagement metrics on the Shopify platform to uncover key factors driving app success. Using DAX calculations and Power BI visualizations, it highlights patterns and developer practices linked to higher user satisfaction and performance.

### Research Question/Project Guidelines

1. Create calculated columns such as helpful_reviews (rating × [1 + helpful_count]) and developer_answered (1 if developer reply exists, 0 otherwise) to enhance review data analysis.
2. Analyze key metrics including review count, average ratings, and developer responsiveness across time, category, and region using scatterplots, line charts, and bar graphs.
3. Build an interactive Power BI dashboard featuring KPI cards, trend visualizations, and filters (e.g., by category or review count) to deliver clear insights on app performance and customer engagement. 

### Methodology
* Imported the shopify.xlsx file into Power BI and established a data model by creating a many-to-one relationship between the Reviews and Apps tables using app_id and id as key fields.
* Focused analysis on core metrics including ratings, review counts, and developer information to evaluate app performance and engagement.
* Developed calculated columns using DAX: helpful_reviews to weight ratings by helpfulness (rating × [1 + helpful_count]) and developer_answered as a binary flag for developer responses.
* Created multiple visualizations including KPI cards, line charts, scatterplots, and bar charts to compare app performance, track trends, and assess developer responsiveness—filtered to highlight apps with over 500 reviews for reliable insights.

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

[Click here to see live Version --> ](https://mpickar-my.sharepoint.com/:u:/g/personal/mackpickar_mpickar_onmicrosoft_com/EXP-TNCMb_dChKClWFkpY1UBLTkYz11cjix00p1pmrKlLQ?e=yHCpga)
