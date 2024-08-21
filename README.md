# Zomato Bangalore Restaurants Dataset Analysis

## Introduction:
The Zomato Bangalore Restaurants Dataset Analysis aims to provide insight into what people prefer when dining out, especially in Bangalore. This dataset contains detailed information about different restaurants, such as customer ratings, popular dishes, and trending dining styles. By analyzing this data, we aim to help restaurant owners understand their customers better and improve their services.

## Dataset Overview:
The dataset consists of the following fields:

- **url**: The website link to the restaurant's Zomato page.
- **address**: The physical address of the restaurant.
- **name**: The name of the restaurant.
- **online_order**: A binary indicator of whether the restaurant offers online ordering (e.g., Yes, No).
- **book_table**: A binary indicator of whether the restaurant allows table booking (e.g., Yes, No).
- **rate**: The customer rating provided by customer(e.g., 4.1/5).
- **votes**: The customer votes received by the restaurant.
- **phone**: The contact phone number for the restaurant.
- **location**: The geographical area where the restaurant is situated.
- **rest_type**: The type of restaurant (e.g., Casual Dining, Quick Bites).
- **dish_liked**: Popular dishes preferred by customers.
- **cuisines**: The types of cuisines offered by the restaurant (e.g., North Indian, Chinese).
- **approx_cost(for two people)**: The estimated cost for dining for two people.
- **reviews_list**: Customer reviews and ratings.
- **menu_item**: Featured items on the restaurant's menu.
- **listed_in(type)**: Categorization of dining options (e.g., Buffet, Dine-out).
- **listed_in(city)**: The city in which the restaurant is listed.

## Project Objective:
The main aim of this project is to explore dining habits among Zomato users in Bangalore. By looking at factors like restaurant type, popular cuisines, average ratings, and spending habits, we hope to help restaurants tailor their offerings and marketing strategies to better meet customer needs.

## Processing Steps:
1. **Data Collection**: Acquire a comprehensive Zomato dataset for analysis.
2. **Library Setup**: Install and import essential Python libraries, including NumPy, Pandas, Matplotlib, and Seaborn.
3. **Data Preprocessing**: Import the dataset and clean data by handling missing values and formatting inconsistencies.
4. **Exploratory Data Analysis**: Conduct in-depth analysis across various dimensions, including restaurant types, cuisines, dining options, and customer ratings.

## Business Problem Statement
**Problem Statement**: The goal of the Zomato Dataset Analysis is to explore customer dining preferences and ratings, as restaurant owners often struggle to understand their customers' needs. This can lead to missed opportunities for improving menus and marketing tactics. By analyzing the dataset, we aim to uncover essential insights about customer behaviors, including the types of restaurants they prefer, whether they order online or offline, their average spending, and the ratings they give.

The insights gained from our analysis will guide restaurant owners in enhancing their services, boosting customer satisfaction, and creating effective marketing plans.

### Objectives:
1. Determine the total number of online and offline orders to assess customer preferences.
2. Analyze customer voting data for dining options to identify popular preferences.
3. Compare customer ratings between online and offline ordering experiences.
4. Assess the average ratings of restaurants to evaluate overall performance.
5. Calculate the average spending per order to tailor pricing strategies.
6. Identify which restaurant types perform well with offline orders.
7. Find the highest number of Online and Offline customer orders.
8. Find which cuisines are most ordered by customers.
9. Find the type of Restaurants where majority of orders are received from customers.
10. Find the cuisines that are ordered online and offline by customers.

### Answers to the Business Problem Statement
1. Order Preference:

Online Orders vs. Offline Orders: Customers show a strong preference for online orders over offline orders.

2. Dining Options:

Popular Choices: The dining options that received the majority of votes from customers include 'Delivery,' 'Dine-out,' and 'Drinks & Nightlife.'

3. Customer Ratings:

Experience Comparison: On average, customers tend to give slightly higher ratings for their online ordering experiences compared to offline ones.

4. Restaurant Ratings:

Overall Performance: The average customer rating for the majority of restaurants stands at 3.7.

5. Average Spending:

Cost Per Order: Customers spend an average of ₹ 555.78 for two plates, which can be utilized to tailor pricing strategies effectively.

6. Restaurant Types for Offline Orders:

Top Performers: The types of restaurants that have received the highest number of offline orders are 'Quick Bites,' 'Casual Dining,' and 'Café.'

7. Order Volumes by Location:

Highest Order Location: The location with the highest number of online and offline customer orders is BTM.

8. Most Ordered Cuisines:

Cuisine Preferences: The top cuisines ordered by customers are North Indian and Chinese.

9. Restaurant Type Preferences:

Preferred Restaurant Type: Customers primarily order from 'Casual Dining' restaurants, with online orders totaling 7011 and offline orders totaling 3242.

10. Cuisine Ordering Trends:

Online and Offline Cuisine Orders:
1) North Indian Cuisines:
Online: 12,312
Offline: 8,488

2) Chinese Cuisines:
Online: 9,436
Offline: 5,902

## Conclusion:
In conclusion, we can see some clear trends in customer ordering habits. First, more customers prefer to place their orders online rather than going to restaurants. When it comes to dining, options like 'Delivery,' 'Dine-out,' and 'Drinks & nightlife' are the most popular choices. Interestingly, customers tend to rate their online dining experiences a bit higher than those they have offline.
Most restaurants earn an average rating of 3.7, indicating that there’s room for improvement. On average, spending for two plates at a restaurant is about ₹ 555.78. For offline dining, 'Quick Bites,' 'Casual Dining,' and 'Cafes' are the top restaurant types.
The area with the most orders, both online and offline, is BTM. In terms of food preferences, North Indian and Chinese cuisines lead the way, with many customers ordering them both online and offline. In fact, 'Casual Dining' restaurants are particularly popular, with 7,011 online orders and 3,242 offline orders from this type.
Overall, North Indian cuisine has received 12,312 online orders and 8,488 offline orders, while Chinese cuisine has received 9,436 orders online and 5,902 orders offline.
This data highlights the strong preference for online orders and showcases which cuisines and dining formats customers find most appealing.
