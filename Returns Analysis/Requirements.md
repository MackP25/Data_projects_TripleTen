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
* The *Superstore.xlsx* file was imported into Tableau Public Desktop for analysis. After joining the Orders and Returns tables, the primary metrics used were **return rates** and the **total number of returns**.
* A calculated field was created to convert the Returned values into binary form (1 for "Yes," 0 for null), enabling analysis of return rates across product subcategories, categories, customers, states, and time periods to explore potential correlations and seasonal trends.
* Filters were applied to exclude customers with only one order, allowing the analysis to focus on repeat customers who are more likely to make returns. Additional filters were added to the final dashboard, enabling users to interactively view data by product category and month of the year.

### Data Analysis
1. Returns vs. Sales and Product Categories:
    * Created a scatterplot to show the correlation between total sales and total returns, aggregated by product subcategory.
    * Used a bar chart to compare return rates across product categories and identify high-return segments.

2. Customer Return Analysis:
    * Analyzed return rates by customer, applying a filter to exclude single-order customers and focus on trends among repeat buyers more prone to returns.

3. Returns by Geographic and Time Dimensions:
    * Developed a map to visualize return rates by state, highlighting regional return patterns.
    * Compared return rates by month and year to assess potential seasonal trends in return behavior.

### Results
  * Sales do not consistently correlate with return rates, indicating that high sales volumes do not always lead to more returns.
  * The Technology category has the highest return rate at 27.3%, followed by Office Supplies and Furniture, both at 25%.
  * West Coast states and the Technology category exhibit the highest return rates, while customers with multiple orders generally show lower return tendencies.
  * The year 2021 recorded both the highest sales and return rates, with August standing out as the month with the highest return rate.

### Conclusion
* Several sub-categories within the Office Supplies category generate less than $100,000 in profit, potentially indicating product quality concerns that warrant further investigation.
* Return rates increase during the summer and year-end periods; Superstore should consider implementing seasonal discounts or adjusting pricing strategies during these times to manage return volume more effectively.
* Customers with fewer total orders tend to have higher return rates. Analyzing these customers by region may help identify whether logistics or shipping issues are contributing factors.
* The Technology category shows the highest return rates overall. Introducing a return policy that reduces refund value for items returned damaged or in poor condition could help mitigate associated losses.

[Click here to see live Version --> ](https://public.tableau.com/app/profile/mack.pickar/viz/ReturnsAnalysis_17458624776980/ReturnsAnalysis)
