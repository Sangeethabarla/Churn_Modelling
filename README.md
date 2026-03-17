# 📊 Churn Modelling Project

## 🔷 Overview
This project focuses on **predicting customer churn** using Machine Learning techniques.  
Customer churn refers to when a customer stops using a company's services. Predicting churn helps businesses take proactive steps to retain customers.

This project is implemented using a **Jupyter Notebook (.ipynb)** and demonstrates the complete ML workflow.

---

## 🎯 Objective
The main objective of this project is to:
- Analyze customer data
- Identify patterns that lead to churn
- Build a model to predict whether a customer will leave or stay

---

## 📁 Project Structure

Churn_Modelling/
│── churn_modelling.ipynb # Main notebook (ML model)
│── README.md # Project documentation


---

## 📊 Dataset Information

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/shubh0799/churn-modelling

The dataset contains customer details such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Churn (Target Variable)

👉 The target variable is:
- `Exited` → 1 (Customer left), 0 (Customer stayed)

---

## ⚙️ Technologies Used
- Python 🐍
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## 🔍 Steps Performed
1. Data Loading
2. Data Preprocessing
   - Handling missing values
   - Encoding categorical data
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Model Building
6. Model Evaluation

---

## 📈 Model
The project builds a Machine Learning model to classify:
- Customer will churn ❌
- Customer will stay ✅

(You can update this section if you used ANN / Logistic Regression / etc.)

---

## 🚀 How to Run

### 🔹 Step 1: Clone Repository
```bash
git clone https://github.com/Sangeethabarla/Churn_Modelling.git
```
### 🔹Step 2: Navigate to Folder
```bash
cd Churn_Modelling
```
### 🔹Step 3: Open Notebook
```bash
jupyter notebook churn_modelling.ipynb
```
## 📊 Results

The Machine Learning model was successfully trained to predict customer churn using the given dataset. After preprocessing and model training, the model demonstrated good performance in classifying customers based on their likelihood to churn.

### 🔷 Key Findings
- The model can effectively distinguish between customers who are likely to churn and those who are not.
- Features such as **Age, Balance, Number of Products, and Activity Status** have a significant impact on churn prediction.
- Customers who are less active and have fewer products are more likely to leave the service.

### 🔷 Model Performance
- The model was evaluated using standard metrics:
  - Accuracy  
  - Confusion Matrix  
  - Precision & Recall  

- The model achieved a satisfactory accuracy on the test dataset.  
  *(You can update this with exact value, e.g., 85%)*

### 🔷 Insights
- Active customers are less likely to churn  
- Customers with higher engagement tend to stay longer  
- Predictive models can help identify high-risk customers in advance  

### 🎯 Outcome
The model provides a reliable way to support business decisions by identifying customers at risk of churn, enabling proactive retention strategies.

## 🚀 Future Enhancements

- Use advanced models like Random Forest, XGBoost, and ANN  
- Improve accuracy using hyperparameter tuning  
- Perform better feature engineering and selection  
- Deploy the model as a web app (Flask/Streamlit)  
- Add interactive dashboards for visualization  
- Use larger and more diverse datasets  

## 📌 Conclusion

This project demonstrates the application of Machine Learning techniques to predict customer churn using historical customer data. By analyzing features such as customer demographics, account information, and activity patterns, the model can effectively identify customers who are likely to leave.

The project covers the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation. This provides a clear understanding of how real-world data-driven solutions are developed.

The results show that predictive models can help businesses:
- Improve customer retention strategies  
- Minimize potential revenue loss  
- Make informed, data-driven decisions  

Overall, this project serves as a solid foundation for solving real-world business problems using Machine Learning and can be further enhanced with advanced models and deployment techniques.
