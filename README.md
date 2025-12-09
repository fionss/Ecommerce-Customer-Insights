<h1>E-commerce and Customer Insights Sales Report</h1>
<h4>Excel and Power BI End-to-End Analytics Project</h4>

<h2>1. Background and Overview</h2>
<p>This project analyzes the sales perfomance for a global e-commerce company that was established in November 2023. The business sells consumer products on both web and mobile applications, reaching customers across multiple countries.</p>

<p>The dataset contains transactional-level sales data where each row represents a unique order. Some key fields include: </p>
<ul>
  <li>Invoice Date</li>
  <li>Customer ID</li>
  <li>Unit Price and Quantity</li>
  <li>Sales Channel</li>
  <li>Country</li>
</ul>

<p>Using Excel for data cleaning and Power BI for advanced modelling and visualization, this project uncovers insights across: </p>
<ul>
  <li>Sales trends</li>
  <li>Channel performance</li>
  <li>Customer purchasing behaviour</li>
  <li>Geograhic revenue distribution</li>
  <li>Product and category performance</li>
</ul>

<h2>2. Data Structure and Overview</h2>
<h3>Data Preparation - Excel</h3>
<h4>Data Cleaning and Validation</h4>
<ul>
  <li>Removed duplicates(119 duplicates were found) especially across invoice and product records to ensure data intergrity.</li>
  <li>Filtered for blanks and missing values.</li>
  <li>Identified and corrected data errors, like the inconsistent product descriptions and misaligned channel names</li>
  <li>Corrected data entry errors, like the inconsistent product and incorrect channel names.</li>
  <li>Verified </li>
</ul>

<h3>Data Model and Structure - Power BI</h3>
<p>After data cleaning in Excel, the dataset was modeled in Power BI using a star schema for better performance and optimized analytics. This is an image of the star schema : </p>

<img width="590" height="325" alt="image" src="https://github.com/user-attachments/assets/9ddbdde8-acf5-4ea2-9b43-e9c632934dfd" />



<h4>Data Model Features</h4>
<ul>
  <li>Active relationship between FactSales and dimension tables.</li>
  <li>Time intelligence made through DimDate.</li>
  <li>DAX measures created for advanced business metrics:</li>
  <ul>
    <li>Total Revenue</li>
    <li>Total Orders</li>
    <li>Total Quantity</li>
    <li>Total Customers</li>
    <li>Average Order Value</li>
    <li>Average Revenue per Customer</li>
    <li>YoY Growth</li>
    <li>MoM Growth</li>
    <li>Customer Retention Rate</li>
    <li>New Customers</li>
    <li>Returning Customers</li>
  </ul>
</ul>

<h2>3. Executive Summary</h2>
<p>Revenue has shown consistent month-over-month growth since the company launched even though it's a slight increase, it's still a positive that shows a strong need for improvement as companies in the early stage aim for at least 10% . The customer retention rate is 0, showing that there are no return customers and all the sales made were by first time customers. This shows that every single customer was lost from the time the company was launched, this shows that there may be isues with the product, overall customer serviceand there is need for immediate and drastic measures to be taken to prevent an end to the business. It shows no loyalty from the customers and a major failure in the customer journey, support, product quality or market fit </p>

<h2>4. Insights</h2>
<ol>
  <li>Sales Trends</li>
  <ul>
    <li>Revenue increases steadily especially in the beginning months, then peaked in November 2024 with a total revenue of $282,258 and then remained steady in that range the end of 2025.</li>
    <li>The AOV is stable, showing consistensy int customer spending behaviour.</li>
    <li>The YoY growth is at 1.81% which isn't terrible but not good for a company at this stage in business who also has high-growth goals.</li>
  </ul>
  <li>Product and Category Performance</li>
  <ul>
    <li>Toys are the top perfoming product category, followed by beauty, home, books, electronics and then clothing.</li>
    <li>With toys the top performing products were action figures and dolls, though the highest revenue for the products came from the biography and children books in the book category.</li>
  </ul>
  <li>Channel Performance</li>
  <ul>
    <li>The top performing channels are paid ads and social media, with referrals, organic and email coming close.</li>
    <li>Paid ads in comparison to social media has a higher total revenue but a lower AOV. This shows an opporunity for optimization.</li>
  </ul>
  <li>Geographic Distribution</li>
  <ul>
    <li>Revenue is concentrated in a few major countries.</li>
    <li>United Kingdom has the highest revenue followed by India then France.</li>
    <li>Need more investment into United States, Canada, Nigeria and Germany to increase sales there through promotions and marketing.</li>
    <li>Look into other emerging markets to improve reach.</li>
  </ul>
  <li>Customer Behaviour</li>
  <ul>
    <li>All the customers are first time customers, there's no return customers.</li>
    <li>The AOV is high</li>
    <li>Limited data coverage on customers for in depth behavioural analysis.</li>
  </ul>
</ol>

<h2>5. Recommendations</h2>
<h4>Product Strategy</h4>
<ul>
  <li>Invest more into higher-performing product categories.</li>
  <li>Evaluate underperforming items for re-pricing, re-packaging or removal.</li>
</ul>
<h4>Channel Optimization </h4>
<li>Double down on high performing channels </li>
<li>Grow mid-performing channels</li>
<li>Fix the underperforming channel</li>
<li>Investigate "Unknown" channel traffic</li>

<h4>Customer Life Cycle Strategy</h4>
<li>Introduce loyalty or rewards programs to improve customer retention.</li>
<li></li>

<h4>Geographic Expansion</h4>
<li>Allocate more marketing resources to top performing countries</li>


<h2>6. Assumptions</h2>


