# EasyVisa - Visa Approval Prediction Project

## 💼 Problem Statement
The goal of this project is to build a classification model that predicts whether a visa application will be **approved or denied**, based on a variety of features related to the employer, employee, and job role. The model aims to help streamline the decision-making process for visa officers and increase transparency in the application pipeline.

---

## 🧠 Objectives

- Understand the key factors that influence visa approval.
- Preprocess and clean real-world visa application data.
- Perform Exploratory Data Analysis (EDA) to extract insights.
- Build and evaluate multiple machine learning models.
- Select the best-performing model for deployment.

---

## 📁 Dataset Overview

The dataset includes features such as:

- `case_status` (target): 1 for Approved, 0 for Denied  
- `employer_name`: Name of the employer  
- `job_title`: Title of the job role  
- `education_level`, `salary`, `full_time_position`  
- `state`, `country_of_citizenship`, etc.

*Note: You can find the dataset used in the project root.*

---

## 🛠️ Project Workflow

1. **Importing Required Libraries**
2. **Data Cleaning & Preprocessing**
3. **Exploratory Data Analysis (EDA)**
4. **Feature Engineering**
5. **Model Building** (Logistic Regression, Decision Trees, Random Forest, XGBoost, etc.)
6. **Model Evaluation** (Accuracy, ROC-AUC, Confusion Matrix)
7. **Hyperparameter Tuning**
8. **Final Model Selection**
9. **Conclusion & Recommendations**

---

## 📊 Model Evaluation Metrics

- Accuracy
- Precision & Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## ✅ Conclusion

The final model was able to successfully predict visa approval with strong performance metrics. The most significant factors influencing the prediction included job role, education level, full-time status, and salary.

This model can help in pre-screening visa applications and flagging high-risk profiles for further review.

---

## 📌 Tech Stack Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / LightGBM (optional)
- Jupyter Notebook

---

## 📂 Project Contents

| File Name                           | Description                              |
|------------------------------------|------------------------------------------|
| `EasyVisa_Full_Code_Notebook.ipynb` | Complete implementation notebook          |
| `EasyVisa_Dataset.csv`             | Dataset used for training & testing       |
| `EasyVisa_Project_Summary.pdf`     | Presentation-ready summary (optional)     |
| `README.md`                        | Project overview and documentation        |

---

## ✨ Author

Adam Smith  
*PGP AI/ML Candidate | Data Science Enthusiast*
