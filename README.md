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
