# MNIST Handwritten Digit Recognition (CNN)

A convolutional neural network built with TensorFlow/Keras that classifies handwritten digits (0–9) from the MNIST dataset.

## What it does
- Loads MNIST through `tensorflow_datasets`.
- Preprocesses and batches the data.
- Trains a CNN: `Conv2D(32, 5×5)` → `MaxPooling` → `Conv2D(64, 3×3)` → `MaxPooling` → `Flatten` → `Dense` layers with `Dropout`.
- Trains with a sparse categorical cross-entropy loss and tracks training/validation accuracy.

## Stack
`TensorFlow / Keras` · `TensorFlow Datasets` · `Matplotlib`

## Run it
Open `MNIST.ipynb` in Google Colab or locally (`pip install -r requirements.txt`). The dataset downloads automatically.
