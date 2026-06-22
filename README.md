# CodeAlpha-Handwritten-Character-Recognition
Handwritten Character Recognition using CNN and MNIST Dataset

## Project Overview

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The model is trained using TensorFlow and Keras and achieves approximately 99% test accuracy.

## Technologies Used

* Python
* TensorFlow/Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Dataset

MNIST Dataset:

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* Digits: 0–9

## Model Architecture

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* Flatten Layer
* Dense Layer (128 neurons)
* Output Layer (10 classes)

## Results

* Training Accuracy: 99.47%
* Validation Accuracy: 98.81%
* Test Accuracy: 99%

## Evaluation Metrics

* Precision: 99%
* Recall: 99%
* F1-Score: 99%

## Future Improvements

* Data Augmentation
* Hyperparameter Tuning
* Real-time Digit Recognition
