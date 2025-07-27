# Traffic Flow Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting traffic flow across urban junctions using machine learning and deep learning models. The aim is to help reduce congestion, optimize traffic signals, and assist city planners in managing road traffic more efficiently.

## 🧠 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  

## 📊 Dataset
The dataset contains historical traffic volume data recorded at four major junctions at hourly intervals. It includes:
- DateTime
- Junction ID
- Vehicle count
- Sensor ID

## 🔍 Methodology
- **Data Preprocessing**: Handled missing values, created time-based features (year, month, weekday, hour).
- **Exploratory Data Analysis**: Identified patterns, trends, and seasonality.
- **Stationarity Check**: Performed Augmented Dickey-Fuller test.
- **Data Transformation**: Applied differencing and normalization.
- **Modeling**: Used GRU (Gated Recurrent Unit) to forecast traffic volume per junction.
- **Evaluation**: Used RMSE and plotted actual vs predicted results.

## 📈 Results
The GRU model provided better accuracy compared to traditional methods, showing strong performance in capturing temporal patterns and trends in traffic data.

## ✅ Conclusion
Machine learning models, especially recurrent neural networks, can significantly enhance traffic flow prediction accuracy and support intelligent transportation systems.

## 🧑‍💻 Author
**Dinesh Kumar** 
