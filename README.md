# Cooking Analysis Preferences
This repository contains an analysis of user preferences, cooking sessions, and order details from a dataset of cooking orders. The goal is to derive insights about user demographics, popular dishes, and the relationship between cooking sessions and user ratings. The analysis includes data cleaning, merging multiple datasets, and generating visualizations to explore trends in cooking behaviors.

## Project Overview
The dataset includes three main sheets:

#### UserDetails: 
Contains information about users such as their registration date, age, and favorite meal.
#### CookingSessions: 
Contains data on cooking sessions, including session ratings, meal types, and session start/end times.
#### OrderDetails: 
Contains information about the orders placed by users, including dish names, order dates, and ratings.
## Steps Taken in the Analysis
1. Data Cleaning
Missing Values: Missing values were identified and rows with missing data were removed.
Duplicates: Duplicate rows were identified and removed.
Data Type Consistency: Date columns were converted to the appropriate datetime format.
2. Data Merging
The datasets were merged on common columns to create a unified dataset containing:

User details
Cooking session information
Order details
3. Analysis
Relationship Between Cooking Sessions and Orders: Analyzed the average session rating and order rating for each dish.
Popular Dishes: Identified the most ordered dishes.
Demographic Analysis: Investigated order preferences based on age and favorite meal type.
4. Visualizations
The following visualizations were created:

Popular Dishes: A bar plot showing the most ordered dishes.
Session Rating vs. Order Rating: A scatter plot showing the relationship between session ratings and order ratings.
Demographic Analysis: A heatmap showing the number of orders by age and favorite meal type.
## Insights and Recommendations
#### Insights:
The most popular dish based on order count.
The correlation between session ratings and order ratings.
Trends in meal type preferences based on user age.
#### Recommendations:
Offer personalized dish recommendations based on session ratings.
Target specific age groups with campaigns for popular meal types.
