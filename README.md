# Customer Churn Prediction

## 📌 Objective
The goal of this project is to predict whether a customer is likely to churn based on historical telecom data. This helps businesses identify at-risk customers and take proactive retention measures.

---

## 📊 Dataset
- Telco Customer Churn Dataset (Kaggle)
- Contains customer demographics, account information, and service usage details

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🔄 Approach

### 1. Data Preprocessing
- Converted `TotalCharges` to numeric and handled missing values  
- Dropped irrelevant columns (e.g., customerID)  
- Encoded categorical variables  

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution  
- Compared MonthlyCharges and tenure with churn  
- Visualized key patterns using plots  

### 3. Feature Engineering
- Transformed categorical variables  
- Scaled numerical features using StandardScaler  

### 4. Model Building
- Logistic Regression  
- Random Forest Classifier  

### 5. Evaluation
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  

---

## 📈 Results
- Logistic Regression Accuracy: **81.5%**  
- Random Forest Accuracy: **79.4%**  
- Recall for churn class: **~48%**

---

## 🔍 Key Insights
- Customers with higher MonthlyCharges and TotalCharges are more likely to churn  
- Customers with lower tenure show higher churn probability  
- Contract type significantly influences customer retention  
- Model shows good overall accuracy but lower recall for churned customers, indicating scope for improvement  

---

## 🚀 Conclusion
The model provides a strong baseline for predicting customer churn. Improving recall through class balancing or advanced techniques can enhance performance and make the model more effective for real-world business use.

---

## 📁 Project Structure
Customer-Churn-Prediction
- churn_analysis.ipynb --> WA_Fn-UseC_-Telco-Customer-Churn.csv --> README.md


---

## 📬 Future Improvements
- Apply SMOTE or class balancing techniques  
- Hyperparameter tuning  
- Try advanced models (XGBoost, Gradient Boosting)  
- Deploy as a web app for real-time predictions  
