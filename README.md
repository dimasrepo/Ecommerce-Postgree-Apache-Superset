# Superset Dashboard

![Executive Summary New](https://github.com/user-attachments/assets/8fbb465c-3799-492f-81fb-e4de73cc548e)



This repository contains a collection of visualizations created with Apache Superset. The dashboards are designed to provide insights into various aspects of the Olist dataset, including product performance, sales trends, customer profiles, and more.

## Visualizations


### 1. Presentation Order by Category
**Objective:** Identify the best and worst performing products by category. By linking data from `olist_products_dataset` and `olist_order_items_dataset`, you can analyze the most and least frequently purchased product categories.
**Description:** 
From this graph, it can be concluded that household products such as bedding, bathroom, and dining equipment are very popular among consumers. Additionally, beauty and sports products also have quite high demand. This information can be a reference for businesses to allocate resources, such as inventory and promotions, to the most in-demand product categories. By understanding consumer preferences, businesses can increase sales and customer satisfaction.

### 2. The Influence of Product Weight and Dimensions on Price and Freight Value
**Objective:** Assess whether the weight and dimensions of products influence their price and freight value. Data from `olist_products_dataset` and `olist_order_items_dataset` can be used for this analysis.
**Description:**
This graph provides interesting insights into the relationship between product weight and dimensions and price and shipping costs. Each point on the graph represents a product category, with the size of the circle indicating the amount or value of a variable (e.g., total sales). The position of the point on the x- and y-axes indicates the overall weight and dimensions of the product.

From this graph, we can observe several things:
- **Price and Shipping Cost Variation:** There is significant variation in price and shipping costs across product categories. Some product categories have significantly higher prices and shipping costs than others.
- **Effect of Weight and Dimensions:** In general, products with larger weights and dimensions tend to have higher prices and shipping costs. This makes sense since production and shipping costs are usually proportional to the size and weight of the product.
- **Role of Product Categories:** Different product categories have different characteristics. For example, the category "agro_industry_and_commerce" tends to have products with larger weights and higher shipping costs than the category "art".

### 3. The Influence of Purchase Time on Order Status
**Objective:** Analyze whether there are specific time patterns when orders tend to experience delays or status changes. Data from `olist_orders_dataset` can be used to understand these trends.
**Description:**
This graph illustrates the relationship between purchase time and order status. There are three main metrics measured: total time to customer delivery, average delivery time, and average other time.

Overall, the graph shows that orders with a status of “delivered” have a shorter total time to customer delivery time than orders with a status of “canceled.” This suggests that faster order fulfillment tends to result in higher success rates. Additionally, the average other time for canceled orders is also higher, which may indicate additional bottlenecks or issues that are causing cancellations.

### 4. Seller Performance
**Objective:** Assess seller performance based on their location. By linking data from `olist_sellers_dataset` and `olist_order_items_dataset`, you can determine whether seller location affects their sales volume.
**Description:**
This graph provides a clear picture of the sales performance across cities in Brazil. Sao Paulo significantly dominates in terms of total orders and total sales, far above other cities. This shows that Sao Paulo is a very important and potential market for this business. Other cities such as Ibitinga, Curitiba, and Rio de Janeiro also contribute significantly to total sales, but are still far below Sao Paulo.

From this graph, we can draw several important conclusions:
- **Market Concentration:** Most of the sales activity is concentrated in a few large cities such as Sao Paulo and Rio de Janeiro. This indicates that there is untapped market potential in other cities.
- **Growth Potential:** Cities such as Ibitinga, Curitiba, and Rio de Janeiro have significant growth potential. With the right marketing strategy, the company can increase its market share in these cities.
- **Performance Differences:** There are significant differences in sales performance across cities. This shows that local factors such as purchasing power, competition, and consumer preferences have a major impact on sales results.

### 5. The Influence of the Number of Product Photos on Sales
**Objective:** Measure whether the number of product photos affects sales levels. Data from `olist_products_dataset` and `olist_order_items_dataset` can be used for this analysis.
**Description:**
This pie chart provides a clear picture of the distribution of products based on the number of photos used. We can see that the majority of products (shown by the dark blue segment) have only 1 photo. This indicates that many sellers are not fully utilizing the potential of visuals to promote their products. In contrast, products with a higher number of photos (5 or more) have a much smaller proportion.

- **Importance of Visuals:** The number of product photos used has a significant impact on the appeal of the product to consumers. Products with more photos tend to attract more attention and provide more complete information to potential buyers.
- **Growth Potential:** There is still great potential to increase sales by increasing the number of product photos. Sellers can utilize additional features such as video, zoom, and 360 degrees to provide a more interactive visual experience to customers.
- **Market Segmentation:** There are differences in visual strategies between sellers. Some sellers may focus more on products with high profit margins, so they are willing to invest more time and resources in creating quality product photos.

### 6. Comparison of Payment Methods to Payment Value
**Objective:** Analyze how payment methods (e.g., credit card vs. bank transfer) affect the average payment value. Data from `olist_order_payments_dataset` can be used for this insight.
**Description:**
From this graph, it can be concluded that credit cards are the most popular payment method and generate the largest transaction value. This indicates that most customers feel comfortable using credit cards to make transactions. Additionally, the low transaction value in the "not_defined" category shows the importance of ensuring that payment data is recorded correctly so that data analysis becomes more accurate. This information is very valuable for businesses to optimize payment strategies, such as offering special promotions for credit card users or providing more diverse payment options.

### 7. Purchase Patterns Based on Time
**Objective:** Analyze purchase patterns based on time of day or month to understand peak purchase periods. Data from `olist_orders_dataset` can be used to determine these patterns.
**Description:**
This graph shows a significant upward trend in the number of orders from October 2017 to a peak in early 2018. After that, the number of orders tends to be stable with little fluctuation. A fairly clear seasonal pattern is seen, with a significant increase occurring towards the end of the year (most likely due to the holiday season) and a relative decline at the beginning of the year.

Some insights that we can draw from this graph are:
- **Business Growth:** Overall, the graph shows positive business growth during the observed period. This indicates that the business strategy implemented is quite effective.
- **Seasonal Pattern:** The presence of a clear seasonal pattern indicates that seasonal factors have a significant influence on sales volume. The company needs to prepare for these seasonal fluctuations by managing inventory and marketing campaigns accordingly.
- **Growth Potential:** Although there has been a significant increase, there is still potential for further increase in the number of orders, especially during off-peak periods.

### 8. Customer Profile Based on Location and Purchase Frequency
**Objective:** Identify customer characteristics such as location (city, state) and purchase frequency to determine the most active customer segments. Data from `olist_customers_dataset` and `olist_order_items_dataset` can provide these insights.
**Description:**
This visualization provides an interesting overview of customer profiles based on location and purchase frequency. Large cities such as Sao Paulo and Rio de Janeiro have a very significant number of customers, indicated by their larger land area. This indicates that these two cities are key markets for the business in question. Additionally, there is variation in purchase frequency across cities, indicated by the different colors or color intensity of each small box. Cities with lighter colors tend to have higher purchase frequencies.

Overall, this visualization can be used to identify cities with high growth potential, as well as to design more effective marketing strategies based on customer characteristics in each location. For example, businesses can allocate more marketing resources to cities with high purchase frequencies, or develop products and services that are more in line with customer preferences in each region. Additionally, this visualization can also help identify interesting purchasing patterns, such as certain seasons or special events that trigger increased sales in certain regions.

### 9. Sales Growth
**Objective:** Identify months with significant sales growth to plan better marketing and promotional strategies in the future. This analysis can also provide insights into strong or weak sales periods, helping in inventory planning and other business strategies.
**Description:**
Insights from the Sales Growth Chart:
- **Overall Trend:** The chart depicts a general upward trend in sales over the period from October 2017 to July 2018. This indicates overall business growth and positive sales performance.
- **Specific Observations: Significant Growth Spikes:** There are several periods of rapid sales growth, particularly in late 2017 and early 2018. These spikes might be attributed to factors such as successful marketing campaigns, product launches, or seasonal trends.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
