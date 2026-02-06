# Detecting Aberrations in Optical Fiber Networks

## 📌 Overview
**Detecting Aberrations in Optical Fiber Networks** is a machine learning–driven system designed to automatically detect and localize faults in optical fiber networks. The project focuses on identifying abnormal patterns in network signals at an early stage, reducing dependency on manual diagnostics and minimizing service downtime.

The system leverages a hybrid approach combining **deep learning** and **traditional machine learning models** to achieve accurate anomaly detection and fault localization.

---

## 🎯 Objectives
- Automatically detect anomalies in optical fiber network data  
- Localize faults with minimal human intervention  
- Improve network reliability and performance  
- Reduce maintenance time and operational costs  
- Enable early fault detection to prevent service outages  

---

## 🧠 Methodology
The project employs multiple models to capture different characteristics of network behavior:

- **Variational Autoencoders (VAEs)**  
  - Learn normal signal patterns in an unsupervised manner  
  - Detect deviations indicating potential anomalies  

- **Recurrent Neural Networks (RNNs)**  
  - Model temporal dependencies in time-series network data  
  - Identify sequential and evolving fault patterns  

- **Random Forest**  
  - Perform robust feature-based classification  
  - Improve interpretability of detected anomalies  

- **XGBoost**  
  - Enhance fault classification and localization accuracy  
  - Handle complex, non-linear relationships efficiently  

The outputs of these models are combined to provide reliable anomaly detection and precise fault localization.

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Deep Learning:** TensorFlow / PyTorch  
- **Machine Learning:** scikit-learn, XGBoost  
- **Data Processing:** NumPy, Pandas  
- **Visualization:** Matplotlib, Seaborn  

---

## ⚙️ System Workflow
1. Network signal data is collected and preprocessed  
2. VAEs learn baseline normal behavior  
3. RNNs analyze temporal patterns in the data  
4. Random Forest and XGBoost classify and localize faults  
5. Detected anomalies are flagged for maintenance action  

---

## 📊 Results & Impact
- Automated fault detection reduced manual diagnostics effort  
- Early anomaly identification improved network reliability  
- Faster fault localization enabled quicker maintenance response  
- Reduced service downtime and operational disruptions  

---

## 🚀 Applications
- Optical fiber communication networks  
- Telecom infrastructure monitoring  
- Large-scale network performance management  
- Predictive maintenance systems  

---

## 🔮 Future Enhancements
- Real-time streaming anomaly detection  
- Integration with network management systems (NMS)  
- Explainable AI for clearer fault interpretation  
- Scalability to multi-node and large-scale fiber networks  

---

