# Assignment 5: Comparing RNN, LSTM, and GRU for Sequence Classification

## Objective
Implement and compare Simple RNN, LSTM, and GRU models for sequence classification using evaluation metrics.

## Dataset
**IMDb movie-review sentiment dataset**, loaded through `tf.keras.datasets.imdb`. Reviews are encoded as integer sequences and labelled as negative (`0`) or positive (`1`).

## Implementation
- Load the built-in IMDb dataset.
- Limit the vocabulary and pad review sequences to a common length.
- Build and train Simple RNN, LSTM, and GRU classifiers with comparable embedding and output layers.
- Generate predictions for the test set.
- Compare accuracy, precision, recall, and F1-score.
- Display confusion matrices as heatmaps.

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Run
Open `DL_A5.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom. The dataset is downloaded automatically by Keras if it is not already cached.

## Files
- `DL_A5.ipynb` — implementation notebook
- `Vedanti Raut_CSEAI_E_38_A5.pdf` — practical record / exported report
