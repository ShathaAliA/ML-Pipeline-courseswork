# Loan Approval Prediction using Machine Learning
A machine learning project that predicts whether a loan will be approved or not using a Random Forest Classifier. 
The project includes data preprocessing, feature engineering, model training, evaluation, and visualization.

# Dataset
Source: Kaggle
Format: CSV file

# Technologies Used
Python
Pandas & NumPy
Scikit-learn
SciPy
Matplotlib / Seaborn

# Data Preprocessing
Removed duplicate rows
Dropped irrelevant columns
Handled missing values using SimpleImputer
Cleaned categorical values
Converted categorical data into numerical format

# Feature Engineering
Created a custom risk_score feature based on:
Credit score
Loan-to-income ratio

# Outlier Handling
Used Z-score method to detect and remove outliers
Applied on key numerical features

# Model
Algorithm: Random Forest Classifier

# Train-Test Split
80% Training
20% Testing

# Evaluation Metrics
Accuracy
Classification Report (Precision, Recall, F1-score)

# Visualization
Histograms for feature distributions
Boxplots for outlier analysis
Scatter plots 
Correlation heatmap
