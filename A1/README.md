
# A1 - Breast Cancer Diagnosis

## Objective
The objective of this task is to classify breast cancer tumors as Malignant or Benign using machine learning models.

## Dataset
- Dataset: Breast Cancer Wisconsin (Diagnostic)
- Samples: 569
- Features: 30
- Classes: Malignant (212), Benign (357)

## Machine Learning Models
1. Logistic Regression
2. Support Vector Machine (RBF)
3. Random Forest

## Data Preprocessing
- Stratified 80/20 train-test split
- StandardScaler for Logistic Regression and SVM
- GridSearchCV for hyperparameter tuning

## Results
SVM achieved the best test performance:
- Accuracy: 98.25%
- Malignant Precision: 97.62%
- Malignant Recall: 97.62%
- Malignant F1-score: 97.62%
- ROC-AUC: 99.77%

## Files
- A1_Breast_Cancer_Diagnosis.ipynb: Complete notebook
- class_distribution.png: Class distribution
- correlation_heatmap.png: Feature correlation heatmap
- confusion_matrices.png: Model confusion matrices
- roc_curve.png: ROC curves
- feature_importance.png: Random Forest feature importance
- requirements.txt: Required Python libraries

## Tools
Python, Google Colab, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
