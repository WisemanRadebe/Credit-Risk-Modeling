# 📊 Credit Risk Analysis with Machine Learning  

## 📌 Project Overview  
This project focuses on **credit risk assessment** using machine learning techniques.  
The goal is to **predict whether a customer is a good or bad credit risk** using customer demographics, financial behavior, and account details.  

The project demonstrates:  
- Data preprocessing & feature engineering  
- Exploratory data analysis (EDA) with visualizations  
- One-hot encoding of categorical variables  
- Correlation analysis  
- Model building and evaluation with multiple algorithms  
- Insights into key drivers of credit risk  

---

## 🗂️ Dataset  
The dataset used is the **German Credit Risk dataset**, which contains:  
- Customer demographics  
- Credit amount & duration  
- Housing, job, and financial account details  
- Target variable: **Risk** (`good` / `bad`)  

---

## 🔍 Exploratory Data Analysis (EDA)  
Some of the analyses performed include:  
- Distribution plots of credit amount by housing, sex, and job  
- Violin plots & boxplots to compare good vs. bad risks  
- Heatmaps to identify correlations between variables  
- Count plots for categorical variables  

---

## 🛠️ Data Preprocessing  
- Missing values handled (e.g., saving/checking accounts)  
- One-hot encoding applied to categorical variables  
- Risk variable encoded into numerical form for modeling  
- Feature scaling and transformations where needed  

---

## 🤖 Machine Learning Models  
The following algorithms were tested and compared:  
- Logistic Regression  
- Decision Trees  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Naive Bayes  
- Linear Discriminant Analysis (LDA)  
- XGBoost  

**Model evaluation metrics:**  
- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  
- Cross-validation  

---

## 📈 Results & Insights  
- Bad credit risks tend to request **higher credit amounts**, especially among skilled and highly skilled jobs.  
- **Housing status** and **job type** are strong predictors of credit risk.  
- Ensemble methods such as **Random Forest and XGBoost** provided the best predictive performance.  

---

## 🚀 How to Run the Project  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/credit-risk-analysis.git
   cd credit-risk-analysis
   
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Open the notebook:
```
jupyter notebook Notebook.ipynb
```

## 📌 Future Improvements

- Hyperparameter tuning for better model performance.
- Implementing deep learning approaches.
- Building a web-based API for credit risk prediction.
- Deploying as a dashboard (Streamlit or Flask).

## 📜 License

This project is licensed under the MIT License.
