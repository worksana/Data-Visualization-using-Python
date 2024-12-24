# Data-Visualization-using-Python
This repository contains Python code for visualizing and analyzing datasets.

## Project Overview
The dataset used in this project contains information about users, orders, and cooking sessions.

### Key Visualizations:
1. **Distribution of Order Amounts**: Histogram with KDE is used to visualize the distribution of order amounts, helping to identify the frequency of different price ranges in the dataset.
2. **Distribution of Order Ratings**: A count plot showing the distribution of ratings, with a pastel color palette, highlighting the frequency of each rating in the dataset.
3. **Orders by Meal Type**: A horizontal count plot shows the distribution of orders across different meal types, providing insight into the most popular meal preferences among users.
4. **Orders by Time of day**: A vertical count plot displays the distribution of orders based on the time of day, helping to identify peak order times and user behavior.
5. **Total Order amount over time**: used line plot showing the sum of total order amounts (in USD) for each order date, highlighting trends in revenue over time.
6. **Distribution of Session Ratings**: A histogram showing the distribution of session ratings, revealing how frequently different ratings occur.
7. **Session Duration vs Rating**: A scatter plot displaying the relationship between session duration and ratings, with meal types distinguished by color.
8. **Session Ratings by Meal Type**: A boxplot visualizing how session ratings vary across different meal types, showing distribution and outliers.
9. **Count of Sessions by Meal Type**: A count plot providing the number of sessions for each meal type, highlighting the frequency of each type.
10. **Session Duration Distribution by Meal Type**: A histogram showing the distribution of session durations for different meal types, revealing session length trends.
11. **Average Session Rating by Meal Type**: A bar plot displaying the average session rating for each meal type, showing which meal types received the highest ratings.
12. **Session Duration vs Session Rating (Meal Type as Hue)**: A scatter plot that correlates session duration with ratings, further segmented by meal type, showing trends in different meal categories.
13. **Session Count by Meal Type and User**: A count plot visualizing how many sessions were held for each meal type, categorized by user.
14. **Session Start vs Session End**: A scatter plot showing the relationship between session start and end times, with duration as the size and hue of the points.
15. **Session Count by User and Meal Type**: A count plot visualizing the number of sessions for each user, categorized by meal type.
16. **Session Rating Distribution by Meal Type**: A violin plot displaying the distribution of session ratings for each meal type, showing detailed variation and density.
17. **Age Distribution by Location**: Visualizes how age is distributed across different locations, revealing regional age demographics.
18. **Total Orders by Favorite Meal and Location**: Shows how total orders vary by favorite meal type and location, highlighting meal preferences across locations.
19. **Age vs Total Orders by Location**: Illustrates the relationship between age and total orders, colored by location, to uncover regional trends.
20. **Total Orders by Registration Date and Location**: Tracks how total orders change over time, with location-based variations, indicating seasonal or registration-based trends.
21. **Distribution of Favorite Meal by Location**: Displays the distribution of favorite meals across locations, helping to identify regional meal preferences.
22. **Age Distribution by Favorite Meal**: Highlights how age groups differ in their meal preferences, showing potential generational trends.
23. **Total Orders vs Age by Favorite Meal**: Demonstrates how total orders vary with age, with meal preferences influencing the ordering patterns.
24. **Total Orders by Location and Favorite Meal**: Examines how total orders are distributed across locations with respect to favorite meal types, revealing regional meal consumption patterns.

#### Requirements
The following libraries are required to run the code:
- `pandas` - For data manipulation.
- `seaborn` - For statistical data visualization.
- `matplotlib` - For creating static, animated, and interactive plots.

