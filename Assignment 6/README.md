# Assignment 6: CNN for Tomato Leaf Disease Classification

## Objective
Design and implement a Convolutional Neural Network (CNN) to classify tomato leaf images by disease category.

## Dataset
Tomato leaf image dataset downloaded using KaggleHub (`kaustubhb999/tomatoleaf`). The notebook uses the dataset's `tomato/train` and `tomato/val` directories, with subfolders representing classes.

## Implementation
- Download and locate the dataset.
- Load training and validation images from their class directories.
- Resize images to 128 × 128 and use batches of 32.
- Inspect class names and visualize sample images.
- Normalize pixel values for model input.
- Build a CNN with convolution, max-pooling, dense, and dropout layers.
- Train the model and evaluate validation loss and accuracy.
- Predict classes for validation images and visualize predictions.
- Save the trained model as `tomato_disease_cnn.keras`.

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- KaggleHub

## Run
Open `DL_A6.ipynb` in Google Colab and run the cells in order. An internet connection is required to download the dataset. GPU acceleration is recommended for faster training.

## Files
- `DL_A6.ipynb` — implementation notebook
- `Vedanti Raut_CSEAI_E_38_A6.pdf` — practical record / exported report
