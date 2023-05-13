# Convex Neural Networks
This is an implementation of Convex Neural Network Optimization using the [CVXPY](https://www.cvxpy.org/)
 library. The implementation solves the problem of optimizing a neural network with convex loss functions and linear constraints.

The implementation is based on the paper "[Convex Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2005/file/0fc170ecbb8ff1afb2c6de48ea5343e7-Paper.pdf)" by Yoshua Bengio, Nicolas Le Roux, Pascal Vincent, Olivier Delalleau, and Patrice Marcotte, published in 2006.

The Python notebook demonstrates the use of Convex Neural Networks to solve the classification problem on the NSL-KDD dataset. The algorithm used is the Incremental Convex NN Algorithm, which updates the weights and biases of a linear classifier at each step to minimize the loss function and regularization penalty.


## Dataset

The NSL-KDD dataset is a benchmark dataset for intrusion detection systems. It contains a labeled set of network traffic data that is divided into four categories: normal, DOS, probe, and R2L (remote to local).


## Dependencies

The following dependencies are required to run this code:

  - NumPy
  - Pandas
  - Scikit-learn
  - CVXPY


## Results

The algorithm achieves a test accuracy of approximately 85%, which is a reasonable performance for the NSL-KDD dataset.


## Contributing

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue or submit a pull request.
Acknowledgements

This implementation was created by [Raneem Khafagy] as part of a project for [EEC 494 - Optimization], [Faculty of Engineering - Alexandria University]. The code is provided as-is, without any warranties or guarantees of any kind.
