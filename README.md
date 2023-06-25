# CNN-Horse-vs-Human-Classifier
**Image Classification: Humans and Horses using CNN and Transfer Learning**

This repository contains a CNN model implemented using Tensorflow for classifying human or horse image. 

The datasets used in this project are sourced from the [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning.](https://www.coursera.org/learn/introduction-tensorflow/home/welcome) The course, created by DeepLearning.AI

## Introduction

The objective of this project is to implement a Convolutional Neural Network (CNN) model for classifying images of horses and humans. CNNs are a popular deep learning architecture for image classification tasks as they can effectively capture spatial hierarchies and patterns in images. In addition to the custom CNN architecture, this project incorporates transfer learning from the InceptionV3 model, allowing us to compare the performance of both approaches.

## CNN Model Architecture

The CNN model in this repository is implemented using Python and the TensorFlow library. The architecture consists of convolutional and pooling layers, followed by fully connected layers for classification.

The CNN model architecture is as follows:

1. Convolutional Layers: Convolutional layers apply filters to input images, extracting relevant features through convolutions. The filters learn various patterns and spatial representations.

2. Pooling Layers: Pooling layers reduce the spatial dimensions of the convolved features while retaining important information. Max pooling is typically used to downsample the features.

3. Fully Connected Layers: Fully connected layers take the flattened output from the convolutional and pooling layers and perform classification based on learned features. These layers combine the extracted features to make predictions.

## Transfer Learning with InceptionV3

To further enhance the classification performance, this project incorporates transfer learning from the InceptionV3 model. InceptionV3 is a deep convolutional neural network architecture pre-trained on a large-scale dataset, including various object categories.

The transfer learning process involves the following steps:

1. Import Pre-trained Model: The pre-trained model used in this project is sourced from the [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow/home/welcome). The course created by DeepLearning.AI.

2. Define New Model: Set-up the model with InceptionV3 library, choosing specific layer for further processing, and then train new model.

## Dataset Attribution

The datasets used in this project are sourced from the Coursera course [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://www.coursera.org/learn/introduction-tensorflow/home/welcome). The course, created by DeepLearning.AI, provides comprehensive learning materials and practical exercises on CNN. The datasets are used here for educational purposes only, in accordance with the course's terms of use.

To access the datasets used in this project, please refer to the course. It is recommended to enroll in the course to gain a deeper understanding of the data and the concepts explored in this project.

>Note: Respect the terms of use and licensing restrictions associated with the datasets. 

If you have any questions or suggestions, please don't hesitate to reach out.

