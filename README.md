# Employee Promotion Prediction using Decision Tree

## Project Overview

This project uses a Decision Tree Classification model to predict whether an employee will be promoted based on their work-related and personal information.

The model learns patterns from employee data and predicts the promotion status of a new employee.

## Objective

The objective of this project is to build a Decision Tree classification model that predicts whether an employee will be promoted.

The model uses the following information:

- Age
- Experience
- Performance Score
- Training Hours
- Projects Completed
- Job Satisfaction

The target variable is:

- 0 → Not Promoted
- 1 → Promoted

## Dataset Description

The dataset contains information about employees and their work-related characteristics.

### Features

- **Age** – Age of the employee
- **Experience** – Years of work experience
- **Performance_Score** – Employee performance score
- **Training_Hours** – Number of training hours completed
- **Projects_Completed** – Number of projects completed
- **Job_Satisfaction** – Employee job satisfaction score

### Target Variable

- **Promoted** – Promotion status
  - 0 → Not Promoted
  - 1 → Promoted

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Machine Learning Model

A **Decision Tree Classifier** was used to predict employee promotion status.

The model uses the **Gini impurity** criterion and a maximum tree depth of 4.

## Project Workflow

1. Create the dataset
2. Understand the dataset
3. Perform Exploratory Data Analysis
4. Select features and target
5. Split the data into training and testing sets
6. Train the Decision Tree model
7. Make predictions
8. Evaluate the model
9. Analyze feature importance
10. Visualize the Decision Tree
11. Predict a new employee's promotion status

## Model Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

## Feature Importance

Feature importance was used to understand which features contributed most to the model's predictions.

In this dataset, **Projects_Completed** had the highest feature importance.

## Prediction

The trained model was used to predict the promotion status of a new employee based on their employee-related information.

## Conclusion

In this project, we built a Decision Tree Classification model to predict whether an employee will be promoted.

The project demonstrated the complete machine learning workflow, including data creation, exploratory data analysis, feature selection, train-test splitting, model training, prediction, evaluation, feature importance analysis, and Decision Tree visualization.

## Note

This project uses a small synthetic dataset created for learning and demonstration purposes. The results should not be considered suitable for real-world employee promotion decisions.
