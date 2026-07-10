## 📌 Overview

This project is a **Machine Learning-based Crop Recommendation System** that predicts the most suitable crop based on soil and environmental parameters.

The application allows users to input relevant values and get instant crop predictions using a trained ML model.

---

## 🚀 Features

* User-friendly interface for input
* Takes parameters such as:

  * Nitrogen (N)
  * Phosphorus (P)
  * Potassium (K)
  * Temperature
  * Humidity
  * pH value
  * Rainfall
* Predicts the most suitable crop
* Fast and interactive predictions

---

## 🧠 Machine Learning

* Model trained on agricultural dataset
* Model saved using **joblib** (`agro.pkl`)
* Used for real-time predictions

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Scikit-learn
* Pandas, NumPy

---

## 📁 Project Structure

### Crop Recommendation System
* app.py
* Agro_model.pkl
* README.md


---

## ⚙️ How to Run

1. Install required libraries:

python -m pip install joblib scikit-learn pandas

python -m pip install streamlit


2. Run the application:

streamlit run app.py


---

## 📊 Usage

* Enter input values in the interface
* Click on predict
* View the recommended crop instantly
