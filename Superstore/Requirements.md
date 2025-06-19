# Superstore									

  The project covers:
    
      -Profit centers and areas of loss.
      
      -Advertising insights.
      
      -Return Rates by product and customer.

# SUPERSTORE

## Executive Summary
* This project analyzes profitability and return rates for the Superstore dataset.

### Research Questions/Project Guidelines

1. Analyze combinations of key dimensions (e.g., sub-category + region) to identify the two most and least profitable pairs, revealing major profit centers and loss-makers. Use these insights to recommend specific products for discontinuation and determine three subcategories to prioritize and three to phase out based on overall performance.
2. Create a calculated field that converts return data into binary format to identify products and customers with the highest return rates. Analyze the relationship between average profit and return rate across a selected dimension to support a data-driven recommendation on whether to maintain or discontinue operations in that area.
3. Identify the top three state–month combinations with the highest average profit to guide targeted advertising efforts. Visualize monthly profit trends for these states and, using a ROAS model that allocates 1/5 of projected profit to advertising, calculate and justify the recommended ad spend for each.

### Methodology
* Downloaded the dataset as an .xlsx file and uploaded it into Tableau Public Desktop for analysis.
* Established relationships between tables to join the data, forming a unified base for exploratory analysis focused on identifying major profit and loss centers.
* Analyzed profit trends across time and geographic dimensions to determine the most effective periods and locations for targeted advertising.

### Data Analysis
1. Profit Analysis Across Categories and Dimensions:
    * Created a bar chart to visualize total profit by sub-category, color-coded by region, and a pie chart to compare overall profit distribution across regions.
    * Analyzed profit by product ID and shipping mode to identify performance patterns and potential areas for improvement.
[Click here to see live Version -->](https://public.tableau.com/app/profile/mack.pickar/viz/ProfitandLossCenters/ProfitsLosses?publish=yes)
2. Advertising Analysis by State and Month:
    * Compared average monthly profit for each state to identify top-performing state–month combinations: California in August ($6,368), New York in September ($12,125), and Washington in March ($5,766).
    * Calculated a return on ad spend (ROAS) of 20% for each, establishing recommended advertising budgets based on their respective average profits.
[Click here to see live Version --> ](https://public.tableau.com/app/profile/mack.pickar/viz/shared/9P5K7NCG4)

3. Return Rate Analysis:
    * Created a calculated field (return_indicator) assigning 1 to "Yes" and 0 to null values in the Returned column, then visualized average return rates by product ID and customer to identify high-return items and frequent returners.
    * Compared average profit against average return rate by state to determine which states may be less profitable and potential candidates for discontinuing business operations.
[Click to see the live version -->](https://public.tableau.com/app/profile/mack.pickar/viz/Superstore_Returns_17503746181360/ReturnedItems?publish=yes)

### Results
  * The West and East regions are the most profitable, while Same Day shipping is the least profitable shipping method. Despite housing the product with the greatest loss, Standard Class shipping remains the most profitable shipping method overall.
  * Binders yield zero profit in the Central region, and the DocuBind P400 Binding System and Cubify CubeX 3D Printer are the largest loss-making products, with losses of –$20,388 and –$8,880, respectively.
  * The most profitable subcategories are Phones, Copiers, and Accessories, while Tables, Supplies, and Bookcases are the least profitable.
  * Top-performing state–month combinations for advertising include California in August ($6,368 avg. profit), New York in September ($12,125), and Washington in March ($5,766), supporting calculated ROAS-based ad budgets. Products with the highest return rates include Printers/Copiers, Phones, and other tech, with Ronald Murray and Hilary Holden identified as the most frequent returners, each with a return rate of 1.0.

### Conclusion
* Superstore should stop selling binders in the Central region, as they generate no profit, and discontinue underperforming products such as the DocuBind P400 Binding System and categories like Tables, Supplies, and Fasteners.
* Prioritize sales efforts in the West and East regions, which consistently show strong profitability, and shift resources away from the Central region.
* Expand offerings and marketing around Copiers, Accessories, and Phones, which are the top-performing subcategories.
* Allocate advertising budgets based on profit potential—$1,153 for Washington, $2,425 for New York, and $1,274 for California. Continue operations in Vermont, which yields positive profit and has a 0% return rate, while reevaluating or ceasing operations in Ohio, which shows average losses of –$43 and a 0.224 return rate.
