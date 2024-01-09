 Image Classification using CNN


Image classification is the task of assigning a label or class to an input image. It is a supervised learning problem, where a model is trained on a labeled dataset of images and their corresponding class labels, and then used to predict the class label of new, unseen images.

There are many architectures for image classification, one of the most popular being convolutional neural networks (CNNs). CNNs are especially effective at image classification because they can automatically learn the spatial hierarchies of features, such as edges, textures, and shapes, which are important for recognizing objects in images.



In this Image Classification, we used dog and cat images as inputs to classify.
The main goal of this project is to train the machine to classify the image accurately with the high resolution and low resolution of images(input).
The dataset I used has more than 10000 images for input and split them for training and testing the data.

The libraries used :
	Tensorflow
	Keras
	Random
	matplotlib
	Numpy
TensorFlow is an open-sourced end-to-end platform, a library for multiple machine learning tasks, while Keras is a high-level neural network library that runs on top of TensorFlow. Both provide high-level APIs used for building and training models easily.

The Classification model learns from the input data and generates a random image from the loaded dataset on its own. The model predicts the random image using Tensorflow and Keras functions.  

