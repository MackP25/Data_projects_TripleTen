# Vacation Rentals									

  The project covers:
    
      -Prepare and organize raw data for analysis by handling missing values, formatting, and standardizing entries.
      
      -Create Pivot tables and visualizations to summarize key metrics and reveal trends in rental data.
      
      -Analyze data to uncover the most sought-after properties and neighborhoods among renters.

# VACATION RENTALS

## Executive Summary
* The following analysis is to determine which neighbourhoods and property sizes are most attractive for vacation rentals and how much revenue they generate, to assist our client in deciding which properties to invest in.

### Research Question/Project Guidelines
1. Which neighborhoods and property sizes (i.e. number of bedrooms) are most attractive for vacation rentals?
2. How much money did the most attractive listings generate?

### Methodology
* Standardized text by removing inconsistent capitalization and trailing spaces, replaced empty fields with "0", and stored cleaned data in new columns for neighborhoods and other key fields.
* Used Pivot tables and bar charts to identify top 10 listings and neighborhoods, analyze bedroom popularity, and summarize nightly revenue by listing ID.
* Added a column to flag top listings, calculated nightly and projected annual revenue (based on a 30-day sample), and transferred results to an existing sheet for reporting.

### Data Analysis
1. Data Processing:
    * Standardized text formatting, replaced empty fields with "0", and stored cleaned values in new columns for analysis.
    * Added a column to flag top listings, calculated nightly and projected annual revenue, and transferred results to an existing report sheet.
![Screenshot 2025-06-19 155009](https://github.com/user-attachments/assets/e9a15dcf-5cf0-438b-a618-1a0ca52b0130)

2. Top Neighborhoods:
    * Compared number of reviews across neighborhoods using a Pivot table and bar chart to identify the most attractive areas.
    * Filtered results to highlight the top ten neighborhoods by review count.
![Screenshot 2025-06-18 132954](https://github.com/user-attachments/assets/cf3bc663-61a0-4574-a68e-34865be20258)

3. Bedroom Analysis by Top Rental:
    * Analyzed the number of bedrooms in top listings across the top ten neighborhoods to identify popular rental configurations.
    * Used a Pivot table to determine the most in-demand bedroom counts and filtered results to the top ten neighborhoods.
<img width="796" alt="Screenshot 2025-06-18 134644" src="https://github.com/user-attachments/assets/8e4cb9c4-0cb2-4313-b714-425dc7b6a58f" />

4. High Revenue-Generating Properties:
    * Calculated nightly revenue for each listing and summarized it using a Pivot table by listing ID.
    * Estimated annual revenue by extrapolating from a 30-day sample and transferred results to an existing sheet for reporting.

### Results
  * A comparison of the total number of reviews by neighborhood identified the top ten most popular neighborhoods, with the Lower East Side, Hell's Kitchen, and Harlem emerging as the top three areas with the highest renter engagement.
  * One-bedroom units are the most sought-after property size, followed by studios and two-bedroom apartments, reflecting a preference for compact, cost-effective living options.
  * The highest revenue-generating property is a **studio in Midtown** (User ID: **49946551**), followed by **one-bedroom units in Hell's Kitchen and the Lower East Side**, highlighting the strong profitability of smaller units in highly sought-after neighborhoods.
![Screenshot 2025-06-18 143422](https://github.com/user-attachments/assets/56f16fe9-49f6-4342-a2b2-422b5b534491)

### Conclusion
* Analysis of property sizes shows that studios, one-bedroom, and two-bedroom units are the most in-demand among renters, indicating a strong preference for smaller, more affordable living spaces.
* Based on these insights, our client should consider investing in properties with 0–2 bedrooms located in the top-performing neighborhoods, where demand and occupancy rates are likely to be higher.
* The highest revenue-generating listing is a studio in Midtown (User ID: 49946551), making it a strong candidate for investment due to its proven earning potential and location appeal.

[Click here to see live Version --> ](https://docs.google.com/spreadsheets/d/1XGy0eCdSyyz_avJ2ikeeh4g6DTfHpYiuE-8i02rU_4U/edit?gid=1185972781#gid=1185972781)
