# Airline-Customer-Satisfaction
Customer Satisfaction Analysis Report¶
Introduction: 
This report presents an analysis of customer satisfaction data collected from an undisclosed airline company. The dataset contains information on various factors that may influence customer satisfaction, such as flight punctuality, service quality, and class of travel. The goal of this analysis is to gain insights into the factors affecting customer satisfaction and to provide recommendations for improving the overall customer experience.

Dataset Overview:
The dataset comprises 22 columns and 129,880 rows.

Key columns include:

Satisfaction: Indicates whether the customer was satisfied, dissatisfied, or neutral.
Customer Type: Specifies if the customer is a loyal or disloyal customer.
Age: Age of the customer.
Type of Travel: Indicates if the travel was for personal or business purposes.
Class: Specifies the class of travel (e.g., Economy, Business).
Various service ratings (e.g., seat comfort, food and drink, cleanliness).
Flight distance and departure/arrival delay in minutes.

Analysis:

Customer Satisfaction Distribution:

Majority of customers seem to be satisfied, with a smaller proportion being dissatisfied or neutral.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/c400db24-1062-4799-a7f0-b3e31084c261)


Customer Type Distribution:
The dataset contains more entries from loyal customers compared to disloyal customers.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/e5ea4032-aa17-4333-a777-3f227dbdea12)


Age Distribution:
The age distribution of customers spans a wide range, with a peak in the middle age group.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/5d8120ea-8cc3-4318-bc97-8474d79c5dc8)


Type of Travel Distribution:
Personal travel appears to be more common than business travel among the customers in the dataset.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/b23d6099-d627-4895-922b-4f11f95bcebc)


Class Distribution:
Economy class seems to be the most common class of travel, followed by business class.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/771ef03b-e85f-4e8d-8701-5b9203e7f322)


Service Ratings:
Boxplot analysis reveals varying levels of satisfaction across different service aspects. Some areas, such as seat comfort and cleanliness, have higher average ratings compared to others.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/8c741625-f191-4a36-8570-57dfa8929a0b)


Flight Distance Distribution:
The distribution of flight distances shows that the dataset covers a wide range of travel distances.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/242ca932-e8d2-4e8e-8188-d83c77462684)


Departure Delay vs Arrival Delay:
There is a positive correlation between departure delay and arrival delay, indicating that flights with longer departure delays tend to have longer arrival delays as well.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/0ee5d303-4cfe-4941-91fc-303f4b9bc5ca)


Correlation Matrix:
A correlation matrix shows the relationships between different variables. Positive correlations exist between certain service ratings (e.g., seat comfort and inflight entertainment), while departure delay is positively correlated with arrival delay.

![image](https://github.com/khorkina/Airline-Customer-Satisfaction/assets/166530415/4d552d44-e73b-4140-906d-f6e042344fcc)


Recommendations:

Improve service quality: Focus on areas with lower service ratings, such as online support and onboard service, to enhance the overall customer experience.
Address delays: Implement strategies to reduce departure and arrival delays, as they negatively impact customer satisfaction.
Tailor services: Personalize services based on customer type and purpose of travel to meet specific needs and preferences.
Monitor age preferences: Analyze age-related preferences and adapt services accordingly to cater to different age groups effectively.
Conclusion: This analysis provides valuable insights into customer satisfaction within the airline industry. By understanding the factors influencing satisfaction and implementing appropriate strategies, airlines can enhance customer experiences, improve loyalty, and ultimately drive business success.

Limitations:

The analysis is based on historical data and may not capture recent trends or changes in customer preferences.
The dataset does not include information on external factors (e.g., weather, airport conditions) that may affect customer satisfaction.
Further analysis and validation may be required to draw conclusive recommendations.

Future Work:

Conduct customer surveys or feedback analysis to gather real-time insights into satisfaction levels and areas for improvement.
Incorporate external data sources to enhance the analysis and gain a comprehensive understanding of customer satisfaction dynamics.
Overall, continuous monitoring and analysis of customer satisfaction data are essential for airlines to remain competitive and deliver exceptional experiences to their customers.
