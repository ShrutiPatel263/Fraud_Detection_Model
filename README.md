Here is your **professional, ATS-friendly, recruiter-impressive `README.md`** tailored exactly to your final results (ROC-AUC 0.977 with XGBoost).
You can copy-paste this directly into your GitHub repository.

---

# 💳 Credit Card Fraud Detection — ML Classification Pipeline

An end-to-end Machine Learning project for detecting fraudulent credit card transactions using ensemble learning techniques. This project benchmarks multiple tree-based models and demonstrates superior performance using gradient boosting methods on a highly imbalanced dataset.


Credit card fraud detection is a highly imbalanced binary classification problem where fraudulent transactions represent a very small percentage of total transactions.

The objective of this project is to:

* Build a robust fraud detection pipeline
* Compare multiple ensemble learning models
* Evaluate performance using ROC-AUC and classification metrics
* Identify the best performing model for real-world deployment

---

## 📊 Dataset Information

* Real-world credit card transaction dataset
* Highly imbalanced (~0.17% fraud cases)
* Features:

  * PCA transformed features (`V1`–`V28`)
  * `Time`
  * `Amount`
  * Target variable `Class` (0 = Legitimate, 1 = Fraud)

* Dataset Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* LightGBM
* CatBoost
* Matplotlib
* Seaborn

---

## 🧠 Models Implemented

The following ensemble models were trained and evaluated:

* Random Forest
* AdaBoost
* CatBoost
* LightGBM
* XGBoost

---

## 📈 Model Performance (ROC-AUC Score)

| Model          | ROC-AUC    |
| -------------- | ---------- |
| 🥇 **XGBoost** | **0.9771** |
| 🥈 LightGBM    | 0.9682     |
| CatBoost       | 0.8578     |
| Random Forest  | 0.8529     |
| AdaBoost       | 0.8135     |

### 🔥 Best Model: XGBoost

* Achieved **ROC-AUC = 0.977**
* Excellent class separation capability
* Strong performance on imbalanced dataset
* Suitable for production-level fraud detection systems

---

## 📊 Evaluation Metrics Used

* ROC Curve & AUC Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

> Special focus was given to Recall to minimize false negatives (missed fraud cases).

---

## 🗂 Project Structure

```
Fraud_Detection_Model/
│
├── credit_card_fraud_detection.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

1️⃣ Clone the repository

```bash
git clone https://github.com/ShrutiPatel263/Fraud_Detection_Model.git
```

2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3️⃣ Run the notebook

```bash
jupyter notebook credit_card_fraud_detection.ipynb
```

---

## 📌 Key Highlights

✔ Implemented complete ML pipeline
✔ Compared 5 ensemble learning algorithms
✔ Handled severe class imbalance
✔ Achieved high ROC-AUC (0.977)
✔ Conducted systematic model benchmarking



---

## 👩‍💻 Author

Shruti Patel
Machine Learning & AI Enthusiast

GitHub: [https://github.com/ShrutiPatel263](https://github.com/ShrutiPatel263)

---

---


Tell me your goal (placements / internships / research / portfolio showcase).
