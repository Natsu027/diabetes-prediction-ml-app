# diabetes-prediction-ml-app
A Flask-based web app that predicts diabetes using 10 ML models


# 🩺 Diabetes Prediction ML Web App

This is a full-stack **Machine Learning web application** built using **Flask** that predicts whether a person is diabetic based on health parameters. It uses **10 different ML algorithms**, a **StandardScaler**, and displays both model-wise results and a final evaluation based on majority voting.

### 🔍 Features

- ✔️ Predicts diabetes using 10 machine learning models
- ✔️ Displays each model’s prediction (Positive/Negative)
- ✔️ Shows a final evaluation based on majority voting
- ✔️ Responsive, mobile-friendly UI using Bootstrap 5
- ✔️ 🌙 Dark Mode toggle for better user experience
- ✔️ Reset button to clear form and results
- ✔️ Input validation for 8 health metrics

---

## 🧠 Machine Learning Models Used

- Logistic Regression  
- K-Nearest Neighbors  
- Support Vector Machine (Linear & RBF)  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- AdaBoost  
- Naive Bayes  
- XGBoost

All models and the scaler are trained using the **Pima Indians Diabetes dataset** and saved as `.pkl` files using `pickle`.

---

## 🛠️ Tech Stack

| Layer       | Technologies                      |
|-------------|------------------------------------|
| Backend     | Python, Flask, scikit-learn, XGBoost |
| Frontend    | HTML, CSS, Bootstrap 5, JavaScript |
| ML Tools    | StandardScaler, Pickle             |
| Deployment  | Localhost / Render (optional)      |

---



