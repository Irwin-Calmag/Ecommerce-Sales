## E-Commerce Sales Analysis
### Project Background
An E-Commerce Sales Company is a business that sells products or services online through digital platforms. It operates via websites, mobile apps, or online marketplaces. This project analyzes e-commerce sales data by focusing on key metrics such as Total Profit, Profit Margin (%), Sales by Product Category, and Average Order Value. The goal is to provide decision-makers with insights into sales growth, seasonality, and revenue trends, enabling them to make informed, data-driven business decisions.


### Objectives
1. Sales and Profit Analysis: Evaluation of performance differences on sales, profit, quantity and profit margin, this helps compare product categories to see which ones drive the highest revenue and profit and hence 
   help in inventory strategies and allocation of  marketing budgets effectively.
2. Product Category Performance: Determine the best-performing and worst-performing product categories,regions and states and also top 5 best and worst products. This will helps marketing teams focus efforts on high- 
   performing areas while addressing underperforming segments to drive profitability and growth.
3. Shipping and Delivery Performance: Analyze which shipping types cause the most delays, identify regions or products with frequent delivery issues and compare scheduled vs. actual delivery time to assess efficiency. This 
   will helps stakeholders to work on optimizing shipping strategies to minimize delays and improve overall service reliability, hence enhancing customer satisfaction.

  An interactive power bi dashboard can be downloaded here.
  ### Data Strucrure & Initial Checks
  The dataset consists of the following columns:
 1. Calendar Table :  Reference table that includes Product name,Product name id,product family and product type... Allows us to evaluate which products are most popular and profitable.
 
 2.Ecommerce: Sales, COGS, order date and quantity. It helps us track purchasing patterns and 
    identify high-performance products.
    -Each unique record represents a sales transaction with information about the sales dates as well as the sales quantity and product. 
 
 3. State Codes: The dataset includes plants geographical details such as country, country_code,latitude and longitude. This helps us evaluate regional performance and tailor marketing strategies to different areas.
    
Include an ERD (Entity relationship diagram)- can be created using CANVA 
  ### Executive Summary:
In 2022, sales have declined (YoY YTD = -0.83%), with October ($1.11M) recording the highest sales and December ($0.74M) the lowest. While the quantity sold has decreased (-7.29%), profit (+4.50%) and profit margin (+5.37%) have increased, suggesting a rise in product prices. Office Supplies remains the top-selling category ($6.92M), but sales growth has declined in both Office Supplies (-1.22%) and Technology (-1.37%), whereas Furniture sales have increased (+0.73%). The company should analyze the marketing strategies that boosted Furniture sales and apply them to other categories. The West Region leads in performance (YTD = $3.72M), with California contributing $2.34M, while the South Region ($1.87M) is the weakest, with Louisiana performing the worst ($45.88K).
* ADD SOMETHING ABOUT SHIPPING HERE*

The following section will explore additional contributing factors and highlight key opportunity areas for improvement.
 
  ### Insights Deep-Dive

  #### Sales and Profit Analysis:
  - In 2022, sales followed an alternating upward and downward trend, peaking in October ($1.11M), while December ($0.74M) recorded the lowest sales. 
  - The West and East Regions contribute 60% of total sales, with the West Region alone accounting for 32%. Within the West, California contributes 63% of the region’s sales. The South Region ranked as the lowest- 
    performing, contributing only 16% of total sales, with Louisiana being the weakest-performing state.
  

  #### Product Category Performance:

  - Office supplies is the category having the maximum number of sales ($6.92M). While there is a decline in sales growth in both Office supplies(-1.22%) and technology (-1.37%), furniture has increased its sales by 0.73% 
    hence the company should reveiw the strategies they applied in marketing furnitures to the other product categories.
  - YTD sales by customer segment shows that Consumers lead with $5.98M (YoY -0.55%), followed by Corporates at $3.50M (YoY -0.66%), while Home Offices have the lowest sales at $2.06M (YoY -1.93%), 
    experiencing the largest decline.
  - With the Home Office segment experiencing the largest decline (YoY -1.93%), there is a need for targeted promotions, personalized marketing campaigns, and bundled offers to re-engage this customer group and boost 
    sales.
  - The Staple Envelopes is the top-performing product, contributing $57.09K in YTD sales, while the Rediform S.O.S Phone Message Books is the lowest-performing product, with YTD sales of only $0.18K.    
  

  #### Shipping and Delivery Performance:
  - Standard Class is the most frequently used shipping method, accounting for 60% of total shipments, despite having a longer delivery time of 4 days. This suggests that customers may prioritize cost savings over faster 
    delivery, as Standard Class is typically the most affordable option.
 - Second Class (19%) and First Class (15%) shipping options, which generally offer moderate delivery speeds at a higher cost, are used significantly less than Standard Class. This indicates that while some customers are 
   willing to pay for faster shipping, the majority still opt for economical delivery choices.
 -  Same Day shipping accounts for only 6% of total shipments, even though it has the fastest delivery time of 0 days. This low adoption rate suggests that factors such as higher shipping costs, limited product 
    availability for same-day delivery, or customer preferences for planned purchases over urgent ones may be at play. 
 ### Methodology & Skills(Technical Details):
The technical analysis involved:
Excel (Power query and power pivot) : for data extraction, and advanced exploratory data analysis (EDA) via interactive pivot tables and charts.[here]..

SQL: CTEs, Joins, Case, aggregate functions
 - SQL query that extracts, cleans, and transforms the data from the database.

Power BI: Dax, writing functions, ETL, calculated columns, data visualization, data modeling 
 -  Build a dashboard in Power BI that tracks the gross profit change across the years.
 -  Conduct a more detailed analysis in Power BI to drill down and determine the worst performing countries and plant categories.


  ### Recommendations:
  ...THEY SHOULD BE TIED TO THE INSIGHTS WEVE FOUND- LIST THE PRODUCTS AND GIVE A REASON WHY SO E.G GIVEN THE UPWARD TREND IN ELECTRIC LETTER OPENERS AND BLANK IN THE TECHNOLOGY  CATEGORY CONSIDER RE-ALLOCATING MARKETTING BUDGET FOR THE NEXT 2 YEARS TO FOCUS ON THESE PRODUCTS....NB: what if asked this in an interview(16:01)..can explain it??
- Hire marketing managers, run influencer campaigns, and use retargeting ads in both office 
   supplies and technology product categories to help boost the sales.
- Provision of state-specific discount codes and offer free shipping or faster delivery in 
    targeted regions that are underperforming.
- Run holiday smart promotions e.g digital gift cards to attract customers, and exclusive 
    discounts in the month of december to help maximize revenue.
- Analyze California’s success (63% of West’s sales) and implement similar regional marketing campaigns.




### Caveats and Assumptions:
   ...DATA CLEANING PROCESS AND ANY ASSUMPTIONS YOU MADE ABOUT THE DATA.
   Data Completeness: A significant portion of revenue(15%) came from 'unclassified' categories, which may reflect product categorization inconsistencies or data entry issues.     
  
