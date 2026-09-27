# 📊 Predictive Analytics Using Historical Data

## 📌 Project Overview

This project focuses on predictive analytics using historical sales data.

The objective is to analyze historical sales trends, preprocess the dataset, build a machine learning model, evaluate its performance, and forecast future sales.

A Random Forest Regression model is used to predict monthly sales based on historical time-series features.

---

## 🎯 Objectives

- Analyze historical sales data
- Clean and preprocess the dataset
- Identify sales trends over time
- Create time-series features
- Build a predictive machine learning model
- Evaluate model performance
- Compare actual and predicted sales
- Forecast future sales
- Analyze feature importance

---

## 📂 Dataset

The project uses the Sample Superstore sales dataset.

The dataset contains information such as:

- Order Date
- Sales
- Quantity
- Discount
- Profit
- Category
- Region
- Customer information
- Product information

The dataset is transformed into monthly sales data for forecasting.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Model

### Random Forest Regression

A Random Forest Regression model is used to predict monthly sales.

The model uses historical time-series features including:

- Year
- Month
- Quarter
- Previous month sales
- Previous 2-month sales
- Previous 3-month sales
- Previous 6-month sales
- Previous 12-month sales
- 3-month rolling average
- 6-month rolling average

---

## 📊 Data Processing

The following preprocessing steps were performed:

1. Loaded the historical dataset
2. Checked dataset structure
3. Checked missing values
4. Removed duplicate records
5. Converted Order Date into datetime format
6. Converted Sales into numeric format
7. Removed invalid records
8. Sorted records chronologically
9. Aggregated sales by month
10. Created time-series features

---

## 📈 Data Visualization

The project generates visualizations for:

- Historical monthly sales
- Actual vs predicted sales
- Historical sales and future forecasts
- Feature importance

---

## 📏 Model Evaluation

The model is evaluated using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted sales.

### Root Mean Squared Error (RMSE)

Measures prediction error while giving higher weight to larger errors.

### R² Score

Measures how well the model explains the variation in sales.

---

## 🔮 Future Forecast

The trained model is used to forecast sales for the next six months.

The forecast is generated recursively using previously predicted sales values as historical inputs.

---

## 📁 Project Structure

```text
Predictive_Analytics/
│
├── Data/
│   └── Sample - Superstore.csv
│
├── predictive_analytics.ipynb
│
├── README.md
│
└── requirements.txt