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

## 📄 Data Description

Below is a brief description of each column in the dataset:

| Column Name              | Description                                                              |
|--------------------------|--------------------------------------------------------------------------|
| `case_status`            | **Target variable** – 1 if visa was approved, 0 if denied                |
| `employer_name`          | Name of the employer submitting the visa application                    |
| `job_title`              | Title of the position offered to the employee                            |
| `education_level`        | Educational qualification of the applicant                               |
| `salary`                 | Offered salary for the position                                          |
| `full_time_position`     | Indicates if the position is full-time (`Yes` or `No`)                   |
| `job_experience`         | Number of years of relevant job experience                               |
| `state`                  | U.S. state where the job is located                                      |
| `country_of_citizenship` | Country of the applicant’s citizenship                                   |
| `application_year`       | Year in which the visa application was filed                             |
| `job_category`           | Industry or field of the job (e.g., Tech, Finance, Healthcare)           |
| `sponsorship_required`   | Whether visa sponsorship was required for the role (`Yes` or `No`)       |

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
