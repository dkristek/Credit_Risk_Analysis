# Credit_Risk_Analysis
## Overview
The objective of this project was to analyze the results of various supervised machine learning and sampling models to predict credit risk. The sampling methods used were the RandomOverSampler algorithm, the SMOTE algorithm, the ClusterCentroids algorithm, and the SMOTEENN algorithm. The machine learning models were a Balanced Random Forest and the Easy Ensemble AdaBoost Classifier.

## Results
### Naive Random Oversampler
<details>
  <summary>Random Oversampling Results</summary>
  
  ![Sumamry of Random Oversampling](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/naive_random_sampling.png)
  </details
  
  - Balanced Accuracy Score: 0.624998
  - The precision is low (0.01) for high-risk and high (1.00) for low-risk
  - Recall: high-risk is 0.60 and low-risk is 0.65
 
### SMOTE Sampling
  <details>
  <summary> SMOTE Sampling</summary>
  
  ![Summary of SMOTE Sampling](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/smote_sampling.png)
  </details>
  - Balanced Accuracy Score: 0.651258
  - High-risk precision: 0.01, Low-risk precision: 1.00
  - Recall: high-risk/low-risk 0.64/0.66

### Undersampling
  <details>
  <summary> Undersampling Summary</summary>
  
  ![Undersampling Summary](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/undersampling.png)
  </details>
  - Balanced Accuracy Score: 0.52927
  - High-risk Precision: 0.01, Low-risk precision: 1.00 
  - Recall: high-risk/low-risk 0.45/0.61

### Combination Over/Under Sampling
  <details>
  <summary> Summary of Combo Sampling </summary>
  
  ![Combo Sampling Results Summary](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/combo_over_under_sampling.png)
  </details>
  - Balanced Accuracy Score: 0.53939
  - Precision: high-risk/low-risk 0.01/1.00
  - Recall: high-risk/low-risk 0.70/0.57
 
 ### Balanced Random Forest Model
  <details>
  <summary>Balanced Random Forest</summary>
  
  ![Balanced Random Forest Summary of Results](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/balanced_random_forest.png)
  </details>
  - Balanced Accuracy Score: 0.787767
  - Precision: high-risk/low-risk 0.04/1.00
  - Recall: high-risk/low-risk 0.67/0.91
  
### EasyEnsemble AdaBoost Classifier
  <details>
  <summary>Easy Ensemble</summary>
  
  ![EasyEnsemble AdaBoost results summary](https://github.com/dkristek/Credit_Risk_Analysis/blob/main/images/easy_ensemble_adaboost.png)
  </details>
  - Balanced Accuracy Score: 0.925427
  - Precision: 0.07/1.00
  - Recall: 0.91/0.94
 
 ## Summary
 
