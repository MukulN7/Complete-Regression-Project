# Student Exam Score Prediction
## Overview
This project uses machine learning to predict students' exam scores using various features provided like previous scores attendance etc, it uses a publicly available kaggle dataset and various data pre processing and data visualization steps throughout and is a complete regression solution to the task.
The project leverages a robust data preprocessing pipeline, including cleaning, encoding, scaling, and visualization, followed by predictive modeling with grid search optimization.

## Features
The dataset includes the following features:
Hours_Studied	
Attendance
Parental_Involvement	
Access_to_Resources
Extracurricular_Activities	
Sleep_Hours	
Previous_Scores	
Motivation_Level
Internet_Access	
Tutoring_Sessions	
Family_Income
Teacher_Quality	
School_Type
Peer_Influence
Physical_Activity
Learning_Disabilities	
Parental_Education_Level	
Distance_from_Home	
Gender	
Exam_Score

## Workflow
1. Data Preprocessing
Data Cleaning: Handling missing or inconsistent data.
Data Encoding: Converting categorical features into numerical formats using various techniques.
Data Scaling: Normalizing feature values to improve model performance.
2. Exploratory Data Analysis (EDA)
Data Visualization: Insights on feature correlations and distributions using Matplotlib.
3. Model Development
Model Selection: Implementing regression models to predict exam scores.
Hyperparameter Tuning: Using Grid Search for optimized model performance.

## Tools and Libraries
The project uses the following Python libraries:
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Matplotlib: For data visualization.
Scikit-learn: For machine learning models and utilities.
and other mentioned libraries.

## Results
Evaluation metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE) and R² Score were used to assess model performance.
Grid Search helped identify the best hyperparameters, improving prediction accuracy.

## Dataset
The Students Performance dataset can be found on Kaggle:https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

## License
This project is available under the MIT License.
