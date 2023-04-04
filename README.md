# Feed-Forward-Neural-Network

You are given the MNIST dataset (Modified National Institute of Standards and
Technology database) of handwritten digits consisting of a training set of 60,000
examples and a test set of 10,000 examples. The images from the data set have the size
28 x 28. They are saved in the csv data files mnist_train.csv and mnist_test.csv. Every
line of these files consists of an image, i.e. 785 numbers between 0 and 255. The first
number of each line is the label, i.e. the digit which is depicted in the image. The following
784 numbers are the pixels of the 28 x 28 image. The images of the MNIST dataset are
greyscale and the pixels range between 0 and 255 including both bounding values. We
should map these values into the interval [0, 1] by dividing each pixel by 255.
Build a neural network and perform the classification task with the specifications
mentioned as follows. Your implementation can have the following modules
1. Data loader (optional): Use this module to load all datasets. (You can also optionally
create mini batches, with each mini batch having 60 training examples)
2.. Weight initializer: This module should initialize all weights randomly.
3. Forward pass: Define the forward function where you do a forward pass (forward
propagation) of the neural network.
4. Backpropagation: Define a backward function where you compute the loss and do a
backward pass (backpropagation) of the neural network and update all weights.
5. Training: Implement a simple mini batch SGD loop/ batch GD and train your neural
network, using forward and backward passes.
6. Predict: To test the learned model weights to predict the classes of the test set.
NN Specification: No of hidden layers: 1, No. of neurons in hidden layer: 10, Activation
function in the hidden layer: ReLu ,. number neurons in the output layer.10(Use one-hot
encoding), Activation function in the output layer: Softmax, Optimization algorithm : Mini
Batch Stochastic Gradient Descent (SGD) / Batch Gradient Descent (GD), Loss
function: Categorical Cross Entropy Loss, Learning rate: 0.1, No. of epochs = 500.
Your code must output the following: (1). Show the training accuracy after every 10
epochs (or plot it in a single plot), (2) Print the final training accuracy and (3) Print the test
accuracy.
