# Titanic Survival Challenge

This project is based on the Kaggle challenge called 'Titanic: Machine Learning from Disaster.'
It aims to use existing data regarding passengers aboard the Titanic, including their age, gender, cabin class, ticket fare, etc. to build a model that can  predict the survival of a passenger from the test set. 

The following steps have been taken to process the data and feed it to various classfication models.
1. Data Cleaning and substitutions for null values
2. Encoding categorical variables using the sklearn library
3. Reducing skewness of numerical variables using log transfrmation
4. Creating new, meaningful features that capture the relevant information better.
5. Making trial runs with various classification models and assessing accuracy using 5-fold cross validation
