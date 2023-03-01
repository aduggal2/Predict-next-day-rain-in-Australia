# Predict-next-day-rain-in-Australia

The project aims to predict next-day rain in Australia by training classification models on the target variable “RainTomorrow”. The dataset used for the analysis was sourced from Kaggle.
Source: https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

The project includes the following steps:

1. Data cleaning and exploratory data analysis
2. Data was split into input and output features.
3. Data was split into training and test data (70-30 split).
4. Data imbalance was handled using SMOTE (Synthetic Minority Oversampling Technique).
5. Various machine learning classification models were implemented using scikit-learn library. Algorithms such as logistic regression,    support vector, Random Forest, Naïve Bayes, K- nearest neighbors, XG-Boost, Gradient Boost, Ada Boost, CatBoost, and Artificial Neural 
6. Network were implemented using default and Grid-Search CV parameter tuning methods.
7. The best model was deployed for prediction.
8. The models used in the analysis are KNN, Naïve Bayes, Logistic Regression, SVM, Random Forest, XG-Boost, Gradient Boost, Ada Boost, CatBoost, and Artificial Neural Network. The best model was chosen based on evaluation metrics, and it was found that logistic regression performed the best with an accuracy of 85.30% after resolving the overfitting issue by tuning the model.

The link for our deployed application: https://rainfall-prediction-aus.herokuapp.com/
 
In summary, the project uses various classification models to predict next-day rain in Australia and selects the best model based on evaluation metrics.

Requirements to run the application:
Flask==1.1.2
gunicorn==20.1.0
itsdangerous==1.1.0
Jinja2==2.11.3
MarkupSafe==1.1.1
Werkzeug==1.0.1
click==7.1.2
numpy>=1.19.5
scipy>=1.4.1
scikit-learn>=0.24.2
matplotlib>=3.2.2
pandas>=1.1.5
xgboost==0.90
