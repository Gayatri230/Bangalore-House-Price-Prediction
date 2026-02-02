# 🏠 Bangalore House Price Prediction

This project predicts house prices in Bangalore using machine learning techniques.

## 📌 Problem Statement
Given house features such as location, total square feet, number of bathrooms, and BHK,
predict the house price.

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn

## 🔍 Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- Converted `total_sqft` ranges into numerical values
- Feature engineering for BHK
- One-hot encoding for location
- Removed outliers based on:
  - Price per square feet
  - BHK vs price inconsistency
  - Bathroom count

## 📊 Model Training
Models evaluated:
- Linear Regression
- Lasso Regression
- Decision Tree Regressor

Used **GridSearchCV** and **cross-validation** to select the best model.

## ✅ Best Model
- **Linear Regression**
- R² Score ≈ **0.90**

## 🔮 Price Prediction Function
A custom function was created to predict prices based on:
- Location
- Square feet
- Bathrooms
- BHK

## 📈 Result
The model achieved around **90% R² score**, indicating strong predictive performance.

## 📂 Dataset
Source: Kaggle (Bengaluru House Prices)
