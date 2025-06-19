# global-air-quality-index-ML-project
EDA + ML Modeling on Global Air Quality dataset (CO, NO2, SO2, PM2.5, etc.) to predict AQI using regression models like LR, KNN, RF, XGBoost.

# 🌍 Global Air Quality Analysis & AQI Prediction

This project explores a global air quality dataset from six major cities and builds machine learning models to predict the Air Quality Index (AQI) using key environmental features like CO, NO2, SO2, O3, PM2.5, and PM10.

## 📌 Project Highlights

- 🔍 **EDA (Exploratory Data Analysis)** with visualizations to understand pollutant trends and correlations
- 🧹 **Feature Engineering** including date processing and label encoding
- 🤖 **Regression Models**:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - XGBoost
- 📈 **Model Evaluation** using:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score
  - Residual Plots & Scatter Visualizations

---

## 🗂️ Dataset Info

- Source: [Kaggle](https://www.kaggle.com/datasets/youssefelebiary/global-air-quality-2023-6-cities)
- Features:
  - Pollutants: CO, NO2, SO2, O3, PM2.5, PM10
  - AQI values
  - City and Date

---

## 📊 Results Summary

| Model          | MSE     | MAE    | R² Score |
|----------------|---------|--------|----------|
| Linear Regression | 126.57  | 8.13   | 0.79     |
| KNN Regressor     | 75.75   | 5.19   | 0.88     |
| Random Forest     | 48.85   | 4.04   | 0.92     |
| XGBoost           | 48.56   | 4.11   | 0.92     |

📌 **Random Forest** and **XGBoost** outperformed others with the lowest error and highest accuracy.

---

## 🔧 Tools & Libraries Used

- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Seaborn, Matplotlib
- Google Colab

---

## 📁 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `Global_Air_Quality_Analysis_and_ML.ipynb` | Full EDA + modeling notebook |
| `.gitignore` | Git tracking exclusions |
| `README.md` | Project documentation |

---

## 🚀 Future Work

- Classify AQI into categories (Good, Moderate, etc.)
- Time Series Forecasting with advanced models
- Dimensionality reduction with PCA
- Hyperparameter tuning using GridSearchCV or Optuna

---

## 📬 Feedback & Contributions

Pull requests and suggestions are welcome!  
If you found this useful, feel free to ⭐ the repo and connect with me.

