# CarRatingsNHTSA
The NHTSA's New Car Assessment Program (NCAP) evaluates vehicle safety through rigorous crash tests, rollover resistance assessments, and advanced driver assistance system (ADAS) testing to measure a vehicle's ability to protect occupants and prevent crashes.


# About the Dataset
<img width="433" alt="image" src="https://github.com/user-attachments/assets/87b83afe-c5c4-4146-b56d-d5f6e7d420f1" />


# Goal of the Project
Prediction of target variable Overall_Rating which is a multi-class Classfier (2,3,4,5)

# EDA/Preprocessing
- Checking the null values
- Columns with more than 50% blanks will be dropped
- Removing rows with nan target variable
- Describing the data (numerical variables)
- Correlation matrix for numerical variables with target (also check multicollinearity)
- Distribution of features (histograms, boxplots) 
- Outlier detection
- Data Cleaning for categorical variables
- Simple imputer : mean or median depends on the dataset
- Standard Scaler

# Train_Test Split 
Cleaned Dataset split into 80:20, stratify to make it robust

# Modelling
- Different models should be trained on the training datset and the results should be compared
- Confusion matrix
- Precision-Recall Curves

# Important Features
The most important features are found 
