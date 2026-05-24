✈️ Flight Price Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting flight ticket prices using machine learning regression models. The workflow includes exploratory data analysis (EDA), data preprocessing, feature engineering, model building, hyperparameter tuning, cross-validation, and residual analysis.

The goal of this project is to understand the factors affecting airline ticket prices and build optimized regression models capable of accurately predicting flight fares.

📂 Dataset Information

The dataset contains flight booking details such as:

Airline
Source City
Destination City
Departure Time
Arrival Time
Number of Stops
Travel Class
Duration
Flight Price (Target Variable)
🎯 Problem Statement

Flight ticket prices vary significantly depending on multiple factors such as airline, class, journey duration, and number of stops. The objective of this project is to analyze these factors and build machine learning models capable of predicting flight prices accurately.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📊 Exploratory Data Analysis (EDA)

Performed detailed EDA to identify:

Distribution of flight prices
Airline-wise pricing trends
Relationship between duration and ticket price
Effect of stops on fare prices
Correlation between numerical features
Outliers and skewed distributions

Various visualizations were created using Matplotlib and Seaborn.

⚙️ Feature Engineering & Preprocessing

The following preprocessing techniques were applied:

Handling categorical variables
One-Hot Encoding
Feature Scaling using StandardScaler
ColumnTransformer and Pipeline implementation
Outlier analysis
Data transformation
🤖 Machine Learning Models Used

The following regression models were trained and evaluated:

Linear Regression
Ridge Regression
Lasso Regression
Decision Tree Regressor
Random Forest Regressor
🔍 Hyperparameter Tuning

Model optimization was performed using:

GridSearchCV
RandomizedSearchCV

This helped improve model generalization and reduce overfitting.

📈 Model Evaluation Metrics

Models were evaluated using:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Cross Validation Score

Residual plots were also analyzed to understand model behavior and prediction errors.

📉 Residual Analysis

Residual analysis was performed to evaluate how well the models captured underlying patterns in the data.

Key observations:

Linear models showed structured residual patterns indicating nonlinear relationships.
Tree-based models performed better due to their ability to capture complex interactions.
Heteroscedasticity was observed in some linear models, especially for higher ticket prices.
📌 Key Insights

Some important insights from the analysis:

Flight duration significantly impacts ticket pricing.
Business class flights create distinct pricing clusters.
Airlines and number of stops strongly influence fare prices.
Tree-based models outperformed linear models due to nonlinear relationships within the dataset.
🚀 Future Improvements

Potential future enhancements include:

Model deployment using Flask or Streamlit
Advanced boosting algorithms such as XGBoost or CatBoost
Feature selection techniques
Real-time fare prediction system
Model explainability using SHAP values

Project Structure 
flight-price-prediction/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   ├── flight_price_EDA.ipynb
│   └── flight_price_predictor.ipynb
│
├── images/
│   ├── residual_plot.png
│   ├── feature_importance.png
│   └── correlation_heatmap.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
