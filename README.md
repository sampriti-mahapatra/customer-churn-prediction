# customer-churn-prediction

# Overview
Analysed Telco customer dataset to predict behavior that results in customer churn.


# Data Decsription
The raw data contains 7043 rows (customers) and 21 columns (features). Among the columns, 16 are categorical, 4 are numerical and 1 is the binary target variable (Churn).

# Data Preprocessing
- There were no missing or duplicate variables.
- The entries in TotalCharges needed to be converted to float type.
- Used Min-Max scaling to standardise numerical data
- Used one hot encoding to encode categorical variables

# Exploratory Data Analysis
- did box plots of numerical variables vs churn to understand customer behaviour
- plots of categorical variables vs churn also provided some insight

# Model Training
- used models like Logistic Regression, KNN, Decision Trees, Random Forest

# Model Evaluation
- used metrics like accuracy, precision, recall, but primarily, F! Score and ROC Curve to evaluate model performance

# Conclusion
Logistic Regression gave the best results. Performed hyperparameter tuning to enhance performance.
