# Assignment 2: Multilayer Perceptron for Wine Classification

## Objective
Design and implement a Multilayer Perceptron (MLP) to classify samples in the Wine dataset and evaluate its performance.

## Dataset
**Scikit-learn Wine dataset**. Each sample has 13 numerical features and belongs to one of 3 wine classes.

## Implementation
- Load the built-in Wine dataset.
- Split the data into training and testing sets.
- Standardize the input features with `StandardScaler`.
- Build an MLP with Dense layers using ReLU and Softmax activations.
- Train the model using the Adam optimizer.
- Evaluate test loss and accuracy.
- Generate predictions, a classification report, and a confusion matrix.
- Plot training and validation accuracy.

## Evaluation
Accuracy, precision, recall, F1-score, and confusion matrix.

## Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Matplotlib

## Run
Open `DL_A2.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom. The dataset is included in Scikit-learn and does not need a separate download.

## Files
- `DL_A2.ipynb` — implementation notebook
- `Vedanti Raut_CSEAI_E_38_A2.pdf` — practical record / exported report
