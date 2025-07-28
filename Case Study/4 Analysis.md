<h2>Case Study: Supestore Sales Performance Analysis</h2>

<b> Analysis</b>
  -  [A. Key Performance Indicators (KPIs) Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/Analysis.md#a-key-performance-indicators-kpis-analysis)
  -  [B. Segment/Regional Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/Analysis.md#b-segment-regional-analysis)
  -  [C. Product.Category Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/Analysis.md#c-product-category-analysis)
  -  [D. Trend & Seasonality Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/Analysis.md#d-trend--seasonality-analysis)
    
---

<h2>Analysis</h2>

To gain a comprehensive understanding of Superstore Inc.'s operational performance and financial health, several key performance indicators (KPIs) were analyzed using the `sample_superstore_orders.xls` dataset. These metrics provide crucial insights into sales effectiveness, profitability, and customer engagement.
     
<h3>A. Key Performance Indicators (KPIs) Analysis</h3>

The dashboard incorporates several key visualizations to provide a holistic view of the Superstore's sales performance:

- <b>Total Sales:</b> Displays the total sales in thousands, with a specific color code of "#76b7b2" and disabled tooltips.
  - The company generated a total sales revenue of $2,297,200.86 across all transactions. This figure represents the aggregate income before any deductions, indicating the overall market demand for Superstore Inc.'s products.

- <b>Total Profit:</b> Similar to Total Sales, showing total profit in thousands with the same formatting requirements.
  - From these sales, Superstore Inc. achieved a total profit of $286,397.0. This critical metric reflects the company's financial success after accounting for costs, demonstrating its ability to convert sales into actual earnings.

- <b>Overall Profit Ratio:</b> The overall profit ratio stands at 12.47%. This percentage indicates that for every dollar of sales, Superstore Inc. retains approximately 12.47 cents as profit. This ratio is vital for assessing the efficiency of the company's pricing strategies and cost management.

- <b>Total Volume:</b> Presents the total volume (quantity) of sales, formatted similarly to sales and profit but not as a currency.
  - Total Volume (Quantity Sold): A total of 37,873 units of products were sold. This metric provides insight into the sheer scale of product movement and customer demand.

- <b>Sales Per Customer:</b> Shows the average sales per customer.
  - Average Sales Per Customer: On average, each unique customer contributes $2,896.85 in sales to Superstore Inc. This KPI helps in understanding the value of individual customer relationships.
  - Sales Per Customer by Segment:
    - Corporate: $2,992.15
    - Home Office: $2,903.06
    - Consumer: $2,839.61

  This breakdown reveals that Corporate customers, on average, generate slightly higher sales per customer compared to Home Office and Consumer segments, suggesting    potential for focused strategies on this segment.

- <b>Sales by Region:</b> Illustrates the percentage of total sales by region, using the Summer Color Palette with black borders. Tooltips display region name, percent of total sales, and total sales
in thousands.
  -  Standard Class: $1,754.80
  -  Second Class: $834.90
  -  First Class: $711.39
  -  Same Day: $565.48

It is observed that customers utilizing "Standard Class" shipping contribute significantly more in sales per customer than those using expedited options. This could imply that larger or more complex orders, often associated with higher sales values, tend to use standard shipping, or it may point to differences in customer behavior across shipping preferences.

- <b>Top N States by Sales:</b> A horizontal bar chart showing the top N states by sales, with 'N' controlled by a user-adjustable parameter. Bars are sorted in descending order and display labels in dollars.
  - The concentration of sales varies significantly across different regions, with the top 10 states by sales contributing a substantial portion of the overall revenue:

  - California: $457,687.63
  
  - New York: $310,876.27
  
  - Texas: $170,188.05
  
  - Washington: $138,641.27
  
  - Pennsylvania: $116,511.91
  
  - Florida: $89,473.71
  
  - Illinois: $80,166.10
  
  - Ohio: $78,258.14
  
  - Michigan: $76,269.61
  
  - Virginia: $70,636.72
  
  California and New York are clearly the strongest markets in terms of sales. A deeper analysis into the profitability of these top states, especially Texas, Pennsylvania, Ohio, and Illinois, which are known to have significant discount rates, is warranted to ensure sales volume translates into healthy profit margins.


- <b>Sales by Sub-Category:</b> Visualizes sales by sub-category, with bubbles colored by category. Tooltips show sub-category and sales value in thousands.

- <b>Sales Trend by Month-Year:</b> A continuous line chart displaying sales trends over time, with the X-axis formatted as "MMM YY." Tooltips show Month-Year and sales value in thousands.
  - Analyzing the sales trend over time provides insight into seasonal patterns and overall growth trajectory:

    - Highest Sales Month: November 2021 recorded the highest sales at $118K. This peak likely aligns with holiday shopping seasons or major promotional events.
    - Lowest Sales Month: April 2018 saw the lowest sales at $28K. Identifying consistent low-performing months can help in planning targeted marketing campaigns or inventory adjustments during these periods.

<br>

<b>Business Question(s)</b>

-  What are the overal total sales, profit, and volume for the Superstore?
-  What is the average sales amount per customer, and how does this metric differ across various customer segments or ship modes?

---

<h3>B. Segment Regional Analysis</h3>

<br>

<b>Business Question(s)</b>

  -  Which regions contribute the most to total sales, and what is their percentage share of the overall sales pie?
  
  -  Are there any regions that are underperforming in terms of sales, and why might that be the case?
  
  -  What are the top 'N' performing states by sales, and how does changing 'N' reveal different insights about geographical sales concentration?
  
  -  How do different customer segments (e.g., Consumer, Corporate, Home Office) contribute to overall sales and profit?
  
  -  Does the choice of shipping mode impact sales or profit margins?
  
  -  Can we identify specific states or regions that are consistently profitable versus those that are consistently less profitable, despite high sales volume?

---

<h3>C. Product/ Category Analysis</h3>

<br>

<b>Business Question(s)</b>

- Which sub-categories generate the highest sales, and how does this vary across different product categories?

- Are there any particular sub-categories that, while having high sales, might have low-profit margins, indicating a need for pricing or cost review?

---

<h3>D. Trend & Seasonality Analysis</h3>

<br>

<b>Business Question(s)</b>

- How do sales trends vary month-over-month and year-over-year? Are there any seasonal patterns or significant spikes/drops in sales?

---
