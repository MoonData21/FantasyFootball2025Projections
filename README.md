# FantasyFootball2025Projections

Project Overview:
Developed and compared position-specific machine learning models to generate 2025 Fantasy Football PPR projections. Using scikit-learn and XGBoost, I built a cross-validated pipeline that trains separate models for RB, WR/TE, and QB, leveraging historical performance, age, and health metrics to predict next-season fantasy output.

The project incorporates:

5-fold and 3-fold cross-validation for model generalization

XGBoost feature importance analysis to identify key predictive stats

Custom overrides for injured or retired players

Automated CSV export of final predictions for post-season evaluation

At season’s end, model performance (based on Mean Absolute Error) will be compared to determine which algorithm most accurately predicted fantasy outcomes.

Tech Stack: Python, Pandas, scikit-learn, XGBoost, Cross-Validation, Feature Engineering, and Model Evaluation.
