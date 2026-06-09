# Week 3 - Day 1 Machine Learning Fundamentals Challenge

## Objective

This project demonstrates the complete Machine Learning workflow using Scikit-learn. The goal is to build a Linear Regression model that predicts student marks based on study hours, attendance, and assignments.

## Dataset

The dataset contains the following columns:

* Study_Hours
* Attendance
* Assignments
* Marks

## Tasks Performed

### 1. Dataset Exploration

* Loaded dataset using Pandas
* Displayed first and last 5 rows
* Checked shape, columns, and data types
* Generated summary statistics

### 2. Feature and Label Identification

Features:

* Study_Hours
* Attendance
* Assignments

Label:

* Marks

### 3. Machine Learning Workflow

* Data Collection
* Data Cleaning
* Feature Selection
* Train-Test Split
* Model Training
* Testing
* Evaluation
* Prediction

### 4. Train-Test Split

* 80% Training Data
* 20% Testing Data

### 5. Model Training

* Algorithm: Linear Regression
* Displayed coefficients (slope)
* Displayed intercept

### 6. Predictions

Predicted marks for new student data using the trained model.

### 7. Actual vs Predicted Comparison

Compared actual marks with predicted marks and calculated prediction differences.

### 8. Model Evaluation

Evaluation Metrics:

* Mean Absolute Error (MAE)
* R² Score

### 9. Data Visualization

Created the following Plotly visualizations:

* Study Hours vs Marks
* Attendance vs Marks
* Assignments vs Marks
* Regression Line Visualization
* Predicted Marks Trend

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Plotly
* Jupyter Notebook
* VS Code

## Repository Structure

week3-day1-ml-fundamentals

├── student_performance.csv

├── assignment.ipynb

├── ml_workflow.txt

├── answers.txt

├── screenshots/

│ ├── plot1.png

│ ├── plot2.png

│ ├── plot3.png

│ ├── plot4.png

│ └── plot5.png

└── README.md

## Conclusion

A Linear Regression model was successfully built and evaluated using student performance data. The project demonstrates the basic concepts of machine learning, including data preprocessing, model training, prediction, evaluation, and visualization.
