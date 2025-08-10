<h2>Case Study: Optimizing Superstore Sales Performance for Enhanced Profitability</h2>

<h2> Data Source</h2>

The analysis utilizes the [Sample_Superstore.xls](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Data/sample_superstore.xls) dataset, which is a sample dataset readily available in Tableau Desktop. The data connection is established as an extract, not a `Live` connection.

---
<h2>Data Description</h2>

The analysis is based on a detailed dataset comprised of three interconnected tables from the `sample_superstore.xls` file: <b>Orders</b>, <b>Returns</b>, and <b>People</b>. The Orders table serves as the central hub of this data, containing 9,994 detailed records of every sales order placed. It includes key information for each transaction, such as Order ID, Order Date, Customer ID, Segment, Product Name, and State, along with crucial financial metrics like Sales, Quantity, Discount, and Profit.

The <b>Returns</b> table augments this data with a list of 800 records for 296 unique returned orders. The Order ID in the Returns table acts as a foreign key, establishing a one-to-many relationship with the Orders table and allowing for a more accurate assessment of net profitability by linking each return record back to its specific transaction.


<h2>Entity Relationship Diagram (ERD)</h2>


![Sample Superstore Dataset ERD](https://github.com/LashawnFofung/Superstore-Sales-Performance/blob/main/Images/Sample%20Superstore%20Dataset%20ERD.png)

