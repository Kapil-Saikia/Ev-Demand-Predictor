# 🔋 EV Adoption Forecasting

As electric vehicle (EV) adoption surges, urban planners and policymakers must anticipate future infrastructure needs—especially EV charging stations. This project builds a predictive model to forecast future EV adoption trends using real-world data from Washington State.

---

## 📌 Problem Statement

The dataset includes monthly vehicle registration data broken down by county and vehicle type (electric vs non-electric) from 2017 to early 2024. Our objective is to:
- Forecast the growth in EV adoption.
- Provide data-driven insights to support sustainable transportation infrastructure planning.

---

## 🎯 Goal

To develop a regression model that can predict future EV registration volumes using historical trends, regional factors, and vehicle usage patterns.

---

## 📊 Dataset

**Source:** [Kaggle – Electric Vehicle Population Size (2024)](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

**Key Features:**
- `Date`: Date of vehicle count (monthly)
- `County`, `State`
- `Vehicle Primary Use`: Passenger / Truck
- `Battery Electric Vehicles (BEVs)`
- `Plug-In Hybrid Electric Vehicles (PHEVs)`
- `Electric Vehicle (EV) Total`
- `Non-Electric Vehicle Total`
- `Percent Electric Vehicles`

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn

---

## 🧹 Data Cleaning & Preprocessing (Completed)

Improvements made:
- Converted `Date` column to `datetime` format
- Handled missing values in `County` and `State` by filling with `'Unknown'`
- Capped outliers in `Percent Electric Vehicles` using IQR method
- Filtered invalid dates and cleaned nulls from critical columns

These steps ensure the dataset is consistent, reliable, and ready for further analysis and modeling.

---

## 👤 Author

**Kapil Saikia**  
B.Tech CSE Final Year Student  
💻 GitHub: [Kapil-Saikia](https://github.com/Kapil-Saikia)


