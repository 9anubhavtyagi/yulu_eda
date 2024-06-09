
### Problem Statement

#### About Yulu

Yulu is India’s leading micro-mobility service provider, offering unique vehicles for daily commutes. With a mission to eliminate traffic congestion in India, Yulu provides a safe and user-friendly mobile app to enable shared, solo, and sustainable commuting. Yulu zones are strategically located at key locations including metro stations, bus stands, office spaces, residential areas, and corporate offices, ensuring smooth, affordable, and convenient first and last-mile connectivity.

#### Business Challenge

Recently, Yulu has experienced significant dips in its revenues. To address this issue, Yulu has engaged a consulting company to understand the factors influencing the demand for its shared electric cycles in the Indian market. Specifically, Yulu aims to identify the key variables that significantly impact the demand and how these variables can help predict future demand.

#### How you can help here?

The company wants to know:

1. Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
2. How well those variables describe the electric cycle demands?

---

### Technologies and Strategies Used:

1. **Python:** Utilized for overall data analysis and manipulation.
2. **Numpy and Pandas:** Employed for efficient data handling, cleaning, and preprocessing.
3. **Seaborn and Matplotlib.pyplot:** Used for data visualization to identify trends and patterns.
4. **Statistical/Hypothesis Testing:** Applied t-tests and chi-2 tests to validate insights and identify significant differences.
5. **Data Cleaning and Preprocessing:** Ensured data quality by handling missing values, outliers, and transforming raw data into a usable format.
6. **Outliers Handling using IQR Method:** Identified and managed outliers to maintain data integrity and improve analysis accuracy.

---

### Summarizing Insights:

1. **Time of Day Analysis:**
   - **Highest Rentals:** Evening time has the highest number of bikes rented.
   - **Moderate Rentals:** Morning and Noon times follow in the number of rentals.
   - **Lowest Rentals:** Night time has the lowest number of bikes rented.

2. **User Type and Day of the Week:**
   - **Casual Users:** There are more bikes rented by casual users on weekends compared to weekdays.

3. **Seasonal Trends:**
   - **Winter Rentals:** Fewer bikes are rented in January, February, and March.

4. **Yearly Trends:**
   - **2011 Rentals:** Approximately 782,000 bikes were rented in 2011.
   - **2012 Rentals:** Approximately 1,303,000 bikes were rented in 2012, showing a significant increase in usage and popularity of Yulu bikes over the years.

5. **Weather Impact:**
   - **Highest Rentals:** Clear weather (type 1) has the highest number of bike rentals.
   - **Moderate Rentals:** Misty weather (type 2) follows in the number of rentals.
   - **Lowest Rentals:** Light snow and light rain (type 3) weather saw the least number of bikes being rented (excluding type 4 weather due to it being a single datapoint).

6. **Working Day Impact:**
   - **Higher Rentals:** More bikes are rented on working days compared to non-working days.

7. **Holiday Impact:**
   - **Higher Rentals:** More bikes are rented on non-holidays compared to holidays.

8. **Seasonal Impact:**
   - **Highest Rentals:** Fall (type 3 season) has the highest number of bike rentals.
   - **Moderate Rentals:** Followed by summer (type 2 season) and winter (type 4 season).
   - **Lowest Rentals:** Spring (type 1 season) saw the least number of bike rentals.

#### Hypothesis Testing Insights:

1. **Working Day vs. Non-Working Day:**
   - There is no significant difference in the average number of bikes rented on working days compared to non-working days.

2. **Weather Impact:**
   - There is a significant impact of weather on the number of bikes being rented.

3. **Season Impact:**
   - There is a significant impact of the season on the number of bikes being rented.

4. **Holiday vs. Non-Holiday:**
   - There is no significant difference in the average number of bikes rented on holidays compared to non-holidays.

---

### Recommendations:

1. **Optimize Evening Availability:**
   - **Increase Fleet During Peak Hours:** Since the evening has the highest number of rentals, ensure that more bikes are available during these hours to meet the demand. Consider deploying additional bikes or ensuring rapid turnaround times for bikes returned earlier in the day.

2. **Weekend Promotions for Casual Users:**
   - **Target Weekend Casual Users:** Since casual users rent more bikes on weekends, implement targeted marketing campaigns or promotions for weekends. Discounts or loyalty programs could further boost weekend rentals.

3. **Seasonal Adjustments:**
   - **Prepare for Winter:** Given the lower rental rates in winter (January, February, March), consider offering special promotions or services (e.g., heated seats or weather-resistant bikes) to encourage usage during these months.

4. **Expand Capacity:**
   - **Scale Up Operations:** The significant increase in bike rentals from 2011 to 2012 indicates growing popularity. Plan for continuous expansion of the fleet and infrastructure to meet the rising demand and avoid shortages.

5. **Weather-Related Strategies:**
   - **Improve Weather Readiness:** Since clear weather (type 1) sees the highest rentals, and misty weather (type 2) also maintains moderate rentals, ensure bikes are well-maintained and ready for diverse weather conditions. Provide users with real-time weather updates and safety tips through the app.

6. **Enhance Working Day Utilization:**
   - **Corporate Partnerships:** Since more bikes are rented on working days, collaborate with companies to offer bike-sharing as a part of corporate wellness programs or provide dedicated bikes for office commutes.

7. **Holiday Specials:**
   - **Non-Holiday Incentives:** To address the lower rentals on holidays, introduce special holiday promotions or events to encourage usage. Highlight the benefits of biking for leisure during holidays.

8. **Seasonal Promotions:**
   - **Leverage Seasonal Popularity:** Since fall (type 3) has the highest rentals, followed by summer (type 2) and winter (type 4), plan seasonal campaigns that promote biking in these favorable seasons. Introduce seasonal passes or packages to attract consistent usage.

9. **Improve Data-Driven Decision Making:**
   - **Continuous Analysis:** Regularly monitor and analyze rental patterns to adapt strategies quickly. Use data analytics to forecast demand and optimize bike availability accordingly.

10. **Enhance User Experience:**
    - **App Improvements:** Integrate features in the app that cater to the insights, such as recommending the best times to rent, providing weather forecasts, and offering route suggestions based on historical data.

*By implementing these recommendations, Yulu can optimize bike availability, enhance user experience, and drive higher rentals throughout the year.*

