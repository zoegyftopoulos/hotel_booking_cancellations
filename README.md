# Classification Prediction of Hotel Booking Cancellations

# Problem
A chain of hotels from Portugal has noticed that the cancellation rate has risen in the past years. This often leads to rooms that are left unrented for multiple days at a time.

# Idea
Develop a model to predict the likelihood that a customer will cancel their reservation. This 
can be used to optimize the hotel booking service.

# Data
Booking data with over 119k entries from two hotels inclu-ding 32 variables with details about the bookings, collected between 07/2015 & 08/2017.
Source: Hotel booking demand datasets by N. Anto-nio, A. de Almeida, & L. Nunes for Data in Brief (2019)

# Steps
* Consistency checks
* Explore relationships
* Principial Component Analysis
* Train and compare Decision Tree & Logistic Regression
* Balance data for greater performance

# Results
After balancing the data, the Decision Tree performed better with a F1-Score of 76% com-pared to the Logistic Regression with a F1-Score of 69%. 

# Conclusion
* Use Decision Tree model for an average performance
  
# Outlook
* Perform Factor Analysis of Mixed-Type Data instead of PCA in order to include categorical variables
* Try different algorithms to improve model performance
