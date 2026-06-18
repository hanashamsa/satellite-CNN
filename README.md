# satcnn

PyTorch CNN for satellite image classification.

## Overview

This project trains a convolutional neural network on labeled image folders, evaluates it with validation metrics and visualizations, and generates predictions for a separate test set.

## What it does

- Loads images from `data/`
- Splits the dataset into training and validation sets
- Applies image augmentation and normalization
- Trains a custom CNN in PyTorch
- Plots training curves, confusion matrix, and misclassified samples
- Creates predictions for `public_test_data`

## Files


- `assets/plots/` — saved figures
- `assets/weights/` — saved best model weights
- `public_test_data/` — unlabeled test images

## Setup

Install the main dependencies:

```bash
pip install torch torchvision numpy pandas matplotlib scikit-learn pillow
```

## Run

Open the notebook and run all cells from top to bottom.

## Output

The notebook saves:
- best model weights
- training and validation plots
- confusion matrix
- misclassified image examples
- test predictions
