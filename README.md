# 🏠 House Price Category Prediction using Logistic Regression

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made with Scikit-learn](https://img.shields.io/badge/Made%20with-Scikit--learn-orange)](https://scikit-learn.org/)

A machine learning project that classifies synthetic house prices into categories using Logistic Regression. It uses features such as area, number of bedrooms, and bathrooms to predict whether a house falls into a low, medium, or high price range.

---

## 📁 Files

- `synthetic_house_data.csv`: The synthetic dataset used for training and testing.
- `house_price_prediction.py`: The main Python script for training, prediction, and visualization.
- `README.md`: Project documentation.

---

## 📌 Price Category Mapping

| Category | Price Range            |
|----------|------------------------|
| 0        | Below $300,000         |
| 1        | $300,000 to $449,999   |
| 2        | $450,000 and above     |

---

## 🔍 Project Overview

This project includes the following steps:

1. ✅ **Load and inspect data**
2. 🏷️ **Transform raw price into categorical classes**
3. ✂️ **Split dataset into training and test sets**
4. 🤖 **Train a logistic regression model**
5. 📊 **Evaluate model performance (accuracy, confusion matrix, and classification report)**
6. 📉 **Visualize actual vs. predicted price categories**

---

## 🧠 Model

**Algorithm:** Logistic Regression (Multi-class)  
**Library:** scikit-learn  
**Evaluation Metrics:**  
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  

---

## 🖥️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/house-price-category-prediction.git
cd house-price-category-prediction
