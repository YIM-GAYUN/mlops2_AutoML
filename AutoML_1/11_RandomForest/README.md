# Summary of 11_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 30
- **max_depth**: 7
- **eval_metric_name**: logloss
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

63.4 seconds

## Metric details
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0854321 |  nan        |
| auc       | 0.974706  |  nan        |
| f1        | 0.805829  |    0.304323 |
| accuracy  | 0.97185   |    0.304323 |
| precision | 0.973947  |    0.304323 |
| recall    | 1         |    0        |
| mcc       | 0.80514   |    0.304323 |


## Metric details with threshold from accuracy metric
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0854321 |  nan        |
| auc       | 0.974706  |  nan        |
| f1        | 0.805829  |    0.304323 |
| accuracy  | 0.97185   |    0.304323 |
| precision | 0.973947  |    0.304323 |
| recall    | 0.687206  |    0.304323 |
| mcc       | 0.80514   |    0.304323 |


## Confusion matrix (at threshold=0.304323)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            73075 |              125 |
| Labeled as 1 |             2127 |             4673 |

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
