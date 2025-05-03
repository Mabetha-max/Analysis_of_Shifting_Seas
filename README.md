# 🌊 Ocean Climate Analysis & Coral Bleaching Prediction

This project analyzes realistic ocean climate data to uncover patterns related to **sea surface temperature (SST)**, **pH levels**, **marine heatwaves**, and **coral bleaching severity**. It also leverages machine learning and deep learning to predict bleaching outcomes based on environmental conditions.

---

## 📁 Dataset
- **File**: `realistic_ocean_climate_dataset.csv`
- **Features**:  
  - `Date`: Timestamp of observation  
  - `SST (°C)`: Sea Surface Temperature  
  - `pH Level`: Ocean acidity level  
  - `Marine Heatwave`: Boolean indicator of heatwave  
  - `Bleaching Severity`: Severity of coral bleaching  
  - `Species Observed`: Count of marine species  
  - `Location`: Observation point  

---

## 🧠 Objectives
- Visualize ocean climate trends and ecological patterns
- Analyze the impact of SST and pH on marine biodiversity
- Predict coral bleaching severity using:
  - Logistic Regression (ML)
  - Deep Neural Network (DL)

---

## 📊 Key Visualizations
- SST trends over time
- SST vs pH levels
- Species observed vs SST
- Bleaching severity distribution
- Marine heatwave occurrences by location

---

## 🤖 Models Used
### Logistic Regression (ML)
- Input: SST, pH, species observed
- Output: Bleaching severity classification
- Metrics: Accuracy, Confusion Matrix, Classification Report

### Deep Learning (DL)
- 2 hidden layers (64, 32 units)
- Activation: ReLU, Sigmoid
- Loss: Binary Crossentropy
- Optimizer: Adam

---

## 🔮 Future Scope
- Time-series forecasting using LSTM
- Geospatial heatmaps for high-risk zones
- Incorporation of more environmental features (salinity, oxygen, etc.)
- Interactive dashboard using Streamlit or Dash
