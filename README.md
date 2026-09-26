**TRAFFIC VIOLATION TYPE PREDICTION USING ENSEMBLE LEARNING**

**PROJECT OVERVIEW**

This project focuses on predicting traffic violation types using machine learning techniques. The analysis uses traffic records and compare multiple classification models to identify the performance.

**OBJECTIVE**
- Predict traffic violation types
- Compare Ensemble and classification models
- Evaluate model performance

**DATASET**

Dataset is taken from the Kaggle website which contains 12,92,399 records. A sample of 1,00,000 records was used for model development and evaluation.

**METHODOLOGY**
  1. Data preprocessing and cleaning
  2. Feature engineering
  3. Encoding categorical variable
  4. Train-test split
  5. Handling class imbalance using Random Oversampling
  6. Model training and comparison
  7. Model evaluation
  8. Feature importance and SHAP analysis
 
**MODELS USED**
  - Decision Tree
  - Random Forest
  - XGBoost
  - Voting Classifier
  - Stacking Classifier

**EVALUATION METRICS**
  - Accuracy
  - Precision
  - Recall
  - Macro F1-score
  - ROC-AUC
  - Confusion matrix
  - ROC Curve

**PROJECT RESULTS**

The different models were compared based on their classification report. The complete implementation, model comparison, visualizations and evaluation are available in the Notebook included in this repository.The Stacking Classifier achieved the strongest overall performance among the evaluated models, with:
* **Accuracy:** 57%
* **Macro F1-score:** 0.44
* **ROC-AUC:** 0.674

Macro F1-score and ROC-AUC were given particular attention because the target classes were imbalanced.


  
  
     
  
