# Employee Attrition Prediction using Machine Learning

## 📌 About

This project uses machine learning models to predict **whether an employee will leave the company** based on HR data. It helps organizations take proactive steps in employee retention and human resource planning.

---

## 🧠 Problem Statement

High employee turnover leads to increased hiring costs and lost productivity. By analyzing historical employee data, this project predicts attrition and identifies the key factors influencing employee decisions to leave.

---

## 📁 Dataset

- **File**: `HR_comma_sep.csv`
- Contains features such as:
  - `satisfaction_level`, `last_evaluation`
  - `number_project`, `average_montly_hours`, `time_spend_company`
  - `Work_accident`, `promotion_last_5years`, `salary`, `department`
  - Target: `left` (1 = employee left, 0 = stayed)

The dataset is clean and widely used in HR analytics case studies.

---

## 🧰 Tools and Technologies

- Python
- Pandas, Numpy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 🏗️ Model Used

- Logistic Regression, Decision Trees, or Random Forests
- Evaluation with metrics such as:
  - Accuracy
  - Precision, Recall
  - Confusion Matrix

Data preprocessing includes:
- Encoding categorical variables
- Normalization (if applied)
- Train-test split

---

## 📊 Evaluation and Results

- Achieved strong classification performance
- Identified key features driving attrition:
  - Low satisfaction level
  - Long work hours
  - Lack of promotion

Visualizations include:
- Heatmaps
- Correlation matrix
- Feature importance

---

## 🛠️ Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


## 🔭 Future Work
- Deploy model using Flask or Streamlit for HR departments

- Implement deep learning or ensemble models

- Integrate real-time HR data streams

## 🙏 Acknowledgments
- Dataset often used in ML tutorials and HR analytics case studies

- Scikit-learn documentation and open-source contributors

