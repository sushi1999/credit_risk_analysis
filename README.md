# Credit Default Prediction & Financial Loss Analysis
This project uses 10 borrower variables (age, income, debt ratio, credit utilization, past-due history, and others) to predict whether a borrower is likely to default, so the bank can decide who should be approved.

**Data**: Kaggle [Give Me Some Credit](https://www.kaggle.com/competitions/GiveMeSomeCredit/overview) (150,000 borrower records)

**What this project does**:
- Builds and compares Logistic Regression and Decision Tree models (AUC ~0.85)
- Translates model errors (missed defaulters) into estimated dollar losses for the bank
- Tunes the classification threshold on a validation set to minimize total cost
- Tests how sensitive the recommended threshold is to the underlying cost assumptions

**Files**:
- `credit_risk_analysis0926.ipynb` — full analysis, runnable end-to-end
- `cs-training.csv` — dataset

**To run**: open the notebook in Jupyter; requires pandas, numpy, scikit-learn, matplotlib, seaborn.
