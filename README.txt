# Customer Purchase Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a customer will purchase a product or not using machine learning classification algorithms. The goal is to analyze customer demographic and behavioral data and build models that can accurately classify purchase behavior.

This project is designed at a beginner to intermediate level and demonstrates the complete machine learning workflow.

---

## 📂 Dataset Description
The project uses the **Mall Customers Dataset**, which contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

Since the dataset does not originally include a purchase label, a new target variable **Purchase** was engineered based on the Spending Score:
- Spending Score ≥ 50 → Purchased (1)
- Spending Score < 50 → Not Purchased (0)

---

## 🧠 Machine Learning Workflow

1. Data Loading and Understanding  
2. Data Preprocessing  
   - Encoding categorical variables  
   - Feature scaling  
   - Train-test split  
3. Exploratory Data Analysis (EDA)  
4. Model Building  
5. Model Evaluation and Comparison  

---

## ⚙️ Algorithms Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

---

## 📊 Evaluation Metrics

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

A comparison was made to identify the best-performing model.

---

## 🏆 Results and Conclusion

Among the implemented models, **Random Forest Classifier** achieved the best performance in terms of accuracy and stability. The results show that customer income and spending score play an important role in predicting purchase behavior.

---

## 🛠️ Tools and Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

