# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

60.9 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.116766 | nan         |
| auc       | 0.902468 | nan         |
| f1        | 0.801973 |   0.0687019 |
| accuracy  | 0.9719   |   0.0687019 |
| precision | 1        |   0.0687019 |
| recall    | 1        |   0.0110152 |
| mcc       | 0.805895 |   0.0687019 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.116766 | nan         |
| auc       | 0.902468 | nan         |
| f1        | 0.801973 |   0.0687019 |
| accuracy  | 0.9719   |   0.0687019 |
| precision | 1        |   0.0687019 |
| recall    | 0.669412 |   0.0687019 |
| mcc       | 0.805895 |   0.0687019 |


## Confusion matrix (at threshold=0.068702)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            18300 |                0 |
| Labeled as 1 |              562 |             1138 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
