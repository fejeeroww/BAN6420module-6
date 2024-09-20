# BAN6420module-6
# Developing Convolutional Neural Network For Classifying the Fashion MNIST dataset

## Project Overview

This Jupyter notebook project demonstrates the implementation of a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset. The project is designed to showcase  image classification technique using TensorFlow and Keras.

## Requirements

- Python 3.7+
- Jupyter Notebook
- TensorFlow 2.x
- NumPy
- Matplotlib

You can install the required packages using: pip install jupyter tensorflow numpy matplotlib


## Project Structure

The project consists of a single Jupyter notebook  that contains the following main sections:

1. Data Loading and Preprocessing
2. Model Definition (6-layer CNN)
3. Model Training
4. Model Evaluation
5. Visualization of Results

## CNN Architecture

The implemented CNN has the following structure:

1. Convolutional Layer (32 filters, 3x3 kernel)
2. Max Pooling Layer (2x2)
3. Convolutional Layer (64 filters, 3x3 kernel)
4. Max Pooling Layer (2x2)
5. Convolutional Layer (64 filters, 3x3 kernel)
6. Flatten Layer
7. Dense Layer (64 neurons)
8. Output Dense Layer (10 neurons, softmax activation)

## Usage

1. Download the Jupyter notebook file.
2. Ensure you have all the required packages installed.
3. Open the notebook in Jupyter Lab or Jupyter Notebook.
4. Run all cells in order.

## Results

The notebook will display:

- Model summary
- Training and validation accuracy/loss plots
- Test set accuracy
- Predictions on sample images
