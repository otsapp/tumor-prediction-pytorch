# Predicting Malignant Tumor Diagnosis With Pytorch
#### objective
Exercise in initiating a logistic regression using Pytorch and comparing two common optimser functions when it comes to loss reduction:

* Activation function: Sigmoid.
* optimiser functions: Stochastic gradient decent & Resilient backpropagation.

Credit to hunkim for the code structure for the exercise: https://github.com/hunkim/PyTorchZeroToAll/blob/master/07_diabets_logistic.py

#### Dataset
`https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29`
* Diagnosis (1 = malignant, 0 = benign).
* 30 measurements.

#### Finding
Rprop apears to be a far more effective method but needs more exploration as to why.