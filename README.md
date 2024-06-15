# Car-Price-Prediction-Using-Random-Forest-Regression

This project focuses on predicting the resale value of used cars based on various factors using a Random Forest Regressor. By leveraging machine learning techniques, we aim to create a model that can accurately estimate the selling price of a car given its model, age, and mileage.

**Key Steps and Analysis:**

**Data Loading and Visualization:**

Load the dataset containing car details such as model, age, mileage, and selling price.
Visualize the relationship between the age of the cars and their selling price using a scatter plot to understand trends and patterns.

**Data Preprocessing:**

Encode categorical variables like car models using Label Encoding to convert them into numerical format.
Standardize the features to have zero mean and unit variance, which is essential for the performance of many machine learning algorithms.

**Outlier Detection and Removal:**

Identify and remove outliers using the Z-score method to ensure the model is not skewed by extreme values.

**Feature Selection:**

Select relevant features for the model: Car Model, Age(yrs), and Mileage.

**Model Training:**

Train a Random Forest Regressor on the cleaned and preprocessed data.

**Prediction:**

Predict the selling price for specific car configurations such as a 4-year-old Mercedes Benz with 45000 miles and a 7-year-old BMW X5 with 86000 miles.

**Outcome:**

The Random Forest Regressor model provides predicted prices for used cars with specified features, demonstrating its utility in the used car market. Additionally, the model's accuracy score indicates its reliability in predicting car prices, highlighting the effectiveness of machine learning in the automotive resale industry. This project underscores the practical application of regression techniques for real-world financial estimations.
