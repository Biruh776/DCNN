# Vibration Signal Classification with DCNN

This repository contains a minimal implementation of a Deep Convolutional Neural Network (DCNN) for classifying vibration signal data.

## Files

- **`dcnn_preprocess.ipynb`** – Loads, reshapes, and preprocesses raw vibration data. Saves processed data as `.npy` files.
- **`dcnn_main.ipynb`** – Defines and trains a 1D CNN model using PyTorch. Evaluates and plots training/testing performance.

## Requirements

- Python 3.x  
- NumPy, Pandas, Matplotlib  
- PyTorch, TorchMetrics  
- scikit-learn

## Usage

1. Make sure you either rename your file or change the name of the vibration file in the code
1. Run `dcnn_preprocess.ipynb` to generate the input datasets.
1. Run `dcnn_main.ipynb` to train and evaluate the CNN model.
