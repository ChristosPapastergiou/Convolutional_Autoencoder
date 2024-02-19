# Convolutional Autoencoder

Implementation of a convolutional autoencoder to encode and decode a dataset with images with high fidelity.

The Convolutional Autoencoder is a Neural Network and it is using the Mnist dataset to encode the images to lower dimensions.
The saved model of the Neural Network is been used by the **reduce.py** to finally export the files with the lower dimension images of the Mnist dataset.
Τhis technique, the minimization of the dimension, is helpful because if someone wants to use a dataset in some applications such as classification or clustering it can reduce the running time of the program to a great extent.

# Compilation & Run

To reduce the dimension of the images you must first run the **NeuralNetwork.py** to produce the model. 
When the Neural Network is done the **reduce.py** is coming to the game to use this model that have been saved as **autoencoder.h5**. 
When **reduce.py** is done, it will have created the files with the images in reduced size. If you want to play with the dimensions just change the **latent_dimension**.

    compile & run (1st) : py NeuralNetwork.py
    compile & run (2nd) : py reduce.py

In collaboration with [Dimitriadis Christos](https://github.com/chrisdimCs)
