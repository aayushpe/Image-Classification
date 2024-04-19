# MNIST Digit Classifier

This project contains a Jupyter notebook hosted on Google Colab that demonstrates how to build and train a neural network to classify handwritten digits from the MNIST dataset. The MNIST dataset is a collection of 60,000 grayscale images of handwritten digits (0 through 9) that has been used as the basis for benchmarking classification algorithms.

## Getting Started

### Prerequisites

No installation is required when using Google Colab since it comes with most of the needed packages pre-installed.

### Accessing the Notebook

The notebook can be accessed via Google Colab:

1. Open the Google Colab website.
2. Upload the notebook file `mnist-classification.ipynb` to your Google Drive.
3. Open the notebook with Google Colab from your Google Drive interface.

### Usage

Follow the instructions in the notebook, which will guide you through loading the data, preprocessing it, defining the neural network model, training the model, and finally evaluating its performance.

## Notebook Overview

The notebook is divided into several sections:

2. **Data Loading**: Code to load the MNIST data using TensorFlow Keras.
3. **Data Preprocessing**: Normalization and reshaping of the data.
4. **Model Definition**: Building the Sequential neural network model.
5. **Model Compilation**: Setting up the model with loss function, optimizer, and metrics.
6. **Model Training**: Training the model with the training data.
7. **Evaluation**: Assessing the model's performance using the test data.
8. **Visualization**: Code to visualize the results and a few sample predictions.

## Features

- Use of TensorFlow 2.x and Keras for model building and training.
- Implementation of a Sequential model with Flatten, Dense, and Dropout layers.
- Visualization of training progress and model accuracy.
- Prediction examples with test dataset.

## Acknowledgments

- The MNIST dataset, provided by Yann LeCun, Corinna Cortes, and Christopher J.C. Burges.
- TensorFlow and Keras teams for providing excellent documentation.
