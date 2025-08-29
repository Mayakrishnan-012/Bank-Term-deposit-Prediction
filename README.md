# Bank-Term-deposit-Prediction
Prediction model for bank term-deposit subscription using Machine Learning Models (Logistic Regression, Random Forest, Decision Tree &amp; SVM). Achieved ~90% accuracy with hyper parameter tuning.

## 📌 Project Overview
This project predicts whether a bank customer will subscribe to a **term deposit** based on personal and campaign-related attributes.  
It applies **Machine Learning models** with proper preprocessing, balancing, and hyperparameter tuning to achieve strong prediction accuracy.

👉 Goal: Help banks **reduce marketing costs** and **improve targeting efficiency** by focusing only on customers who are more likely to subscribe.
---

## 📊 Dataset
- **Source:** Kaggle  
- **Rows:** 4521  
- **Features:** 17 (age, job, marital status, education, balance, housing loan, personal loan, contact type, campaign details, etc.)  
- **Target Variable (`y`):** Term deposit subscription (Yes/No)

---

## 🔧 Approach
1. **Data Preparation**
   - Handled categorical encoding (Label Encoding, One-Hot Encoding, Target Encoding)  
   - Scaling with StandardScaler  
   - Balanced dataset using **SMOTE**  

2. **Model Training**
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Support Vector Classifier (SVC)  

3. **Model Tuning & Validation**
   - GridSearchCV with **5-fold cross validation**  
   - Hyperparameter tuning (max_depth, n_estimators, C, gamma, etc.)  

4. **Evaluation Metric**
   - Accuracy Score  
   - Confusion Matrix  

---

## 📈 Results
- **Random Forest Classifier** achieved the **highest accuracy: ~89.94%** (after tuning).  
- Support Vector Classifier also performed well but showed risk of overfitting.  
- Business Impact: This model can help banks reduce **~28% wasted customer calls** while keeping **90% of conversions**.  

| Model                     | Correct Predictions | Misclassifications |
|-------------------------  |---------------------|--------------------|
| Logistic Regression       | 374                 | 79                 |
| Random Forest             | 388                 | 65                 |
| Decision Tree             | 362                 | 91                 |
| Support Vector Classifier | 391                 | 62                 |

------
