# Summary of 13_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.6
- **min_samples_split**: 50
- **max_depth**: 6
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

49.2 seconds

## Metric details
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0873966 |  nan        |
| auc       | 0.973147  |  nan        |
| f1        | 0.798442  |    0.271141 |
| accuracy  | 0.9709    |    0.271141 |
| precision | 1         |    0.995046 |
| recall    | 1         |    0        |
| mcc       | 0.797955  |    0.271141 |


## Metric details with threshold from accuracy metric
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0873966 |  nan        |
| auc       | 0.973147  |  nan        |
| f1        | 0.798442  |    0.271141 |
| accuracy  | 0.9709    |    0.271141 |
| precision | 0.970737  |    0.271141 |
| recall    | 0.678088  |    0.271141 |
| mcc       | 0.797955  |    0.271141 |


## Confusion matrix (at threshold=0.271141)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            73061 |              139 |
| Labeled as 1 |             2189 |             4611 |

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
