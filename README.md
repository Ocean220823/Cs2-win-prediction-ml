# 🎯 CS2 Win Prediction ML Model

A machine learning project that predicts the outcome of Counter-Strike 2 (CS2) matches using player statistics and FACEIT data.

---

## 📌 Overview

This project builds a predictive system that estimates the probability of a team winning a CS2 match. It uses historical player performance data collected from the FACEIT API and applies multiple machine learning algorithms to generate accurate predictions.

The final model achieves approximately **77% accuracy**.

---

## 🚀 Features

- Predicts win probability for CS2 matches  
- Multiple ML models implemented and compared  
- Deep learning model using PyTorch (CNN)  
- Automated data collection and preprocessing pipeline  
- Feature engineering using player and team statistics  

---

## 🧠 Models Used

- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- XGBoost  
- Convolutional Neural Network (PyTorch)  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- PyTorch  
- Requests (API integration)  
- Jupyter Notebook  

---

## 📊 Dataset

- ~9,600+ match records  
- Data from 50,000+ FACEIT player IDs  
- Features derived from last 100 matches per player  

---

## 📂 Project Structure
├── ML_Assignment.ipynb
├── Win Prediction Model Fitting and Tuning.ipynb
├── Win Prediction Neural Net.ipynb
├── win_prediction_functions.py
├── data_win_prediction_*.xlsx
└── README.md


---

## ⚙️ How It Works

1. Collect data using FACEIT API  
2. Clean and preprocess player/match data  
3. Generate features (ELO, K/R ratio, win rate, etc.)  
4. Train multiple machine learning models  
5. Evaluate and select the best-performing model  
6. Predict win probability for new matches  

---

## ⚠️ Limitations

- Focused primarily on FACEIT NA region  
- Less accurate for new players or low-data accounts  
- Depends heavily on recent match history  

---

## 🔮 Future Improvements

- Expand dataset to EU region  
- Improve predictions for low-data players  
- Deploy as a web application  
- Enable real-time predictions  

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied to esports analytics to predict competitive match outcomes in CS2.
