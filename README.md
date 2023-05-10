# nn_mnist

**Background**:

This is a neural network developed from scratch using Python, NumPy and the MNIST dataset that recognizes handwritten digits. This implementation is an educational exercise that is based off of the book "Make Your Own Neural Network" by Tariq Rashid, with the added functionality of saving and loading weights within the neural network.

To train my neural network, I used the dataset available at http://www.pjreddie.com/media/files/mnist_train.csv which contains 60,000 images. I used approximately 50,000 images from this dataset to train my NN. The test dataset contains 10,000 records. After five epochs of training, the model achieved an accuracy of about 95%.

I implemented additional functionality to preserve the network's weights and subsequently integrated them into another network. By testing this feature on a new neural net, I successfully attained the same level of accuracy as the original neural net.

**Architecture details**:

The architecture comprises a three-layer neural network with 784 input nodes, 200 hidden nodes, and 10 output nodes, using a learning rate of 0.01.

To circumvent issues related to saturation and zero-value weights, the implementation incorporates certain assumptions about the network. For weight initialization, the code samples from a normal distribution with a mean of zero and a standard deviation equal to the inverse of the square root of the number of links into a node. The network employs the sigmoid activation function and the square of the difference loss function. Backpropagation is used to minimize errors within the weights.


**The notebook is organized into the following sections:**:

Defining the Neural Network

Training the Neural Network

Testing the Neural Network

Defining a new Neural Network and loading saved weights

Testing the new Neural Network with the saved weights

Example Calculations


