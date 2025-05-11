# Client Escalation Risk Prediction Model

This project uses support ticket text and account metadata to predict whether a client is at risk of escalating their concerns to higher management.

###  Features
- Text preprocessing (TF-IDF, sentiment, urgency)
- Feature engineering (usage patterns, response time, ticket volume)
- XGBoost classifier with SHAP explainability

###  Project Structure
- `data/`: contains sample input data
- `notebooks/`: contains the Jupyter notebook with full pipeline
- `src/`: optional scripts if code modularized
- `requirements.txt`: Python dependencies

###  To Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open notebook: `jupyter notebook notebooks/escalation_risk_model.ipynb`

###  Example Output
- Classification report
- Confusion matrix
- SHAP value plot for explainability
