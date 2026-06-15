# Telecom Customer Churn Prediction

Machine learning project for predicting telecom customer churn with a Streamlit web app.

## Files

- `streamlit_app.py` - Streamlit app for making churn predictions.
- `ML_Model_Building.ipynb` - Notebook used for data preprocessing, model training, evaluation, and model export.
- `Customer-Churn (1).csv` - Customer churn dataset used by the app and notebook.
- `requirements.txt` - Python dependencies.

## Run The App

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Streamlit:

```bash
streamlit run streamlit_app.py
```

The app expects the trained model file `best_optuna_churn_model.pkl` in the project folder. Generate it from the notebook before running the app.
