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

| Classifier | Accuracy | F-1   | Specificity | Sensitivity | Precision | ROC_AUC |
|-------|----------|-------|-------------|-------------|-----------|---------|
| SVM (RBF)   | 92.60%   | 0.89  | 0.94        | 0.89        | 0.89      |         |
| SVM (Polynomial)      | 92.60%   | 0.89  | 0.94        | 0.89        | 0.89      |         |
| SVM (Linear)      | 91.99%   | 0.89  | 0.91        | 0.92        | 0.86      |         |
| RF    | 95.17%   | 0.93  | 0.96        | 0.93        | 0.93      | 0.9872  |
| DT    | 93.98%   | 0.91  | 0.96        | 0.90        | 0.92      | 0.9432  |
| LR    | 91.64%   | 0.88  | 0.92        | 0.91        | 0.85      | 0.9701  |
| NB    | 86.72%   | 0.83  | 0.81        | 0.98        | 0.73      | 0.9466  |
| KNN   | 87.60%   | 0.81  | 0.93        | 0.78        | 0.85      | 0.9450  |
