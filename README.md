# **🔍 Credit Card Fraud Detection using Machine Learning**
**Detecting fraudulent transactions using various machine learning models.** This project focuses on handling **imbalanced datasets** and optimizing classification models to maximize fraud detection accuracy.

![Fraud Detection](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Credit-Card-Logo.svg/320px-Credit-Card-Logo.svg.png)

---

## 📌 **Project Overview**
Credit card fraud is a significant financial risk. This project leverages machine learning to classify transactions as **fraudulent (1) or legitimate (0)** using a dataset of real transactions. Since fraud cases are rare, we address **class imbalance** through **random undersampling**.

---

## 🏰 **Tech Stack**
- **Python** 🐍
- **Jupyter Notebook** 📚
- **Pandas, NumPy** (Data Preprocessing)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-Learn, XGBoost, LightGBM** (Model Training)
- **AUC-ROC, Confusion Matrix** (Evaluation Metrics)

---

## 📊 **Dataset**
The dataset used in this project is from **[Kaggle’s Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)**. Special thanks to **[Jânio Bachmann](https://www.kaggle.com/janiobachmann)** for their work related to this dataset. I am particularly grateful for this resource as it helped me understand class imbalance in datasets and was instrumental in shaping this project.

> **Acknowledgment:**  
> This project was inspired by the work of **[Jânio Bachmann](https://www.kaggle.com/janiobachmann)** on Kaggle. His notebook helped in understanding class imbalance and was a key resource in shaping this implementation.  
> Parts of the implementation are adapted from his publicly available work, released under the **Apache 2.0 License**.  
> The original notebook can be found **[here](https://www.kaggle.com/janiobachmann)**.

📁 **File**: `creditcard.csv`  
✅ **Features**: 30 numerical features (V1–V28, Amount, Time)  
🎯 **Target**: `Class` (0 = Legitimate, 1 = Fraud)

---

## 🔍 **Project Workflow**
### **1️⃣ Exploratory Data Analysis (EDA)**
- Check dataset structure & missing values.
- **Visualize class imbalance** (`sns.countplot()`).
- Identify feature correlations.

### **2️⃣ Handling Class Imbalance**
- Fraud cases are significantly fewer than normal transactions.
- Applied **Random Undersampling** to balance fraud & non-fraud cases.

### **3️⃣ Model Training**
- **Logistic Regression** (Baseline Model)
- **Random Forest**
- **XGBoost**
- **LightGBM**

### **4️⃣ Model Evaluation**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)
- **AUC-ROC Curve** (Measures fraud detection performance)

---

## 🎯 **Key Results**
✅ **Best Model:** `{INSERT BEST MODEL HERE}`  
📈 **AUC-ROC Score:** `{INSERT SCORE HERE}`  
📊 **F1-Score for Fraud Detection:** `{INSERT SCORE HERE}`  

---

## 🛠 **How to Run This Project**
### **1️⃣ Install Dependencies**
```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost lightgbm
```
### **2️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook Credit_Card_Fraud.ipynb
```

---

## 📌 **Next Steps & Improvements**
✅ **Implement SMOTE (Synthetic Minority Over-sampling) to improve fraud recall**  
✅ **Try an ensemble model (XGBoost + LightGBM + Random Forest)**  
✅ **Deploy a real-time fraud detection system using FastAPI / Flask**  

---

## 👨‍💻 **Contributors**
- **[Your Name]** ([@YourGitHubHandle](https://github.com/YourGitHubHandle))
- **Open to Contributions!**

---

## 🐟 **License**
This project is licensed under the **MIT License**.

---

