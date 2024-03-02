# Airline-Customer-Reviews-Sentiment-Analysis-for-Delta-Airlines


### Introduction

By analyzing reviews of Delta Airlines, this project aims to gain insights into how customers feel about their experiences with the airline. This information can then be used by the airlines to make data-driven strategic decisions to improve customer satisfaction thereby fostering business growth.


### Technologies Used

- R


### Dataset Description

- Link: https://www.kaggle.com/datasets/datazng/delta-airline-review-dataset-sentiment-analysis?select=Delta_Airline_Review_Dataset-Asof02172023.csv
- The original dataset comprises 8 columns and 2689 observations. However, here data is split into additional columns for ease of calculation.
- Data Dictionary:
    - **Traveler_types**: The type of traveler, i.e, Solo Leisure, Couple Leisure, Family Leisure and Business - Categorical
    - **Star rating**: A numerical rating from 1 to 10 stars given to Delta Airlines by the customer where 10 is the highest rating and 1 is the lowest rating - Numerical
    - **Date**: The date when the review was written. This variable was split into day, month and year for our analysis.
    - **Seat Type**: the type of seat the customer flew in, such as Economy Class, Premium Economy, First Class and Business Class - Categorical
    - **Routes**: The origin and destination of the flight. This variable was split into departure, arrival and via for our analysis.
    - **Country**: The country where the customer is from.
    - **Reviews**: The reviews a customer has written about their experience with Delta Airlines, including positive and negative aspects of their trip.

      
### Methodology

1. **Data collection and Preprocessing**:
       Including data cleaning, cleaning stop words, lemmetization, corpus/ Term Document Matrix creation
2. **Performing Sentiment Analysis**:
       Understanding overall customer sentiment as well as finding if factors like time of the year, rating number affect sentiment score  
3. **Data Mining for understanding and predicting customer experience**:
       Deploying different statistical modeling techniques like Logistic Regression, Naive Bayes, Random Forest Classification, Hierarchical Clustering and Topic Modeling
4. **Vizualizing outcomes**:
       Understanding customer review using graphical outputs like given below help to analyze customer data better. Please note that detailed findings are available as the report.

      Overall Review Sentiment:
       ![image](https://github.com/AYamdagni/Delta-Airline-Reviews-Sentiment-Analysis/assets/136560732/ec27eefe-1a65-4f57-ab3f-ec77f528966a)

      Top Topics:
       ![image](https://github.com/AYamdagni/Delta-Airline-Reviews-Sentiment-Analysis/assets/136560732/8cfaced7-c40e-459f-93bd-3ce8fb95c457)


### Inferences and Future Scope

- Although the overall sentiment regarding Delta Airlines is positive, the difference is marginal and can be improved upon by reflecting on the results derived, i.e, actionable measures looking to minimize problems such as flight cancellations, flight scheduling, waiting time for passengers, etc.
- The model can be further improved upon by incorporating more data which would give a better aggregate measure of the sentiment of the crowd.
- While there are limitations to sentiment analysis, it remains a powerful tool for businesses looking to improve customer satisfaction and stay competitive in today's market.


### References and Acknowledgements

I would like to thank _Dr.Kislaya Prasad_ my professor for Data Mining and Predictive Analytics course at Robert H. Smith School of Business, University of Maryland - College Park for guiding me throughout the project. I am grateful to other contributors on my project team - _Aparna Raghavendra Rao, Nishanthi Ravichandran, Hareeca Chintala and Charishma Jaladi_ for their inputs.






