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
  - OVERALL WHAT THE AVERAGE SALES AND REVENUE ARE ACROSS THESE MONTHS, WHAT THE AVERAGE GROWTH RATES ARE AND THE BEST PERFORMING MONTHS AND THE WORST PERFORMING MONTHS,,,THEN,,,THE BEST PERFORMING CATEGORIES ,,,AND THEN,,,THE BEST PERFORMING PROVINCES (say what those values are)
SAY SOMETHING LIKE AN UPWARD TREND IN MONTHLY SALES AND REVENUES - SPECIFY THE MONTHS .Key performance indicators(WHICH ONES - DEEP DIVE)  have all shown the year-over-year sales changes.Key performance indicators(WHICH ONES - DEEP DIVE)  have all shown the year-over-year sales changes. the following section will explore additional contributing factors and highlight key opportunity areas for improvement.
  ### Insights Deep-Dive
...ACTUAL NUMBERS, ACTUAL GROWTH RATES, THE MONTHS AND THE PRODUCTS THAT DO WELL OR BADLY AND  BE MORE SPECIFIC
  #### Sales Trends:
  With respect to current year, sales are going down (YoY YTD = -0.83%), October being the month 
  with high sales and December the one with low sales. There is also a decline in quantity 
  sold(-7.29%) but increase in profit(YoY YTD = 4.50%) and profit Margin (5.37%), implying price 
  increment in their products.

  #### Product Category Performance:
  .... plant categories, regions(west....), countries(Bottom 10) - ALL THESE WITH SPECIFIC VALUES.
...ACTUAL NUMBERS, ACTUAL GROWTH RATES, THE MONTHS AND THE PRODUCTS THAT DO WELL OR BADLY AND  BE MORE SPECIFIC
.............
  Office supplies is the category having the maximum number of sales ($6.92M). While there is a 
  decline in sales growth in both Office supplies(-1.22%) and technology (-1.37%), furniture has 
  increased its sales by 0.73% hence the company should reveiw the strategies they applied in 
  marketing furnitures to the other product categories.
  West Region is the leading region in terms of performance (YTD = $3.72M) with California being the 
  best performing state contributing upto $2.34M of the sales, while South Region is the worst
  performing region ($1.87M) with Louisiana state having a very poor performance ($45.88K).

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


### Caveats and Assumptions:
   ...DATA CLEANING PROCESS AND ANY ASSUMPTIONS YOU MADE ABOUT THE DATA.
   Data Completeness: A significant portion of revenue(15%) came from 'unclassified' categories, which may reflect product categorization inconsistencies or data entry issues.     
  
