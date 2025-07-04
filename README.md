# ☁️ Weather Forecasting for Early Warning System using Predictive Analytics

A Capstone Project submitted in partial fulfillment of the requirements for the degree of **Bachelor of Technology in Computer Science and Engineering** at **Vellore Institute of Technology**.

---

## 👨‍💻 Team Members
- **Anjali Mishra** (21BCE0872)  
- **Dherya Chaudhary** (21BCE3913)  
- **Amogh Vardhan Kona** (21BDS0148)  

🧑‍🏫 **Project Supervisor:** Dr. Jafar Ali Ibrahim S, Assistant Professor Sr. Grade 2, School of Computer Science and Engineering

---

## 🔍 Project Overview
The project proposes a predictive system that forecasts short-term weather conditions (temperature, rainfall) using **ARIMA** and **LSTM** models. The aim is to support **Early Warning Systems (EWS)** for communities at risk of extreme weather events such as heatwaves and floods.

> ✅ The system uses real-time data from the **Meteostat API** and locally stored CSV files, making it lightweight, transparent, and deployable even in low-resource environments.

---

## 🎯 Objectives
1. Forecast temperature and precipitation using ARIMA and LSTM models.
2. Classify forecasted data into risk levels — *Mild*, *Moderate*, *High*, *Severe*.
3. Provide accurate, interpretable, and actionable insights for real-time early warning.
4. Deliver a CSV-driven local pipeline, with optional Flask-based visualization.

---

## 🧠 Models Used
- **ARIMA (AutoRegressive Integrated Moving Average):**
  - Ideal for short-term, interpretable forecasts with low computational demand.
- **LSTM (Long Short-Term Memory):**
  - Capable of handling multivariate time series with improved accuracy, but requires high computational power.

---

## 🧪 Tools & Technologies
- **Languages & Frameworks:** Python, Jupyter Notebook, Flask (optional)
- **Libraries:** statsmodels, pandas, numpy, matplotlib, scikit-learn, Keras, TensorFlow
- **API:** [Meteostat API](https://dev.meteostat.net/)
- **Data Format:** CSV

---

## 📈 System Architecture
```
Input Layer         → CSV/API Weather Data
Preprocessing       → Clean & Interpolate Data
Forecasting         → ARIMA / LSTM
Risk Classification → Rule-Based Threshold Mapping
Output Layer        → CSV Report + Plots (matplotlib / plotly)
```

---

## 📊 Key Features
- **Modular Pipeline**: Each stage (preprocessing, forecasting, classification, visualization) is modular.
- **Risk Labeling**: Forecasts are classified into real-world severity levels.
- **Deployment Ready**: Fully functional without cloud dependence.
- **Low Resource**: Designed for execution on standard computers.

---

## 📁 Folder Structure (Suggested)
```
weather-warning-forecasting/
├── data/                  # Raw & processed weather data
├── code/             # Jupyter notebooks (ARIMA, LSTM)
└── README.md              # This file
```

---

## 🧪 Testing & Results
- **Accuracy:**
  - ARIMA: Reliable short-term forecasts, MAE < 2.0°C
  - LSTM: Better on complex multivariate data, but slower and needs more data
- **Risk Classification:**
  - Rule-based mapping provided clear outputs for decision makers.
- **Execution Time:**
  - ARIMA: Fast, ideal for real-time use
  - LSTM: Slower, better for batch processing

---
### 📘 Notebook Previews

- [Weather Forecasting Notebook (ARIMA)](https://nbviewer.org/github/anjali2128/weather-forecasting/blob/main/code/final_arima_review.ipynb)
- [Data Collection](https://nbviewer.org/github/anjali2128/weather-forecasting/blob/main/code/DataCollection.ipynb)
- [LSTM Model](https://nbviewer.org/github/anjali2128/weather-forecasting/blob/main/code/lstm.ipynb)
---
## 💡 Future Enhancements
- Add more weather parameters (humidity, wind, solar radiation)
- Develop ARIMA+LSTM hybrid models
- Build lightweight mobile/edge-ready versions
- Enable real-time streaming forecasts via Flask/REST APIs

---

## 📜 References
> A full list of research papers and technical resources is provided in the project report.

---


> 📝 *This README summarizes the capstone project submitted in April 2025 at Vellore Institute of Technology.*
