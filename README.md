# traffic-flow-prediction
Traffic flow prediction using machine learning time-series model
# Traffic Flow Prediction using Machine Learning

## Overview
Accurate traffic prediction is essential for smart city planning and congestion management.

This project uses machine learning techniques to predict traffic volume based on historical data.

---

## Objectives
- Predict future traffic flow
- Understand time-series traffic patterns
- Apply machine learning for forecasting

---

## Dataset
- Synthetic time-series traffic data
- Features:
  - Time index
  - Traffic volume
- Created using sinusoidal pattern + noise

---

## Methodology
1. Generated time-series traffic data  
2. Created lag features (previous time steps)  
3. Trained Random Forest Regression model  
4. Predicted future traffic values  
5. Compared actual vs predicted  

---

## Results
- Model successfully captured traffic trends  
- Predicted values closely follow actual traffic patterns  

---

## Visualization
Graph comparing actual vs predicted traffic shows strong alignment.

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## Project Structure
traffic-flow-prediction/
│
├── traffic_flow_prediction.ipynb
├── traffic_time_series.csv
├── final_predictions.csv

---

## Conclusion
Machine learning models can effectively predict traffic flow patterns and support intelligent transport systems.

---

## Future Work
- Use real-world traffic datasets  
- Apply advanced models (LSTM, ARIMA)  
- Integrate with live traffic systems  

---

## Author
Moideen Nawaf  
Traffic Engineer | Transport Data Science Enthusiast
