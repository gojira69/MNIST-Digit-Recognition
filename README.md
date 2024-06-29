# MNIST Handwritten Digit Recognition

This project demonstrates a convolutional neural network (**CNN**) for recognizing handwritten digits using the `MNIST` dataset. The model is built with TensorFlow and Keras, and it achieves high accuracy on the `MNIST` test set.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction

The `MNIST` dataset contains 60,000 training images and 10,000 testing images of handwritten digits (0-9). The goal of this project is to train a **CNN** to accurately classify these digits.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/`mnist`-digit-recognition.git
   ```
2. Change to the project directory:
   ```sh
   cd `mnist`-digit-recognition
   ```
3. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv your_venv_name
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

To run the project, execute all the cells in the [notebook](code.ipynb):

The notebook will:

- Load and preprocess the `MNIST` dataset.
- Define and compile a **CNN** model.
- Train the model on the training data.
- Evaluate the model on the test data.
- Display a sample prediction.

## Results

After training the model for 5 epochs, we achieve a high accuracy on the `MNIST` test set. The results are as follows:

`Accuracy` - 0.9923

`Loss` - 0.0260
