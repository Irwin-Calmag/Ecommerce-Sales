## E-Commerce Sales Analysis
### Project Background
An E-Commerce Sales Company is a business that sells products or services online through digital platforms. It operates via websites, mobile apps, or online marketplaces. This project analyzes e-commerce sales data across 2021 and 2022 by focusing on key metrics such as Total Profit, Profit Margin (%), and Sales by Product Category. The goal is to provide decision-makers with insights into sales growth, seasonality, and revenue trends, enabling them to make informed, data-driven business decisions.


### Objectives
1. *Sales and Profit Analysis*: Evaluation of performance differences on sales, profit, quantity and profit margin, this helps compare product categories to see which ones drive the highest revenue and profit and hence 
   help in inventory strategies and allocation of  marketing budgets effectively.
   
2. *Product Category Performance*: Determine the best-performing and worst-performing product categories,regions and states and also top 5 best and worst products. This will helps marketing teams focus efforts on high- 
   performing areas while addressing underperforming segments to drive profitability and growth.
   
3. *Shipping and Delivery Performance*: Analyze the commonly used shipping types, identify regions or products with frequent delivery issues to assess efficiency. This will helps stakeholders to work on optimizing 
   shipping strategies to minimize delays, hence enhancing customer satisfaction.


### Data Strucrure & Initial Checks
The dataset consists of the following columns:
1. *Customers Table*:  Comprises of customers details like First name, last name, customer id, country, segment and the city .  Allows us to evaluate which products are most popular and profitable.
 
2. *Orders Table*: Each unique record represents a sales transaction with information about the order dates, total sales, order id, order quantity and product name.
 
3. *State Codes*: This table gives the state names, latitudes and longitudes.
    
   ![ERD E-commerce](https://github.com/user-attachments/assets/e86243ac-bd86-4963-94a9-58d1d0267c7d)

### Executive Summary:

In 2022, sales have declined (YoY YTD = -0.83%), with October ($1.11M) recording the highest sales and December ($0.74M) the lowest. While the quantity sold has decreased (-7.29%), profit (4.50%) and profit margin (5.37%) have increased, suggesting a rise in product prices. Office Supplies remains the top-selling category ($6.92M), but sales growth has declined in both Office Supplies (-1.22%) and Technology (-1.37%), whereas Furniture sales have increased (0.73%). The company should analyze the marketing strategies that boosted Furniture sales and apply them to other categories. The West Region leads in performance (YTD = $3.72M), with California contributing $2.34M, while the South Region ($1.87M) had the least sales, with Louisiana ($45.88K) being the worst performing state. Additionally, 60% of total shipments are made via Standard Class, even though it has the longest delivery time of 4 days.

Below is the overview page from the powerBI dashboard and more examples are included throughout the report.
![E-Commerce Overview](https://github.com/user-attachments/assets/772469f5-4e7c-419f-b670-3e02ef002f24)



 
### Insights Deep-Dive

#### Sales and Profit Analysis:
- Reflecting on 2022 figures, sales followed an alternating upward and downward trend, peaking in October ($1.11M), with a decline in December reaching $0.74M.
- The West and East Regions contribute 60% of total sales, with the West Region alone accounting for 32%. Within the West, California contributes 63% of the region’s sales. The South Region ranked as the lowest- 
  performing, contributing only 16% of total sales, with Louisiana being the poorest performing state.
- On a month-on-month basis, July was the second-best performing month in sales but had the lowest profit margin (0.10), indicating that the company may have prioritized sales volume over profitability, possibly through 
  mid-year promotions and bulk discounts. In contrast, April recorded the highest profit margin (0.13) despite being among the bottom four months in sales, suggesting a focus on profitability rather than high sales 
  volume. This could be due to fewer discounts and a greater emphasis on selling premium and high-margin products.

  ![Ecommerce-MONTHS](https://github.com/user-attachments/assets/3b9710a9-79d4-4913-8e30-e7349d90c332)

  

#### Product Category Performance:

- Office supplies is the category having the maximum number of sales ($6.92M). While there is a decline in sales growth in both Office supplies(-1.22%) and technology (-1.37%), furniture has increased its sales by 0.73% 
  hence the company should reveiw the strategies they applied in marketing furnitures to the other product categories.
- YTD sales by customer segment shows that Consumers lead with $5.98M (YoY -0.55%), followed by Corporates at $3.50M (YoY -0.66%), while Home Offices have the lowest sales at $2.06M (YoY -1.93%), 
  experiencing the largest decline.
- With the Home Office segment experiencing the largest decline (YoY -1.93%), there is a need for targeted promotions, personalized marketing campaigns, and bundled offers to re-engage this customer group and boost 
  sales.
- The Staple Envelopes is the top performing product, contributing $57.09K in YTD sales, while the Rediform S.O.S Phone Message Books is the lowest performing product, with YTD sales of only $0.18K.    
  

#### Shipping and Delivery Performance:
- Standard Class is the most frequently used shipping method, accounting for 60.51% of total shipments, despite having a longer delivery time of 4 days. This suggests that customers prioritizes cost savings over faster 
  delivery, as Standard Class is typically the most affordable option.
- Second Class (19.22%) and First Class (15.1%) shipping options, which generally offer moderate delivery speeds at a higher cost, are used significantly less than Standard Class. This indicates that while some customers 
  are willing to pay for faster shipping, the majority still opt for economical delivery choices.
- Same Day shipping accounts for only 5.17% of total shipments, even though it has the fastest delivery time of 0 days. This low adoption rate suggests that factors like higher shipping costs, limited product 
  availability for same day delivery and customer preferences for planned purchases over urgent ones are at play.

  ![SHIPPING TYPE E-COMMERCE](https://github.com/user-attachments/assets/646d9081-b9f4-4fd6-81a9-18e6821ebe99)

   

    
   
 ### Recommendations:
 1. *Sales and Marketing Strategy Enhancement*
 - Given the declining performance on both office supplies and technology product categories consider hiring marketing managers and running influencer campaigns for six months to help boost the sales.
 - December being the worst performing month, try to run holiday smart promotions like digital gift cards to attract customers, and exclusive discounts to help maximize revenue.
 2. *Data Analysis and Reporting Enhancement*
 - Consider analyzing California’s success (63% of West’s sales) and implement similar strategies on other states like Louisiana. 
 - Adopt region-specific discount codes, such as SOUTH15 for 15% off, to boost sales in the South Region.
   
 3. *Optimize Pricing for Same Day Shipping*
 - Implementation of discounted same day shipping offers based on order value whereby there is a 10% off same day shipping for orders above $50 and free same day shipping for orders over $100. This 
   encourages larger purchases while making fast delivery more appealing.
 - Expand product availability for same day delivery by strategically positioning high demand products across fulfillment centers to ensure broader and faster same day shipping coverage. 
  




### Caveats and Assumptions:
- **Data Completeness**: A significant portion of revenue(15%) came from 'unclassified' categories, which may reflect product categorization inconsistencies or data entry issues.
- **Stable Demand**: Assuming consistent sales trends across the four regions without accounting for economic variations and local preferences may impact the accuracy of the analysis. This limitation may require the data 
  engineering team to verify whether the observed relationships align with actual market dynamics.


  
