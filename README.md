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
