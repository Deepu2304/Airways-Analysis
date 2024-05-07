# Airways-Analysis
# British Airways Review 
# 1.Introduction
# Project overview
This dataset comprises reviews of British Airways flights from various travelers, detailing their experiences with the airline. Reviews range from dissatisfaction with service quality, flight delays, and issues with amenities to occasional praise for excellent onboard service. Key themes include declining standards, reliability concerns, and dissatisfaction with business class experiences. The dataset provides valuable insights into customer sentiment regarding British Airways, highlighting areas for improvement and potential areas of strength. Analyzing these reviews can inform strategic decisions for the airline, focusing on areas such as customer service enhancement, operational efficiency, and product quality improvements to enhance overall customer satisfaction and loyalty.
# Objectives 
1. Identifying Common Complaints: Analyze the reviews to identify recurring issues or complaints among passengers, such as poor service, delays, or discomfort during the flight.
2. Assessing Overall Customer Satisfaction: Evaluate the overall sentiment of the reviews to gauge customer satisfaction levels with British Airways across different flight classes and routes.
3. Examining Service Quality: Assess the quality of onboard services, including cabin staff interactions, meal offerings, and in-flight entertainment, to identify areas for improvement.
4. Understanding Reliability: Analyze feedback related to flight delays, cancellations, and rescheduling to understand the reliability and punctuality of British Airways services.
5. Evaluating Seat Comfort: Examine reviews concerning seat comfort, legroom, and the condition of seating arrangements across different classes to assess passenger comfort levels.
6. Reviewing Lounge Facilities: Evaluate feedback on lounge facilities, including cleanliness, overcrowding, and amenities, to understand the pre-flight experience for passengers.
7. Assessing Catering Quality: Analyze reviews regarding the quality, variety, and presentation of onboard meals and beverages to assess catering standards.
8. Investigating Communication and Transparency: Review feedback regarding communication from airline staff, including updates on delays, cancellations, and procedural information, to assess transparency and clarity of communication.
9. Examining Check-in and Boarding Procedures: Analyze feedback on check-in and boarding processes, including efficiency, organization, and staff professionalism, to identify areas for streamlining procedures.
10. Identifying Opportunities for Improvement: Synthesize findings from the analysis to identify key areas where British Airways can make improvements in service quality, reliability, customer communication, and overall passenger experience.

# About Dataset
The dataset was loaded and split into two parts:'ratings_data' and 'other_data' .For 'other_data,' missing values were filled with column means, categorical variables were encoded, and numeric features were standardized. Optional steps included date column conversion and feature engineering.Removed all the null values from Route and aircraft columns Unnecessary columns were dropped. The processed 'other_data' was then combined with 'ratings_data' to create the final dataset, "processed_airline.csv," ready for analysis or modeling.

# 2.Methodology:
The project will employ a multi-faceted methodology combining data collection, preprocessing, analysis, and visualization techniques. The following steps will be undertaken:

## Data Collection:
Gathering comprehensive datasets from reputable sources such as automotive industry reports, government agencies, and market research firms. This includes historical sales data, economic indicators, demographic information, and vehicle specifications.
## Data Preprocessing:
Cleaning and organizing the collected data to ensure accuracy and consistency. This involves handling missing values, standardizing formats, and removing duplicates or outliers.
## Exploratory Data Analysis (EDA):
Conducting exploratory analysis to uncover patterns, trends, and correlations within the data. Visualizations such as time series plots, heatmaps, and geographical maps will be utilized to facilitate insights discovery.
## Statistical Analysis:
Applying statistical techniques to quantify relationships between variables and validate hypotheses. This may involve regression analysis, correlation tests, and hypothesis testing.
## Visualization and Reporting: 
Creating visually appealing and informative dashboards, charts, and reports to present the findings of the analysis. Clear and concise narratives will be provided to convey key insights and recommendations.

## distribution of bookings by seat type
![download](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/192b819c-aad5-4458-8c7c-e24be07a7c66)

Graph Description:

  - The bar graph displays the distubution of bookings by seat type.
  - where the seat type is represented on the x-axis, while the average count is depicted on the y-axis.

Observations:

  - Economy class has the highest number of bookings, indicating it is the most popular seat type among passengers.
  - Business class follows economy class in terms of the number of bookings, suggesting a preference for upgraded seating options among a significant portion of travelers.
  - First class, while less popular than economy and business classes, still represents a notable number of bookings, indicating a demand for premium services and amenities.
  - Premium economy has the fewest bookings compared to the other seat types, suggesting it may be less commonly chosen by passengers seeking a balance between comfort and affordability.


## Distrubution of rating for different seat type
![download-1](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/55b11b7a-d3ee-4e90-8012-3d095c61ba65)

  - The graph shows the number of bookings for different seat types on a flight. The x-axis shows the seat type, and the y-axis shows the number of bookings. The seat types are Economy Class, Premium Economy, Business Class, and First Class.
  - The graph shows that Economy Class has the most bookings, followed by Premium Economy, Business Class, and First Class. This suggests that most passengers are looking for the most affordable option, while some are willing to pay more for a more comfortable or luxurious seat.
  - The graph also shows that there are more bookings for higher-rated seats. This suggests that passengers are willing to pay more for a seat that they believe is more comfortable or luxurious.

