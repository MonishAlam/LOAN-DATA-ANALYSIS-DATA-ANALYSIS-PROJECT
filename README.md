# LOAN-DATA-ANALYSIS-DATA-ANALYSIS-PROJECT

# 🏦 Loan Data Analysis Project

This project demonstrates how a data analyst approaches a real-world business scenario using a loan dataset. The goal is to uncover insights related to loan approval based on applicant demographics, income, and credit history.

## 📌 Problem Statement

- Analyze the demographic characteristics of loan applicants.
- Understand the influence of credit history on loan approval.
- Identify loan trends by gender, marital status, and income.
- Determine the maximum and minimum loan amounts applied.

---

## 📂 Dataset Information

- **Source Format**: CSV (`loan_analysis.csv`)
- **Size**: ~38 KB
- **Records**: 614 rows, 13 columns

### 📊 Data Features

- **Numerical Columns**:
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`, `Dependents`
- **Categorical Columns**:
  - `Loan_ID`, `Gender`, `Married`, `Education`, `Self_Employed`, `Property_Area`, `Loan_Status`

---

## 🔧 Tools & Technologies Used

- **Programming Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Platform**: Jupyter Notebook
- **Data Storage**: CSV file, optionally SQL database

---

## 🧹 Data Cleaning

- Loaded dataset using `pandas`
- Checked for null values using `df.info()` and `pd.isnull().sum()`
- Imputed missing categorical data with **mode**
- Imputed missing numerical data with **median**
- Saved the cleaned data as `LOAN_ANALYSIS_NEW_DATA.csv` for further analysis

---

## 📊 Exploratory Data Analysis (EDA)

Performed EDA using visual tools and statistical summaries to extract meaningful insights:

- Majority of applicants are **educated, married males**
- Most loan approvals are for applicants with **Credit_History = 1**
- **Semi-urban** areas have the highest concentration of loan applicants
- Created visualizations like:
  - Count plots
  - Bar plots
  - Histograms
  - Scatter plots

---

## 📈 Dashboard Creation

- Used plots to create a visual dashboard for presenting key insights
- Visualized:
  - Distribution of Loan Status
  - Loan Amount trends
  - Relationship between credit history and loan approval

---

## ✅ Conclusion

- Educated, married males dominate loan applications and approvals
- Applicants with positive credit history are more likely to get approved
- Semi-urban areas have higher approval rates
- Loan amounts tend to be lower for low-income groups

---

## 📁 File Structure

```plaintext
├── loan_analysis.csv              # Raw dataset
├── LOAN_ANALYSIS_NEW_DATA.csv    # Cleaned dataset
├── Loan_Data_Analysis.ipynb      # Jupyter Notebook with code
├── Loan data analysis.ppt.pptx   # Project presentation
├── README.md                     # Project documentation

