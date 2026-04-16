Ad Click Prediction Using Logistic Regression
Overview

This lab focuses on building a model to determine whether a user is likely to click on an advertisement. By using a set of user-related features, a Logistic Regression algorithm was trained on a synthetic dataset to classify user responses with high reliability.

Data Description

The dataset contains multiple features that describe user behavior and demographics:

Daily Time Spent on Site: Number of minutes a user spends browsing the website
Age: Age of the user
Area Income: Average income in the user’s region
Daily Internet Usage: Time spent online per day (in minutes)
Ad Topic Line: Title or headline of the advertisement
City: User’s city
Male: Gender indicator (1 = Male, 0 = Female)
Country: User’s country
Timestamp: Time at which the user interacted with the ad
Clicked on Ad: Target variable indicating whether the ad was clicked
Process
Data Exploration

Initial analysis was performed to better understand the dataset:

Used histograms to observe how age values are distributed
Applied joint plots to examine the relationship between age and income
Investigated how time spent on the site relates to internet usage
Created pair plots categorized by ad-click behavior to highlight patterns
Data Preparation
Selected only numerical features for model training
Divided the dataset into training (67%) and testing (33%) sets
Model Development
Applied Logistic Regression using the Scikit-Learn library
Increased iteration limit to ensure the model converges properly
Results

The model performed very well, achieving an accuracy of 97%.

Additional evaluation metrics:

Precision: 0.98 → very few false positives
Recall: 0.96 → most actual clicks are correctly identified
F1-Score: 0.97 → balanced and reliable performance
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Summary

The results show that Logistic Regression is highly effective for predicting whether users will click on ads. The selected features capture user behavior efficiently, leading to strong overall performance.