## Seat Preference distrubution
![download-2](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/00aaef2d-ca4a-4cf2-aece-e21dd28e1045)

  - The graph illustrates the distribution of bookings across various seat types on a flight.
  - Economy Class emerges as the most popular seat type, garnering the highest number of bookings.
  - Following Economy Class, Business Class exhibits the second-highest number of bookings.
  - Premium Economy, although less popular than Economy and Business Class, still captures a significant portion of bookings.
  - First Class, the most luxurious and presumably expensive option, attracts the fewest bookings among the four seat types.
  - The trend indicates that a majority of passengers opt for the most affordable option, which is Economy Class.
  - However, there is a segment of passengers willing to pay a premium for enhanced comfort or luxury, as evidenced by the bookings in Business Class, Premium Economy, and First Class.

## Rating Distribution Analysis
![download-3](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/b8398e89-e64e-4429-a500-0cec60621ac0)

  - The bar graph provides an overview of the distribution of ratings for three types of flight classes: Business, Premium Economy, and First Class.
  - Ratings range from 1 to 10 on the x-axis, representing the spectrum of passenger satisfaction.
  - The y-axis displays the count of ratings, indicating the frequency of each rating within the dataset.
  - The analysis reveals that the most common rating is 1, with a count exceeding 400, suggesting a prevalent dissatisfaction among passengers.
  - Conversely, the least popular rating is 10, with a count of fewer than 100, indicating rare instances of exceptional satisfaction.

## Aircraft Rating Distribution Analysis
![download-4](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/d0558fbd-12b2-4952-9e0f-18587d928a66)

  - The bar graph presents the distribution of aircraft ratings ranging from 1 to 10, with the x-axis denoting the rating and the y-axis indicating the count.
  - Data is categorized into two groups: "trip_verified" and "not_verified," shedding light on the impact of verification status on passenger ratings.
  - Across both categories, the most prevalent rating is 1, with counts exceeding 400, indicative of a common dissatisfaction among passengers regardless of verification status.
  - Following closely, the rating of 2 emerges as the second most common, with counts surpassing 200 for both "trip_verified" and "not_verified" classifications.
  - Ratings of 4, 5, 6, 7, and 9 demonstrate relatively lower counts, suggesting less frequent occurrences within both verification statuses.
  - Conversely, ratings of 10, 8, and 3 exhibit similar counts of approximately 100, indicating a moderate level of satisfaction or dissatisfaction across verified and non-verified trips.
  - The comparison between verified and non-verified trip ratings offers insights into potential variations in passenger experiences based on verification status.

## Aircraft Distribution Analysis on the Busiest Day: January 1, 2017
![download-5](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/44d68d07-f493-48b5-8ace-ff2c03d27087)

  - The bar graph illustrates the distribution of aircraft types on January 1, 2017, the most flown date.
  - The x-axis represents different aircraft types, while the y-axis displays the count of each aircraft type.
  - Among the aircraft types, the A320 emerges as the most frequently flown, with a count of 12, indicating its popularity or availability on that particular day.
  - Following the A320, the Boeing 777 ranks as the second most flown aircraft type, with a count of 10, suggesting significant utilization during the observed period.
  - The Boeing 747 secures the third position in terms of frequency, with a count of 8, showcasing its substantial presence on the busiest day.
  - The distribution of aircraft types provides insights into the operational preferences or requirements of airlines on high-traffic dates like January 1, 2017.

## highly rated aircrafts with above 8 rating
![download-6](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/fd6845eb-8b7c-48f9-a36f-91d0de29a055)

  - The graph shows the average rating of different aircraft models. The x-axis shows the aircraft model, and the y-axis shows the average rating.
  - the list of aircrafts that are with more than 8 rating is plotted in the graph 
 ## correlation matrix
![download-8](https://github.com/Deepu2304/Airways-Analysis/assets/86673603/c33e79f0-e6b0-4d1a-adfb-289555704886)

The graph is a correlation matrix, which is a heatmap that shows the correlation between different variables.

 -  The darker the color, the stronger the correlation.
 
   In this case, the variables are:
 
 -   rating
 -  seat_comfort
 -  cabin_staff_service
 -  food_beverages
 -  ground_service and value_for_money.

The correlation between rating and seat_comfort is 0.62, which is a strong positive correlation. This means that as seat comfort increases, rating also tends to increase. The correlation between rating and cabin_staff_service is 0.55, which is also a strong positive correlation. This means that as cabin staff service increases, rating also tends to increase.

# Conclusion
the analysis of British Airways reviews provides valuable insights into passenger sentiments and preferences, highlighting areas for improvement and strengths within the airline's services. Common complaints include issues with service quality, flight delays, and discomfort during flights. Despite challenges, passengers express varying levels of satisfaction across different flight classes, with Economy Class dominating bookings but higher-rated classes also garnering significant interest. The distribution of ratings underscores prevalent dissatisfaction, particularly with ratings of 1, across both verified and non-verified trip categories. On the busiest day, January 1, 2017, the A320 emerges as the most frequently flown aircraft type, followed by the Boeing 777 and Boeing 747, Finally, the correlation analysis reveals strong positive relationships between factors such as seat comfort, cabin staff service, and overall rating, emphasizing the importance of these elements in shaping passenger experiences and satisfaction.


The analysis conducted on aircraft ratings within the dataset aims to provide recommendations for selecting the most suitable aircraft for desired locations based on historical passenger ratings. By examining the average ratings of different aircraft models, the analysis identifies which aircraft consistently received high ratings from passengers. This information can guide airlines or travelers in choosing the best aircraft for specific routes or destinations.
