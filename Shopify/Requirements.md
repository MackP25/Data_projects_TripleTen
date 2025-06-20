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
1. App Landscape Visualization:
    * Created a KPI Card showing the total unique number of apps and a Line Chart displaying the sum of review counts over time using lastmod date on the X-axis without hierarchy.
    * Developed a Scatterplot comparing reviews_count to average rating, accompanied by an annotated text box interpreting the results.
![Screenshot 2025-06-20 002554](https://github.com/user-attachments/assets/faa3435e-40eb-45c3-b48b-9fe162f99cf3)

2. Review Data Enhancement and Visualization:
    * Created a new calculated column, helpful_reviews, in the Reviews table using the formula: rating × (1 + helpful_count), and visualized its average value using a KPI card.
    * Developed a binary developer_answered column indicating if a developer replied, then created a scatterplot comparing average rating against developer responsiveness.
![Screenshot 2025-06-20 002925](https://github.com/user-attachments/assets/1f7adaad-252a-42ec-ae08-0e02d2a27aec)

3. Developer Performance and Responsiveness Analysis:
    * Established a many-to-one relationship between the Reviews and Apps tables using app_id and id, then created bar charts comparing developers by total ratings and by average helpful_reviews for more accurate insights.
    * Identified the most responsive developers with a filtered bar chart showing developer responsiveness (based on developer_answered), including only apps with more than 500 reviews for meaningful comparison.
![Screenshot 2025-06-20 004844](https://github.com/user-attachments/assets/a575119c-afd0-48a7-a392-c79087367fac)

### Results
  * Most reviews in the dataset have average ratings between 4 and 5 stars, with the majority having fewer than 5,000 reviews.
  *Surprisingly, average ratings tend to be lower when developers respond compared to when they do not.
  * The most responsive developers identified are FireApps, followed by DSers and PageFly.

### Conclusion
* Most Shopify apps receive average ratings between 4 and 5 stars, with the majority having fewer than 5,000 reviews. Encouraging users to leave reviews—such as by prompting them after app use or offering incentives—could help increase review volume. Interestingly, average ratings tend to be lower when developers respond to reviews. The most responsive developers, including FireApps, DSers, and PageFly, play a significant role in Shopify’s success, emphasizing the value of active developer engagement and customer interaction.

[Click here to see live Version --> ](https://mpickar-my.sharepoint.com/:u:/g/personal/mackpickar_mpickar_onmicrosoft_com/EXP-TNCMb_dChKClWFkpY1UBLTkYz11cjix00p1pmrKlLQ?e=yHCpga)
