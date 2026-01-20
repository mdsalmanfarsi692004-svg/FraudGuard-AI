# 🛡️ FraudGuard AI | Financial Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange)

**FraudGuard AI** is a machine learning-based application designed to detect fraudulent financial transactions in real-time. It analyzes transaction patterns to classify them as **Safe** or **Fraudulent**.

🔗 **Live Demo:** [Click Here to View App](INSERT_YOUR_STREAMLIT_LINK_HERE)

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](images/home_page.png) 
*(Make sure to put your actual screenshot filenames here)*

### ✅ Safe Transaction Result
![Safe Result](images/safe_result.png)

### ⚠️ Fraud Detected Alert
![Fraud Result](images/fraud_result.png)

---

## 🚀 Features
* **Real-time Analysis:** Instant prediction upon data entry.
* **User-Friendly UI:** Built with Streamlit for a clean, interactive experience.
* **Secure & Fast:** Uses a pre-trained ML pipeline (`joblib`) for quick inference.
* **Actionable Insights:** Provides specific recommendations for flagged transactions.

---

## 🛠️ Tech Stack
* **Frontend:** Streamlit (Python)
* **Machine Learning:** Scikit-Learn, Pandas, NumPy
* **Model Serialization:** Joblib

---

## 💻 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/FraudGuard-AI.git](https://github.com/your-username/FraudGuard-AI.git)
   cd FraudGuard-AI
2. **Install Dependencies**
   pip install -r requirements.txt
3. **Run the App**
   streamlit run main.py
