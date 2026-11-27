# Student Exam Performance Prediction

## Project Overview

This project explores the application of machine learning in predicting students' mathematics examination scores using demographic and educational characteristics.

The project uses the Students Performance in Exams dataset, containing 1,000 student records and information such as gender, parental level of education, lunch type, test preparation course and examination scores.

The main objective was to investigate whether these characteristics could provide sufficient information to predict students' mathematics performance.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

The project followed these main stages:

1. Data loading and inspection.
2. Data cleaning and quality checks.
3. Exploratory Data Analysis (EDA).
4. Feature selection and target definition.
5. Categorical feature encoding using One-Hot Encoding.
6. Training and testing data splitting (80:20).
7. Regression model development.
8. Model evaluation and comparison.

## Machine Learning Models

Four regression algorithms were tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

A baseline model was also developed to establish a performance benchmark.

## Model Evaluation Results

The models were evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R-squared (R²).

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 11.27 | 14.16 | 0.176 |
| Decision Tree | 12.73 | 16.10 | -0.065 |
| Random Forest | 12.40 | 15.73 | -0.017 |
| Gradient Boosting | 11.61 | 14.76 | 0.104 |

## Key Findings

Linear Regression achieved the best overall performance among the four algorithms. However, its R² score of 0.176 indicates limited predictive power.

Decision Tree and Random Forest showed evidence of overfitting, while Gradient Boosting performed comparatively better on unseen data but did not outperform Linear Regression.

The findings suggest that the selected features alone do not provide sufficient information for reliable individual mathematics score prediction.

## Conclusion

Although the project did not produce a sufficiently reliable model for practical deployment, it provided valuable experience in data analysis, preprocessing, machine learning model development and evaluation.

Future improvements could include collecting more data and incorporating additional features such as study hours, school attendance, previous academic performance and access to learning resources.

## Project Status

**Completed – Initial Model Development and Evaluation**

Further improvements and validation would be required before considering practical deployment.
