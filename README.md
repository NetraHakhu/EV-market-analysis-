⚡ Electric Vehicle (EV) Analytics & Prediction Hub
An end-to-end data science project featuring comprehensive exploratory data analysis (EDA), feature engineering, a machine learning model, and an interactive dashboard built on a dataset of modern Electric Vehicles.

🚀 Project Overview
This repository contains a complete pipeline for analyzing EV specifications, pricing trends, and performance metrics (covering 2,000+ vehicle records across 24 features such as battery capacity, range, charging speed, and autopilot levels).

Key Highlights:
Data Cleaning & Validation: Handled missing values, checked logical duplicates, validated ranges (prices, ratings, warranties), and treated outliers using the Interquartile Range (IQR) method.

Feature Engineering: Created robust analytical features including:

price_per_mile (Cost efficiency relative to range)

range_per_kwh (Battery efficiency)

power_to_weight (Performance metric)

sales_value_proxy (Market valuation potential)

Machine Learning Model: (Add details about your model here—e.g., Price prediction using Random Forest / XGBoost).

Interactive Dashboard: (Add details about your dashboard tool here—e.g., Streamlit / Dash / Power BI).
📊 Exploratory Data Analysis & Insights
Price Distribution: Visualized luxury vs. mid-range market segmentation using Seaborn and Matplotlib.

Efficiency Metrics: Evaluated the correlation between battery capacity (kwh) and driving range (miles).

🛠️ Tech Stack
Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Dashboard: Streamlit / Plotly

Environment: Google Colab / Jupyter Notebook

💡 Future Enhancements
Incorporate real-time EV market data scraping.

Deploy the dashboard on Streamlit Community Cloud / Hugging Face Spaces.

Optimize the ML model hyperparameters for better prediction accuracy.
