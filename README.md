 # <mark>Business Requirements Document (BRD)</mark>

## <mark>Project: Pizza Sales Analysis</mark>

### <mark>Project Overview<mark>




The Pizza Sales Analysis project is designed to analyse transactional sales data from a pizza store. The goal is to identify key business insights, trends, and KPIs that will help management make informed decisions related to sales, marketing, and operations. 
 
### <mark>Business Objectives</mark> 

Identify overall revenue,total pizzas sold, and total number of orders. 
Determine sales distribution by pizza category, size, and type. 
Analyse time-based trends in sales (daily, monthly, and yearly). 
Highlight best-selling and least-selling pizzas by revenue and quantity. 
Understand customer purchasing behaviour through Average Order Value (AOV) and Average Pizza per Order. 
Provide visualization dashboards for effective decision-making. 


   
### <mark>Data Source & Description</mark>
### Dataset: pizza_sales.csv 
   Key fields: 

    order_id → Unique identifier for each order 

    pizza_id → Unique identifier for each pizza 

    pizza_name → Name of the pizza sold 

    quantity → Number of pizzas sold per order 

    total_price → Total revenue for each transaction 

    date, time → Order timestamp for time-based analysis 

    pizza_category, pizza_size → Attributes for pizza classification 



### <mark>Question number 1 <mark>

   Key Performance Indicators (KPIs) 

   Total Revenue = Sum of total_price 

   Total Pizzas Sold = Sum of quantity 

   Total Orders = Count of unique order_id 

   Average Order Value (AOV) = Total Revenue ÷ Total Orders 

   Average Pizza per Order = Total Pizzas Sold ÷ Total Orders 

**KPI Calculated value**
    Total Revenue: $817860.05
    Total Pizzas Sold: 49574.qty
    Total Orders: 21350
    Average Order Value (AOV): $38.31
    Average Pizza per Order: 2.32

 
## <mark>Analysis & Visualizations<mark> 


### Ingredient Analysis

The pizza business aims to understand which ingredients are most frequently used across different pizza types. By identifying the most common ingredients, the store can 


  ###  Frequency of Pizza Ingredients
