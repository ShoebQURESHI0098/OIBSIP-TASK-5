# OIBSIP-TASK-5
OIBSIP tech internship Sales Prediction using Python
# 📊 Sales Prediction using Python & Machine Learning

## 📖 Overview
This project predicts future sales based on historical data using various machine learning models. The dataset includes features like date, store, product, and past sales to generate accurate forecasts.

## 📊 Dataset
The dataset contains the following features:
- 🏪 **Store ID** (Unique identifier for each store)  
- 🛍 **Product ID** (Unique identifier for each product)  
- 📅 **Date** (Daily/Monthly sales data)  
- 💰 **Sales (Target Variable)** (Total sales for a given period)  
- 🎯 **Promotions, Discounts, Seasonality Effects** (Optional)  

## 🚀 Technologies Used
- 🐍 Python  
- 📊 Pandas, NumPy  
- 📈 Matplotlib, Seaborn  
- 🤖 Scikit-learn (Machine Learning)  
- ⏳ Statsmodels (Time Series Analysis)  
- 🔢 Jupyter Notebook  

## 🏗️ Machine Learning Models Used
- ✅ Linear Regression  
- ✅ Decision Tree Regressor  
- ✅ Random Forest Regressor  
- ✅ XGBoost Regressor  
- ✅ ARIMA (For time-series forecasting)  
- ✅ LSTM (Deep Learning for advanced forecasting)  

## 📌 Project Workflow
1. **Data Preprocessing:** Handle missing values, feature engineering, and scaling.  
2. **Exploratory Data Analysis (EDA):** Identify trends, seasonality, and correlations.  
3. **Feature Engineering:** Convert categorical variables, create new time-based features.  
4. **Model Training & Evaluation:** Train multiple models and compare performance using RMSE and R² scores.  
5. **Forecasting & Visualization:** Generate future sales predictions and plot insights.  

## 🛠️ Installation & Setup
To run this project locally:

```sh
# Clone this repository
git clone https://github.com/yourusername/sales-prediction.git
cd sales-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook
📊 Model Performance
Model	RMSE (Lower is Better)	R² Score (Higher is Better)
Linear Regression	3000	85%
Decision Tree	2500	88%
Random Forest	2000	92%
XGBoost	1800	94%
ARIMA	2200	90%
LSTM	1500	96%
