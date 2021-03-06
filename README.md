# Neural Network Classifier with One Hidden Layer for Planner Data
Inspired by the human brain's neural network, Artificial Neural Network (ANN) seeks to develop information processing. The ANN helps train the computers (programming) to respond appropriately to events instead of dictating what needs to be done. Each neuron in this network is a processing element and solves different problems along with other processing elements.
<br/><br/>

<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/66460485/132514356-3142b8f1-9abf-4c0d-879f-b58252ee58d2.gif">
</p>

In order to build a Neural Network, we should follow these six steps:

1. Define the number of input units and the number of hidden units
2. Initialize the parameters
3. Implement forward propagation
4. Compute loss
5. Implement backward propagation (to get the gradients)
6. Update parameters (gradient descent)

In this project, planner data in the form of a scatter plot is produced and needs to be classified into two classes. A neural network consisting of one hidden layer is used as the classifier. The number of examples is equal to 400, and the size of the hidden layer is hard-coded to 4. The Weights matrices are initialized randomly, and bias vectors are initialized to zero values. The non-linear *tanh* function is used as the activation function in the hidden layer.
