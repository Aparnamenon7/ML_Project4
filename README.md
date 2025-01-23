# ML_Project4
Orinson Machine Learning Internship Task 4
**Student Performance Prediction Model**
This Python project demonstrates the development of a machine learning model to predict student performance based on various features using the Random Forest Regressor algorithm. The dataset used includes attributes that influence student performance, and the model aims to predict the final grades.

**Project Overview**
This project performs the following steps:-
Data Loading: The student performance dataset is loaded from a CSV file.
Data Preprocessing: Categorical features are encoded using LabelEncoder, and a correlation heatmap is generated.
Feature Engineering: Features are prepared for model training by splitting into training and testing sets and standardizing the numerical features.
Model Training: A Random Forest Regressor model is trained on the data.
Model Evaluation: The model's performance is evaluated using Mean Squared Error (MSE) and R-squared score. A scatter plot of actual vs. predicted values is also shown.
Feature Importance: The importance of each feature is calculated and visualized.
Model Saving: The trained model is saved to a file for future use.


**Dependencies**
The following Python libraries are required to run this code:-
pandas: For data manipulation and analysis.
matplotlib: For plotting graphs and visualizations.
seaborn: For creating statistical visualizations.
scikit-learn: For machine learning algorithms and data preprocessing.
joblib: For saving the trained model.
