# 🚀 Food Delivery Time Prediction

## 📌 Problem Statement

Accurately predicting food delivery time is crucial for improving customer experience in online food delivery platforms like Swiggy and Zomato.
This project aims to build a machine learning model that predicts delivery time based on various real-world factors such as distance, traffic conditions, weather, and time of day.

---

## 📂 Dataset

* Dataset: Food Delivery Times Dataset
* Features include:

  * Distance (km)
  * Weather conditions
  * Traffic level
  * Time of day
  * Vehicle type
* Target variable:

  * **Delivery_Time_min**

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

## 🔍 Approach

### 1. Data Preprocessing

* Handled missing values by removing null entries
* Converted categorical variables using one-hot encoding
* Removed unnecessary columns like Order_ID

### 2. Exploratory Data Analysis (EDA)

* Analyzed relationship between distance and delivery time
* Observed impact of traffic and time of day on delays
* Identified key trends affecting delivery efficiency

### 3. Feature Engineering

* Encoded categorical features (Weather, Traffic, Vehicle Type, Time of Day)
* Prepared dataset for machine learning models

### 4. Model Building

* Applied **Linear Regression** as baseline model
* Improved performance using **Random Forest Regressor**

### 5. Model Evaluation

* Evaluated using:

  * Mean Absolute Error (MAE)
  * R² Score

---

## 📊 Results

| Metric   | Value         |
| -------- | ------------- |
| MAE      | ~6.85 minutes |
| R² Score | ~0.74         |

👉 The model predicts delivery time with an average error of ~7 minutes, showing strong performance for real-world scenarios.

---

## 📈 Key Insights

* Distance is the most significant factor affecting delivery time
* Traffic conditions have a major impact on delays
* Peak hours increase delivery time variability
* Weather conditions slightly influence delivery efficiency

---

## 📌 Visualization

* Actual vs Predicted Delivery Time scatter plot
* Shows strong correlation between predicted and actual values

---

## 🚀 Future Improvements

* Use advanced models like XGBoost for better accuracy
* Incorporate real-time traffic data
* Deploy model using Flask or FastAPI
* Build dashboard using Power BI or Streamlit

---

## 📁 Project Structure

```
delivery-time-prediction/
│
├── Food_Delivery_Times.csv
├── notebook.ipynb
├── README.md
```

---

## 🎯 Conclusion

This project demonstrates how machine learning can be used to solve real-world logistics problems by predicting delivery times and analyzing key influencing factors. It highlights the importance of data preprocessing, feature engineering, and model evaluation in building effective predictive systems.

---

## 🙌 Author

**Shekhar Prajapat**

* GitHub: https://github.com/shekhar-prajapat1
* LinkedIn: https://www.linkedin.com/in/shekhar-prajapat-92576a210/
=======
