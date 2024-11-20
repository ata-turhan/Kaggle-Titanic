# **Titanic Survival Prediction**

This repository contains a comprehensive solution for the Kaggle **Titanic - Machine Learning from Disaster** competition. Using machine learning techniques, we predict the survival of passengers based on key features like age, gender, class, and more. This project also includes **Explainable AI (XAI)** techniques to understand model predictions.

---

## **Project Overview**

- **Goal**: Predict whether a Titanic passenger survived or not, using features such as age, gender, ticket class, and more.
- **Techniques**:
  - Data Cleaning and Feature Engineering.
  - Model Training and Hyperparameter Tuning.
  - Model Stacking for improved performance.
  - Explainable AI using SHAP, permutation importance, and feature importances.

---

## **Features**

- **Extensive Data Exploration**: Visualizations and insights from the dataset.
- **Feature Engineering**: New features such as `AgeGroup`, `FareBin`, `FamilySize`, `IsAlone`, and `Title`.
- **Model Training**: Logistic Regression, RandomForest, XGBoost, MultiLayer Perceptron, and Stacked Ensembles.
- **Explainable AI**: Insights into model predictions with SHAP values, permutation importance, and feature coefficients.
- **Kaggle Submission**: Prepares predictions in the required format for submission.

---

## **Setup Instructions**

### **1. Clone the Repository**
```bash
git clone https://github.com/ata-turhan/titanic-survival-prediction.git
cd titanic-survival-prediction
```

### **2. Install Dependencies**
Ensure you have Python 3.8+ installed. Install the required packages using:
```bash
pip install -r requirements.txt
```

### **3. Run the Notebook**
Launch Jupyter Notebook and open `notebooks/titanic_predicting_survivors.ipynb`:
```bash
jupyter notebook
```

---

## **Key Results**

| **Model**             | **Accuracy** | **F1-Score** |
|-----------------------|--------------|--------------|
| Logistic Regression   | 80.45%      | 0.80         |
| RandomForest          | 82.68%      | 0.82         |
| MultiLayer Perceptron | 79.33%      | 0.79         |
| XGBoost               | TBD         | TBD          |
| **Stacked Model**     | **83.50%**  | **0.83**     |

---

## **Explainable AI (XAI)**

This project uses several techniques to explain model predictions:

1. **Logistic Regression Coefficients**:
   - Visualizes the top features affecting survival.

2. **RandomForest Feature Importances**:
   - Highlights features most impactful for survival predictions.

3. **Permutation Importance**:
   - Explains predictions of the MLP model by permuting feature values.

4. **SHAP Values**:
   - Detailed explanations for RandomForest predictions with SHAP plots.

---

## **Kaggle Submission**

The repository includes the final predictions in the `outputs/` directory:
- **File**: `submission.csv`
- **Format**:
  ```csv
  PassengerId,Survived
  892,0
  893,1
  ...
  ```

---

## **Future Improvements**

- Explore advanced stacking techniques
- Incorporate additional external datasets for richer feature engineering.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
