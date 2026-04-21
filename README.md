# 📡 Network Traffic Prediction using Deep Learning

## 📌 Project Overview
This project focuses on analyzing and predicting network traffic using deep learning techniques. It combines time-series forecasting, anomaly detection, and model comparison to build an intelligent network analysis system.

The primary goal is to predict future network traffic (`bytes_sent`) and identify abnormal behavior using statistical and machine learning approaches.

---

## 🚀 Features
- 📊 Network Traffic Prediction (Time-Series)
- ⚠️ Anomaly Detection (Statistical + Labeled)
- 📈 Traffic Analysis (Time & Hour-based)
- 🤖 Multi-Model Comparison
- 🧠 Multi-Feature Deep Learning Model

---

## 🧠 Models Implemented
- LSTM (Long Short-Term Memory)
- BiLSTM (Bidirectional LSTM) ✅ *Best Performing*
- Transformer Model
- Self-Attention Model

---

## 📊 Evaluation Metrics
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

---

## 🏆 Key Result
BiLSTM achieved the best performance due to its ability to capture bidirectional temporal dependencies in network traffic data.

---

## 📂 Dataset Description
The dataset contains network traffic logs with features such as:

- `time` → Timestamp
- `bytes_sent` → Target variable (traffic to predict)
- `bytes_received`
- `packet_count`
- `duration`
- `bytes_per_packet`
- `label` → Indicates anomaly (0 = normal, 1 = anomaly)

---

## 🔍 Project Workflow

### 1️⃣ Data Preprocessing
- Time sorting
- Feature selection
- MinMax scaling
- Sequence generation for time-series

---

### 2️⃣ Traffic Analysis
- Average, peak, and minimum traffic
- Traffic variation over time
- Hourly traffic patterns

---

### 3️⃣ Anomaly Detection
- Statistical method (mean + 2×std)
- Dataset-based labeled anomalies
- Visualization of anomalies

---

### 4️⃣ Model Training
- Training multiple deep learning models
- Comparing performance using error metrics

---

### 5️⃣ Multi-Feature Prediction
- Using multiple input features
- BiLSTM for improved accuracy

---

## 📈 Results & Insights
- Network traffic is highly **noisy and dynamic**
- BiLSTM captures trends better than other models
- Transformer requires larger datasets for better performance
- Anomalies correspond to traffic spikes and unusual patterns

---

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📸 Output Visualizations
- Traffic Over Time Graph
- Hourly Traffic Distribution
- Anomaly Detection Graph
- Model Comparison (MAE, RMSE, MAPE)
- Prediction vs Actual Graph

---

## 🎯 Applications
- Network Monitoring
- Intrusion Detection Systems
- Traffic Forecasting
- Performance Optimization

---

## ⚠️ Limitations
- Dataset is noisy and irregular
- Transformer not fully optimized for small dataset
- Multi-feature prediction requires further tuning

---

## 🔮 Future Work
- Real-time traffic prediction
- Deployment using web dashboard
- Hybrid models (BiLSTM + Attention)
- Advanced anomaly detection using ML

---

## 👩‍💻 Author
**Mansi Adarsh**  
M.Tech Computer Networking  
MANIT Bhopal

---

## ⭐ Final Note
This project demonstrates how deep learning can be used to build intelligent systems for network analysis, combining prediction, anomaly detection, and data-driven insights.
