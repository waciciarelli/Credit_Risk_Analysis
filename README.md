# Credit_Risk_Analysis

## Overview of the analysis: 
### Explain the purpose of this analysis.

This analysis evaluates credit card risk data and determines which machine learning algorithm utilized would be the best fit for the dataset. This was done by utilizing classifiers and resampling methods.

## Results: 
### Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

This analysis was conducted using six machine learning models:
* Random Oversampling
* SMOTE Oversampling
* Cluster Centroids Undersampling
* SMOTEENN Combination Sampling
* Balanced Random Forest Classifier
* Easy Ensemble AdaBoost Classifier

To determine the efficiency of each model, the balanced accuracy score, precision, and recal were all calculated.

### Random Sampling

![Random Sampling balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score.png?raw=true)

![Random Sampling Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced.png?raw=true)

As demonstrated above:
* The balanced accuracy score is

### SMOTE Oversampling

![SMOTE Oversampling balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_smote.png?raw=true)

![SMOTE Oversampling Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_smote.png?raw=true)

### Cluster Centroids Oversampling

![Undersampling balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_undersampling.png?raw=true)

![Undersampling Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_undersampling.png?raw=true)

### SMOTEENN Combination Sampling

![SMOTEENN balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_over_and_under.png?raw=true)

![SMOTEENN Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_over_and_under.png?raw=true)

### Balanced Random Forest Classifier

![Forest balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_balanced_accuracy_score.png?raw=true)

![Forest Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_classification_report_imbalanced.png?raw=true)

### Easy Ensemble AdaBoost Classifier

![AdaBoost balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_balanced_accuracy_score_adaboost.png?raw=true)

![AdaBoost Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_classification_report_imbalanced_adaboost.png?raw=true)


## Summary: 
### Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
