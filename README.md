# Titanic Survival Prediction

This repository contains a comprehensive notebook for the Kaggle Titanic Challenge. It predicts survival based on passenger features using machine learning techniques and explains predictions with interpretability tools.

## Features
- Extensive data exploration and visualization.
- Feature engineering and preprocessing.
- Model training with Logistic Regression, RandomForest, XGBoost, and MultiLayer Perceptron.
- Model stacking for improved accuracy.
- Explainable AI (XAI) using SHAP, permutation importance, and feature coefficients.

## Setup
To set up the environment:
```bash
git clone https://github.com/ata-turhan/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
```


## Results
- Best Model: Stacked Ensemble
- Final Accuracy: 83.5%
- Top Features:
- `Sex`
- `Pclass`
- `AgeGroup`
- `FamilySize`

5. **Scripts in `src/`**
- **`preprocessing.py`**: Handles data cleaning and feature engineering.
- **`train.py`**: Contains code for training and saving models.
- **`evaluation.py`**: Includes evaluation metrics and comparison utilities.
