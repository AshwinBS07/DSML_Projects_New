<h1>About data</h1>
Company is a globally renowned brand and a prominent retailer in the United States. Company makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.

This particular business case focuses on the operations of Company in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analyzing this extensive dataset, it becomes possible to gain valuable insights into Company's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

<h1>Business Problem</h1>

Assuming as a data analyst/ scientist at company,the task is to analyze the given dataset to extract valuable insights and provide actionable recommendations.

---

## Project Goal

### Objective

Conduct a comprehensive data analysis to gain insights into customer behavior and order patterns for company, a major retailer. The analysis will help in identifying trends, understanding customer demographics, and providing actionable recommendations to improve business strategies.

### Recommendations

- **Data-Driven:** Ensure each recommendation is supported by robust data analysis.
- **Audience:** Tailor findings for business executives with a basic understanding of data science. Avoid technical jargon.

### Key Questions Explored

1. **Dataset Import and Initial Analysis**

   - Import the dataset and analyze its structure and characteristics.
   - Check the data types of all columns in the "customers" table.
   - Determine the time range during which orders were placed.
   - Count the cities and states of customers who placed orders during the given period.

2. **In-depth Exploration**

   - **Order Trends:**

     - Analyze if there is a growing trend in the number of orders placed over the past years.
     - Investigate monthly seasonality in the number of orders placed.
     - Identify the time of day when Brazilian customers mostly place their orders (Dawn, Morning, Afternoon, or Night).

   - **E-commerce Orders in Brazil:**
     - Get the month-on-month number of orders placed in each state.
     - Analyze the distribution of customers across all states.
     - Evaluate the impact on the economy by examining order prices, freight, and other costs.
     - Calculate the percentage increase in the cost of orders from 2017 to 2018 (include months between Jan to Aug only).

3. **Economic Impact Analysis**

   - **Order Costs:**

     - Use the "payment_value" column in the payments table to determine the cost of orders.
     - Calculate the total and average value of order prices for each state.
     - Calculate the total and average value of order freight for each state.

   - **Delivery Analysis:**
     - Calculate the number of days taken to deliver each order from the order's purchase date as delivery time.
     - Calculate the difference (in days) between the estimated and actual delivery date of an order.
     - Identify the top 5 states with the highest and lowest average freight value.
     - Identify the top 5 states with the highest and lowest average delivery time.
     - Determine the top 5 states where order delivery is significantly faster than the estimated date.

4. **Payments Analysis**

   - **Payment Trends:**
     - Analyze the month-on-month number of orders placed using different payment types.
     - Evaluate the number of orders based on the payment installments that have been paid.

### Recommendations and Insights

- **Trend Analysis:** There is a growing trend in the number of orders over the past years, with noticeable monthly seasonality. Focus marketing efforts during peak months to maximize sales.
- **Customer Behavior:** Brazilian customers tend to place orders mostly during the morning and afternoon. Tailor marketing campaigns to these times to increase engagement.
- **Economic Impact:** The cost of orders has increased from 2017 to 2018. Understanding this trend can help in pricing strategy and managing customer expectations.
- **Delivery Efficiency:** Identify states with high and low delivery efficiency to optimize logistics and improve customer satisfaction. States with the fastest delivery can serve as benchmarks.
- **Payment Preferences:** Analyze payment trends to understand customer preferences and tailor payment options accordingly.
