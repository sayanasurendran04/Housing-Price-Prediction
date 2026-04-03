# Housing-Price-Prediction
Developed a complete end-to-end supervised regression model to predict median house prices in California districts. This project demonstrates the full Machine Learning pipeline — from data exploration to model deployment — using real-world housing data

Objective:
To accurately predict house prices based on various district-level features such as median income, housing age, number of rooms, population, and location, helping potential buyers, sellers, and real estate agencies make data-driven decisions.

Dataset:
California Housing Dataset (20,640 observations) from scikit-learn, containing 8 numerical features and 1 target variable (MedHouseVal).
Key Steps & Techniques:

Performed comprehensive Exploratory Data Analysis (EDA) including correlation heatmap and target distribution analysis.
Handled data preprocessing, feature selection, and train-test splitting (80-20).
Built and compared four regression models: Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.
Evaluated models using key performance metrics: MAE, MSE, RMSE, and R² Score.
Achieved the best performance with Random Forest Regressor (R² ≈ 0.82).
Visualized model results using Predicted vs Actual scatter plots and identified the most influential features.
Interpreted feature importance to understand key price drivers.

Major Insights:

Median Income (MedInc) is by far the strongest predictor of house prices.
Location (latitude & longitude) and average number of rooms also significantly impact pricing.

Tools & Technologies:

Python, Pandas, NumPy, Matplotlib, Seaborn
Scikit-learn (for modeling and evaluation)
Joblib (model serialization)

