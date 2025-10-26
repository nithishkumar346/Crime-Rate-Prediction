# 🚨 Crime Rate Prediction Web App

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Framework-Flask-red)
![Machine Learning](https://img.shields.io/badge/ML-Model-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📘 Overview
The **Crime Rate Prediction Web App** predicts the **crime rate in Indian cities** based on historical data, city population, and crime type using a pre-trained **Machine Learning model**.  
Built with **Python, Flask, and HTML/CSS**, the app provides a **user-friendly interface** for users to check the crime severity and estimated number of cases for a selected year.

---

## 🚀 Features
- Predicts crime rates for different **Indian cities**.
- Categorizes areas as **Very Low, Low, High, or Very High Crime Area**.
- Displays **total number of expected cases** based on population.
- Uses a **pre-trained ML model (Pickle)** for prediction.
- Simple **Flask web interface** with input forms and results page.

---

## ⚙️ Tech Stack
| Component | Technology |
|-----------|------------|
| **Backend** | Python 3.x, Flask |
| **Machine Learning** | Scikit-learn (Pickle model) |
| **Frontend** | HTML, CSS |
| **Data** | City-wise population & crime statistics |

---

## 🧩 How It Works
1. User selects **City**, **Crime Type**, and **Year**.
2. App adjusts population based on growth rate (~4.61% per year since 2011).
3. ML model predicts **crime rate per 1000 people**.
4. App calculates total number of cases and assigns a **crime status**.
5. Results displayed on a **dedicated result page**.

---

## ⚙️ Setup & Run
1️⃣ Cl
