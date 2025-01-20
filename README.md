
# Credit Risk Analysis Project

This project aims to simulate a credit risk analysis pipeline using synthetic data. The pipeline includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and an interactive dashboard for predictions.

## Features

1. **Data Generation**:
   - Synthetic dataset generation for binary classification with balanced features.

2. **Exploratory Data Analysis (EDA)**:
   - Heatmap of feature correlations.
   - Distribution plots of individual features by class labels.

3. **Model Training**:
   - Logistic Regression.
   - Random Forest Classifier.

4. **Model Evaluation**:
   - Classification reports.
   - AUC-ROC scores and visualizations.

5. **Data Preprocessing**:
   - Train-test split with stratification.
   - Feature scaling using StandardScaler.

## File Structure

```
credit_risk_project/
├── Notebook.ipynb                # Notebook for data processing and training
├── data/
│   ├── synthetic_credit_risk_data.csv  # Generated dataset
│   └── model_performance.csv           # Model evaluation results
├── README.md              # Project documentation
```


## Dependencies

- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Future Work

- Integrate more advanced models such as Gradient Boosting Machines (e.g., XGBoost, LightGBM).
- Add feature selection and hyperparameter tuning.
- Extend the dashboard to include more interactive visualizations.
- Adding dashboard visualisation with streamlit 


## Acknowledgments
This project is inspired by real-world credit risk modeling scenarios in the finance sector but was done as an academic project for practice.

