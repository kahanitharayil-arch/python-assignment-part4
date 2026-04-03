Part 4 – Student Data Analysis & Prediction
Overview

This section focuses on analyzing student performance data and building a simple machine learning model to predict whether a student will pass or fail.

Dataset:
The dataset (students.csv) contains information such as:

Subject marks (Math, Science, English, History, PE)
Attendance percentage
Study hours per day
Pass/Fail status


Data Analysis:
Using pandas, the dataset is explored to understand:

Basic structure (rows, columns, data types)
Statistical summary (mean, min, max, etc.)
Pass vs Fail distribution
Average marks across subjects
An additional column avg_score is created to represent each student’s overall performance.

Data Visualization:
Graphs are used to better understand patterns:

Bar Chart → Average score per subject
Histogram → Distribution of math marks
Scatter Plot → Study hours vs average score (Pass/Fail comparison)
Seaborn Plots → Cleaner visual insights for relationships

Machine Learning Model:

A Logistic Regression model is used to predict pass/fail outcomes.

Steps:
Select features (marks, attendance, study hours)
Split data into training (80%) and testing (20%)
Scale features using StandardScaler
Train the model using training data
Evaluate accuracy on both training and test sets

Output:
The model prints:
Training Accuracy → how well it learned
Test Accuracy → how well it performs on new data

Conclusion:
This part demonstrates how raw student data can be analyzed, visualized, and used to build a basic predictive model. It shows the complete workflow from data exploration to machine learning in a simple and practical way.