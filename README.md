The objective of this project is to develop a hybrid ML-based model for phishing attack detection including different classification algorithms including Support Vector Machine, Logistics Regression, Decision Tree, and Random Forest.

Made by:-
Bikash Panda,
Harapriya Pradhan,
Ipsita Behera,
Abhilash Kumar Behera




## Table 1: Empirical Analysis of ML Classifiers without CFS

| Classifier | Accuracy | F-1   | Specificity | Sensitivity | Precision | ROC_AUC |
|-------|----------|-------|-------------|-------------|-----------|---------|
| SVM (RBF)   | 94.26%   | 0.92  | 0.95        | 0.92        | 0.91      |         |
| SVM (Polynomial)      | 94.21%   | 0.92  | 0.95        | 0.92        | 0.91      |         |
| SVM (Linear)      | 93.15%   | 0.90  | 0.93        | 0.91        | 0.89      |         |
| RF    | 96.92%   | 0.96  | 0.97        | 0.96        | 0.95      | 0.9948  |
| DT    | 95.41%   | 0.93  | 0.96        | 0.94        | 0.93      | 0.9503  |
| LR    | 87.91%   | 0.81  | 0.94        | 0.75        | 0.88      | 0.9480  |
| NB    | 84.16%   | 0.73  | 0.96        | 0.62        | 0.88      | 0.9555  |
| KNN   | 80.44%   | 0.70  | 0.87        | 0.68        | 0.73      | 0.8741  |



## Table 2: Empirical analysis of ML classifiers with CFS 

|Classifier|Accuracy| F-1| Specificity | Sensitivity | Precision | ROC_AUC |
|-------|----------|-------|-------------|-------------|-----------|---------|
| LDA   | 89.04%   | 0.90  | 0.80        | 0.97        | 0.83      | 0.9646  |
| RF    | 92.79%   | 0.93  | 0.92        | 0.92        | 0.93      | 0.9772  |
| DT    | 91.59%   | 0.92  | 0.93        | 0.89        | 0.93      | 0.9359  |
| LR    | 90.68%   | 0.91  | 0.86        | 0.94        | 0.88      | 0.9657  |
| NB    | 89.07%   | 0.90  | 0.80        | 0.97        | 0.83      | 0.9276  |
| KNN   | 91.12%   | 0.91  | 0.89        | 0.93        | 0.90      | 0.9655  |
