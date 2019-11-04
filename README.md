# neural-network-explore-ReLU-Sigmoid-with-SGD-L-BFGS

I will be exploring the use of some neural network models|also known as multi-layer perceptron (MLP) models
The data is laid out in what is the XOR pattern, with classes that cannot be separated by any technique like logistic
regression using solely linear functions on the data, but which can be handled using a neural network classifier with 
a single hidden layer.

I will examine different optimization algorithms(SGD and L-BFGS) for learning neural network weights (designated by the solver 
parameter in sklearn models), as well as different activation functions: ReLU and Sigmoid

There are two Python files that will be called upon by my notebook to do some of the visualization work, 
and provide a better interface to some model internals.

Data files in the usual CSV format for inputs/outputs of a training and test set. Each input
data-point has two features, x1 and x2, and output labels are either 0 or 1.
