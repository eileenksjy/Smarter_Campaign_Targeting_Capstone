# Smarter Campaign Targeting – Capstone Project
for NTUC Capstone


Welcome to my Capstone Project, **Smarter Campaign Targeting**, built from the AIAP technical assesment program. This project represents a significant enhancement of the original work — with cleaner data processing, stronger models, and a fully integrated **interactive dashboard**.

Refer to Smarter Campaign Targeting Documentation.docx (Appendix G for step by ste guide to run the dashboard)

---

## Objective

To improve marketing campaign effectiveness by using machine learning to identify clients most likely to subscribe to a term deposit.

---

## Dataset

This project uses the bank_full.csv based on a Portuguese bank's marketing campaigns.  
- Original source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---

## Key Features

- **Data Cleaning & Feature Engineering**  
  Handled missing values, encoded categorical features, engineered meaningful predictors.

- **Modeling**  
  Explored several models:  
  `Logistic Regression`, `Random Forest`, `XGBoost`and  `ANN'
  Tuned for performance using `RandomizedSearchCV` and evaluated with F1, AUC, and confusion matrices.

- **Imbalance Handling**  
  Applied `SMOTE` for oversampling to balance the target classes.

- **Dashboard Integration**  
  Built an interactive dashboard using `Gradio` to demo live predictions — allowing non-technical users to try the model.

---

## Dashboard Preview
Run `DashboardSmarterCampaignTarget.ipynb` or use the Gradio interface (`gradio.Interface(...)`) to interact with the model.

---

## Project Structure

- `*.ipynb` – Jupyter notebooks for data exploration, modeling, and dashboard
- `*.pkl` – Saved model and encoders
- `requirements.txt` – Python dependencies
- `DashboardSmarterCampaignTarget.ipynb` – Gradio interface and final dashboard

## 🛠 Tech Stack

- Python 3.12
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, TensorFlow
- SMOTE (Imbalanced-learn)
- Gradio (Dashboard)
- VS Code, GitHub

---

## 🚀 Getting Started

1. Clone this repo
2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt

