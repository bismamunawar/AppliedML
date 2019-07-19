Applied Machine Learning
In this part, I will be working with an advertising data set, indicating whether or not a particular internet user clicked on an Advertisement. The goal is to create a model that will predict whether or not a given user will click on an ad based on the features characterizing him/her.

This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

Questions
Exploration and analysis

Explore the features and their types.
Build a linear regression model to check what are the most significant features, using statsmodels. What are the features you would consider for building a prediction model? Why? Justify
Create a histogram of the users Age.
Create a plot showing Area Income vs. Age. Is there any correlation between these two features?
Create a plot of 'Daily Time Spent on Site' vs. 'Daily Internet Usage'

Modeling and prediction

We would like to predict if a given user would click on an ad. Is this a classification or regression task? Why?
Split the data into training and testing sets.
Using sickit learn and cross validation, calculate the accuracy of a Logistic Regression model.
What is the accuracy of a KNN classifier? What is the best K value for this problem? What is the difference between the two models?
