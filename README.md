# uber-traffic-analysis
"Traffic Forecasting - Data Cleaning, Preprocessing, Feature Engineering"

# 🚦 Uber Traffic Volume Forecasting

This project focuses on **analyzing and preparing historical traffic data** to build a predictive model that forecasts **hourly traffic volumes** at different road junctions. The dataset simulates Uber vehicle count data from Nov 2015 to Dec 2016.

## 🧠 Objective

Develop a predictive model to accurately forecast traffic volume using:
- Historical traffic patterns
- Time-based features (hour, day, month)
- Feature engineering & data pre-processing

---

## 📁 Dataset

- Dataset Name: `Dataset_Uber Traffic.csv`
- Time Period: November 2015 to December 2016
- Features: DateTime, Junction ID, Vehicle count

---

## ✅ Tasks Completed

### 🔍 1. Exploratory Data Analysis (EDA)
- Time series trend analysis
- Traffic peaks by hour, weekday, and junction
- Visualizations using `matplotlib` and `seaborn`

### 🧹 2. Data Cleaning & Preprocessing
- Handled missing values (`dropna()`)
- Removed duplicates
- Converted `DateTime` to datetime format
- Resampled traffic data to hourly intervals
- Standardized `Vehicles` count for model input

### ⚙️ 3. Feature Engineering & Selection
- Created time-based features:
  - `Hour`, `Day`, `Weekday`, `Month`, `IsWeekend`
- Created **lag features**:
  - Previous hour (`Lag_1`), Previous day (`Lag_24`)
- Performed **correlation analysis** to assess feature importance

---

## 🧰 Tools & Libraries Used

- Python Jupyter notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

                           
