# Temperature-Forecasting-In-Jordanian-Cities

##  Project Title  
Temperature Forecasting in Jordanian Cities using Machine Learning and Deep Learning

##  Author  
Ali AlAwiede

##  Supervised by  
Eng. Maysa Khalil

##  Conducted at  
Ideal Innovation House

---

##  Overview  
This project focuses on predicting **daily temperature** in three major cities in Jordan:  
**Amman**, **Irbid**, and **Aqaba** using machine learning and deep learning techniques.  
By analyzing historical weather data, the model can provide accurate forecasts that support sectors such as **agriculture**, **energy**, and **tourism**.

---

##  Dataset Details  
- **Source:** Kaggle  
- **Time Range:** 2008 – 2021  
- **Total Records:** ~14,000 daily entries  
- **Unit:** Celsius (Fahrenheit removed)  
- **Format:** CSV  
- **Features:** Originally 42, selected relevant ones

---

##  Selected Features  
- Pressure  
- Wind Speed  
- Wind Direction  
- Dew Point  
- Sun Hour  
- Humidity  
- Day, Month (converted to sin/cos)  
- UV Index  
- Visibility (KM)  
- Total Precipitation (mm)  
- Wind Gust (KM)  
- Weather Code  
- Cloud Cover  

---

##  Data Preprocessing  
- Dropped irrelevant features (Fahrenheit, miles)  
- Handled missing values  
- Normalized features and target  
- Converted temporal data to sine/cosine  
- Split data: 80% training / 20% testing

---

##  Models Used  

- Linear Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  
- XGBoost  
- LightGBM  
- SVR (Support Vector Regression
- Multi-Layer Perceptron (MLP)  
- LSTM (Long Short-Term Memory) 

---

##  Evaluation Metric  
- **R² Score** (Coefficient of Determination)

LSTM achieved the highest performance, especially in modeling time dependencies in temperature data.

---

##  Future Work  
- Predict more variables (e.g., humidity, wind, etc.)  
- Build a web-based forecasting dashboard  
- Integrate real-time weather API  
- Expand to more cities or hourly predictions  
- Add satellite imagery or external geospatial data

---

##  Environment & Requirements  

```bash
Python >= 3.8
