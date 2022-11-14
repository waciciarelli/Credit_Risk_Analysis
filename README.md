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
* The balanced accuracy score is 0.64
* Precision for the minority class is very low (0.01), and very high for the majority class (1.00)
* Recall for the minority class is high (0.69), and a little lower for the majority class (0.59)

### SMOTE Oversampling

![SMOTE Oversampling balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_smote.png?raw=true)

![SMOTE Oversampling Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_smote.png?raw=true)

As demonstrated above:
* The balanced accuracy score is 0.66
* Precision for the minority class is very low (0.01), and very high for the majority class (1.00)
* Recall for the minority class is high (0.63), and a little higher for the majority class (0.69)

### Cluster Centroids Oversampling

![Undersampling balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_undersampling.png?raw=true)

![Undersampling Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_undersampling.png?raw=true)

As demonstrated above:
* The balanced accuracy score is 0.54
* Precision for the minority class is very low (0.01), and very high for the majority class (1.00)
* Recall for the minority class is high (0.69), and lower for the majority class (0.40)

### SMOTEENN Combination Sampling

![SMOTEENN balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_balanced_accuracy_score_over_and_under.png?raw=true)

![SMOTEENN Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_resampling_classification_report_imbalanced_over_and_under.png?raw=true)

As demonstrated above:
* The balanced accuracy score is 0.67
* Precision for the minority class is very low (0.01), and very high for the majority class (1.00)
* Recall for the minority class is high (0.76), and lower for the majority class (0.59)

### Balanced Random Forest Classifier

![Forest balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_balanced_accuracy_score.png?raw=true)

![Forest Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_classification_report_imbalanced.png?raw=true)

As demonstrated above:
* The balanced accuracy score is 0.79
* Precision for the minority class is very low (0.03), and very high for the majority class (1.00)
* Recall for the minority class is high (0.70), and a little higher for the majority class (0.87)

### Easy Ensemble AdaBoost Classifier

![AdaBoost balanced accuracy](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_balanced_accuracy_score_adaboost.png?raw=true)

![AdaBoost Classification Report](https://github.com/waciciarelli/Credit_Risk_Analysis/blob/main/Screenshots/cr_ensemble_classification_report_imbalanced_adaboost.png?raw=true)

As demonstrated above:
* The balanced accuracy score is 0.93
* Precision for the minority class is low (0.09), and very high for the majority class (1.00)
* Recall for the minority class is high (0.92), and also high for the majority class (0.94)

## Summary: 
### Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
