# 🌞 State-wise Renewable Energy Forecasting (India)

This project forecasts state-wise renewable energy generation in India for 2023 using historical data (2017–2022). It also clusters states based on their energy generation profile using machine learning.

---

## 📌 Problem Statement

Due to the increasing reliance on renewable energy and the impact of COVID-19 on energy trends, state-level forecasting is essential for planning and grid management.

---

## ✅ Project Objectives

- Forecast 2023 renewable energy generation for all Indian states using historical data
- Compare predictions against actual 2023 generation
- Evaluate model using MAE, RMSE, MAPE, SMAPE, and R²
- Cluster states by renewable profile using KMeans and PCA

---

## 📊 Dataset Sources

- Central Electricity Authority (CEA)
- Rajya Sabha Question Responses (Sessions 245, 259)
- Compiled and cleaned manually using Excel and Python

---

## 🔍 EDA (Exploratory Data Analysis)

- Period classification: Pre-COVID, During COVID, Post-COVID
- Source-wise and state-wise generation trends
- Region assignment and outlier handling
- Bar chart races, geo-animated maps, cluster heatmaps

---

## 🤖 Forecasting Methodology

- **Model Used**: Poisson Regression (non-negative)
- **Trained on**: 2018–2022
- **Tested on**: 2023 dataset (actual values)
- **Metrics**:
  - MAE: `982.10`
  - RMSE: `2631.41`
  - MAPE (cleaned): `58.89%`
  - SMAPE: `68.33%`
  - R² Score: `0.81`

---

## 🧠 Clustering

- Used **KMeans (k=3)** on average generation per energy source
- Applied **PCA** for 2D visualization
- Insights:
  - Cluster 0: High hydro states
  - Cluster 1: Low to medium all-source states
  - Cluster 2: High solar/wind states

---

## 🛠️ Tools & Libraries

- Python, Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn, statsmodels
- Jupyter Notebook, Excel (data cleaning)

---

## 🔮 Future Work

- Expand to forecasting 2024–2026
- Integrate weather + installed capacity data
- Explore hybrid models (ETS + Poisson + Prophet)
- Build web dashboard (Streamlit/Plotly Dash)

---

## 📜 License

[CC0 1.0 Universal](LICENSE)

---

## 👨‍💻 Author

- **Rajas Bhingarde**
- Contact: rajasbhingarde18@gmail.com
