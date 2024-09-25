# Brazilian E-Commerce Data Analysis Using Olist Dataset

## Project Overview

This project presents a comprehensive analysis of the **Brazilian E-Commerce Public Dataset by Olist**, which contains data about e-commerce orders made on the Olist platform between 2016 and 2018. The dataset provides detailed insights into various aspects of e-commerce such as customer behavior, product sales, seller performance, and order fulfillment processes.

The main objective of this project is to explore and understand the e-commerce landscape in Brazil, focusing on key metrics such as customer satisfaction, product demand, delivery efficiency, and payment preferences. By leveraging this dataset, we aim to generate actionable insights that can be useful for improving business decisions and operational strategies in the e-commerce industry.

## Dataset Overview

The dataset includes the following key tables:

- **Orders**: Contains information about order status, timestamps, and delivery details.
- **Products**: Includes product information such as categories and attributes.
- **Customers and Sellers**: Provides details about customers and sellers, including geolocation data.
- **Payments**: Information on payment types and the sequence of payments for each order.
- **Order Items**: Details about each item in an order, including price and freight value.
- **Reviews**: Customer reviews and ratings for their shopping experience.
- **Geolocation**: Latitude and longitude data mapped to Brazilian zip codes.

### Key Questions Answered

1. What are the cities with the most number of orders?
2. Who are the top 5 or 10 customers with the most total orders?
3. What is the order with the highest paid price?
4. What is the most preferred payment type among customers?
5. What are the top-selling product categories?
6. How efficient is the delivery process, and what are the reasons for late deliveries?

## Tools & Technologies

- **Power BI**: Used for data cleaning, transformation, and visualization.
- **Power Query**: For data merging and preprocessing.
- **DAX**: Used for creating custom measures and calculated columns.

## Data Cleaning Process

- **Merging Tables**: Combined data from different tables such as orders, reviews, payments, and geolocation.
- **Adding Custom Columns**: Added new calculated columns such as `Number of Payment Types` and `Total Payment Value`.
- **Removing Irrelevant Data**: Removed unnecessary columns such as `Customer Unique ID` and `Customer State` to simplify the dataset.
- **Data Model**: Implemented a star schema with a central fact table (`olist_order_items_dataset`) and supporting dimension tables.

## Visualizations

The analysis includes several key visualizations, such as:

- **Bar charts**: Showing top cities, top customers, and top-selling products.
- **Pie charts**: Representing payment types, order status, and customer satisfaction.
- **Line charts**: Tracking delivery times and order volume growth over time.

## Key Insights

1. **Geographic Concentration**: A large number of orders come from major cities like São Paulo and Rio de Janeiro.
2. **Customer Retention**: High-value customers with 10 or more orders contribute significantly to total sales.
3. **Digital Payments**: The majority of customers prefer digital payment methods like credit and debit cards.
4. **Delivery Efficiency**: Most orders are delivered on time, but a small percentage of late deliveries needs to be addressed.
5. **Top Products**: Certain product categories consistently perform better than others, which can guide inventory and marketing strategies.

## Recommendations

1. **Expand Geographical Coverage**: Focus on underserved regions to increase market share.
2. **Loyalty Programs**: Implement targeted marketing campaigns to retain high-value customers.
3. **Improve Delivery Efficiency**: Address late deliveries by optimizing logistics and improving forecasting.
4. **Upselling & Cross-Selling**: Leverage high-value orders to offer complementary products.
5. **Encourage Seller Engagement**: Provide incentives to top-performing sellers and encourage active participation.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ahmed1magdy2/brazilian-ecommerce-data-analysis.git
