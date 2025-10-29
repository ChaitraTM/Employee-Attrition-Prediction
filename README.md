# 🧠 Employee Attrition Prediction and Analysis

This project predicts whether an employee will **stay or leave** a company using **Machine Learning**.  
It also includes a **Tableau dashboard** for visualizing the results.

---

## 📘 Project Overview

Employee attrition means when employees leave the company.  
High attrition increases the cost of hiring and training new people.  

The goal of this project is to:
- Analyze employee data and understand factors that cause attrition.
- Build a machine learning model to predict attrition.
- Show insights and predictions in a Tableau dashboard.

---

## 🧰 Tools & Technologies Used

| Category | Tools Used |
|-----------|-------------|
| Programming Language | Python |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn |
| Data Visualization | Tableau |
| Environment | Jupyter Notebook |
| Optional | SQL for data storage |

---

## 🧩 Project Workflow

### 1️⃣ Data Collection
- Dataset used: **HR-Employee-Attrition.csv**
- Columns include: Age, Salary, Job Role, Gender, Department, Overtime, etc.

### 2️⃣ Data Preprocessing
- Removed unnecessary columns like: `EmployeeCount`, `Over18`, `StandardHours`, etc.
- Checked for missing values and duplicates.
- Encoded categorical data using `LabelEncoder` (for Gender, Department, etc.).

### 3️⃣ Exploratory Data Analysis (EDA)
Visualized employee trends using **Matplotlib** and **Seaborn**:
- Attrition by Department  
- Attrition by Salary  
- Attrition by Overtime  
- Attrition by Gender  
- Correlation Heatmap  

### 4️⃣ Model Building
- Split the dataset into **training** and **testing** sets.
- Trained models like:
  - Logistic Regression  
  - Random Forest Classifier
- Evaluated model using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score
  
### 5️⃣How to Run the Project

Clone this repository:

Always show details
git clone https://github.com/yourusername/Employee-Attrition-Prediction.git


Install required libraries:

Always show details
pip install -r requirements.txt


### 6️⃣Export Results for Tableau
  After making predictions, export them:
  ```python
  results_df.to_csv("employee_attrition_results.csv", index=False)

   Tableau Dashboard Preview
   <img width="1341" height="834" alt="Screenshot 2025-10-29 043805" src="https://github.com/user-attachments/assets/d098995a-8912-4c4e-adc4-0a422234da80" />
   📈 Model Evaluation Example
   Metric	Score
   Accuracy	0.85
   Precision	0.82
   Recall	0.78
   F1-Score	0.80
   🧠 Key Insights
  -Highest attrition occurs in Sales and R&D departments.
  -Employees doing Overtime are more likely to leave.
  -Younger employees (age 25–35) and those with low salary have higher attrition risk.
  -Model gives around 85% accuracy in predicting attrition.



Open the notebook:

Always show details
jupyter notebook employee_attrition_analysis.ipynb


Run all cells to train and evaluate the model.
