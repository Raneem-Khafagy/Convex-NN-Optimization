# Convex Neural Networks
This is an implementation of Convex Neural Network Optimization using the [CVXPY](https://www.cvxpy.org/)
 library. The implementation solves the problem of optimizing a neural network with convex loss functions and linear constraints.

The implementation is based on the paper "[Convex Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2005/file/0fc170ecbb8ff1afb2c6de48ea5343e7-Paper.pdf)" by Yoshua Bengio, Nicolas Le Roux, Pascal Vincent, Olivier Delalleau, and Patrice Marcotte, published in 2006.

This code uses the CVXPY library to solve a binary classification problem using the hinge loss function and L2 regularization. The code generates a toy dataset, preprocesses the data, splits it into training and testing sets, defines the optimization problem using CVXPY, solves the problem, extracts the learned weight vector and bias term, and evaluates the model on the test set.


## Dataset

The code uses a toy dataset generated using the make_classification function from Scikit-learn. The dataset consists of 1000 samples, 10 features, and 5 informative features.


## Dependencies

The following dependencies are required to run this code:

  - NumPy
  - Pandas
  - Scikit-learn
  - CVXPY


## Results

The algorithm achieves a test accuracy of approximately 85%. The hinge loss function is used as a loss function and the "L1 regularization" is used as a regularization penalty with the regularization parameter set to 0.1. The theta vector and the b scalar (representing the learned weight vector and bias term, respectively) are extracted from the solution and used to compute predicted labels for the test set, which are then compared to the true labels to compute the accuracy.


## Contributing

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue or submit a pull request.
Acknowledgements

This implementation was created by [Raneem Khafagy] as part of a project for [EEC 494 - Optimization], [Faculty of Engineering - Alexandria University]. The code is provided as-is, without any warranties or guarantees of any kind.