![Frequency of Pizza Ingredients](https://raw.githubusercontent.com/pinkimahato9814-afk/Pizza_sales_analysis/main/frequency%20_of_pizza_ingredients.png)

<mark>Reports<mark> :- The chart illustrates the frequency of different pizza ingredients, showing that garlic and tomatoes are the most commonly used, followed by red onions and red peppers. Ingredients like mozzarella cheese, pepperoni, and spinach have moderate usage, while chicken and capocollo are used less frequently. Overall, the data highlights a strong preference for vegetable-based and traditional pizza ingredients.



 
### <mark>Question number 2 <mark>


A line/bar chart showing sales by day of the week. 
Useful for staffing and operations planning. 

![Daily Sales Varying](https://raw.githubusercontent.com/pinkimahato9814-afk/Pizza_sales_analysis/main/daly_sales_varying.png)

 <mark>Reports<mark>:-The chart illustrates the Sales gradually increase from Sunday to Friday.
Friday records the highest revenue, indicating peak customer activity before weekends.
Sunday shows the lowest sales, suggesting slower business at the start of the week.



### <mark> Question number 3<mark>

**Hourly Trend**

A line/bar chart showing sales by hour of the day. 
Useful for staffing, ingredients, customer rush and operations planning 

### 3. Hourly Sales Variation
![Hourly Sales Variation](hourly_sales_varying.png)

 <mark>Insight<mark>:- Sales peak during 12:00 PM – 1:00 PM (lunch time) and 6:00 PM – 8:00 PM (dinner time).
Very low sales are observed in early morning and late night hours.
This highlights strong demand during typical meal times.




<mark>**Question number 4**<mark>
            
**Monthly Trend**

A line chart depicting monthly revenue and orders. 
Helps track seasonality and identify peak sales months. 
Summer months show higher sales due to promotional campaigns. 

### 4. Monthly Sales Variation
![Monthly Sales Variation](monthly_sales_varying.png)

<mark>Insight<mark>:- Sales fluctuate across months with peak performance around July–August.
The lowest sales are observed in September and October.
Indicates possible seasonal demand patterns.


<mark>**Question number 5**<mart>


% of Sales by Category 

A bar chart representing revenue and quantity sold for each pizza category (Classic, Supreme, Veggie, Chicken). 
Helps identify customer preferences. 
Classic pizzas dominate sales, while Veggie has lower demand. 

### 5. Percentage of Pizza sales by Category
![Percentage of Pizza by Category](percentage_of_pizza_by_category.png)

<mark>Insight<mark>:- Classic pizzas dominate sales (27%), making them the most preferred category.
Chicken and Veggie categories contribute equally (~24% each).
Supreme pizzas follow closely, indicating balanced category demand.


<mark>**Question number 6**<mark>


% Sales by Pizza Size & Category 

A bar/ donut chart comparing sales revenue and quantity by pizza size (S, M, L, XL). 
Highlights demand distribution by size and assist inventory planning. 
Large (L) pizzas contribute the highest revenue. 


 ### 6. Revenue Distribution by Pizza Size and category
![Revenue Distribution by Pizza Size](sales_percentace_by_pizza_size_and_category.png)

<mark>Insight<mark>:-  Large (L) size pizzas contribute the highest sales across all categories.
Medium (M) sizes show consistent demand.
Small (S), XL, and XXL sizes have comparatively lower contributions.
Suggests customers prefer larger portion sizes.

 <mark>**Question number 7**<mark>

 
Total Pizzas Sold by Pizza Category 
Manage inventory by stocking ingredients used in the most popular categories. 
Evaluate if low-performing categories should be optimized, redesigned, or discontinued. 

  ### 7. Percentage of Pizza by Category
![Percentage of Pizza by Category](total_pizzas_sold_by_category.png)


<mark>Insight<mark>:- Classic category has the highest number of pizzas sold.
Supreme and Veggie categories show moderate sales.
Chicken category follows closely, maintaining steady demand.

 **Question number 8**

 
Top 5 Best-Selling Pizzas 
A horizontal bar chart showing pizzas with the highest sales (by revenue, orders or quantity). 
Supports promotional and menu strategy. 

### 8.Top_5_best-Selling Pizzas
![Bottom 5 Least-Selling Pizzas](top_best_selling_pizza.png)

<mark>Insight<mark>:- Thai Chicken Pizza is the top-selling item.
Barbecue Chicken and California Chicken pizzas also perform strongly.
Chicken-based pizzas dominate the top-selling list, indicating high customer preference.
 
 <mark>**Question number 9**<mark>

 
 Bottom 5 Least-Selling Pizzas 
A horizontal bar chart of pizzas with the lowest sales. 
Identifies products for improvement or possible removal from the menu. 
 
 ### 9.Bottom 5 Least-Selling Pizzas
![Bottom 5 Least-Selling Pizzas](least_5_selling_pizza.png)

<mark>Insight<mark>:- The Brie Carre Pizza has the lowest sales among all.
Other low-performing pizzas include Spinach-based and Mediterranean varieties.
These items may require menu optimization or promotional strategies.

 <mark>**Question number 10**<mark>

Business Questions Answered 
What is the total revenue generated? 
How many pizzas were sold in total? 
Which category and size of pizzas perform best? 
Which pizzas are the top and bottom performers? 
What is the average order value and average pizzas per order? 
What are the sales trends by day, month, and time of day? 
 
 
 
**Deliverables **


Jupyter Notebook with complete Python analysis. 
Visualizations (bar charts, line charts, trend charts). 
Business Requirements Document (BRD). 
Insights and recommendations for management. 

 
**Conclusion & Recommendations **


The analysis provides a comprehensive view of pizza sales performance. Management can leverage these insights to: 
Focus marketing on high-performing categories. 
Optimize the menu by reconsidering least-selling pizzas. 
Plan inventory and staffing based on sales peaks. 
Monitor KPIs regularly through dashboards for continuous improvement. 
 


