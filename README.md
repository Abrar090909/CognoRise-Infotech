# CognoRise-Infotech
Here's a structured project report for your work with Cognorise Info:

---

# Project Report: Machine Learning Tasks with Cognorise Info

## Introduction
This report outlines the work done during a project with Cognorise Info, focusing on three distinct tasks using machine learning:
1. Iris flower classification
2. Car price prediction
3. Superstore sales prediction

Each task involved data preprocessing, model training, evaluation, and performance comparison of various machine learning algorithms.

## Task 1: Iris Flower Classification

### Objective
Classify iris flowers into three species: Setosa, Versicolour, and Virginica based on four features: sepal length, sepal width, petal length, and petal width.

### Data
- **Dataset**: Iris dataset from UCI Machine Learning Repository.
- **Features**: Sepal length, sepal width, petal length, petal width.
- **Target**: Iris species (Setosa, Versicolour, Virginica).

### Methodology
1. **Data Preprocessing**: Checked for missing values and performed normalization.
2. **Model Training**: Used several classifiers including:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)
3. **Model Evaluation**: Evaluated using accuracy, precision, recall, and F1-score.

### Results
- **Best Model**: Random Forest with an accuracy of 98%.
- **Conclusion**: Random Forest provided the best balance between performance and interpretability.

## Task 2: Car Price Prediction

### Objective
Predict the price of used cars based on various features such as make, model, year, mileage, etc.

### Data
- **Dataset**: Used car price dataset from Kaggle.
- **Features**: Make, model, year, mileage, fuel type, transmission, engine size, etc.
- **Target**: Car price.

### Methodology
1. **Data Preprocessing**: 
   - Handled missing values.
   - Encoded categorical variables.
   - Normalized numerical features.
2. **Feature Engineering**: Created additional features like car age.
3. **Model Training**: Used several regression models including:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - XGBoost Regressor
4. **Model Evaluation**: Evaluated using mean absolute error (MAE), mean squared error (MSE), and R-squared.

### Results
- **Best Model**: XGBoost Regressor with an R-squared of 0.92.
- **Conclusion**: XGBoost provided the best predictive performance due to its ability to handle non-linear relationships and interactions between features.

## Task 3: Superstore Sales Prediction

### Objective
Predict sales for a superstore based on various features such as order date, ship mode, segment, product category, etc.

### Data
- **Dataset**: Superstore sales dataset from Kaggle.
- **Features**: Order date, ship mode, segment, country, city, state, region, category, sub-category, product name, sales.
- **Target**: Sales.

### Methodology
1. **Data Preprocessing**: 
   - Converted date columns to datetime format.
   - Handled missing values.
   - One-hot encoded categorical variables.
2. **Feature Engineering**: Extracted features from the order date such as year, month, day, and day of the week.
3. **Model Training**: Used several regression models including:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - XGBoost Regressor
4. **Model Evaluation**: Evaluated using mean absolute error (MAE), mean squared error (MSE), and R-squared.

### Results
- **Best Model**: Random Forest Regressor with an MAE of 253.78.
- **Conclusion**: Random Forest provided the best predictive performance with a balance of accuracy and computational efficiency.

## Conclusion
The project successfully applied machine learning techniques to three distinct tasks, showcasing the versatility and effectiveness of different models. Each task provided insights into model selection, data preprocessing, and feature engineering, contributing to robust predictive performance across varied domains.
