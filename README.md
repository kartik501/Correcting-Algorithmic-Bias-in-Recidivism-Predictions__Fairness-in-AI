
# Fairness in AI - COMPAS Recidivism

## Objective:

Fairness algorithms, a recent topic in machine learning, aims to avoid outcome decisions that are unfair to certain groups or individuals. In this project we implement two of such fairness algorithms, [Fairness-Aware Classifier with Prejudice Remover Regularizer](https://www.researchgate.net/publication/262176212_Fairness-Aware_Classifier_with_Prejudice_Remover_Regularizer) and [Handling Conditional Discrimination](https://www.researchgate.net/publication/220766841_Handling_Conditional_Discrimination), in an attempt to reduce racial bias and improve fairness in recividism predictions for individuals.

## Dataset:
COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) is a popular commercial algorithm used by judges and parole officers for scoring criminal defendant’s likelihood of reoffending (recidivism). The dataset used in this project contains variables used by the COMPAS algorithm in scoring defendants, along with their outcomes within 2 years of the decision, for over 10,000 criminal defendants in Broward County, Florida. 

## Accuracy Metrics:
The metric for evaluating fairness varies based on the context of the problem. However, in this project comparions between the algorithms were made on the basis on overall accuracy, calibration score ( difference between accuracies of each class) and False Positive Rate (FPR) of each class.

## Methodology:
A logistic regression model was first implemented to acquire baseline prediction metrics for the dataset. Recidivism predictions were obtained by implementing the two fairness algorithms and then the metrics of all the models were compared.

## Fairness-Aware Classifier with Prejudice Remover Regularizer:

## Handling Conditional Discrimination:

## Results:
