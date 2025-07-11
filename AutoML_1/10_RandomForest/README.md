# Summary of 10_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.5
- **min_samples_split**: 20
- **max_depth**: 4
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

26.8 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.105246 | nan          |
| auc       | 0.955361 | nan          |
| f1        | 0.802248 |   0.132446   |
| accuracy  | 0.971413 |   0.132446   |
| precision | 1        |   0.890705   |
| recall    | 1        |   0.00345914 |
| mcc       | 0.801838 |   0.132446   |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.105246 |  nan        |
| auc       | 0.955361 |  nan        |
| f1        | 0.802248 |    0.132446 |
| accuracy  | 0.971413 |    0.132446 |
| precision | 0.973557 |    0.132446 |
| recall    | 0.682206 |    0.132446 |
| mcc       | 0.801838 |    0.132446 |


## Confusion matrix (at threshold=0.132446)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            73074 |              126 |
| Labeled as 1 |             2161 |             4639 |

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
