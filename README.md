<h2>Superstore Sales Performance Analysis: Optimizing Superstore Sales Performance for Enhanced Profitability (Orders from January 2014 - December 2017)</h2>

This repository contains a comprehensive data analysis project focused on understanding and optimizing Superstore Inc.'s sales performance. Leveraging a rich transactional dataset, this project employs a multi-dimensional approach to identify key profitability drivers, uncover performance discrepancies across regions, products, and customer segments, and formulate actionable, data-driven recommendations.

<h2>Background</h2>
Superstore Inc. has experienced inconsistent profitability across different regions, product categories, and customer segments. The company's leadership wants to understand the key drivers of sales and profit, identify areas of underperformance, and develop data-driven strategies to improve overall business performance and maximize profit margins. A comprehensive performance analysis of Superstore was undertaken to identify key trends, performance drivers, and opportunities for enhanced profitability. The core objective was to move beyond high-level sales figures and provide actionable, data-driven insights to improve the company's bottom line. This report details findings from a deep dive into critical areas, including sales trends, profitability drivers, and regional performance, to inform strategic decision-making and steer the company toward sustainable, profitable growth.


<h2>Executive Summary</h2>
Superstore Inc., a prominent retail entity with a diverse product portfolio spanning Furniture, Office Supplies, and Technology, has established a significant market presence across the United States. Serving a wide customer base segmented into Consumer, Corporate, and Home Office, the company achieved over $2.3 million in total sales. However, recent observations indicated inconsistencies in financial performance, leading to a modest profit of $286,397 and a 12.47% profit ratio. The leadership team recognized the critical need to delve deeper into its operational data to understand the underlying factors contributing to these varying levels of sales and profitability. The analysis of 9,994 records across 2014-2017 shows a significant challenge: high sales volume does not consistently translate to profitability. The company's financial performance is uneven, with profitable regions like the West and East, and the Home Office customer segment, standing in contrast to high-revenue, low-profit areas such as Texas and specific product categories like Tables and Bookcases. The key recommendation is to implement a profitability-first strategy. This involves directing marketing efforts and resources to proven successes while strategically intervening in underperforming areas by adjusting pricing and discounts or re-evaluating their market presence. By capitalizing on seasonal sales peaks and focusing on high-margin products and customer segments, Superstore can move towards a more sustainable and financially healthy future.


<h2>Data Structure Overview</h2>

The analysis is based on a detailed dataset comprised of three interconnected tables from the `sample_superstore.xls` file: <b>Orders</b>, <b>Returns</b>, and <b>People</b>. The Orders table serves as the central hub of this data, containing 9,994 detailed records of every sales order placed. It includes key information for each transaction, such as Order ID, Order Date, Customer ID, Segment, Product Name, and State, along with crucial financial metrics like Sales, Quantity, Discount, and Profit.

The <b>Returns</b> table augments this data with a list of 800 records for 296 unique returned orders. The Order ID in the Returns table acts as a foreign key, establishing a one-to-many relationship with the Orders table and allowing for a more accurate assessment of net profitability by linking each return record back to its specific transaction.


![Sample Superstore Dataset ERD](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Images/Sample%20Superstore%20Dataset%20ERD.png)


This project serves as a practical example of how data-driven analysis can inform strategic business decisions to enhance profitability and operational efficiency.

- <b>Read the full report:</b> [HERE](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Case%20Study/Case%20Study-%20Optimizing%20Superstore%20Sales%20Performance%20for%20Enhanced%20Profitability.pdf) for detailed insights and recommendations.





<br>

<h2>Technologies Used:</h2>

- <b>MySQL Workbench:</b> For data cleaning, preprocessing, and analysis.

- <b>SQL:</b> Data manipulation and numerical operations.

- <b>Tableau Desktop:</b> For creating compelling data visualizations and interactive dashboards/stories.

- <b>Microsoft Excel:</b> Source data file (`sample_superstore.xls`).



<h2>How to Use This Repository:</h2>

- <b>Clone the repository:</b> `git clone https://github.com/LashawnFofung/Superstore-Sales-Performance.git`

- <b>Navigate to the project directory.</b>

- <b>Explore the data:</b> Find the [sample_superstore.xls](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Data/sample_superstore.xls) dataset.

- <b>Review the analysis scripts:</b> Examine the Python notebooks or scripts for data processing and analytical methodologies.

- <b>Open Tableau Workbook:</b> Access the [Superstore Sales Performance.twbx](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Tableau/Superstore%20Sales%20Performance%20Case%20Study.twbx) files to view the interactive dashboards and the [Superstore Sales Performance Case Study](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Tableau/Superstore%20Sales%20Performance.twbx).


<br>

<h2>Other Project Documents</h2>

- [Project Management Plan](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Project%20Management/Plan/Project%20Management%20Plan.md)
  - [WBS Overview & Project Timeline](https://youtu.be/t5fny7NXkSs)
  - [WBS (Export from Smartsheet)](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Project%20Management/WBS/Superstore_Sale_Performance_Dashboard_WBS.xlsx)

---
