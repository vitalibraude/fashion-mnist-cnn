# Fashion MNIST CNN Classifier

## Description
This project implements a Convolutional Neural Network (CNN) for classifying images from the FashionMNIST dataset using PyTorch. The dataset consists of grayscale images of 10 different clothing categories, such as shirts, sneakers, and dresses.

## Features
- Uses PyTorch for deep learning
- Trains a CNN model on FashionMNIST
- Evaluates model accuracy on test data
- Saves trained model for later use

## Installation
To install required dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage
To train the model, run:
```bash
python train.py
```

## Model Architecture
The model consists of:
- Two convolutional layers
- Max pooling layers
- Fully connected layers
- ReLU activations
- LogSoftmax output

## Results
The model achieves approximately **90% accuracy** on the test dataset.

## Author
Vitali Pavlovski
