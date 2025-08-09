<h2>Case Study: Optimizing Superstore Sales Performance for Enhanced Profitability</h2>

<h2> Data Source</h2>

The analysis utilizes the [Sample_Superstore.xls](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Data/sample_superstore.xls) dataset, which is a sample dataset readily available in Tableau Desktop. The data connection is established as an extract, not a `Live` connection.

---
<h2>Data Description</h2>

The dataset is composed of three interconnected tables: `Orders`, `People`, and `Returns`.

  - The`Order` table contains 9,994 detailed records of every sales order placed. It is the central table of the dataset and includes key information about each transaction such as Order ID, Order Date, Customer ID, Segment, Product Name, and State.
  - The `People` table is a small lookup table with 4 entries that maps each of the four geographical regions to its respective regional manager.
  - The `Returns` table contains a list of 800 orders that have been returned. It can be used to identify which orders from the Orders.csv file were returned.


<h2>Entity Relationship Diagram (ERD)</h2>


![Sample Superstore Dataset ERD](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Images/Sample%20Superstore%20Dataset%20ERD.png)

