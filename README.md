# MNIST-CNN-Classification
---
This repository contains a convolutional neural network model for the classification of handwritten digits from the MNIST dataset. The code preprocesses the input data, defines the neural network architecture using the Keras Sequential model, and trains the model on the training data. The repository also includes code to evaluate the model on the test data and use it to predict the class of new images.

### Requirements
---
The following packages are required to run the code:

- numpy
- keras
- matplotlib

PS: The code was tested on Python 3.11.

### Usage
---
To use the code, follow these steps:

- Clone the repository: `git clone https://github.com/SeasonLeague/MNIST-CNN-Classification.git`
- Install the required packages: `pip install numpy keras matplotlib`
- Run the code: python `mnist_cnn.py`

The code will download the MNIST dataset, preprocess the data, define the neural network architecture, train the model, and evaluate the performance of the model on the test data. The predicted class of the first test image and the image itself will be displayed using matplotlib.

### Acknowledgments
---
The code is based on the example code provided in the Keras documentation: https://keras.io/examples/mnist_cnn/.