# Convolutional Autoencoder

Implementation of a convolutional autoencoder to encode/decode images from mnist dataset with high fidelity.

The Convolutional Autoencoder is a Neural Network and it is using the Mnist dataset to encode the images to lower dimensions.
The saved model of the Neural Network is been used by the **reduce.py** to finally export the files with the lower dimension images of the Mnist dataset.
Τhis technique is helpful because if someone wants to use this dataset in some applications such as classification or clustering it can reduce the running time of the program to a great extent.

# Compilation & Running
    compile & run : py file_name
    filename : NeuralNetwork.py, reduce.py

First you run the **NeuralNetwork.py** to produce the model. Then **reduce.py** is coming to the game to use this model that have been saved as **autoencoder.h5**. 
When **reduce.py** is done, it will have created the files with the images in reduced size. If you want to play with the dimensions just change the **latent_dimension**.
