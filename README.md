# 📊 Advertising Click-Through Rate Prediction  

## 📌 Overview  
This project aims to predict whether a user will click on an advertisement based on various behavioral and demographic features. A Logistic Regression model was trained on a synthetic advertising dataset to classify user interactions with high accuracy.

---

## 📂 Dataset  
The dataset includes the following features:

- **Daily Time Spent on Site** – Time spent on the website (minutes)  
- **Age** – User age (years)  
- **Area Income** – Average income of the user's region  
- **Daily Internet Usage** – Daily internet usage (minutes)  
- **Ad Topic Line** – Advertisement headline  
- **City** – User’s city  
- **Male** – Gender indicator (1 = Male, 0 = Female)  
- **Country** – User’s country  
- **Timestamp** – Interaction time  
- **Clicked on Ad** – Target variable (1 = Clicked, 0 = Not Clicked)  

---

## 🔍 Exploratory Data Analysis (EDA)  

Data visualization was performed to understand patterns and relationships:

- Distribution of age using histograms  
- Relationship between Age and Area Income using joint plots  
- Correlation between Daily Time Spent on Site and Daily Internet Usage  
- Pair plots based on "Clicked on Ad" to analyze behavior differences  

---

## ⚙️ Data Preparation  

- Selected numerical features:  
  - Age  
  - Area Income  
  - Daily Time Spent on Site  
  - Daily Internet Usage  
- Split dataset into:
  - **Training set (67%)**
  - **Testing set (33%)**

---

## 🤖 Model  

- Algorithm: **Logistic Regression**  
- Library: **Scikit-Learn**  
- Adjusted parameter:
  - Increased `max_iter` to ensure convergence  

---

## 📈 Performance  

The model achieved strong results:

- **Accuracy**: 97%  
- **Precision**: 0.98  
- **Recall**: 0.96  
- **F1-Score**: 0.97  

---

## 🛠️ Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

## ✅ Conclusion  

The Logistic Regression model demonstrated excellent performance in predicting ad click behavior. The selected features effectively represent user activity, resulting in high accuracy and balanced evaluation metrics.

---

