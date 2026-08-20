# 🎓 Student Dropout Prediction using Machine Learning

A machine learning pipeline built to predict student dropouts and academic success using demographic, socio-economic, and academic performance data.

---

## 📌 Project Overview
Student retention is a critical metric for educational institutions. This project analyzes academic and enrollment data to predict whether a student is at risk of dropping out or likely to succeed. 

Using **Logistic Regression**, the model achieves an **accuracy of ~83.16%** in binary classification (`Dropout` vs. `Not Dropout`).

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook / VS Code

---

## 📊 Key Features & Workflow
1. **Target Transformation:** Converted multi-class targets into binary classification (`Dropout` / `Not Dropout`).
2. **Data Cleaning & Preprocessing:**
   * Handled missing/unusual numerical values using median imputation.
   * Standardized and encoded categorical/numerical columns using `ColumnTransformer` pipelines.
3. **Model Training:** Trained a Logistic Regression classifier (`max_iter=1000`) for high performance and interpretability.
4. **Evaluation:** Evaluated model performance using Accuracy Score and Confusion Matrix analysis.

---

## 📈 Key Data Insights
* **1st-Semester Grades:** Academic performance during the first semester serves as one of the strongest indicators of student retention.
* **Tuition Fee Status:** Up-to-date tuition payments show a significant correlation with lower dropout rates.

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/princekumar-001/student-dropout-prediction.git](https://github.com/princekumar-001/student-dropout-prediction.git)
   cd student-dropout-prediction