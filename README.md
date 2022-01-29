# My Data Science Portfolio

# [Project 1: Predicting Credit Card Default (Classification)](https://github.com/VictorDonjuan/Credit-Card-Default-Prediction)

- In this project, we study a dataset from a credit card company with 30,000 observations on borrowers and several demographic features, as well as the payment history of the last 6 months. The goal is to predict wheter an account owner will default the next month (i.e, will not make the payment corresponding to that month).
- After a data analysis, we found that the data is unbalanced and some of the features need cleaning.
- We built a model with XGBoost Regressor and trained on 80% of the data, holding out the rest for testing purposes. The model got an accuracy score equal to 0.82 and ROC AUC score 0.78.
- In the last part of the project, we performed a Financial Analysis, estimating the total losses that the credit card company gets for account owners who default. We simulate a scenario where we use the model we built to propose an optimized way to obtain savings by preventing account owners from defaulting. 

# [Project 2: Heart Failure Prediction (Classification)](https://github.com/VictorDonjuan/Heart-Failure-Prediction)

- The objective of this project is to analyze and predict whether a person has a cardiovascular disease based on 11 clinical features, such as age, sex, cholesterol, max heart rate, etc.
- We start with a Data Analysis and study the correlation between the response variable and the numerical and categorical features.
- After data prepation, we build 5 differente classifier models on 80% of the test data: Logistic Regression, KNN, SVM, Random Forests and Gradient Boosting. We also study the impact on scaling and not scaling the data.
- The model that performed best is the KNN model, with a 90% of accuracy on the test data. We also take a look at Feature Importance from the Random Forests and Gradient Boosting models.

# [Project 3: Forecasting Sales - Kaggle Competition (Regression)](https://github.com/VictorDonjuan/Forecasting_Sales_Kaggle_Competition)

- In this Kaggle Competion, we are told to train a model on a dataset that provides sales from the years 2015, 2016, 2017 and 2018 and predict the sales on 2019. There are two fictional stores and products being sold in the Nordic Countries, however true seasonily and trends (such as weekends) were implemented on the dataset to simulate real-world situations.
- First, we tried to get a good score with a baseline Linear (Multiplicative) Regression, from which we obtained a score among the best 20% competitions in the competition.
- Then we tried to improve the previous score. By Feature Engineering from two external datasets, such as the GDP per country in those years, as well as the holiday dates, we were able to get a much better score, ranking among the best 11%.
- At the end of the project, use the year 2018 as a hold-out test in order to visualize how well the model performs on unseen data.

# [Project 4: Customer Segmentation (Clustering)](https://github.com/VictorDonjuan/Customer_Segmentation_ML)

- In this project, we are provided with a dataset with demographic characteristics and buying behaviors from customers of a store in the US. The objective is to perform a Customer Analysis by using Machine Learning Clustering techniques. 
- After data visualization and data cleaning, we use PCA (Principal Component Analysis) to reduce the dimension of the dataset since there are many features. Then we use Agglomerative Clustering in order to segment the customers into 4 Clusters.
- Every Cluster is then studied. We find what they have in common and describe the characteristics, thus making a general profile for every customer based on the cluster label.
