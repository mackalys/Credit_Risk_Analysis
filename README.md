# Credit Risk Analysis

## Overview of the Analysis
For this analysis, we are taking the the data we were given in the loan_stats.csv file to predict whether the customers of LendingClub are at high or low credit risk. This will be accomplished by using six machine learning models to determine how accurate credit risk is being evaluated. The following learning machines are used in this analysis.

  - Naive Random Oversampling
  - SMOTE Oversampling
  - Undersampling (ClusterCentroids)
  - Combination Oversampling/Undersampling (SMOTEEN)
  - Balanced Random Forest Classifier
  - Easy Ensemble AdaBoost Classifier
 
 We will be looking to see which learning machine model will be the best to use in further analysis of risks within the company.

## Results

### Naive Random Oversampling
![naive_random_oversampling.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/naive_random_oversampling.png)
- Accuracy Score: 65.04%
- High Risk Presicion Score: 1%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 68%
- Low Risk Recall Score: 62%
### SMOTE Oversampling
![smote_oversampling.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/smote_oversampling.png)
- Accuracy Score: 65.04%
- High Risk Presicion Score: 1%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 68%
- Low Risk Recall Score: 62%
### Undersampling
![undersampling.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/undersampling.png)
- Accuracy Score: 65.04%
- High Risk Presicion Score: 1%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 69%
- Low Risk Recall Score: 40%
### Combination Oversampling/Undersampling
![combination_overunder_sampling.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/combination_overunder_sampling.png)
- Accuracy Score: 54.47%
- High Risk Presicion Score: 1%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 76%
- Low Risk Recall Score: 59%
### Balanced Random Forest Classifier
![balanced_random_forest_classifier.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/balanced_random_forest_classifier.png)
- Accuracy Score: 78.85%
- High Risk Presicion Score: 3%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 70%
- Low Risk Recall Score: 87%
### Easy Ensemble AdaBoost Classifier
![easy_ensemble_adaboost_classifier.png](https://github.com/mackalys/Credit_Risk_Analysis/blob/main/resources/images/easy_ensemble_adaboost_classifier.png)
- Accuracy Score: 93.17%
- High Risk Presicion Score: 9%
- Low Risk Precision Score: 100%
- High Risk Recall Score: 92%
- Low Risk Recall Score: 94%
## Summary of the Analysis
We will determine the best model to use by looking mostly at the Accuracy Score, Precision Score, and Recall Score. When looking at all the scores we have found, the Easy Ensemble AdaBoost Classifier model is the best by far. Across all the scores mentioned (besides Low Risk Precision Score), it scores the best. The High Risk Precision Score and Recall Score for the Easy Ensemble AdaBoost Classifier model is 0.09 and .92. When looking at the recall score, we want to see it as close to 1 as possible. Again, we can see Easy Ensemble AdaBoost Classifier model far out performs the other 5 tests. For any other analysis of the credit risks for LendingClub should utilize the Easy Ensemble AdaBoost Classifier model.
