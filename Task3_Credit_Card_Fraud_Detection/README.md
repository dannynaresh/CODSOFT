# Task 3 - Credit Card Fraud Detection

## 📌 Objective

Build a machine learning model to detect fraudulent credit card transactions.

---

## 📊 Dataset

The dataset contains transaction details such as:

* Transaction amount
* Merchant information
* Location details
* Customer attributes
* Fraud label (`is_fraud`)

The dataset is highly imbalanced, with very few fraudulent transactions compared to normal ones.

---

## ⚙️ Models Used

* Logistic Regression
* Random Forest

---

## 📈 Results

### Logistic Regression

* Accuracy: 93%
* Recall (Fraud): 0.80
* Successfully detects fraudulent transactions

![Logistic Results](logistic_results.png)

---

### Random Forest

* Accuracy: 99%
* Recall (Fraud): 0.00
* Failed to detect fraud due to class imbalance

![Random Forest Results](random_forest_results.png)

---

## 🧠 Key Insight

Accuracy alone is not a reliable metric for imbalanced datasets. Even though Random Forest achieved higher accuracy, it failed to detect any fraud cases.

---

## 🎯 Conclusion

Logistic Regression performed better in identifying fraudulent transactions with a higher recall score. Therefore, it is selected as the final model for this task.

---

## 📁 Files Included

* fraud_detection.ipynb
* logistic_results.png
* random_forest_results.png

---

## 👨‍💻 Author

V Naresh
