# ✈️ Air Ticket Price Prediction (Machine Learning Project)

## 📌 Project Overview

This project focuses on predicting air ticket base fare prices using machine learning techniques. We analyze flight itinerary data and build regression models to estimate ticket prices based on flight features such as airports, airlines, travel duration, cabin type, and flight dates.

The goal is to compare multiple machine learning models and identify the best-performing model for price prediction.

---

## 👨‍🎓 Team Members

* 242UT2449P SEE CHWAN KAI
* 242UT24490 TEO JING AN
* 242UT244B2 TEE KIAN HAO
* 242UT2449Z KHO WEI CONG

---

## 📊 Dataset

* Source: Kaggle Flight Prices Dataset
* Link: [https://www.kaggle.com/datasets/justinmitchel/flightprices-min](https://www.kaggle.com/datasets/justinmitchel/flightprices-min)
* Records: 50,000 rows
* Target Variable: baseFare

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

Machine Learning Models:

* Linear Regression
* K-Nearest Neighbors (KNN)
* Random Forest Regressor

---

## 🧹 Data Preprocessing

We performed data cleaning and feature engineering:

* Removed missing values
* Extracted flight date features:

  * flightMonth
  * flightDayOfWeek
* Converted travel duration (ISO format → minutes)
* Extracted fare class from fareBasisCode
* Estimated number of stops
* Encoded categorical variables using OneHotEncoder
* Standardized numerical features using StandardScaler
* Removed outliers (1st–99th percentile)

---

## 🧠 Machine Learning Models & Results

### Linear Regression

* R² Score: 0.6307
* MAE: 63.84
* RMSE: 88.88

### K-Nearest Neighbors (Optimized)

* R² Score: 0.8341
* MAE: 20.11
* RMSE: 59.57

### Random Forest Regressor (Best Model) 👑

* R² Score: 0.8722
* MAE: 29.15
* RMSE: 52.30

---

## 📊 Key Insights

* Random Forest captures non-linear relationships best
* Flight duration, airline, and cabin type strongly affect price
* KNN performs well but is sensitive to tuning
* Linear Regression underfits complex patterns

---

## 📈 Visualizations Included

* Actual vs Predicted plots
<img width="549" height="393" alt="Image" src="https://github.com/user-attachments/assets/54a767f1-b7da-45d0-994b-76bbf43bd933" />
<img width="549" height="393" alt="Image" src="https://github.com/user-attachments/assets/4b620ff1-4159-4a94-90fa-fd45cad09da7" />
<img width="549" height="393" alt="Image" src="https://github.com/user-attachments/assets/3fc2dfa4-e287-4b1f-98d7-4536381fa4a9" />

* Feature importance (Random Forest)
<img width="590" height="390" alt="Image" src="https://github.com/user-attachments/assets/74b60af7-9d81-4d16-878d-892596f9ba36" />

---

## 🚀 How to Run

### 1. Clone repo

```bash
git clone https://github.com/sylvesterkho1113/PredictingFlightTicketWithMachineLearningModel.git
cd PredictingFlightTicketWithMachineLearningModel
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run notebook

Open:

```
1G_G6_Code.ipynb
```

---
