# heart-prediction-ann
# Heart Failure Prediction using ANN 🫀

---

## **📌 Project Description **

This project implements an **Artificial Neural Network (ANN)** to predict mortality caused by heart failure. By analyzing 12 clinical features, the model identifies high-risk patients to assist in clinical decision-making.

---

## **📂 Dataset Overview **
The dataset contains **299 medical records** with the following key features:
*   **Time:** Follow-up period (The most significant feature).
*   **Ejection Fraction:** Efficiency of the heart pumping.
*   **Serum Creatinine:** Level of creatinine in the blood.
*   **Age, Diabetes, High Blood Pressure, and Smoking.**
*   **DEATH_EVENT:** The target variable (0: Survived, 1: Deceased).

---

## **🛠 Steps Performed **

### **1. Data Analysis **
*   Explored data distribution and handled class imbalance.
*   Visualized correlations using **Heatmaps** and **Swarm plots**.

### **2. Preprocessing**
*   **Feature Scaling:** Using `StandardScaler` to normalize data.
*   **Train-Test Split:** 75% training and 25% testing.

### **3. Model Building | بناء النموذج**
*   **Architecture:** Multi-layer Perceptron (ANN).
*   **Activation:** `ReLU` for hidden layers and `Sigmoid` for output.
*   **Regularization:** Used `Dropout` and `EarlyStopping` to prevent overfitting.

---

## **📈 Evaluation & Results **
The model is evaluated using:
*   **Confusion Matrix:** To track True/False predictions.
*   **Classification Report:** Precision, Recall, and F1-Score.
*   **Visual Curves:** Accuracy and Loss plots over epochs.

---

## **💻 Tech Stack **
*   **Language:** Python 3
*   **Frameworks:** TensorFlow / Keras
*   **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

---

## **👥 Team **
**PINK VOLT TEAM**
*   *Project developed as part of AI & Deep Learning study.*
* 
## رنا احمد فتحى زاكى المغربى
## رنا طارق السيد المندوه المنطاوى
## رجاء صبحى احمد محمد حسن
## دعاء احمد فؤاد احمد خميس
## ساره محمود محمد عبدالعزيز الشوبرى
## سماح رمضان ناجى عيد عبدالكريم

---
**Date:** 2026
