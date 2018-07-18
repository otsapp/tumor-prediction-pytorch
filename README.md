# Predicting Malignant Tumor Diagnosis With Pytorch
#### Objective
Exercise in initiating a logistic regression using Pytorch and just for fun, demonstrating the speed of Rprop in minimising the cost function vs. stochastic gradient decent (SGD) over a couple of hundred Epochs.

* Activation function: Sigmoid.
* Optimiser functions: SGD & Rprop.

#### Dataset
`https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29`
* Diagnosis (1 = malignant, 0 = benign).
* 30 measurements.

A nice quick intro on when SGD can be useful: http://ufldl.stanford.edu/tutorial/supervised/OptimizationStochasticGradientDescent/

Credit to hunkim for the code structure for the exercise: https://github.com/hunkim/PyTorchZeroToAll/blob/master/07_diabets_logistic.py