
# Fruit Freshness Classification Using CNN

## Overview

This project presents a Convolutional Neural Network (CNN) based image classification system for detecting fruit freshness. The model classifies fruits as either Fresh or Rotten using image-based features learned automatically through deep learning.

The system focuses on three fruit categories:

* Apple
* Banana
* Orange

and identifies whether each fruit is fresh or rotten.

## Features

* Automated fruit freshness detection
* Image preprocessing and augmentation
* Deep learning-based classification
* Multi-class fruit recognition
* Real-time image prediction

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* KaggleHub

## CNN Architecture

* Conv2D (32 filters)
* Conv2D (64 filters)
* Conv2D (128 filters)
* MaxPooling Layers
* Dense Layer (128 units)
* Dropout (0.5)
* Softmax Output Layer

## Results

The trained CNN achieved:

* Training Accuracy: 96.54%
* Validation Accuracy: 96.86%
* Training Loss: 0.1018
* Validation Loss: 0.0823

The model successfully classified fresh and rotten apples, bananas, and oranges with high accuracy. Based on the final reported metrics in the project presentation.
