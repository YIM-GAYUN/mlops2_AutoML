# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 4_Default_Xgboost |       10 |
| 7_Xgboost         |        3 |

## Metric details
|           |     score |     threshold |
|:----------|----------:|--------------:|
| logloss   | 0.0789624 | nan           |
| auc       | 0.979507  | nan           |
| f1        | 0.806966  |   0.472006    |
| accuracy  | 0.972012  |   0.472006    |
| precision | 1         |   0.99912     |
| recall    | 1         |   1.23171e-05 |
| mcc       | 0.806367  |   0.472006    |


## Metric details with threshold from accuracy metric
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0789624 |  nan        |
| auc       | 0.979507  |  nan        |
| f1        | 0.806966  |    0.472006 |
| accuracy  | 0.972012  |    0.472006 |
| precision | 0.975203  |    0.472006 |
| recall    | 0.688235  |    0.472006 |
| mcc       | 0.806367  |    0.472006 |


## Confusion matrix (at threshold=0.472006)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            73081 |              119 |
| Labeled as 1 |             2120 |             4680 |

## Learning curves
![Learning curves](learning_curves.png)
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
