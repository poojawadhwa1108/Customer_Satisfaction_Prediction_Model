# Customer-Satisfaction-Prediction-Model

##### Overview
This repository stores the files for a project undertaken for the course ISSS610- Applied Machine Learning offered in SMU MITB.
It is a prototype of a Customer Satisfaction Prediction model built for Airbnb London. The aim of the project is to identify significant features that impact customer ratings of Airbnb using several classification models, by evaluating the best model which is able to predict the  customer rating most accurately. This evaluation has been done by using ROC curve metrics and accuracy and finally to base business recommendations using those identifies factors.

## Data Sources
Listing Data and Reviews Data to be downloaded from the InsideAirbnb website: http://insideairbnb.com/get-the-data.html.
Rest of the data sources as used in the Python notebooks are under the Folder named as Data. 

## Setup
The different models tried are Logistic Regression, Naive Bayes classification, Random Forest, Light GBM, XGBoost, CatBoost, Stacking, Deep Neural Network. The code set for each of these are available in separate python notebooks.

## Results
Based on Micro-average AUC, XGBoost model has the highest score of 0.95904. Micro Average ROC AUC is the chosen metric for selecting the best model. The reason why Micro Average ROC AUC score was chosen is because of the imbalanced class distribution in our data. Micro-average aggregates the contributions of all classes to compute the average metric by taking into account the class imbalance.

## FAQ/Troubleshooting
Please contact poojanwadhwa@gmail.com for more information
