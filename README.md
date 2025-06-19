# global-air-quality-index-ML-project
EDA + ML Modeling on Global Air Quality dataset (CO, NO2, SO2, PM2.5, etc.) to predict AQI using regression models like LR, KNN, RF, XGBoost.

# 🌍 Global Air Quality Analysis & Machine Learning

This project analyzes a global air quality dataset and applies various machine learning models to predict AQI based on environmental features.

## 📊 Sections

1. **Exploratory Data Analysis (EDA)**  
   - Visualized pollutant levels (CO, NO2, SO2, etc.)
   - Correlation heatmap and pairplots

2. **Feature Engineering**  
   - Converted date to `Month`
   - Label-encoded categorical features

3. **Modeling**  
   - ✅ Linear Regression
   - ✅ KNN Regressor
   - ✅ Random Forest Regressor
   - ✅ XGBoost Regressor
   - (Compared using MSE, MAE, R²)

4. **Conclusions**
   - Random Forest and XGBoost achieved highest performance
   - Observed spatial/temporal patterns in air pollution

## 🧠 Learnings
- Used statistical evaluation metrics
- Explored performance through graphs and residual plots
- Gained intuition behind model selection and tuning

## 🔧 Tools
- Python, Pandas, NumPy
- Scikit-Learn, XGBoost
- Seaborn, Matplotlib
- Google Colab

## 📁 Files
- `Global_Air_Quality_Analysis_and_ML.ipynb`: Full Colab notebook

## 🚀 Future Work
- Try classification (e.g., AQI level prediction)
- Apply PCA or dimensionality reduction
- Explore time series modeling

