# Predicting Hotel Reservation Cancellations
This project aims to explore the factors leading to hotel reservation cancellations and develop machine learning models to predict the likelihood of future cancellations and provide actionable insights to enhance customer retention and service quality.

## Data Description
The dataset includes information about hotel bookings along with customer and room attributes. The primary variable of interest is `booking_status`, indicating whether a reservation was canceled or not.

## Visualizations
- **Lead Time Distribution by Booking Status:** 
  - Boxplots showing the distribution of lead times for canceled and non-canceled bookings.
- **Distribution of Room Types by Booking Status:** 
  - Bar charts depicting the count of canceled and non-canceled bookings for different room types.
- **Distribution of Special Requests by Booking Status:** 
  - Histograms showing the number of special requests for canceled and non-canceled bookings.
- **Distribution of Booking Lead Times by Booking Channel:** 
  - Violin plots illustrating the distribution of lead times across different booking channels.
- **Cancellation Proportion by Season of Arrival Occupancy:** 
  - Bar charts showing the proportion of cancellations for different seasons of arrival occupancy.

## Machine Learning Modeling
- **Data Resampling:** 
  - The dataset is split into training and test sets (80-20 split), and folds are created for cross-validation.
- **Logistic Regression Model:** 
  - A logistic regression model is trained to predict the likelihood of booking cancellations.

## Key Findings
- **Lead time**: Customers who cancel reservations have significantly longer lead times compared to those who do not.
- **Room type**: Suites, including presidential and executive suites, have higher cancellation rates compared to studios.
- **Special requests**: Bookings with fewer special requests are more likely to be canceled.
- **Booking channels**: Lead times vary across different booking channels, with corporate partners having the shortest lead times and mobile apps having the longest.
- **Seasonal occupancy**: Higher cancellation rates are observed during peak occupancy periods.

## Modeling Results
Among the models developed (Logistic Regression, k-Nearest Neighbors, and Random Forest), the Random Forest model performed best with an ROC AUC of 0.9263, F1 Score of 0.7985, and Sensitivity of 0.8725.

## Recommendations
- **Personalized Experience**: Tailor marketing strategies and promotions based on lead time insights to encourage commitment and reduce cancellations.
- **Efficient Special Requests Handling**: Streamline special requests management to ensure efficient fulfillment.
- **Channel-Specific Strategies**: Develop targeted marketing and pricing strategies for different booking channels.
- **Seasonal Pricing and Promotions**: Adjust pricing and promotional offers during peak occupancy to mitigate cancellation risks.
- **Customer Engagement**: Implement customer engagement initiatives and loyalty programs tailored to customer preferences.
- **Optimized Revenue Management**: Utilize the Random Forest model for predicting future cancellations and optimize revenue management strategies accordingly.

## Conclusion

Through this comprehensive analysis, we have identified key factors that influence hotel reservation cancellations. Lead time, room type, special requests, booking channel, and season of arrival occupancy all play significant roles in predicting whether a booking will be canceled. 

Our logistic regression model provides a foundational approach to predicting cancellations, enabling hotels to take proactive measures to minimize cancellations and optimize booking strategies. Future enhancements could include exploring additional machine learning algorithms, incorporating external factors such as market trends or economic indicators, and refining data preprocessing techniques to improve model performance.

By leveraging these insights, hotels can better understand their booking patterns, enhance customer satisfaction, and maximize revenue.

Thank you for exploring this project. If you have any questions or suggestions, feel free to reach out!
