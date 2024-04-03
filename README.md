# Rainfall
A Data science project to predict Railfall
Weather Prediction Machine Learning Model
Problem Statement:
The project aims to predict rainfall in Sydney using machine learning models based on weather-related data collected between 2008 and 2017. The dataset encompasses various weather variables such as temperature, humidity, precipitation, pressure, and cloud cover, allowing for the prediction of whether it will rain the following day.

Approach:
Data Preprocessing: Transformed categorical variables, handled missing values by replacing them with means, and checked for outliers.
Model Selection: Explored various classification models, including Decision Trees, Random Forest, Gradient Boosting, AdaBoost, XGBoost, Logistic Regression, and K-Nearest Neighbors.
Model Training and Evaluation: Split data into train and test sets, trained models, and evaluated performance using metrics like accuracy, ROC AUC, recall, and precision.
Model Comparison: Analyzed and compared the performance of different models to select the most accurate one.
Model Optimization: Utilized GridSearchCV to fine-tune hyperparameters for improved model accuracy.
Model Performance:
After evaluating several classification models, the Random Forest model emerged as the most accurate, achieving an 82.4850% accuracy score on the test dataset. It displayed robustness and minimized overfitting through ensemble methods.

Steps for Improvement:
To enhance the selected model's performance further, I used GridSearchCV to optimize hyperparameters for various models:

Decision Tree, Bagging, Gradient Boosting, Random Forest, AdaBoost, XGBoost, Logistic Regression, and K-Nearest Neighbors.
Dataset Information:
The dataset comprises 3337 entries with 17 columns covering weather parameters and the target variable indicating rainfall for the next day. Data preprocessing involved converting categorical variables, handling missing values, and ensuring appropriate data types for analysis and modeling.
