# London House Prices Analysis Prediction

This project analyses and predicts house prices in London using machine learning techniques. The dataset contains various features about properties, including prices and addresses.

<h2>Key Features:</h2>
  
Data Cleaning & Exploration: Handling missing values and exploring correlations using heatmaps.\
Feature Engineering: Removing non-numeric columns (e.g., addresses) to improve model performance.\
Machine Learning Model: Implemented an XGBoost Regressor for price prediction.\
Evaluation Metrics: Assessed model accuracy using standard regression metrics.

<h2>Tech Stack:</h2>

Python, Pandas, NumPy, Matplotlib, Seaborn\
Scikit-Learn, XGBoost\
Jupyter Notebook\

This project demonstrates data preprocessing, feature selection, and predictive modelling techniques, making it a great example of real-world machine learning applications in real estate.

<h2>Project Workflow</h2>

Data Loading & Exploration\
•	Imported the dataset using Pandas.\
•	Displayed the first few rows to understand the structure.\
•	Checked for missing values and general dataset information.

Data Cleaning & Preprocessing\
•	Removed unnecessary columns (e.g., Address which is not useful for numerical prediction).\
•	Identified missing values and handled them appropriately.\
•	Generated correlation heatmaps using Seaborn to analyse feature relationships.

Feature Selection & Splitting\
•	Defined X (independent variables) and Y (target variable: Price).\
•	Split the dataset into training (80%) and testing (20%) sets using Scikit-Learn.

Model Training - XGBoost Regressor\
•	Chose XGBoost, a powerful gradient boosting model, for price prediction.\
•	Trained the model using X_train and Y_train datasets (excluding non-numeric columns).\
•	Evaluated model performance on training data.

Model Evaluation\
•	Used regression metrics to check performance: \
o	Mean Absolute Error (MAE)\
o	Root Mean Squared Error (RMSE)\
•	Compared actual vs. predicted values to validate model accuracy.

Visualization & Insights\
•	Created scatter plots and histograms to show data distribution.\
•	Used heatmaps to display correlations between features and target values.\
•	Displayed model predictions vs. actual house prices.


