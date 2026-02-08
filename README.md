# 📊 ANN Customer Churn Prediction

An end-to-end Deep Learning project that predicts the probability of a bank customer churning (leaving the bank) using an **Artificial Neural Network (ANN)**.

🚀 **Live Web App:** [View Streamlit App](https://ann-customer-churn-prediction-hsjuuxcxrjs2wru954ai8a.streamlit.app/)

---

## 📝 Project Overview
Customer retention is crucial for financial institutions. This project implements a Deep Learning model to identify high-risk customers based on their demographic and financial history. By predicting churn, banks can proactively offer incentives to retain valuable clients.

## 🛠️ Tech Stack
* **Deep Learning:** TensorFlow & Keras
* **Web Framework:** Streamlit
* **Data Science:** Pandas, NumPy, Scikit-learn
* **Version Control:** Git & GitHub

## 📂 Project Structure
* `app.py`: The Streamlit web application script.
* `experiments.ipynb`: Jupyter notebook containing data analysis, model architecture, and training logs.
* `model.h5`: The saved pre-trained Artificial Neural Network model.
* `scaler.pkl`: StandardScaler object used for feature normalization.
* `label_encoder_gender.pkl`: Pickle file for encoding the 'Gender' feature.
* `onehot_encoder_geo.pkl`: Pickle file for encoding the 'Geography' feature.
* `requirements.txt`: List of Python libraries required to run the project.

## 🚀 Features
* **Instant Predictions:** Input customer details and receive a churn percentage and status (Churn/No Churn).
* **Robust Preprocessing:** Automatically handles feature scaling and categorical encoding to ensure data consistency.
* **User-Friendly UI:** Simple, interactive sliders and dropdowns for easy data entry.

## ⚙️ How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/PrincePandit16/ANN-Customer-Churn-Prediction.git](https://github.com/PrincePandit16/ANN-Customer-Churn-Prediction.git)
   cd ANN-Customer-Churn-Prediction
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch the App:**
   ```bash
   pip install -r requirements.txt
   ```
4. **📊 Dataset Information**
   ```bash
   Dataset: Churn_Modelling.csv
   Target variable: Exited
     0 → Customer stays
     1 → Customer churns
   Model: Multi-layer Artificial Neural Network
   Categorical features encoded using Label Encoding & One-Hot Encoding
   Numerical features scaled using StandardScaler
   ```
5. **Results**
   ```
   The ANN model achieves good predictive performance on unseen test data.
   Evaluation metrics and training logs are available in the experiment notebook.
   ```
## 📝 License

* *This project is open-source and intended for educational and learning purposes.*

## 🙌 Acknowledgements

* *This project demonstrates an end-to-end machine learning workflow, from data preprocessing to real-time deployment using Streamlit.*
