# Summary of 4_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

28.5 seconds

## Metric details
|           |     score |     threshold |
|:----------|----------:|--------------:|
| logloss   | 0.0836576 | nan           |
| auc       | 0.975791  | nan           |
| f1        | 0.79889   |   0.278898    |
| accuracy  | 0.971     |   0.278898    |
| precision | 1         |   0.989841    |
| recall    | 1         |   1.21322e-52 |
| mcc       | 0.798715  |   0.278898    |


## Metric details with threshold from accuracy metric
|           |     score |   threshold |
|:----------|----------:|------------:|
| logloss   | 0.0836576 |  nan        |
| auc       | 0.975791  |  nan        |
| f1        | 0.79889   |    0.278898 |
| accuracy  | 0.971     |    0.278898 |
| precision | 0.972973  |    0.278898 |
| recall    | 0.677647  |    0.278898 |
| mcc       | 0.798715  |    0.278898 |


## Confusion matrix (at threshold=0.278898)
|              |   Predicted as 0 |   Predicted as 1 |
|:-------------|-----------------:|-----------------:|
| Labeled as 0 |            18268 |               32 |
| Labeled as 1 |              548 |             1152 |

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
