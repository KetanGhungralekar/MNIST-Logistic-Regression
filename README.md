# MNIST Logistic Regression

## Overview

This project implements a logistic regression model for classifying handwritten digits using the MNIST dataset. The goal is to provide a simple baseline for image classification tasks using PyTorch. The model includes training, evaluation, and performance metrics to assess its effectiveness.

## Features

- Logistic Regression model for digit classification
- Utilizes the MNIST dataset (handwritten digits)
- Training and evaluation pipeline
- Performance metrics including:
  - Accuracy
  - Confusion Matrix
  - Precision
  - Recall
  - F1-score

## Installation

To run this project, make sure you have Python installed on your machine. You can set up a virtual environment and install the required dependencies using the following commands:

```bash
# Clone the repository
git clone https://github.com/KetanGhungralekar/MNIST-Logistic-Regression.git
cd MNIST-Logistic-Regression

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
## Usage

1. **Prepare the MNIST dataset**: The dataset will be automatically downloaded when running the script if not already present.
2. **Train the model**: Run the training script to train the logistic regression model on the MNIST dataset.
   ```bash
    Run the Notebook 6.ipynb

## Dataset
This project uses the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which consists of 70,000 images of handwritten digits, each 28x28 pixels in grayscale. The dataset is divided into 60,000 training images and 10,000 test images.

## Usage
1. Clone this repository:

   ```bash
   git clone https://github.com/KetanGhungralekar/MNIST-Logistic-Regression.git

## Results
The notebook provides visualizations of the training process and the model's accuracy on the test set. You can expect the model to achieve an accuracy of 86.66% on the MNIST test dataset.

## Acknowledgments
- **PyTorch** for the deep learning framework, which provides tools and libraries for building and training neural networks.
- **MNIST dataset** for providing a well-known dataset for training image classification models.
- Various tutorials and documentation that helped in the implementation and understanding of logistic regression and PyTorch.
- The open-source community for sharing resources and knowledge that facilitate learning and development in machine learning.

