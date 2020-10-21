# Data pipeline with Keras and tf.data

## Instructions

In this notebook, you will implement a data processing pipeline using tools from both Keras and the tf.data module. 
You will use the ImageDataGenerator class in the tf.keras module to feed a network with training and test images from 
a local directory containing a subset of the LSUN dataset, and train the model both with and without data augmentation. 
You will then use the map and filter functions of the 
Dataset class with the CIFAR-100 dataset to train a network to classify a processed subset of the images.
