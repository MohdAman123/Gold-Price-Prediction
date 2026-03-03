## 📌 Project Overview

Gold prices are influenced by complex macroeconomic and financial factors including stock market indices, commodity prices, currency strength, and mining sector performance. Accurately modeling these relationships is a challenging regression problem due to non-linearity, multicollinearity, and market volatility.

This project builds a machine learning system to predict gold prices (GLD ETF Close) using financial market indicators such as:

- S&P 500
- Dow Jones Index
- US Dollar Index
- Oil, Silver, Platinum, and Palladium prices
- Gold Miners ETF (GDX)
- Oil ETF (USO)

The system performs:

- Exploratory Data Analysis (EDA)
- Correlation & Feature Importance Analysis
- Outlier Detection (IQR Method)
- Model Training & Comparison
- Performance Evaluation using R², MAE, MSE, RMSE
- Hyperparameter tuning (KNN optimization)
- REST API deployment using Flask

Multiple regression models are compared:

- Simple Linear Regression
- Multiple Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## 🚀 Key Highlights

- Identified strong inverse relationship between Gold and US Dollar Index
- Observed high positive correlation between GLD and GDX
- Compared linear vs non-linear models
- Built complete ML pipeline from data preprocessing to deployment
- Implemented interactive visualizations for financial insight analysis
- Designed scalable API architecture for real-time prediction
- K-Nearest Neighbors (KNN)
- 
## 🔮 Future Improvements

- Implement Time Series Cross-Validation
- Add Lag Features & Rolling Averages
- Integrate XGBoost for improved performance
- Compare with LSTM-based deep learning models
- Deploy on cloud platform (Render / AWS / Railway)

The final model is integrated into a Flask-based web application that provides real-time predictions through a REST API.
=======
# 🪙 Gold Price Prediction Web App

A full-stack machine learning web application that predicts gold prices using financial market indicators.  
The project integrates data analysis, model training, and a Flask-based web interface for real-time predictions.

---

## 📌 Project Overview

Gold prices are influenced by multiple economic and financial factors such as stock indices, currency values, and commodity prices.  

This project builds a predictive system using machine learning models to estimate gold prices based on these indicators.

---

## ⚙️ Features

- 📊 Multiple ML models comparison (KNN, Linear Regression, Random Forest, etc.)
- 📈 Interactive dashboard for data visualization
- 🔍 Feature correlation analysis
- 📉 Model evaluation (R², MAE, RMSE)
- ⚡ Real-time prediction via REST API
- 🌐 Flask-based web interface

---

## 🧠 Machine Learning Models Used

- K-Nearest Neighbors (Best Model)
- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting

---

## 📊 Dataset

The dataset contains financial indicators such as:

- S&P 500 Index
- Dow Jones Index
- USD Index
- Oil Prices
- Silver Futures
- Platinum & Palladium Prices
- ETF Data (GDX, USO)

> Note: Dataset is not included due to size. Add your dataset in the `Dataset/` folder.

---

## 🏗️ Project Structure

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/MohdAman123/Gold-Price-Prediction.git
cd Gold-Price-Prediction
>>>>>>> 25f3514 (Merged remote changes)
