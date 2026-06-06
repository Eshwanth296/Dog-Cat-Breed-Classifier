# Dog and Cat Breed Classifier

## Overview
A deep learning model built with PyTorch that classifies different breeds of dogs and cats.

## Features
- Image classification
- Custom dataset loading
- CNN-based architecture
- Training and prediction scripts

## Technologies
- Python
- PyTorch
- TorchVision
- NumPy

## Dataset
This project was trained on a Dog and Cat Breed image datasets containing multiple breeds of dogs and cats.
The dataset can be downloaded from:
<#!/bin/bash
kaggle datasets download ma7555/cat-breeds-dataset>

<#!/bin/bash
kaggle datasets download darshanthakare/dog-breeds-image-dataset>

## How to Run
1. Clone the repository
2. Install requirements
3. Run the training script
4. Predict using your own image

## Results
Training Accuracy: xx%
Validation Accuracy: xx%

## Predictions
You can predict the image taken from dataset itself.And You can also predict the new image by changing path in last cell

## To Improve Accuracy
Run the training loop upto 15-50 Epochs (Warning:Its consumes more time because of large dataset contains over 100,000k images)


# ResNet18 Dog and Cat Image Classifier

## Overview

This project is a deep learning image classification system developed using PyTorch and the ResNet18 architecture. The model is trained to classify images of dogs and cats by learning visual features from a labeled dataset.

## Features

* Image classification using ResNet18
* Transfer learning with a pre-trained model
* Image preprocessing
* Model training and evaluation using PyTorch
* Predicts the class of a new input image

## Technologies Used

* Python
* PyTorch
* TorchVision
* Matplotlib

## Model Architecture

The project uses the ResNet18 convolutional neural network with transfer learning. The final classification layer is modified to perform binary classification for dog and cat images.

## Dataset

The model is trained on a labeled dataset containing dog and cat images. Images are preprocessed and resized before training.

## Project Workflow

1. Load and preprocess the dataset
2. Apply image transformations
3. Load the pre-trained ResNet18 model
4. Replace the final classification layer
5. Train and validate the model
6. Predict the class for unseen images

## Future Improvements

* Support multiple dog and cat breeds
* Deploy the model as a web application
* Improve accuracy with larger datasets
* Add a user-friendly prediction interface

