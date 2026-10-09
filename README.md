# Data Science Case Studies

Six hands-on case studies from the course. Each folder has the problem statement, a worked solution and the dataset.

| # | Case study | Type | Problem statement | Solution |
|---|---|---|---|---|
| 1 | [Porter - Delivery Time Estimation](01_Porter_Delivery_Time) | Regression | Yes | Notebook |
| 2 | [Ola - Driver Attrition](02_Ola_Driver_Attrition) | Classification (churn) | Yes | PDF export of the notebook |
| 3 | [Loan Case Study](03_Loan_Case_Study) | Classification | LoanTap brief | Home-loan eligibility notebook |
| 4 | [Insurance Premium Prediction](04_Insurance_Premium_Regression) | Linear regression | In notebook | Notebook |
| 5 | [Cars24 - Used Car Price](05_Cars24_Price_Prediction) | Regression + Streamlit app | Assignment | App, model, answer key |
| 6 | [Telecom Churn - Logistic Regression](06_Churn_Logistic_Regression) | Classification | In notebook | Lecture notebooks |

## Running the notebooks
```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy statsmodels streamlit jupyter
jupyter notebook
```
Notebooks that begin with `!gdown ...` download their data from Google Drive. The same files are already in each `data/` folder, so you can read them locally instead.
