# JPX-Tokyo-Stock-Exchange-Prediction-Group7
Lloyds Banking Group Datathon Project Focused on analysing the trade-off between model performance and environmental impact in financial prediction tasks.

## Key Findings

- XGBoost outperformed Logistic Regression and Random Forest on return prediction
- Directional accuracy ~49.5% (near random) — stock returns are hard to predict
- Spearman correlation ≈ 0.001 — weak rank correlation with actual returns
- Logistic Regression collapsed to predicting 0% UP (degenerate classifier)
- Random Forest: highest CO₂ (0.00165 kg) and slowest (118s) with no gain over XGBoost
- XGBoost: best accuracy-to-emissions ratio across all models
- Fundamental features (EPS, NetSales) combined with price features yielded best results
