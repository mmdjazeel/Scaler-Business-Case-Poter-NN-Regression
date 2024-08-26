# Scaler-Business-Case-Poter-NN-Regression

### Context

Porter, India's largest marketplace for intra-city logistics, leads the $40 billion intra-city logistics market. The company aims to improve the lives of over 150,000 driver-partners by providing consistent earning opportunities and independence. Having serviced over 5 million customers, Porter collaborates with a wide range of restaurants to deliver food directly to customers.

To enhance customer satisfaction, Porter seeks to estimate the delivery time for orders based on several factors, including the items ordered, the restaurant, and the availability of delivery partners. The dataset provided contains the necessary information to train a regression model for predicting delivery times.

### Dataset: Porter Data

#### Data Dictionary

Each row in the [dataset](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/015/039/original/dataset.csv.zip?1663710760) represents a unique delivery, and each column corresponds to a feature related to the delivery process:

- **market_id:** Integer ID representing the market where the restaurant is located.
- **created_at:** Timestamp indicating when the order was placed.
- **actual_delivery_time:** Timestamp indicating when the order was delivered.
- **store_primary_category:** The category of the restaurant (e.g., fast food, fine dining).
- **order_protocol:** Integer code representing the method by which the order was placed (e.g., through Porter, via a call, pre-booked, third-party service).
- **total_items:** The final price of the order.
- **num_distinct_items:** The number of distinct items in the order.
- **min_item_price:** Price of the cheapest item in the order.
- **max_item_price:** Price of the most expensive item in the order.
- **total_onshift_partners:** Number of delivery partners available on duty when the order was placed.
- **total_busy_partners:** Number of delivery partners occupied with other tasks at the time of order placement.
- **total_outstanding_orders:** Total number of orders yet to be fulfilled at the time of order placement.

### Objective

The goal is to build a regression model that accurately estimates the delivery time for orders based on the provided features, improving customer satisfaction by providing reliable delivery time predictions.
