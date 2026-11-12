# ⚡ Electric Vehicle (EV) Market Analytics & Prediction Hub

A comprehensive, end-to-end data science web application built with **Python**, **Streamlit**, **Pandas**, **Plotly**, and **Scikit-Learn** to analyze electric vehicle market trends and predict vehicle pricing and customer ratings on the fly.

---

## 🚀 Features

* **Real-Time KPI Metrics:** High-level executive overview tracking total EV models, average vehicle price, customer satisfaction ratings, and driving ranges.
* **Interactive Market Exploration:** Dynamic scatter plots comparing battery capacity against driving range, filtered by manufacturer and data parameters.
* **Machine Learning Price Predictor:** Real-time Random Forest regression model estimating expected vehicle retail pricing based on battery capacity, driving range, and top speed.
* **Customer Rating Estimator:** Predictive module forecasting anticipated consumer satisfaction based on technical specifications.

---

## 🛠️ Tech Stack

* **Frontend & Framework:** Streamlit (v1.38+)
* **Data Processing & Analysis:** Pandas, NumPy
* **Data Visualization:** Plotly Express
* **Machine Learning:** Scikit-Learn (Random Forest Regressor)
* **File Handling:** Openpyxl, Joblib

---

## 📂 Project Structure

```text
dashboard/
│
├── app.py                 # Main Streamlit application script
├── cleaned_ev_data.csv    # Cleaned and processed EV dataset
├── requirements.txt       # Python package dependencies
└── README.md              # Project documentation
