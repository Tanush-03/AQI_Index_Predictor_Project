# 🌫️ AQI Index Predictor | Python · EDA · Machine Learning

This project focuses on predicting the **Air Quality Index (AQI)** using supervised machine learning models. It leverages historical pollutant data from multiple Indian cities to build accurate models and provide visual insights through Exploratory Data Analysis and city-wise trends.

---

## 📌 Project Highlights

- ✅ Performed data cleaning and feature engineering on real-world AQI data.
- 📊 Conducted exploratory data analysis (EDA), including pollutant trends and correlation matrix.
- 🧠 Built and compared 3 ML models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- 📈 Achieved **R² Score of 0.80+** with Random Forest.
- 🔍 Visualized **feature importance** and **city-wise AQI trends** interactively using `ipywidgets`.

---

## 🗂️ Dataset

- **Name**: `city_day.csv`
- **Source**: Central Pollution Control Board, India *(via public repositories)*
- **Columns**: PM2.5, PM10, NOx, SO2, CO, O3, NH3, Benzene, Toluene, Xylene, etc.
- **Target**: `AQI` (Air Quality Index)

---

## 📊 Results

| Model              | R² Score | MAE    | RMSE   |
|-------------------|----------|--------|--------|
| Linear Regression | ~0.65    | 45–50  | ~70    |
| Decision Tree     | ~0.78    | ~30    | ~45    |
| ✅ Random Forest   | **0.80+** | **~25** | **~40** |

---

## 📌 Key Visuals

- 📈 **Correlation Heatmap** showing relationships between pollutants
- 🌲 **Feature Importance Bar Chart** from Random Forest model
- 🧭 **Interactive City-wise AQI Trend** using `ipywidgets` dropdown

---

## 📚 Libraries Used

- `pandas` – Data manipulation and preprocessing
- `numpy` – Numerical operations
- `matplotlib` – Plotting graphs
- `seaborn` – Statistical data visualization
- `scikit-learn` – Machine learning models and evaluation
- `ipywidgets` – Interactive dropdown widget in notebooks


