# 📈 Time Series Forecasting Methods

This repository contains Python implementations of essential **time series forecasting methods**, including:

- ✅ **Simple Exponential Smoothing (SES)**
- ✅ **Double Exponential Smoothing (Holt's Method)**
- ✅ **Triple Exponential Smoothing (Holt-Winters Method)**
- ✅ **Moving Averages**

The goal of this repository is to **demonstrate and compare forecasting techniques** using synthetic demand data with trend and seasonality.

---

## 📊 Methods Covered

### 1. Simple Exponential Smoothing (SES)
- Suitable for data without trend or seasonality.
- Forecasts future values as a constant level, adjusted with a smoothing factor.

### 2. Double Exponential Smoothing (Holt's Method)
- Handles data with a trend.
- Forecast incorporates both level and trend components.

### 3. Triple Exponential Smoothing (Holt-Winters Method)
- Handles data with both trend and seasonality.
- Forecasts are adjusted for seasonal patterns (additive and multiplicative).

### 4. Moving Averages
- Simple method using the mean of past observations.
- Used for short-term forecasts and smoothing series.

---

## 🚀 Features

- ✅ **Self-contained synthetic datasets** — no external files required.
- ✅ **Clean, well-commented Python code** ready for educational and practical use.
- ✅ Automatic **forecast extension** for future periods.
- ✅ **Graphical visualizations** for each method.
- ✅ **Error analysis**: MSE, MAPE, MAD.
- ✅ Statistical tests (Ljung-Box) for autocorrelation checking.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** — Data manipulation
- **NumPy** — Numerical computations
- **matplotlib** — Plotting and visualization
- **scikit-learn** — Error metrics (MSE, MAPE, MAD)
- **statsmodels** — Time series models and statistical tests

---

## ✅ How to Run

1. **Clone this repository:**
```bash
git clone https://github.com/RenatoMaynard/time-series-forecasting-methods.git
```
2. **Install required packages**
```bash
pip install pandas matplotlib numpy scikit-learn statsmodels
```

---

## Acknowledgments
This project is designed for educational purposes to understand time series forecasting techniques in Python.

---

## ⚠️ Disclaimer
This project is for educational purposes only. Errors may exist. Please report issues or contribute improvements via pull requests.

---

## License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

   
