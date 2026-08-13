# HI-823-Final-Project

John Nathaniel Aclan
HI-823-004 Health Informatics
Instructor: Abdul Hafeez
Semester: Summer 2026

Project Overview:
The project uses the machine learning and causal analysis to examine the stroke risk using the demographic, clinical, and lifestyle choices.
The dataset contains about 5,110 records, including the 249 stroke cases.

Methods:
1. Data preprocessing
2. Median BMI imputation
3. One-hot encoding
4. 80/20 stratified train-test split
5. Directed Acyclic Graph (DAG)
6. Hypertension causal analysis
7. LASSO feature selection
8. Logistic Regression
9. Random Forest

Key Results:
Stroke prevalence approximately 4.87%
Age was the strongest of the LASSO predictor
Logistic Regression recall: 80%
Logistic Regression ROC-AUC: 0.848
Random Forest accuracy of 95%
Random Forest recall of 0%
Logistic Regression identified 40 of the 50 stroke cases

Causal Analysis:
Modeled stroke risk:
Hypertension = 0: 4.52%
Hypertension = 1: 6.32%
Risk difference: 1.80 percentage points


Files:
* Jupyter Notebook with Python analysis
* healthcare-dataset-stroke-data.csv
* README.md

How to Run:
1.Download or clone the repository.
2. Open the Jupyter Notebook.
3. Make sure the CSV file is in the project folder.
4. Run all notebook cells from top to bottom.

Conclusion
Logistic Regression was more useful for identifying stroke cases despite having lower overall accuracy than Random Forest. The project also showed why accuracy alone can be misleading with highly imbalanced healthcare data.

Dataset
Fedesoriano. (2021). Stroke prediction dataset [Data set]. Kaggle.
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
