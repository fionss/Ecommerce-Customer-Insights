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




<h4>Data Model Features</h4>
<ul>
  <li>Active relationship between FactSales and dimension tables.</li>
  <li>Time intelligence made through DimDate.</li>
  <li>DAX measures created for advanced business metrics:</li>
  <ul>
    <li>Total Revenue</li>
    <li>Total Orders</li>
    <li>Total Quantity</li>
  </ul>
</ul>





