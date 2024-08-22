# British Airways Good or Bad?
This project is a part of the Data Science virtual internship program offered by Forage with British Airways.

## The virtual Internship is divided into two main tasks
1. Web scraping to gain company insights
2. Predicting customer buying behaviour

### Task 1 - Web scraping to gain company insights
Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA.

This first task is focused on scraping and collecting customer feedback and reviewing data from a third-party source and analysing this data to present any insights you may uncover.

Customer review data for Britis Airways was collected from [Skytrax](Skytrax).

#### Data Cleaning & Exploration:

Reviews were cleaned for punctuation, spelling, and special characters.
###### Exploratory Data Analysis (EDA) revealed the following:
- Average Overall Rating: The average rating for the reviews is 4.58, indicating a generally positive overall customer sentiment.
- Top 5 Reviewing Countries: UK,USA,Australia,Canada,Germany
- Highest Rating Country: Dominician Republic,Ecuador,Costa Rica,Japan.
- Periods of Decreased Ratings:From March 2020 to October 2021, there was a decrease in reviews due to travel restrictions caused by the Covid pandemic. 
  
###### Text Analysis:

- Wordcloud visualization identified the most frequent keywords: flight, seat, service, cabin crew, and good experiences. However, negative sentiments related to delays, problems, and bad experiences are also evident.
- N-gram analysis revealed positive sentiment towards cabin crew.
- Vader sentiment analysis indicated 55.5% positive reviews.


Following insights were uncovered as they are summed up in the one slide presentation.

![Screenshot 2024-08-19 231632](https://github.com/user-attachments/assets/ec313735-9964-4baa-8a80-7a0b8e8d4683)

### Task 2 - Predicting customer buying behaviour
#### Objective:

Predict customer buying behavior for flight bookings.
#### Methodology:

- Model Training: Two models were trained: Random Forest Classifier and XGBoost Classifier.
- Model Evaluation: F1-score was used as the primary evaluation metric.
- Class Imbalance Handling: Oversampling and undersampling techniques (SMOTE-RUS) were employed to address the class imbalance in the dataset.
- Feature Importance: XGBoost feature importance was analyzed to identify key factors influencing bookings.

This task involves building a high quality predictive to predict the successful bookings using customer bookings data.


![Screenshot 2024-08-19 231805](https://github.com/user-attachments/assets/79c95b13-100b-4344-a53e-ba7c62a2cf47)

## Conclusion:

The predictive model successfully identified key factors influencing customer flight bookings, such as sales channel, trip type, length of stay, and passenger count. By leveraging these insights, British Airways can:

- Target marketing efforts more effectively.
- Personalize recommendations for each customer.
- Optimize flight pricing dynamically.
- Proactively engage potential customers.
  
These actions can lead to increased flight bookings and improved customer satisfaction.
