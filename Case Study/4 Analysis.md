<h2>Case Study: Supestore Sales Performance Analysis</h2>

<b> Analysis</b>
  -  [A. Key Performance Indicators (KPIs) Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/4%20Analysis.md#a-key-performance-indicators-kpis-analysis)
  -  [B. Segment/Regional Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/4%20Analysis.md#b-segment-regional-analysis)
  -  [C. Product Category Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/4%20Analysis.md#c-product-category-analysis)
  -  [D. Trend & Seasonality Analysis](https://github.com/LashawnFofung/Superstore-Sales-Performance-Dashboard/blob/main/Case%20Study/4%20Analysis.md#d-trend--seasonality-analysis)
    
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
  - On average, each unique customer contributes $2,896.85 in sales to Superstore Inc. This KPI helps in understanding the value of individual customer relationships.
  - Sales Per Customer by Segment:
    - <b>Corporate:</b> $2,992.15
    - <b>Home Office:</b> $2,903.06
    - <b>Consumer:</b> $2,839.61

    This breakdown reveals that Corporate customers, on average, generate slightly higher sales per customer compared to Home Office and Consumer segments, suggesting    potential for focused strategies on this segment.

- <b>Sales by Region:</b> Illustrates the percentage of total sales by region, using the Summer Color Palette with black borders. Tooltips display region name, percent of total sales, and total sales
in thousands.
  -  <b>Standard-Class:</b> $1,754.80
  -  <b>Second-Class:</b> $834.90
  -  <b>First-Class:</b> $711.39
  -  <b>Same-Day:</b> $565.48
  
  It is observed that customers utilizing "Standard-Class" shipping contribute significantly more in sales per customer than those using expedited options. This could imply that larger or more complex orders, often associated with higher sales values, tend to use standard shipping, or it may point to differences in customer behavior across shipping preferences.

- <b>Top N States by Sales:</b> A horizontal bar chart showing the top N states by sales, with 'N' controlled by a user-adjustable parameter. Bars are sorted in descending order and display labels in dollars.
  - The concentration of sales varies significantly across different regions, with the top 10 states by sales contributing a substantial portion of the overall revenue:

    - <b>California:</b> $457,687.63
    
    - <b>New York:</b> $310,876.27
    
    - <b>Texas:</b> $170,188.05
    
    - <b>Washington:</b> $138,641.27
    
    - <b>Pennsylvania:</b> $116,511.91
    
    - <b>Florida:</b> $89,473.71
    
    - <b>Illinois:</b> $80,166.10
    
    - <b>Ohio:</b> $78,258.14
    
    - <b>Michigan:</b> $76,269.61
    
    - <b>Virginia:</b> $70,636.72
    
    California and New York are clearly the strongest markets in terms of sales. A deeper analysis into the profitability of these top states, especially Texas, Pennsylvania, Ohio, and Illinois, which are known to have significant discount rates, is warranted to ensure sales volume translates into healthy profit margins.


- <b>Sales by Sub-Category:</b> Visualizes sales by sub-category, with bubbles colored by category. Tooltips show sub-category and sales value in thousands.
  - <b>Top Performing Sub-Categories by Sales:</b>
    The analysis reveals that sales are highly concentrated within a few key sub-categories, indicating strong customer demand and market penetration in these areas:
    - <b>Technology (Phones):</b> This sub-category leads in sales with a remarkable $330,007.05. Phones represent a significant revenue driver, highlighting the importance of the Technology category to the company's top line.
    - <b>Furniture (Chairs):</b> Following closely, the "Chairs" sub-category within Furniture achieved $328,449.10 in sales. This indicates robust performance within the Furniture segment, likely driven by both individual and corporate customers.

    These top-performing sub-categories demonstrate significant market capture and should be continually supported through effective inventory management, competitive pricing, and targeted promotional activities.

  - <b>Lowest Performing Sub-Categories by Sales:</b>
    Conversely, several sub-categories within "Office Supplies" show significantly lower sales figures, indicating areas that may require strategic reassessment:
      - <b>Office Supplies (Fasteners):</b> This sub-category recorded the lowest sales at just $3,024.28.
      - <b>Office Supplies (Labels):</b> Sales for Labels were $12,486.31.
      - <b>Office Supplies (Envelopes):</b> This sub-category generated $16,476.40 in sales.
    
    The consistently low sales across these Office Supplies sub-categories suggest potential challenges such as low demand, high competition, or perhaps insufficient marketing efforts. For these segments, Superstore Inc. may need to:

    - <b>Re-evaluate Product Offerings:</b> Determine if these products align with current market needs or if there are more profitable alternatives.

    - <b>Optimize Inventory:</b> Avoid overstocking to minimize holding costs given the low sales volume.

    - <b>Explore Bundling Opportunities:</b> Consider bundling these items with higher-selling products to increase their visibility and sales.

    - <b>Analyze Profitability:</b> A deeper dive into the profitability of these low-sales items is essential, as some might still be profitable despite low volume, while others might be dragging down overall profit margins.

    Understanding both the high and low performing sub-categories is instrumental in allocating resources effectively and developing targeted strategies to maximize revenue and profitability across Superstore Inc.'s entire product portfolio.
    Further analysis would involve examining the profit margins and return rates for these specific sub-categories to gain a complete picture of their financial contribution.

- <b>Sales Trend by Month-Year:</b> A continuous line chart displaying sales trends over time, with the X-axis formatted as "MMM YY." Tooltips show Month-Year and sales value in thousands.
  Analyzing the sales trend over time provides insight into seasonal patterns and overall growth trajectory:
    - <b>Highest Sales Month:</b> November 2021 recorded the highest sales at $118K. This peak likely aligns with holiday shopping seasons or major promotional events.
    - <b>Lowest Sales Month:</b> April 2018 saw the lowest sales at $28K. Identifying consistent low-performing months can help in planning targeted marketing campaigns or inventory adjustments during these periods.

<br>

<b>Business Question(s)</b>

-  What are the overall total sales, profit, and volume for the Superstore?
    - <b>Total Sales:</b> $2,297,200.86
    - <b>Total Profit:</b> $286,397.02
    - <b>Total Volume (Quantity Sold):</b> 37,873 units   

-  What is the average sales amount per customer, and how does this metric differ across various customer segments or ship modes?
    - The overall average sales amount per customer is $2,896.85.
    
    - <b>Across Customer Segments:</b> Corporate customers have the highest average sales per customer ($2,992.15), followed by Home Office ($2,903.06), and then Consumer ($2,839.61).
    
    - <b>Across Ship Modes:</b> Customers opting for "Standard-Class" shipping have a significantly higher average sales amount per customer ($1,754.80) compared to other modes like First-Class ($711.39), Second-Class ($834.90), and Same-Day ($565.48). This suggests that larger orders, or customers making bulk purchases, might prefer or qualify for standard shipping options. 

---

<h3>B. Segment Regional Analysis</h3>

<br>

<b>Business Question(s)</b>

  -  Which regions contribute the most to total sales, and what is their percentage share of the overall sales pie?
    - The geographic distribution of sales reveals distinct contributions from each of Superstore Inc.'s regions:
      - <b>West:</b> $$725,457.82$ (31.58% of total sales)
      
      - <b>East:</b> $$678,781.24$ (29.55% of total sales)
      
      - <b>Central:</b> $$501,239.89$ (21.82% of total sales)
      
      - <b>South:</b> $$391,721.91$ (17.05% of total sales)
      
      The West and East regions are the primary revenue drivers for Superstore Inc., collectively accounting for over 60% of total sales. The Central and South regions, while contributing significantly, represent smaller portions of the overall sales pie.
  
  -  Are there any regions that are underperforming in terms of sales, and why might that be the case?
    -  Based on sales volume, the South and Central regions are comparatively underperforming. The "why" for underperformance is multi-faceted and could stem from:
      - <b>Market Saturation/Competition:</b> Higher competition or a more saturated market in these regions could limit sales growth.
      
      - <b>Demographics/Economic Factors:</b> Differences in population density, economic conditions, or purchasing power.
      
      - <b>Operational Inefficiencies:</b> Higher shipping costs, less effective local marketing, or less optimized logistics compared to other regions.
      
      - <b>Product Fit:</b> The product assortment might not be as well-tailored to the specific needs or preferences of customers in these regions.
      
      - <b>Regional Management Effectiveness:</b> As per the sample_superstore_people.csv, the effectiveness of regional managers and their teams could play a role.
      
      - Further analysis, including profit margins by region, is crucial to determine if low sales are mitigated by higher profitability or if they represent a deeper issue.

  
  -  What are the top 'N' performing states by sales, and how does changing 'N' reveal different insights about geographical sales concentration?
    -  Examining the top 'N' performing states by sales allows for a granular understanding of geographical sales concentration.
       For instance:
        - <b>Top 5 States by Sales:</b>
          - <b>California:</b> $$457,687.63$
          
          - <b>New York:</b> $$310,876.27$
          
          - <b>Texas:</b> $$170,188.05$
          
          - <b>Washington:</b> $$138,641.27$
          
          - <b>Pennsylvania:</b> $$116,511.91$
          
      As previously noted in the KPI analysis, California and New York are overwhelmingly dominant. Changing 'N' from 5 to 10 (as provided by the user in a previous prompt, including Florida, Illinois, Ohio, Michigan, and Virginia) highlights a broader distribution but still emphasizes the concentration within a relatively small number of states.
      
      Insight from changing 'N': A small 'N' (e.g., top 5) reveals the most critical revenue hubs, indicating where the majority of sales efforts might be focused. Increasing 'N' (e.g., top 10, top 20) helps identify the next tier of significant markets, which might represent growth opportunities or states that are important for overall market presence, even if their individual contribution is smaller than the absolute top performers. It also helps to visualize the "long tail" of sales distribution, identifying states with minimal sales that might not warrant significant direct investment.

  
  -  How do different customer segments (e.g., Consumer, Corporate, Home Office) contribute to overall sales and profit?
    -  Customer segments show varying contributions to both sales and profit:
     
        - <b>Consumer Segment:</b>
            - <b>Total Sales:</b> $1,161,401.34
            - <b>Total Profit:</b> $134,119.21
            - <b>Profit Ratio:</b> 11.55%
          
          The Consumer segment drives the highest total sales and profit volume, being the largest customer group. However, its profit ratio is slightly lower than Corporate and Home Office segments.
          
       - <b>Corporate Segment:</b>
           - <b>Total Sales:</b> $706,146.37
           - <b>Total Profit:</b> $91,979.13
           - <b>Profit Ratio:</b> 13.03%
  
         The Corporate segment shows a healthier profit ratio compared to Consumers, indicating potentially more efficient sales or higher-margin product purchases within this group.
       
       - <b>Home Office Segment:</b>
       
           - <b>Total Sales:</b> $429,653.15
           - <b>Total Profit:</b> $60,298.68
           - <b>Profit Ratio:</b> 14.03%
  
         The Home Office segment, while having the lowest total sales volume, boasts the highest profit ratio. This suggests that sales to home offices are highly efficient or involve products with better margins. This segment might be a key focus for increasing profitability.

  
  -  Does the choice of shipping mode impact sales or profit margins?

     Yes, the choice of shipping mode does appear to impact both total sales and profit margins:

      - <b>Standard Class:</b>
        - <b>Total Sales:</b> $$1,358,215.74$
        - <b>Total Profit:</b> $$164,088.79$
        - <b>Profit Ratio:</b> 12.08%
  
       Standard Class is the most frequently used shipping mode and accounts for the vast majority of both sales and profit. Its profit ratio is slightly below the overall average.
      
     - <b>Second Class:</b>
       - <b>Total Sales:</b> $$459,193.57$
       - <b>Total Profit:</b> $$57,446.64$
       - <b>Profit Ratio:</b> 12.51%

      Second Class has a slightly better profit ratio than Standard Class.
      
     - <b>First Class:</b>
        - <b>Total Sales:</b> $$351,428.42$
        - <b>Total Profit:</b> $$48,969.84$
        - <b>Profit Ratio:</b> 13.93%

      First Class shipping shows the highest profit ratio among all modes. This could be due to higher per-item profit margins on products that typically use First Class, or perhaps customers willing to pay more for faster delivery also purchase higher-value goods.
      
     - <b>Same Day:</b>
       - <b>Total Sales:</b> $$128,363.12$
       - <b>Total Profit:</b> $$15,891.76$
       - <b>Profit Ratio:</b> 12.38%

      Same Day delivery has a profit ratio comparable to Second Class, but its overall sales and profit contribution are the lowest.

      The data suggests that while Standard Class handles the bulk of the sales volume, First Class shipping is the most profitable mode per dollar of sales. This might indicate that customers prioritizing speed are less price-sensitive or purchase higher-margin items. 
        
 
  
  -  Can we identify specific states or regions that are consistently profitable versus those that are consistently less profitable, despite high sales volume?

      By analyzing sales and profit ratios at the state level, we can identify such discrepancies:

        <b>High Sales, Low/Negative Profit States:</b>

        - These states generate significant sales but exhibit alarmingly low or negative profit margins, indicating deep-seated issues that erode profitability.
        
          - Ohio: Total Sales: $$78,258.14$, Total Profit: $-16,971.38, Profit Ratio: -21.69%
          
          - Illinois: Total Sales: $$80,166.10$, Total Profit: $-12,607.89, Profit Ratio: -15.73%
          
          - Texas: Total Sales: $$170,188.05$, Total Profit: $-25,729.36, Profit Ratio: -15.12%
          
          - North Carolina: Total Sales: $$55,603.16$, Total Profit: $-7,490.91, Profit Ratio: -13.47%
          
          - Pennsylvania: Total Sales: $$116,511.91$, Total Profit: $-15,559.96, Profit Ratio: -13.35%
          
          - Florida: Total Sales: $$89,473.71$, Total Profit: $-3,399.30, Profit Ratio: -3.80%
          
          States like Texas, Ohio, Pennsylvania, Illinois, North Carolina, and Florida are critical areas for intervention. Despite their relatively high sales volumes (some even in the top 10 for sales), their substantial negative profit margins suggest severe problems, likely due to aggressive discounting, high shipping costs, or a disproportionate number of returns in these areas.
        
      <b>Consistently Profitable States (High Sales, High Profit Ratio):</b>
        
        - These states demonstrate both strong sales volume and healthy profit margins, representing successful market operations.
            - Indiana: Total Sales: $$53,555.36$, Total Profit: $$18,382.94$, Profit Ratio: 34.33% 
            - Georgia: Total Sales: $$49,095.84$, Total Profit: $$16,250.04$, Profit Ratio: 33.10%  
            - Michigan: Total Sales: $$76,269.61$, Total Profit: $$24,463.19$, Profit Ratio: 32.07% 
            - Virginia: Total Sales: $$70,636.72$, Total Profit: $$18,597.95$, Profit Ratio: 26.33% 
            - Washington: Total Sales: $$138,641.27$, Total Profit: $$33,402.65$, Profit Ratio: 24.09% 
            - New York: Total Sales: $$310,876.27$, Total Profit: $$74,038.55$, Profit Ratio: 23.82%  
            - California: Total Sales: $$457,687.63$, Total Profit: $$76,381.39$, Profit Ratio: 16.69%
              
          States like California, New York, Washington, Michigan, Indiana, Georgia, and Virginia are strong performers, demonstrating that high sales can indeed translate into significant profits. Their strategies and operational efficiencies should be studied for best practices that can potentially be replicated in underperforming regions. 




---

<h3>C. Product/ Category Analysis</h3>

<br>

<b>Business Question(s)</b>

  - Which sub-categories generate the highest sales, and how does this vary across different product categories?

    The product portfolio shows varying sales contributions across categories and their respective sub-categories.

      - <b>Overall Top 10 Sub-Categories by Sales:</b>
  
          The highest sales are concentrated in Technology and Furniture, with Office Supplies also having a strong presence.
        
           - <b>Technology - Phones:</b> $330,007.05
            
           - <b>Furniture - Chairs:</b> $328,449.10
            
           - <b>Office Supplies - Storage:</b> $223,843.61
            
           - <b>Furniture - Tables:</b> $206,965.53
            
           - <b>Office Supplies - Binders:</b> $203,412.73
            
           - <b>Technology - Machines:</b> $189,238.63
            
           - <b>Technology - Accessories:</b> $167,380.32
            
           - <b>Technology - Copiers:</b> $149,528.03
            
           - <b>Furniture - Bookcases:</b> $114,880.00
            
           - <b>Office Supplies - Appliances:</b> $107,532.16
          
      - <b>Top Sub-Category within each Product Category:</b>
            
           - <b>Technology:</b> `Phones` lead with $330,007.05 in sales.
            
           - <b>Furniture:</b> `Chairs` are the top performers with $328,449.10 in sales.
            
           - <b>Office Supplies:</b> `Storage` is the highest-selling sub-category at $223,843.61.
  
      This variation highlights that each major product category has its own dominant sub-category. While "Phones" and "Chairs" are the two highest-grossing sub-categories overall, "Storage" is the powerhouse within Office Supplies. This indicates that sales strategies should be tailored to the specific dynamics of each category's top performers.





- Are there any particular sub-categories that, while having high sales, might have low-profit margins, indicating a need for pricing or cost review?

  Yes, an analysis of sales volume versus profit margins reveals several sub-categories that, despite generating significant sales, struggle with profitability. These are crucial areas for pricing or cost review:

    - <b>Sub-Categories with High Sales but Low Profit Margins (Profit Ratio < 10%):</b>
  
      - <b>Tables:</b>
        - <b>Total Sales:</b> $206,965.53
        -	<b>Total Profit:</b> $ -17,725.48
        -	<b>Profit Ratio:</b> -8.56%
    
            Tables represent a significant sales volume but are currently operating at a substantial loss. This sub-category demands immediate attention for pricing adjustments, cost reduction, or re-evaluation of its strategic importance.
  
        <b>Bookcases:</b>
          -	<b>Total Sales:</b> $114,880.00
          -	<b>Total Profit:</b> $ -3,472.56
          -	<b>Profit Ratio:</b> -3.02%
        
            Similar to Tables, Bookcases are unprofitable despite decent sales. This suggests issues with either high purchase costs, aggressive discounting, or high associated operational/shipping expenses.
          
        <b>Machines:</b>
          -	<b>Total Sales:</b> $189,238.63
          -	<b>Total Profit:</b> $3,384.76
          -	<b>Profit Ratio:</b> 1.79%
        
            Machines generate high sales but yield very minimal profit. The extremely low profit ratio suggests that the current pricing or cost structure is barely covering expenses. This sub-category is a prime candidate for margin improvement initiatives.
        
        <b>Chairs:</b>
          - <b>Total Sales:</b> $328,449.10
          - <b>Total Profit:</b> $26,590.17
          - <b>Profit Ratio:</b> 8.10%
        
            Although Chairs are one of the top-selling sub-categories, their profit ratio (8.10%) is below the overall company average and significantly lower than other profitable sub-categories. This high-volume, relatively low-margin scenario presents a significant opportunity to increase overall company profitability if margins can be improved even slightly.
        
        <b>Storage:</b>
          -	<b>Total Sales:</b> $223,843.61
          -	<b>Total Profit:</b> $21,278.83
          -	<b>Profit Ratio:</b> 9.51%
        
            Storage also falls into the high sales, relatively low-profit margin category. While positive, its profit ratio indicates room for improvement to align with higher-performing sub-categories.
        
      These findings underscore the importance of not just looking at sales volume but also the corresponding profitability. Sub-categories like "Tables," "Bookcases," and "Machines" are actively eroding profit, while "Chairs" and "Storage" represent missed opportunities for higher returns given their sales prominence. Targeted reviews of pricing strategies, supplier costs, and operational efficiencies for these sub-categories are highly recommended.
      
---

<h3>D. Trend & Seasonality Analysis</h3>

<br>

<b>Business Question(s)</b>

  - How do sales trends vary month-over-month and year-over-year? Are there any seasonal patterns or significant spikes/drops in sales?

    Analyzing sales data over time reveals clear trends and significant seasonal patterns for Superstore Inc.

      -	<b>Year-over-Year Sales Trend:</b>

        - <b>2018:</b> $484,247.50
          
        -	<b>2019:</b> $470,532.51
          
        -	<b>2020:</b> $609,205.60
          
        - <b>2021:</b> $733,215.26
    
        The yearly sales trend indicates a fluctuating but generally upward trajectory. There was a slight dip in 2019 compared to 2018, but a strong recovery and significant growth in 2020 and 2021. This suggests that the company is experiencing overall growth, especially in recent years.

      -	<b>Month-over-Month Sales Trend and Seasonal Patterns:</b>

       	  The monthly sales data, aggregated across all years, highlights distinct seasonal patterns:

       	  -	<b>Peak Sales Months:</b> Sales consistently surge in the latter part of the year, with November ($352,461.07) and December ($325,293.50) showing the highest figures. September ($307,649.95) also performs exceptionally well. This strong performance towards the end of the year is a clear indication of holiday season impact and possibly back-to-school or end-of-year corporate purchasing.
                
          -	<b>Trough Sales Months:</b> Conversely, February ($59,751.25) and January ($94,924.84) consistently record the lowest sales. This aligns with a typical post-holiday slowdown. April also shows relatively lower sales compared to surrounding months.
                
          - <b>Mid-Year Stability:</b> Months from May to August generally show moderate and relatively stable sales, without significant spikes or drops, after the spring dip and before the autumn surge.
            
              
     -	<b>Significant Spikes and Drops (from Month-Year Trend):</b>
    
           Examining the Sales Trend by Month-Year provides a more granular view of specific performance:
      
           -	<b>Highest Sales Spike:</b> November 2021 stands out with the highest single-month sales at $118,447.82. This confirms the peak season's strong influence and suggests particularly successful campaigns or high demand in that period.
           -	<b>Lowest Sales Drop:</b> The lowest sales month observed is February 2018 with $4,519.89, which is significantly lower than the overall monthly average. While February generally has low sales, this specific month represents an extreme trough. The overall April sales were noted as lowest in the previous KPI analysis at $28K (April 2018).
    
    -	<b>Summary of Sales Trends:</b>
    
          Superstore Inc. exhibits a clear seasonal pattern with sales peaking in the last quarter of the year (September-December) and dipping in the first quarter (January-February). This strong seasonality indicates the importance of strategic planning around these periods, including inventory management, marketing campaigns, and staffing adjustments. The overall year-over-year trend shows healthy growth, suggesting effective long-term strategies despite monthly fluctuations. Further investigation into the specific events or campaigns during peak sales months (e.g., Nov 2021) and the reasons for extreme drops in low-performing months could yield actionable insights.
    
    




---
