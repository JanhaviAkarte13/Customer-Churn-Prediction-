# 📉 Customer Churn Prediction
---

## 📌 Project Overview

**The Customer Churn Prediction System** is a machine learning-based project designed to help businesses predict whether a customer is likely to leave a service. By analyzing customer details such as contract type, tenure, monthly charges, internet service, payment method and other account information, the system estimates the probability that a customer will churn.

To improve reliability, the project implements **multiple classification models** including:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting

Users can compare model performance through accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices and ROC curves. The project also identifies the **key factors that drive churn** and includes a Gradio-based interactive web interface where users can enter customer details and instantly see the churn probability and risk level.

This system aims to:  
- ✅ Identify customers at risk of leaving  
- ✅ Reveal the key factors behind churn  
- ✅ Support data-driven customer retention decisions  

---

## ✨ Features  
- 🔮 Predicts the churn probability of a customer  
- 🧑‍💼 User-friendly **Gradio Web App** with risk levels (low, medium, high)  
- 📊 Performance comparison of multiple ML models  
- 🔎 Includes **EDA, Confusion Matrix, ROC Curves & Feature Importance**  
- ⚖️ Handles class imbalance using balanced class weights  
- ☁️ Runs easily in **Google Colab**  

---

## 🛠 Tech Stack  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Pandas, NumPy, Scikit-learn  
  - Matplotlib, Seaborn (for visualization)  
  - Gradio (for the interactive interface)  
  - Google Colab (for running the notebook)  

---

## 📂 Dataset  
- **Source:** Telco Customer Churn dataset ([Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), IBM sample data)  
- **Size:** ~7,000 customers × 21 columns  
- **Features:**  
  - Customer profile: gender, SeniorCitizen, Partner, Dependents  
  - Services: PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies  
  - Account: tenure, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges  
  - Target: Churn (Yes / No)  

---

## ➡️ Project Workflow

Dataset --> Data Cleaning --> EDA --> Preprocessing --> Model Training --> Model Evaluation --> Feature Importance --> Deployment (Gradio)

---

## ⚙️ Installation & Setup

1. **Open the Notebook in Google Colab**
    - Upload `Customer_Churn_Prediction.ipynb` to [Google Colab](https://colab.research.google.com/), or open it directly from GitHub.

2. **Run All Cells**
    - Run the cells from top to bottom. The first cell installs Gradio and loads the dataset automatically.

3. **Launch the App**
    - Run the last cell and open the Gradio link that appears, or use the interface shown inside the notebook.

---

## 🖥️ How to Use

Enter the customer's details in the Gradio interface, click **Predict**, and get the result.

| You enter | You get |
|---|---|
| Customer profile (gender, senior citizen, partner, dependents) | Churn probability |
| Account details (contract, payment method, paperless billing) | Prediction: likely to stay or leave |
| Services (internet, security, tech support, streaming, etc.) | Risk level: low, medium or high |
| Tenure and monthly charges | |

---

## 🖼️ Sample Output

<img width="1229" alt="Sample output" src="YOUR_SCREENSHOT_LINK_HERE" />
