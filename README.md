# Digit Recognization

This project involves developing a machine learning model to recognize handwritten digits, an essential task with applications in automated document processing, finance, and more. The model was trained on the popular MNIST dataset and achieves high accuracy in classifying digits from 0 to 9.

## Table of Contents

Overview

Dataset

Model Architecture

Technologies Used

Results

Installation

Usage

## Overview

The Digit Recognization project demonstrates the use of deep learning in image classification, specifically for identifying handwritten digits. The Convolutional Neural Network (CNN) model used in this project is designed to accurately interpret and classify images from the MNIST dataset.

## Dataset

Source: MNIST Handwritten Digits Dataset

Size: 60,000 training images and 10,000 test images, each 28x28 pixels.

Preprocessing: Images were normalized to improve model convergence.
## Model Architecture

The model is based on a CNN architecture, which has proven effective for image recognition tasks. Key layers include:

Convolutional Layers: For feature extraction from images.

Pooling Layers: For dimensionality reduction.

Dense Layers: Fully connected layers for classification.
## Technologies Used

Python: For programming.

TensorFlow & Keras: For building and training the CNN model.

NumPy & Pandas: For data processing.

Matplotlib: For visualizations.
## Results

Accuracy: The model achieved an accuracy of approximately 98% on the test dataset.

Evaluation: Performance metrics such as accuracy and confusion matrix were used for evaluation.
## Installation

To run this project locally, follow these steps:

### 1. Clone the repository:
            git clone https://github.com/varshitha-g/Digit-Recognization.git
            cd Digit-Recognization
### 2. Create a virtual environment:
            python -m venv env
            source env/bin/activate  # On Windows, use `env\Scripts\activate`
### 3. Install the dependencies:
            pip install -r requirements.txt
## Usage

### Training the Model: Run train.py to train the model on the MNIST dataset.
              python train.py
### Testing the Model: To test the model’s performance, run:
              python test.py
### Prediction: Use the predict.py script to make predictions on custom input images of handwritten digits.
