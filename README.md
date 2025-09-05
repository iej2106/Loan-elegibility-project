# Loan-elegibility-project
using data science to determine loan eligibility based on monthly spending habits

> **Note on Confidentiality:** This project recreates the methodology and skills used in a professional setting using a public dataset to protect proprietary company data and information.

## Data Source
Data was given to me by company X and will not be avaible publicy due to confidentiality concerns.

## Methodology
1.  **Data Cleaning & EDA:** Handled missing values, explored feature distributions.
2.  **Feature Engineering:** Created new features like 'Tenure Group' and 'Monthly Spend per Service'.
3.  **Modeling:** Trained and evaluated multiple classifiers (Logistic Regression, Random Forest, XGBoost) using cross-validation.
4.  **Evaluation:** The final model was selected based on precision and recall, as the business cost of false negatives (predicting a customer won't churn when they do) is high.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook, Git

## Key Skills Demonstrated
- End-to-end ML pipeline development
- Handling class imbalance (using SMOTE/class weights)
- Hyperparameter tuning with GridSearchCV
- Interpreting model results with SHAP values

## Results
The XGBoost model achieved an **85% recall** on the test set, meaning it successfully identified 85% of customers who were likely to churn. The top predictive features were tenure, monthly charges, and contract type.

[Include a key visualization here, like a feature importance plot]
