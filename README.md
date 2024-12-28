# 📊 **Credit Risk Modeling Project**

## 📚 **Overview**
This project focuses on building a **Credit Risk Model** to assess the **Probability of Default (PD)**, **Loss Given Default (LGD)**, and **Expected Credit Loss (ECL)**. The model is designed to evaluate the risk associated with loan portfolios and enable financial institutions to make data-driven lending decisions.

---

## 🛠️ **What is Credit Risk Modeling?**
- **Probability of Default (PD):** Measures the likelihood that a borrower will default on a loan.
- **Loss Given Default (LGD):** Estimates the proportion of the loan that will not be recovered if the borrower defaults.
- **Expected Credit Loss (ECL):** Combines PD, LGD, and Exposure at Default (EAD) to calculate the anticipated loss.

**Why this matters:** Accurate credit risk modeling helps financial institutions minimize losses, optimize lending strategies, and ensure regulatory compliance (e.g., Basel III framework).

---

## 📊 **Project Steps**

### 1️⃣ **Data Preprocessing**
- Handled missing values and ensured data consistency.
- Applied **label encoding** to categorical variables for machine learning compatibility.

### 2️⃣ **Feature Engineering**
- **Employment Length (emp_length_int):** Categorized into discrete groups.
- **Months Since Issue (mths_since_issue_d):** Binned into meaningful intervals.
- **Interest Rate (int_rate):** Segmented into predefined ranges.


### 3️⃣ **Binary Indicator Creation**
- Created binary columns indicating specific ranges for key variables.

### 4️⃣ **Data Transformation**
- Used `pd.cut` to bin continuous variables into categorical intervals.

### 5️⃣ **Modeling Preparation**
- Engineered features and prepared the dataset for models like **Logistic Regression**, **LightGBM**, and **XGBoost**.

---

## 📈 **How to Use**

### **Prerequisites:**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)  ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![LightGBM](https://img.shields.io/badge/LightGBM-%23FF9900.svg?style=for-the-badge&logo=lightgbm&logoColor=white)  ![XGBoost](https://img.shields.io/badge/XGBoost-%23EE4C2C.svg?style=for-the-badge&logo=xgboost&logoColor=white)

### **Steps to Run the Project:**
1. Load the dataset into a pandas DataFrame.
2. Execute preprocessing and feature engineering scripts.
3. Train machine learning models using the engineered features.
4. Evaluate model performance with metrics like **AUC-ROC**, **Precision**, **Recall**, and **F1-Score**.

### **Expected Outcome:**
- Accurate prediction of loan default probabilities.
- Risk segmentation to support decision-making.
- Insights into key factors influencing credit risk.

---

## 🚀 **Future Work**
- Implement advanced machine learning models.
- Fine-tune hyperparameters for optimal model performance.
- Integrate regulatory compliance metrics for Basel III.
- Develop dashboards for visualizing risk profiles.


---

## 🤝 **Let's Collaborate!**
I'm excited to collaborate on improving credit risk models and exploring advanced techniques. Reach out if you're interested in discussing or enhancing this project.

📧 [chinmakrishna9@gmail.com](mailto:chinmakrishna9@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chinmaykrishna1)

---

✨ *"Accurate risk assessment, smarter lending decisions."* ✨
