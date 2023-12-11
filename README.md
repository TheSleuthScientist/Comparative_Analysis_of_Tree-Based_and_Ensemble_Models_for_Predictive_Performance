
# Predictive Model Comparison: Tree, Ensemble, and Analytical Methods

This repository contains a Jupyter Notebook that performs a comprehensive analysis of a dataset from a banking institution's direct marketing campaigns. The primary objective is to predict whether clients will subscribe to a bank term deposit based on telephone call interactions.

## Dataset Overview:
The dataset originates from direct marketing campaigns (telephone calls) of a banking institution. It involves records of multiple contacts with clients to assess their interest in bank term deposits.

### Features:
- **Client Contact Details**: Includes multiple interactions per client.
- **Campaign Information**: Data related to the telephone call strategies and client responses.

### Objective:
- To predict client subscription to bank term deposits.

## Analysis Steps

### 1. Data Preprocessing
- **Feature Engineering**: Transformation and creation of new features to better capture the essence of client interactions and response patterns.
- **Scaling and Encoding**: Standardisation of continuous variables and encoding of categorical variables for machine learning readiness.

### 2. Model Implementation
- **Model Selection**: A variety of models were chosen for comparison:
  - Logistic Regression
  - Decision Tree Classifier
  - AdaBoost Classifier
  - Gradient Boosting Classifier
  - Other supplementary models (SVC, KNN, Random Forest, etc.)
- **Parameter Optimisation**: Utilised GridSearchCV for hyperparameter tuning.
- **Validation Strategies**: Employed cross-validation techniques to ensure model robustness.

### 3. Performance Evaluation
- **Metrics Used**: Accuracy score, confusion matrix.
- **Comparison Criteria**: Models were evaluated and compared based on their ability to accurately predict client subscription decisions.

### 4. Visualisation and Insights
- Data visualisations using `matplotlib` and `seaborn` to gain deeper insights into the dataset and model performance.

## Conclusion
The notebook provides an in-depth comparative analysis of various predictive models, emphasising tree-based and ensemble methods, to determine the effectiveness of marketing strategies in a banking context. The aim is to leverage this analysis to refine future marketing campaigns and enhance client subscription rates.

