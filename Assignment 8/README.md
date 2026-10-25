# Assignment 8: Pre-trained BERT for Sentiment Analysis / Text Classification

## Objective
Implement a pre-trained BERT model for sentiment analysis or text classification using a sample labelled text dataset.

## Overview
BERT (Bidirectional Encoder Representations from Transformers) learns contextual text representations by considering words in both directions. For classification, a task-specific classification head is fine-tuned on top of the pre-trained model.

## Workflow
1. Import the required libraries.
2. Load and inspect the labelled text dataset.
3. Prepare the text samples and class labels.
4. Split the data into training and testing subsets.
5. Load a pre-trained BERT tokenizer and sequence-classification model.
6. Tokenize text with truncation, padding, and attention masks.
7. Fine-tune BERT using the training data.
8. Generate predictions on the held-out test data.
9. Calculate accuracy, precision, recall, and F1-score.
10. Display the classification report and any confusion matrix included in the notebook.

## Main Technologies
- Python and PyTorch
- Hugging Face Transformers
- Dataset-loading library used in the notebook
- Scikit-learn
- Matplotlib / Seaborn, if used for visualizations

## Evaluation Metrics
- **Accuracy:** Fraction of predictions that are correct.
- **Precision:** Fraction of predicted class-positive instances that are correct.
- **Recall:** Fraction of actual class-positive instances identified correctly.
- **F1-score:** Harmonic mean of precision and recall.

For multi-class classification, macro-averaged precision, recall, and F1-score can give each class equal weight.

## Running the Notebook
1. Open the notebook in Google Colab.
2. Select a GPU runtime if available.
3. Run the setup and dataset-loading cells.
4. Run preprocessing, tokenization, and model-training cells in order.
5. Run the evaluation and visualization cells.
6. Record the metrics produced by your actual run.

## Notes
- Keep the label-to-index mapping consistent during training and evaluation.
- Results depend on the dataset, train/test split, preprocessing, model checkpoint, and training configuration.
- Do not replace measured results with assumed example values.
