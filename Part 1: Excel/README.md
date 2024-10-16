# Documentation Part 1: Excel Dashboard
Feel free to check it out yourself, I have attached a copy of it above called Excel Final Dashboard. :) 

  - **Objective:** Develop an executive summary dashboard for 2017 performance and how it compares to 2016                               
  - **Dataset Overview:** 10,000 row transactions table.

  ![image](https://github.com/user-attachments/assets/2a476b3a-48e6-4135-a5fa-e8cb7e5dc875)
(Headers + first five rows)

## Key Business Questions:
1. What are the key drivers of revenue growth in 2017?
2. Which segments, categories, and regions are the most profitable?
3. What sub-categories, cities, and products are experiencing the highest and lowest growth rates?
4. How do different shipping methods and discount classes impact sales and profitability?
5. What are the key trends in revenue over time, and how do they correlate with business cycles?
6. Which cities and sub-categories should we focus on for future expansion?
7. How does our performance in 2017 compare with the previous year, and what does that indicate for 2018?
  

## Data Preparation
Implemented data modeling by separating the data into multiple worksheets (Orders, Product, Customer, Shipment) and creating relationship between them using Primary Keys (PK) and Foreign Keys (FK).
This approach made computations faster, streamlined data management, and facilitated more efficient analysis using pivot tables and charts.
  
![image](https://github.com/user-attachments/assets/eb4d987d-f26f-455c-8a67-e996b78069fd)



**Transactions Worksheet:** Order ID (FK), Customer ID (FK), Product ID (FK), Segment, Sales, Quantity, Discount, Profit                 
**Product Worksheet:** Product ID (PK), Category, Sub-Category, Product Name            
**Customer Worksheet:** CustomerID (PK), Customer Name, Country, City, State, Postal Code, Region               
**Time Worksheet:** Order ID (PK), Order Date, Ship Date, Ship Mode, Days to Ship

## Insights Summary

**What are the key drivers of revenue growth in 2017?**
- Home Office segment, Technology category, Central region, and First Class shipping led revenue growth percentages.
  
**Which segments, categories, and regions are the most profitable?** 
  - Segment: Consumer (49% of total profit)
  - Category: Technology (54% of total profit)
  - Region: East (39% of total profit); Central region saw a notable 148% profit growth.there lets keep it up.
    
**How do sales performance vary across different sub-categories, cities, and products?** !!!!!
  - Sub-categories - 
  - Cities - 
  - Products -


**What sub-categories should we reconsider keeping?**
  - idk yet
    
**What is the impact of different shipping methods on sales and profit margins?**
  - Shipping: First Class showed the highest performance with 117% profit growth; Standard Class remains dominant (52% of all profit and 53% of all revenue), though with declining profit.
  - Discount: Discounts below 20% or no discounts are most profitable; deeper discounts, while generating higher sales, reduce profitability.

**What does the 2017 performance indicate about potential strategies and targets for 2018? What were the trends?**
  - Sales surged from August to December, mirroring 2016 patterns but with higher revenue in most months of 2017.
  - Performance improved across the board. More revenue, more profit, and more customers!
  - If similar KPI trends continue and if the line chart tells us anything is that sales will continue to rise in 2018.

## Recommendations
- Expand offerings and marketing efforts in the Technology category, particularly in high-performing sub-categories like Phones and Accessories.
- Increase investment in the Central region and focus on underperforming regions with potential for turnaround, such as the South.
- Prioritize First Class and Standard Class shipping methods, which demonstrate high profitability and customer satisfaction.
- Limit deep discounts (>20%) to avoid eroding profitability, and instead, focus on targeted promotions for high-margin products.
- Align inventory and marketing strategies with the August to December sales peak to maximize revenue during this critical period.
- Accelerate expansion in cities showing the highest growth, such as Phoenix and Philadelphia, and assess the potential of underperforming markets for targeted improvement initiatives.

## Final Dashboard
Interactive dashboard that answers ad-hoc business questions. The dashboard contains 5 KPIs across the top, 3 charts, and one graph. It had interactive features like dynamic buttons that alter the charts to show most/least by sales/profit and there are slicers for any more specific analysis.
![image](https://github.com/user-attachments/assets/8216a0bd-e98d-4766-ad4c-4c1c11f3e58b)




