# Pizza Sales Analysis

- This analysis on pizza sales to uncover the actionable insights and improve inventory management to enhance marketting strategies for pizza.

## Table of content
- [Project_Overview](#project-overview)
- [Objectives](#objectives)
- [Tools_used](#tools-used)
- [Explorative_data_analysis](#explorative-data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Reference](#reference)
### Project Overview
- The data set is on Pizza sales analysis. It is an Excel file which consists of 17 columns and 48621 rows . This analysis will help to uncover actionable insights for menu offerings, improve inventory management, and enhance marketing strategies for pizza .

- The data set includes the following columns!
- Pizza id -  give brief explanation of the data set headers.
- Order id – Unique id for customer order.
- Pizza name id – A code representing pizza name.
- Quantity id – Quantity of pizza ordered
- Order date – Date the order was made
- Order time – Time the order as placed
- Order day – Day of the week the order was placed
- Unit Price -  Price of one pizza
- Total price – Total cost for the item (unit price * quantity)
- Pizza size – Size of the pizza ( e. g, “S”, “M”,”L”, “XL”).
- Pizza category - Pizza classification (e.g., "Classic", "Veggie", "Supreme").
- Pizza name - Full name of the pizza 
- Pizza ingredients -  List of ingredients (e.g., "tomato, mozzarella, basil").
- Pizza type – A broader classification of pizza.
- Veggie – Binary indicator for vegetarian pizza
- Non-veggie – Binary indication for non-vegetarian pizza
- Order Month – The month the order was placed

- ### Objectives
  
- This project aims to analyze pizza sales data and give insights to ;
- Sales Trends – Identify the peak order times and the highest number of orders.
- Popular Products – Identify most ordered pizza, most popular pizza and most popular category.
- Revenue Analysis – Which pizza generates the highest revenue , the average order value and the revenue compare between different category,
- Customer Preferences – Preference for vegetarian or non-vegetarian pizza,
- Order Patterns – Identify how often do customer order more than one pizza at a time
- Pricing and time-based insights -  To identify price range of the pizza sold and the periods with unusually high or low sales

- ### Tools used

- Excel (Pivot Tables, Power Query Editor)
- Data Visualization (Pivot Charts Bar/Pie Charts).
- Data Source – Mr Mandela Isoughie ( Instructor)

### Explorative data  analysis

####  Peak order times for Pizza
- Power query editor was used to extract the order hour.
- On Pivot table, order hour was dragged to rows , order Id to values
- Summarised values by count
- Pivot chart – Bar chart

 ####   Days with the highest order.
- Power query editor was used to extract the order day
- On Pivot table, order day was dragged to rows , order Id to values
- Summarised values by count
- Pivot chart – Clustered column chart

####  Most Popular Pizza Category
- On Pivot table, pizza category was dragged to rows , quantity to values
- Summarised values by sum
- Pivot chart – Pie chart

####    Most Ordered Pizza 
- On Pivot table, pizza name was dragged to rows , quantity to values
- Summarised values by sum
- Pivot chart – Clustered column chart

####    Most Ordered Pizza 
- On Pivot table, pizza name was dragged to rows , quantity to values
- Summarised values by sum
- Pivot chart – Clustered column chart

####   Highest Revenue Pizza
- On Pivot table, pizza name was dragged to rows , total price to values
- Summarised values by sum
- Pizza name was filtered to top 5

####   Revenue By Pizza Categories.
- On Pivot table, pizza categories was dragged to rows , total price to values
- Summarised values by sum
- Pivot chart – Column chart

####   Average Order Value.
- Pivot table was used to calculate the average order value by dragging total price in values and summarised by average.
####  Pizza  Price Range
- This was calculated using the pivot table.
- Unit price was dragged to values, summarised values by Minimum and  Maximum
  
 ####  Preference for Vegetarian and Non-Vegetarian Pizza
- Power query editor was used to extract the veggie and non-veggie pizza from the pizza category column.
- On Pivot table, veggie and non-veggie fields were dragged to rows , quantity to values
- Summarised values by count
- Pivot chart – Pie chart 

###  Findings

- From the peak order times chart,  the highest number of orders occurred at 12:00 PM, with a total of 6,543 orders, indicating lunch hours are the busiest.
- 1:00 PM follows closely with 6,203 orders, confirming that mid-day (lunch period) is a key       order window.
- 6:00 PM and 5:00 PM also have high order volumes, at 5,359 and 5,143 respectively, showing significant activity during evening/dinner hours.
- 7:00 PM shows a noticeable drop to 4,350 orders, indicating a decline in customer engagement after peak dinner time.
- From days with highest order chart,  Friday records the highest number of orders with 7,723 orders, indicating strong demand toward the weekend.
- Saturday (7,274) and Thursday (7,243) also see high order volumes, showing strong end-of-week activity.
- Mid-week (Wednesday and Tuesday) maintain moderate levels with 6,907 and 6,833 orders respectively.
- Sunday (6,063 orders) is the lowest, followed by Monday (6,577) — possibly reflecting slower starts and ends to the week.
- Classic is the most popular category with the sum quantity of 14,888 showing strong customer preference over the remaining categories
- Supreme and  Veggie with the sum quantity of 11,987 and 11,649 respectively follow closely, indicating balanced demand for premium and vegetarian options. 
- The most ordered Pizza is Classic Deluxe with the sum quantity of 2,453, followed closely by Barbecue Chicken 2,432 and Hawaiian 2,422 .
- Size L is the most popular pizza size, contributing 18,956 (38.2%) of the sum of the quantity
- Sizes M 15,635 (31.5%) and S 14,403 (29.1%) follow closely, indicating strong demand for standard portions.
- XL 552 (1.1%) and XXL 28 (0.06%) are with minimal sales volume.
- Thai Chicken generates the highest revenue at 43,434.25, followed closely by Barbecue Chicken (42,768) and California Chicken (41,409.50).
- Classic Deluxe (38,180.50) and Spicy Italian (34,831.25) are the lowest revenue earners but still contribute significantly to the total.-  
- Classic dominates with $220,053.10 (26.9% of total revenue), making it the highest revenue-generating category.
- Supreme follows closely with $208,197 (25.5%), showing strong demand for premium offerings.
- Chicken ($195,919.50,  24%) and Veggie ($193,690.45, 23.7%) contribute nearly equally, indicating balanced performance between meat and vegetarian options.

![Uploading Pizza sales analysis dashboard.png…]()


####  Price Range Analysis:
- Average Unit Price: 16.49
- Maximum Unit Price: 35.95 (118% higher than average)
- Minimum Unit Price: 9.75 (41% lower than average)
- The gap between the highest and lowest prices (26.20) suggests a highly varied product lineup, likely catering to different customer segments
- Non-veggie (0) has a significantly higher sum of quantity (37,925) compared to Veggie (1), which has 11,649.
- There is a 3:1 ratio in favor of Non-veggie items, suggesting a strong preference.
- For the periods with unusually high or low sales;
- Peak Months: January ($71,620), March ($71,301), and November ($71,005) are the top-performing months, indicating strong demand during these periods.
- Lowest Months: December ($61,058), September ($63,804), and February ($64,419) show the weakest sales, suggesting seasonal dips or operational challenges.
- Stable Performance: Revenue in other months (April–October) ranges between $67,649–$70,881, showing consistent but moderate performance. 
- The gap between the highest (January) and lowest (December) revenue is $10,562, highlighting notable seasonality.

  ###  Recommendations
- Increase staffing and kitchen readiness between 12:00 PM – 1:00 PM and         5:00 PM - 6:00 PM to meet high demand and maintain service quality.
- Introduce lunch specials (12–2 PM) and early dinner discounts (5–6 PM) to capitalize on peak windows and encourage repeat purchases.
- Ensure that high-demand ingredients and pizzas are well-stocked before these peak periods to avoid shortages or delays.
- Increase inventory, staffing, and delivery logistics from Thursday to Saturday, especially on Fridays, to meet peak demand.
- Ensure ample stock for Classic items to meet high demand.
- Survey customers to understand why Classic outperforms other categories—is it due to taste, pricing, or perceived value?
- Introduce "Monday Motivation" or "Sunday Specials" to boost orders on slower days. These can include combo deals, discounts, or loyalty points.
- Align stock levels with seasonal trends—reduce excess inventory in low months and ramp up for peak periods.
- Capitalize on high-demand periods (Jan/Mar/Nov) by introducing limited-time offers or premium products to maximize revenue.
- Target February, September, and December with discounts, loyalty rewards, or themed campaigns (e.g., "New Year Specials" for December).

- ### Conclusion
- The business thrives on diverse customer preferences and seasonal demand.
- Targeted adjustments such as seasonal promotions, menu optimization, and pricing strategies can enhance profitability and stabilize revenue year-round.
- By focusing on high-performing categories, addressing weak months, and refining product mix, the business can achieve sustainable growth and improved customer satisfaction.
#### Predictive Conclusion
- Revenue increase is achievable by: Capitalizing on peak months (Jan/Mar/Nov).
- Expanding high-margin categories (Supreme, Thai Chicken).

  ### Reference
- Pizza Logo – Google(https://www.freepik.com/free-photos-vectors/pizza-logo)
















