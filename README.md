# 📢 Ads Click-Through Rate (CTR) Prediction  

A machine learning project that predicts whether a user will **click on an advertisement** based on their demographics and browsing activity using a **Random Forest Classifier**.  

---

## 📌 Project Overview  

Click-Through Rate (CTR) is one of the most critical metrics for online advertising.  
This project uses demographic and behavioral data to predict whether a user is likely to click an ad, helping businesses improve ad targeting strategies.  

✅ **Key Highlights:**  
- Data preprocessing and feature encoding  
- Training a **Random Forest Classifier**  
- Evaluating model accuracy  
- Accepting **real-time user input** to predict click behavior  

---

## 🗂 Dataset  

- **Source:** `ad_10000records.csv`  
- **Features:**  
  - `Daily Time Spent on Site`  
  - `Age`  
  - `Area Income`  
  - `Daily Internet Usage`  
  - `Gender` (encoded as 1 = Male, 0 = Female)  
- **Target:**  
  - `Clicked on Ad` (YES or NO)  

---

## 📊 Data Processing  

- Converted `Clicked on Ad` from (0/1) to (NO/YES)  
- Encoded `Gender` to numeric values  
- Dropped non-essential features: `Ad Topic Line`, `City`  

---

## 🧠 Model Training  

**Algorithm Used:** `RandomForestClassifier` from Scikit-Learn  

### Steps:  
1. **Data Cleaning & Encoding**  
2. **Splitting:** 80% training, 20% testing  
3. **Training:** Fit the Random Forest model on training data  
4. **Prediction:** Evaluated model accuracy and created real-time prediction system  

---

## 💻 Example Run  

```python
Ads Click Through Rate Prediction :
Daily Time Spent on Site: 68.5
Age: 27
Area Income: 55000
Daily Internet Usage: 230
Gender (Male = 1, Female = 0): 1

Will the user click on ad =  ['YES']
