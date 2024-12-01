Objective:

This repository contains a Python-based analysis of customer shopping trends using a dataset that includes customer demographics, purchase behaviors, and product performance metrics. The project aims to extract insights through data operations and visualizations, enabling businesses to make data-driven decisions in areas such as customer segmentation, revenue optimization, and marketing strategies.

Dataset Overview

The Customer Shopping Preferences Dataset offers valuable insights into consumer behavior and purchasing patterns. Understanding customer preferences and trends is critical for businesses to tailor their products, marketing strategies, and overall customer experience. This dataset captures a wide range of customer attributes including age, gender, purchase history, preferred payment methods, frequency of purchases, and more. Analyzing this data can help businesses make informed decisions, optimize product offerings, and enhance customer satisfaction. The dataset stands as a valuable resource for businesses aiming to align their strategies with customer needs and preferences.

Dataset Glossary (Column-wise):

Customer ID - Unique identifier for each customer
Age - Age of the customer
Gender - Gender of the customer (Male/Female)
Item Purchased - The item purchased by the customer
Category - Category of the item purchased
Purchase Amount (USD) - The amount of the purchase in USD
Location - Location where the purchase was made
Size - Size of the purchased item
Color - Color of the purchased item
Season - Season during which the purchase was made
Review Rating - Rating given by the customer for the purchased item
Subscription Status - Indicates if the customer has a subscription (Yes/No)
Shipping Type - Type of shipping chosen by the customer
Discount Applied - Indicates if a discount was applied to the purchase (Yes/No)
Promo Code Used - Indicates if a promo code was used for the purchase (Yes/No)
Previous Purchases - The total count of transactions concluded by the customer at the store, excluding the ongoing transaction
Payment Method - Customer's most preferred payment method
Frequency of Purchases - Frequency at which the customer makes purchases (e.g., Weekly, Fortnightly, Monthly)
The dataset provides a comprehensive view of customer shopping patterns, allowing for the exploration of relationships between demographic factors, purchase trends, and product performance.

Data Operations Performed

Data Cleaning and Preprocessing:
Handling missing values in columns like Age, Review Rating, and Purchase Amount. Converting categorical variables into numerical formats where necessary.

Grouped and aggregated data by categories like Location, Season, and Payment Method to summarize key trends. Calculated top-performing items by review ratings and purchase frequency, etc.
Visualizations and Insights

The project leverages advanced data visualization techniques to derive meaningful insights:

Bar Charts: Age group distribution across locations, Top 10 items purchased based on ratings, Purchase amounts by subscription status, season, and payment method.

Heatmaps: Customer concentration across locations, Purchase trends by season and category.

Line Charts and Histograms: Average CLV, Average Purchase Amounts.

Scatter and Dot Plots: Average review ratings for items to identify high-quality products.

Summary of Results:

Customers aged 51-65 exhibited the highest spending trends, while 18-25 contributed the most to lifetime value.
The revenue contributions by male customers were higher compared to female customers
Seasonal analysis revealed peak sales during festive seasons, with significant product category variations.
Purpose of Visualization

Visualizing customer shopping trends is crucial to understanding underlying patterns, identifying high-performing products, and optimizing marketing strategies. It enables businesses to:

Segment customers effectively.
Predict future purchasing behavior.
Enhance decision-making by identifying key drivers of revenue and satisfaction.
This repository is a comprehensive guide to analyzing shopping behavior through Python, offering actionable insights for businesses to improve their operations and marketing strategies.
