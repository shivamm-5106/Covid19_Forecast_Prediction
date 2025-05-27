# covid19-forecast-ai
Simple and to the point – highlights forecasting and AI usage.
# 📊 COVID-19 Case Prediction in India Using Linear Regression

This project presents a basic implementation of time series forecasting for COVID-19 confirmed cases in India using a Linear Regression model. It demonstrates how to apply machine learning techniques for public health data analysis using Python and essential data science libraries.

---

## 📁 Project Overview

This project includes:
- Data preprocessing of global COVID-19 confirmed cases
- Extraction of India's daily confirmed cases
- Model training using Linear Regression
- Forecasting for 30 future days
- Visualization of actual vs. predicted trends

---

## 🧪 Technologies Used

- *Python 3*
- *Pandas* – Data manipulation and analysis
- *NumPy* – Numerical computations
- *Matplotlib* – Data visualization
- *Scikit-learn* – Machine learning model
- *Google Colab* – Cloud-based Python execution

---

## 🚀 How to Use

1. Upload the dataset.zip file in Google Colab.
2. Extract the dataset using Python’s zipfile module.
3. Load the CONVENIENT_global_confirmed_cases.csv file.
4. Clean and preprocess the data.
5. Extract time series data for India.
6. Train a Linear Regression model on the historical data.
7. Forecast the next 30 days and visualize the results.

---

## 📊 Output Visualization

- *Actual Data*: Line chart of historical COVID-19 cases in India.
- *Predicted Data*: Trend line projected using Linear Regression.
- *Train/Test Split*: Visual marker to differentiate training data from prediction range.

The visualization provides a clear comparison between actual and predicted data, aiding in trend analysis.

---

## 🔍 Dataset

- *Source*: CONVENIENT_global_confirmed_cases.csv
- *Format*: CSV
- *Content*: Global confirmed COVID-19 cases by date and country
- *Usage*: Filtered to isolate data for India

---

## 📈 Why Linear Regression?

Linear Regression is a simple, interpretable model ideal for initial trend analysis. Although it may not capture complex non-linear patterns, it offers a quick way to understand the data trajectory and serves as a foundation for more advanced forecasting techniques.

---

## 🔮 Future Enhancements

- Integrate advanced models such as *ARIMA, **Prophet, or **LSTM* for improved accuracy
- Include additional features like vaccination rates or mobility indices
- Build a web interface using *Streamlit* or *Dash*
- Deploy as a cloud-based forecasting tool with auto-updating data

---

## 👤 Author

Shivam Pandey
