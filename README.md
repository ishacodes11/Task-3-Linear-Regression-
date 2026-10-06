# Task 3 - Linear Regression

## 📌 Project Overview

This project is part of my AI & ML Internship Task 3.

The objective of this task is to implement and understand Simple Linear Regression and Multiple Linear Regression using Python and Scikit-learn.

The California Housing dataset was used for predicting median house values.

## 🎯 Objectives

- Import and preprocess the dataset.
- Split the dataset into training and testing sets.
- Implement Simple Linear Regression.
- Implement Multiple Linear Regression.
- Evaluate the models using MAE, MSE, and R².
- Visualize regression results.
- Interpret model coefficients.
- Compare the performance of the two regression models.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## 📊 Dataset

The California Housing dataset was loaded using Scikit-learn's `fetch_california_housing` dataset.

The target variable is:

`MedHouseVal`

which represents the median house value.

## 🔹 Simple Linear Regression

Simple Linear Regression was implemented using:

- Feature: `MedInc`
- Target: `MedHouseVal`

The data was divided into training and testing sets using an 80:20 split.

The model was trained using Scikit-learn's `LinearRegression`.

### Evaluation Metrics

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

A regression line was also plotted to visualize the relationship between median income and median house value.

## 🔹 Multiple Linear Regression

Multiple Linear Regression was implemented using the following features:

- `MedInc`
- `HouseAge`
- `AveRooms`
- `AveBedrms`
- `Population`
- `AveOccup`

The target variable remained:

`MedHouseVal`

The model was evaluated using MAE, MSE, and R².

## 📈 Model Comparison

The performance of Simple Linear Regression and Multiple Linear Regression was compared using:

| Model | MAE | MSE | R² |
|---|---:|---:|---:|
| Simple Linear Regression | Calculated in notebook | Calculated in notebook | Calculated in notebook |
| Multiple Linear Regression | Calculated in notebook | Calculated in notebook | Calculated in notebook |

Lower MAE and MSE indicate smaller prediction errors, while a higher R² indicates that the model explains more variation in the target variable.

## 📊 Visualizations

The project includes:

- Regression line
- Actual vs Predicted values plot
- Model evaluation metrics
- Coefficient analysis

## 💡 Key Learnings

- Simple Linear Regression uses one predictor to estimate a continuous target.
- Multiple Linear Regression uses multiple predictors.
- MAE measures the average absolute prediction error.
- MSE gives greater weight to larger errors.
- R² measures the proportion of target variation explained by the model.
- Model coefficients help understand the relationship between individual features and the predicted target.

## 📁 Project Files

- `Task_3_Linear_Regression.ipynb` - Complete analysis and model implementation.
- `README.md` - Project documentation.

## ✅ Conclusion

Both Simple and Multiple Linear Regression models were implemented and evaluated.

The models were compared using MAE, MSE, and R², while visualizations were used to understand the predictions and regression results.

This project provided practical experience with regression modeling, model evaluation, and interpretation of linear regression models.
