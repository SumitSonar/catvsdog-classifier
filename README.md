# Cat vs Dog Image Classifier

This repository contains an image classification model that can differentiate between images of cats and dogs. The model is built using TensorFlow and Keras, and it is trained on the "Cats vs Dogs" dataset from TensorFlow Datasets (TFDS).

## Dataset

The "Cats vs Dogs" dataset contains 25,000 images of cats and dogs. The dataset is loaded and preprocessed using TensorFlow Datasets (TFDS).

## Model

The model is a Convolutional Neural Network (CNN) with the following architecture:
- 3 Convolutional layers with ReLU activation and MaxPooling
- 1 Fully connected (Dense) layer with ReLU activation
- Dropout for regularization
- Output layer with sigmoid activation for binary classification

## Project Structure

- `cat_dog_classifier_tfds.h5`: The saved model file.
- `README.md`: This readme file.
- `cat_dog_classifier.py`: The script to train and evaluate the model, and to make predictions.

## Requirements

- TensorFlow
- TensorFlow Datasets
- Matplotlib (for plotting training history)

You can install the required packages using pip:
```bash
pip install tensorflow tensorflow-datasets matplotlib
