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
  <li>Filtered for blanks and missing values especially within CustomerID, Country, Product and InvoiceDate fields.</li>
  <li>Identified and fixed data errors, like inconsistent product descriptions and misaligned channel names.</li>
  <li>Corrected data entry errors, particularly where there was inconsistentcy with Product and incorrect Channel names.</li>
  <li>Verified numeric fields, ensuring Quantity and Price contained only positive values.</li>
  <li>Created calculated fields where necessary, such as Total Price and Order Value Category.</li>
  <li>Ensured consistent date formatting across transactional records.</li>
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
<p>The business generated $4.44M in total revenue across 5940 orders, with an Average Order Value of $748.10. This shows some transaction value despite being a newly launched company. With YoY Growth being 1.81% and an MoM Growth at 0.01% this is considered low and shows slow expansion.</p>

<p>When it came to channel performance, Paid Ads and Social Media contributed to the largest share of revenue, followed by Referral and Organic, with Email performing slightly lower but showing potential and Unknown indicating data gaps. Geographically, the United Kingdom generated the most revenue, followed by India and France, this reflects strong engagement in international markets.</p>

<p>Customer behaviour shows that while Average Revenue per Customer is $4.94K, Customer Retention is currently 0%, with all customers classified as new. This highlights a problem an urgent need to build repeat purchasing strategies. High-value customers spent between $12K and $19K, contributing disproportionaltely to revenue. As for products, toys especially action figures and dolls were the strongest category, followed by beauty, home and books. </p>

<p>These insights shows that the business is generating a strong order value, with certain category and channel winners but must improve retention as there is no loyalty from customers and this can mean the business won't be able to survive long term.</p>


<h2>4.Insights and Recommendations</h2>

  <h4>1. Strengthen Retention and Build Repeat Purchasing Behaviour</h4>
  <p>With 0% customer retention and all customers classified as new, the business heavily relies on acquisition of new customers so new retention strategies need to be set. They should be focused on:</p>
  <ul>
    <li>Automated lifecycle emails: a welcome message, post-purchase follow ups, reminders, campaigns etc.</li>
    <li>A loyalty rewards program as an incentive for repeat orders and to increase the customer lifetime value.</li>
    <li>Personalized recommendations based on top-selling products or personal interests.</li>
  </ul>

  <h4>2. Strategically Budget Across Marketing Channels</h4>
  <p>Since Paid Ads and Social Media bring in the highest revenue, followed by Referral and Organic. The channels can be optimized by:</p>
  <ul>
    <li>Amplify top channels and focus on targeting market segments and optimizing creativity.</li>
    <li>Scale referral incentives to reduce cost and grow customers. </li>
    <li>Improve SEO and organic product discovery using content, product optimization.</li>
    <li>Auditing and tracking the "Unknown" channel to improve data accuracy.</li>
  </ul>

  <h4>3. Prioritize High Potential Markets</h4>
  <p>With the United Kingdom, India and France being the highest performing regions. This can be used to advantage by:</p>
  <ul>
    <li>Tailoring campaigns and promotions locally.</li>
    <li>Increase ad spend and partnerships in top regions.</li>
    <li>Conduct segmentaion on gigh order value buyer behaviour and see if it can be replicated in other regions.</li>
  </ul>
  
  <h4>4. Capitalize on Top Performing Product Categories</h4>
  <p>Since Toys, particularly Action Figures and Dolls are the highest revenue items, followed by Beauty, Home and Books: </p>
  <ul>
    <li>Increase inventory and marketing spending on these high demand categories.</li>
    <li>Bundle high-performing items to raise AOV.</li>
    <li>Expand product variations where demand is high i.e other types of toys, toy collections, seasonal toys.</li>
    <li>Introduce cross-selling between products to improve cart value.</li>
  </ul>

  <h4>5. Improve Analytics and Data Quality</h4>
  <p>With having an Unknown channel revenue and already existing data quality issues, this shows that there are gaps in data. So: </p>
  <ul>
    <li>Implement better data standards to improve accuracy in tracking transactions and customers.</li>
    <li>Continue using Power BI dashbpoards to monitor growth, retention and channel performance.</li>
    <li>Introduce UTM standardization across marketing campaings.</li>
  </ul>

  <h4>6. Build A High-Value Customer Strategy</h4>
  <p>The top 10 customers spent between $12k - $18k each, this shows a small but impactful group of high-value buyers.Explore: </p>
  <ul>
    <li>Introduce VIP programs, exclusive discounts, early access etc.</li>
    <li>Personaliza outreach campaigns targeting these customers.</li>
    <li>Look into behavioural patterns to identify future potential high value customers.</li>
  </ul>


<h3>Strategic Outcomes</h3>
<p>Implementing these recommendations will drive revenue growth, improve marketing efficiency, strengthen customer retention and position the company for sustainable long-term success. This project provides key insights into product demand, customer behaviour, channel performance and market strength allowing the business to prioritize growth opportunies.</p>


