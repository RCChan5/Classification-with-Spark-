# Classification-with-Spark-

## About

In this exercise I use services offered by Microsoft Azure, I use blob storage to store a dataset and spark for machine learning tasks. 
#### The goal of this exercise is to create a machine-learning pipeline and determine the best model for the classification of the Census Income dataset

## Dataset

The dataset is credited to Ronny Kohavi and Barry Becker and was drawn from the 1994 United States Census Bureau data and involves using personal details such as education level to predict whether an individual will earn more or less than $50,000 per year.

https://archive.ics.uci.edu/dataset/2/adult

## Results

Linear Regression:
| Accuracy | Recall | Precision | F1  | AUC |
|----------|--------|-----------|-----|-----|
| .85      | .56    | .74       | .64 | .80 |

Decision Tree:
| Accuracy | Recall | Precision | F1  | AUC |
|----------|--------|-----------|-----|-----|
| .85      | .58    | .74       | .65 | .81 |

Random Forest:
| Accuracy | Recall | Precision | F1  | AUC |
|----------|--------|-----------|-----|-----|
| .85      | .53    | .78       | .63 | .82 |

Naive Bayes:
| Accuracy | Recall | Precision | F1  | AUC |
|----------|--------|-----------|-----|-----|
| .78      | .23    | .63       | .34 | .71 |

Gradient Boosting:
| Accuracy | Recall | Precision | F1  | AUC |
|----------|--------|-----------|-----|-----|
| .86      | .56    | .78       | .65 | .83 |

## Future Work

1) Compare my hand-created models to that of sparks automl function.
2) Incorporate interpretable machine learning evaluation metrics to analyze model performance.
