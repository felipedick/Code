## Part 1: Understanding the Seasonality of Bookings

**Objective:** Analyze booking trends to create a dynamic pricing model that increases revenue during peak seasons.

**Approach:**

1. **Data Loading and Cleaning:** Load the booking data from `data.csv`, handle any missing values or inconsistencies.
2. **Visualization:** Create a line plot that shows the number of bookings per day and month to identify seasonal patterns.
3. **Pricing Model:**  Based on the identified seasonal patterns, propose a pricing model with 3-5 categories (e.g., Low Season, Shoulder Season, Peak Season).

**Findings:**

* **Data Seasonality was analyzed by using different types of groups, such as year, day of the month and week of the year. 
Months and Week of the year were shown to be more seasonal while day besides less seasonal would make reservations more complex to manage. 
Final solution proposed adopting the following Seasonality Strategyu
- Peak season (red): 17 to 21 (5 weeks)
- High Season (orange): 13 to 16, 22 to 26, 39 to 42(13 weeks)
- Shoulder Season (blue): 7 to 12 and 27 to 38, 43 to 49 (25 weeks)
- Low season (gray): 1 to 6 and 50 to 53 (10 weeks)



![Seasonality chart](Google and Bayer Data Challenge/images/ Seasonality.PNG)
