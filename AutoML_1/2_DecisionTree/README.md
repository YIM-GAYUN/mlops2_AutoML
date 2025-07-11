# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 4
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

48.8 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.105097 |  nan        |
| auc       | 0.936293 |  nan        |
| f1        | 0.800811 |    0.112737 |
| accuracy  | 0.971762 |    0.112737 |
| precision | 1        |    0.112737 |
| recall    | 1        |    0        |
| mcc       | 0.804862 |    0.112737 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.105097 |  nan        |
| auc       | 0.936293 |  nan        |
| f1        | 0.800811 |    0.112737 |
| accuracy  | 0.971762 |    0.112737 |
| precision | 1        |    0.112737 |
| recall    | 0.667794 |    0.112737 |
| mcc       | 0.804862 |    0.112737 |


## Confusion matrix (at threshold=0.112737)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            73200 |                0 |
| Labeled as 1 |             2259 |             4541 |

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
