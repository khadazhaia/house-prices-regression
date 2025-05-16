# House Prices Prediction

This project aims to predict house sale prices using a structured data science workflow: from exploratory data analysis (EDA) to data cleaning, and finally regression modeling. The dataset contains various features of residential homes, and the ultimate goal is to accurately forecast sale prices using machine learning.

## Exploratory Data Analysis (EDA)

Dives deep into understanding the structure and relationships within the dataset.

Univariate Analysis: Analyzed the distribution of dwelling types, lot areas, and sale prices.

Bivariate & Multivariate Analysis: Assessed how features like dwelling type and lot area affect sale price and identified numeric features that most correlated with sale price.

Notable Insights:

Features such as OverallQual, GrLivArea, and GarageCars showed the strongest correlation with sale price.
Majority of dwellings were priced between $100,000 and $300,000.
Higher-quality homes significantly influenced sale price.

## Data Preprocessing (Clean)

Focuses on transforming the raw dataset into a form suitable for modeling.

Tasks Performed:

Handled missing values and inconsistent entries.
Encoded categorical variables and normalized numeric features.

## Model Evaluation 

Explores and compares different regression models to predict house sale prices.

Models Tried:

Linear Regression,
Random Forest Regressor,
Gradient Boosting Regressor,
XGBoost Regressor,

Model Evaluation Metrics:

Root Mean Squared Error (RMSE): Measures prediction error

R² Score: Measures how well variance is explained

Results:

Tuned Gradient Boosting Regressor (Best Performer)

RMSE ≈ $19,906

R² = 0.88 — Best overall performance

## Conclusion

The tuned Gradient Boosting Regressor model achieved the best accuracy and generalization, predicting house prices within an average error of less than $20,000. It explains nearly 88% of the variability in house prices based on features like overall quality, living area, and number of garage cars.